
# 题目描述

小 X 迷上了一部没有汉化的 Galgame，他决心为这部游戏的汉化尽自己的一份力量。于是，他反汇编了这部游戏，想从汇编代码里找一些线索。然而，由于小 X 太弱，不能人脑汇编，所以他找到了你，要你帮助他进行汇编模拟。也就是说，小 X 讲给你一段 X86_64 汇编代码，请你帮他输出运行后寄存器的内容和内存内容。

小 X 在程序中发现的汇编只是 X86_64 汇编的一个子集。为了简化题目，本题部分细节与 X86_64 汇编不同，请仔细阅读题面叙述。

约定：我们使用 ATT 格式的汇编代码，同时认为内存寻址操作与栈操作相互独立。同时，程序保证仅包含迭代，不包含递归调用。

你需要的前置技能：补码及其运算，否则符号位会让你崩溃。

### 一、寄存器

|指令|说明|
|-|-|
|`[r/e/_/_]a[x/x/x/l]`  <br>  `[r/e/_/_]b[x/x/x/l]`  </br>  `[r/e/_/_]c[x/x/x/l]`  <br>  `[r/e/_/_]d[x/x/x/l]`  <br>  `[r/e/_/_]si[_/_/_/l]`  <br>  `[r/e/_/_]di[_/_/_/l]`  <br>  `[r/e/_/_]bp[_/_/_/l]`  <br>  `[r/e/_/_]sp[_/_/_/l]` | `_` 表示为空。括号中从前到后四个选项分别代表对低 64 位，低 32 位，低 16 位，低 8 位进行操作所需的指令。|

### 二、数据传送

#### 1. 表达式 (Expression)

|指令|说明|
|-|-|
|表达式：**立即数 X** <br> `$X`|我们约定 `x` 均为无符号十进制整数，立即数不会被作为目标表达式。|
|表达式：**一个寄存器** <br> `%Register_Name`||
|表达式：**对内存进行寻址** <br> `x=0(Rb=0,Ri=0,s=1)`|其中 `x` `s` 为两个立即数，`Rb` `Ri` 为两个通用寄存器名称，等号后的值为未列出时的默认值。 <br> 括号内的填充顺序为：`Rb` → `Ri`。如果没有 `Rb` 而单独使用 `Ri`，则应留出前面的逗号：`x(,Ri,s)`。 <br> 在此，我们假设内存以 $8\:\texttt{B}$ 即 $64\:\texttt{bit}$ 为一个数据块。每次读取一整个块。|

#### 2. 数据传送指令

|指令|说明|
|-|-|
|基本数据传送 <br> `mov[q/l/w/b] (:Expression1),(:Expression2)`|表示把 `Expression1` 处的数据传送到 `Expression2` 处。<br> `[q/l/w/b]` 从左到右分别代表传送低 64 位，低 32 位，低 16 位，低 8 位。 <br> 在操作寄存器低位时，高位保持不变。|
|拓展数据传送 <br> `mov[z/s][q/l/w/b][q/l/w/b] (:Expression1),(:Expression2)`|在数据传送的基础上对中的 `Expression2` 处的数据进行拓展。 <br> 第一个 `[q/l/w/b]` 表示 `Expression1` 处的数据大小，第二个表示 `Expression2` 处的数据大小。 <br> `[q/l/w/b]` 从左到右分别代表传送低 64 位，低 32 位，低 16 位，低 8 位。 <br> `z` 表示对无符号数进行零拓展，`s` 表示对有符号数进行符号拓展。 <br> 本题目限定判定符号正负无脑判定首位即可。|
|地址传送 <br> `leaq (:Expression) (:Register)`|把 `Expression` 的地址加载到 `Register` 中。注意 X86_64 的指针都是 64 位的，所以长度码只能为 `q`。|

### 三、算术指令

#### 1. 一元运算

|指令|说明|
|-|-|
|`inc[q/l/w/b] (:Expression)` <br> `dec[q/l/w/b] (:Expression)`|自增 `Expression`。<br> 自减 `Expression`。|
|`neg[q/l/w/b] (:Expression)`|将 `Expression` 变为其相反数。|
|`not[q/l/w/b] (:Expression)`|将 `Expression` 按位取反。|

#### 2. 二元运算

|指令|说明|
|-|-|
|`add[q/l/w/b] (:Expression1),(:Expression2)` <br> `sub[q/l/w/b] (:Expression1),(:Expression2)` <br> `imul[q/l/w/b] (:Expression1),(:Expression2)` | 将 `Expression1` 与 `Expression2` 相加存入 `Expression2` 中。<br> 将 `Expression2` 与 `Expression1` 作差存入 `Expression2` 中。<br> 将 `Expression1` 与 `Expression2` 相乘存入 `Expression2` 中。 |
|`xor[q/l/w/b] (:Expression1),(:Expression2)` <br> `or[q/l/w/b] (:Expression1),(:Expression2)` <br> `and[q/l/w/b] (:Expression1),(:Expression2)` | 将 `Expression1` 与 `Expression2` 按位异或存入 `Expression2` 中。 <br> 将 `Expression1` 与 `Expression2` 按位或存入 `Expression2` 中。 <br> 将 `Expression1` 与 `Expression2` 按位与存入 `Expression2` 中。|
|`[sal/shl][q/l/w/b] (:Expression1),(:Expression2)` <br> `sar[q/l/w/b] (:Expression1),(:Expression2)` <br> `shr[q/l/w/b] (:Expression1),(:Expression2)` | 将 `Expression2` 左移 `Expression1` 位存入 `Expression2` 中。 <br> 将 `Expression2` 算术右移（填上符号位）`Expression1` 位，存入 `Expression2` 中。 <br> 将 `Expression2` 逻辑右移（左边补零）`Expression1` 位，存入 `Expression2` 中。|

~~本来这道题还应该有比较和跳转的，只是因为出题人太弱写不动，放弃了......~~

# 输入格式

第一行一个整数 $n$，代表输入代码的行数。

接下来 $n$ 行，每行一条汇编代码，代表你需要执行的语句。

# 输出格式

第一行 $7$ 个整数，代表除 `%rsp` 外所有寄存器的值。规定以 64 位无符号整数格式输出。

接下来数行，每行两个64位无符号整数，代表内存中元素的地址和数值。

# 样例

#### 样例输入 1
```plain
3
movq $1,%rax
movq $18446744073709551615,%rbx
movb %al,%bl
```

#### 样例输出 1
```plain
1 18446744073709551361 0 0 0 0 0
```

#### 样例输入 2
```plain
6
movq $1,%rax
subq $3,%rax
movq $2147483647,%rbx
movq %rbx,%rcx
movl %eax,%ebx
movsbq %ax,%rcx
```

#### 样例输出 2
```plain
18446744073709551614 4294967294 18446744073709551614 0 0 0 0
```

#### 样例输入 3
```plain
2
movb $2,%al
leaq (%rax,%rax,4),%rax
```

#### 样例输出 3
```plain
10 0 0 0 0 0 0
```

# 数据范围与提示

所有输入数据都是手造的，std 也是人写的。  
保证 $n \le 50$，每一行长度 $\le 100$。  
真·良心题目。基本上写出来就给过。当然写 WA 了除外 2333。

