
# 题目描述

这是一道交互题，只为 C++ 提供接口函数。

Scape 家的后院种了许多二叉树，树上的每个结点最多只有一个父结点、一个左儿子和一个右儿子。作为他家的园丁，你需要帮他维护这些二叉树。

结点有两种状态：正常状态以及枯萎状态。这些二叉树共有 $n$ 个结点，分别编号为 $1$ 到 $n$。初始时有 $n$ 棵二叉树，分别编号为 $1$ 到 $n$，二叉树 $i$ 上只有结点 $i$ 这一个结点，且所有结点都处于正常状态。

接下来可能发生以下的 3 种事件：

- Scape 要求你把二叉树 $x$ 和二叉树 $y$ 连接成一棵新的二叉树。设二叉树 $x$ 中序遍历得到的序列为 $a_1,a_2,...,a_n$，二叉树 $y$ 中序遍历得到的序列为 $b_1,b_2,...,b_m$，那么新的二叉树中序遍历得到的序列应为 $a_1,a_2,...,a_n,b_1,b_2,...,b_m$。
- Scape 要求你把二叉树 $x$ 分离成两棵新的二叉树。设二叉树 $x$ 中序遍历得到的序列为 $a_1,a_2,...,a_n$，那么新的两棵二叉树中序遍历得到的序列应分别为 $a_1,a_2,...,a_k$ 和 $a_{k+1},a_{k+2},...,a_n$。
- Mythological 打算来观赏二叉树 $x$。为了使这棵树变得更美观，Scape 要求你使这棵树的所有结点都变为正常状态，**且所有结点的深度不能超过 $\mathrm{maxdep}$**。一个结点的深度即为祖先结点的个数加 $1$，根结点深度为 $1$。

为了对这些树进行调整，你给每棵树分配了两个手下，我们称之为某棵树的 $1$ 号手下或者 $2$ 号手下，初始时他们都站在负责的树的唯一一个结点上。每次你可以让某个手下移动到一个相邻的结点，这时你可以命令他把该结点的某个儿子修改为某个结点（原来的儿子的子树会分离出去；新的儿子的父结点也会同时修改为当前结点）。由于某种神秘力量的影响，修改某个结点的儿子后该结点的所有祖先结点（包括自己）都会变为枯萎状态。最后他会给该结点浇上水，如果此时该结点的所有儿子（忽略空儿子）都处于正常状态的话，这个结点就会变为正常状态。

<b>简要题意：要求用二叉树维护若干个序列。交互库会对每棵树提供两个指针，分别指向树上的某个结点。允许修改某个指针指向结点的儿子、更新某个指针指向结点的子树信息和以及把某个指针移动到相邻结点。需要通过这些指针完成合并、分裂、查询操作。</b>

### 任务介绍
你需要实现以下的四个函数：

- <code>init(n, maxdep, maxcnt)</code>
 - 该函数只会在初始调用一次，你可以在此时进行初始化的操作。
- <code>join(x, y, &id1, &id2)</code>
 - 表示 Scape 要求你把二叉树 $x$ 和二叉树 $y$ 连接成一棵新的二叉树。设此时存在的二叉树最大的编号为 $\mathrm{tot}$，那么新的二叉树编号为 $\mathrm{tot}+1$。事件结束后不存在编号为 $x$ 和 $y$ 的二叉树，并且也不能再指挥给它们分配的手下。
 - 连接两棵二叉树后，需要决定给二叉树 $\mathrm{tot}+1$ 分配的两个手下的位置，只能从分配给二叉树 $x,y$ 的 $4$ 个手下当前所处的位置中选择。二叉树 $\mathrm{id}+1$ 的 $1$ 号手下位于手下 $\mathrm{id}_1$ 的位置，$2$ 号手下位于手下 $\mathrm{id}_2$ 的位置。请对 $\mathrm{id}_1, \mathrm{id}_2$ 分别赋值，值为 $1,2$ 分别表示是二叉树 $x$ 的 $1,2$ 号手下；值为 $3,4$ 分别表示是二叉树 $y$ 的 $1,2$ 号手下。
- <code>split(x, k, &p1, &p2, &p3, &p4)</code>
 - 表示 Scape 要求你把二叉树 $x$ 分离成两棵新的二叉树。设此时存在的二叉树最大的编号为 $\mathrm{tot}$，那么新的二叉树编号为 $\mathrm{tot}+1$ 和 $\mathrm{tot}+2$。二叉树 $x$ 中序遍历的前 $k$ 个结点会构成二叉树 $\mathrm{tot}+1$，剩余的结点会构成二叉树 $\mathrm{tot}+2$。事件结束后不存在编号为 $x$ 的二叉树，并且也不能再指挥给它分配的手下。
 - 你需要对 $p_1,p_2,p_3,p_4$ 赋值来指定给两棵新的二叉树分配的手下的位置。$p_1, p_2$ 分别表示二叉树 $\mathrm{tot}+1$ 上的 $1,2$ 号手下所处的结点编号；$p_3, p_4$ 分别表示二叉树 $\mathrm{tot}+2$ 上的 $1,2$ 号手下所处的结点编号。
 - 保证 $1\leq k\lt size(x)$。
- `visit(x)`
 - 表示 Mythological 打算观赏二叉树 $x$。你需要按 Scape 的要求调整这棵树的形态，并且返回调整过后这棵树的根结点的编号。

你可以调用 `move()` 来指挥你的手下，<b>但是该函数的总调用次数不能超过 $2 \times 10^6$ 次，并且在每次事件中（即交互库调用 `join()/split()/visit()` 函数到该函数结束的这段时间内）`move()` 函数的调用次数不能超过 $\mathrm{maxcnt}$ </b>。

- `move(k, id, x, c, y)`
 - 把分配给二叉树 $k$ 的 $\mathrm{id}$ 号手下（$\mathrm{id}$ 为 $1$ 或 $2$）移动到结点 $x$。结点 $x$ 要么是该手下原来所处位置（即不移动），要么是其相邻结点。
 - 之后手下会把该结点的儿子 $c$（$c=0$ 表示左儿子，$c=1$ 表示右儿子）改为结点 $y$（$y=0$ 表示空结点），然后给该结点浇水。
 - 如果不希望修改 $x$ 的两个儿子，请把 $c$ 和 $y$ 设置为 $-1$，这样不会导致 $x$ 的祖先结点变为枯萎状态。

### 实现细节
你只能提交一个源文件实现上述的函数，并且遵循下面的命名和接口。源代码中需要包含头文件 `tree.h`。

```cpp
void init(int n, int maxdep, int maxcnt);
void join(int x, int y, int &id1, int &id2);
void split(int x, int k, int &p1, int &p2, int &p3, int &p4);
int visit(int x);
void move(int k, int id, int x, int c, int y);
```

下发文件中附有样例程序。

### 评测方式
交互库将读入如下格式的输入数据：

第一行为四个整数 $n,m,\mathrm{maxdep},\mathrm{maxcnt}$，$m$ 表示事件的个数。读入此行后交互库会调用一次 `init()` 函数。

接下来 $m$ 行，每行描述一次事件。若为事件 join，输入三个整数 `1 x y`；若为事件 split，输入三个整数 `2 x k`；若为事件 visit，输入两个整数 `3 x`。读入每行后交互库会调用对应的函数。

交互库会在每次调用 `visit()` 函数后进行某些输出，如果输出与数据的输出文件一致且 `move()` 函数的调用次数未超过上限，则视为通过该测试点。如果你在调用 `move()` 函数时传入了非法的参数或者返回值不合法，交互库会马上退出。

通过访问输入输出文件、攻击评测系统或攻击评测库等方式所得分数无效。

### 其他语言

C++ 以外的语言可以通过标准输入输出进行交互。

程序开始时，从标准输入读入一行，包含三个空格分隔的正整数 $n, \mathrm{maxdep}, \mathrm{maxcnt}$。

此后，从输入不断读入格式如下的信息：
- `J <x> <y>`：表示一次 join 事件。向标准输出输出一行 `1 <id1> <id2>` 并刷新输出缓冲（例如 Pascal 语言的 `flush(output)` 和 Java 语言的 `System.out.flush()`，其他语言请参阅语言文档），所有值的含义如上所述。
- `S <x> <k>`：表示一次 split 事件。向标准输出输出一行 `1 <p1> <p2> <p3> <p4>` 并刷新输出缓冲。
- `V <x>`：表示一次 visit 事件。向标准输出输出一行 `1 <root>` 并刷新输出缓冲。其中 `<root>` 为调整过后树的根结点编号，相当于 `visit()` 的返回值。
- `F`：结束程序。

其中任何时刻需要调用 `move()` 时，向标准输出输出一行 `0 <k> <id> <x> <c> <y>` 并刷新输出缓冲。

所有输出同样需要满足上述限制。

# 输入格式



# 输出格式



# 样例

请下载「附加文件」。

<!--
| stdin | stdout |
|:---:|:---:|
| <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">4 200000 200000<br>V 3</pre> |  |
|  | <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">1 3</pre> |
| <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">J 4 1</pre> |  |
|  | <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">0 4 2 4 1 0<br>0 1 1 1 0 4<br>1 3 4</pre> |
| <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">S 5 1</pre> |  |
|  | <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">0 5 1 4 -1 -1<br>0 5 1 4 1 0<br>0 5 1 1 0 0<br>1 4 4 1 1</pre> |
| <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">V 6</pre> |  |
|  | <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">1 4</pre> |
| <pre style="margin-top:0; margin-bottom:0; text-align:left; padding-left:2em;">F</pre> |  |
</small>
-->

# 数据范围与提示

- 子任务 1（15分）：保证 $1\leq n,m\leq 1000$，$\mathrm{maxdep}=2 \times 10^5$，$\mathrm{maxcnt}=2 \times 10^6$。
- 子任务 2（25分）：保证 $1\leq n,m\leq 30000$，$\mathrm{maxdep}=2 \times 10^5$，$\mathrm{maxcnt}=2 \times 10^6$。
- 子任务 3（15分）：保证 $1\leq n,m\leq 10^5$，split 和 visit 事件的总个数不超过 $10000$，$\mathrm{maxdep}=2 \times 10^5$，$\mathrm{maxcnt}=2 \times 10^6$。
- 子任务 4（15分）：保证 $1\leq n,m\leq 2 \times 10^5$，没有 split 事件，visit 事件的个数不超过 $20000$，$\mathrm{maxdep}=60$，$\mathrm{maxcnt}=250$。
- 子任务 5（30分）：保证 $1\leq n,m\leq 2 \times 10^5$，split 和 visit 事件的总个数不超过 $20000$，$\mathrm{maxdep}=60$，$\mathrm{maxcnt}=250$。

请注意最终测评使用的 `tree.h` 与下发的文件并不一致。

由于交互量较大，时限放宽至标程在 LOJ 上运行耗时的两倍。

