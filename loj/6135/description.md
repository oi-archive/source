
# 题目描述

**因版权问题，此题暂停评测，请等待重制数据后提交。**

解决了城市人口和道路的规划问题，Lyra 对信息熵产生了浓厚的兴趣，她发现，传输信息所必须的编码长度，与信息的熵成正比。

翡翠城的两座城市之间常常需要进行信息传递，翡翠国传递信息的方式非常奇怪，他们使用一叠 $ n $ 张卡片进行传递，卡片自上而下可以正面朝上也可以背面朝上，正面朝上代表 $ 0 $，背面朝上代表 $ 1 $，自上而下就构成了一个 01 串，他们便用这个来传递信息。

然而，信使在传递卡片的时候，仅仅对一叠卡片打包便放进包里带走了，这导致了一个问题，传输过去之后不知道正反，即可能把整叠卡片倒过来（卡片的位置颠倒同时卡片的朝向反转）。

现在 Lyra 想知道用一叠 $ n $ 个卡片最多能传递多少种不同的信息，即你需要给出尽可能大的 $ m $ 并对 $ 0 \sim m - 1 $ 的信息进行编码和解码操作。

#### 交互接口
在你的程序的最后一行必须写下 `#include "entropy.h"`。

你的程序不应包含主函数，也不应该打开文件，除头文件和宏之外只需要编写一个类 `Entropy`，包含三个 `public` 函数：

```cpp
class Entropy {
public:
    long long getM(int n); 
    std::string encode(long long x);
    long long decode(std::string s);
};
```

加密和解密过程分开进行。

#### 加密过程
交互库会首先调用一次函数 `getM(n)`，参数 $ N $ 表示卡片的数目即编码的长度，你的程序需要对接受的长度 $ n $ 进行必要的预处理和运算，为加密和解密做准备，并返回一个整数 $ m $ 表示你的程序能够加密的最大信息数目。

交互库接下来调用 $ q $ 次 `encode(x)` 函数，每次传入一个 $ 0 \sim m - 1 $ 的整数，你的程序需要对其进行加密并返回一个长度为 $ n $ 的字符串作为加密后的串。

#### 解密过程
交互库会首先调用一次函数 `getM(n)`，参数 $ n $ 表示卡片的数目即编码的长度，你的程序需要对接受的长度 $ n $ 进行必要的预处理和运算，为加密和解密做准备，并返回一个整数 $ m $ 表示你的程序能够加密的最大信息数目。

交互库会判断你返回的 $ m $ 与加密过程中返回的 $ m $ 是否一致，若不一致你将得 `0` 分。

交互库接下来调用 $ q $ 次 `decode(s)` 函数，每次传入一个长度为 $ n $ 的字符串，你的程序需要对其解密并返回一个 $ 0 \sim m - 1 $ 的整数。  
解密传入的字符串有一定概率被进行了如题目所述的翻转操作。

交互库会判断你返回的整数是否与加密前的整数一致，若不一致你将得不会获得解密部分的得分。

# 输入格式

第一行两个正整数 $ n, q $ 表示编码长度和加密的数字个数。  
接下来 $ q $ 行，每行一个在 $ [0, 2 ^ n - 1] $ 区间内的非负整数表示要加密的数，交互库会把输入中的数对你的 $ m $ 取模后传入 `encode` 函数。

# 输出格式



# 样例

#### 样例输入
```plain
5 5
0
1
2
3
4
```

# 数据范围与提示

对于全部数据，$ 1 < n < 60; 0 < q < 50000 $。

**子任务 1**（30 分）$ n \leq 18 $；  
**子任务 2**（70 分）$ n \leq 60 $。

#### 评分标准
* 若你返回的 $ m $ 不在 $ [1, 2 ^ n] $ 区间内，得 $ 0 $ 分；
* 否则设标准答案的 $ m $ 为 $ m_{\text{ans}} $，你的 $ m $ 为 $ m_{\text{you}} $；
  * 若 $ m_{\text{you}} > m_{\text{ans}} $，得零分；
  * 若 $ m_{\text{you}} = m_{\text{ans}} $，得分为 $ 100\% $；
  * 否则你的得分为 $ 50\frac{\ln m_{\text{you}}}{\ln m_{\text{ans}}} \% $；
* 若你的解密结果中有任何一个不正确，你只能根据你的 $ m $ 得到上述标准 $ 20\% $ 的分数。

你每个子任务的得分为所有数据得分的最小值。  
注意：在样例测试库中并没有防止选手访问全局存储空间保存加密过程输入信息的行为，但在正式评测时是被禁止的，在加密和解密之间我们会对内存池进行初始化。你不应当也不允许在。`class Entropy` 之外定义任何变量等存储类型，也不允许定义任何非常量静态存储类型，所有的存储类型都应该定义在。`class Entropy` 内部，除 `rand()` 之外任何对全局或静态变量的访问都是不允许的。

#### 如何测试你的程序
下发文件中有用于检测你的程序的样例交互库 `entropy.h`，把你的程序与 `entropy.h` 放在同一终端下便可以直接编译你的程序。

```bash
g++ entropy.cpp -o entropy -lm
```

接着在终端中运行：

```bash
./entropy < entropy.in > entropy.out
```
会从 `entropy.in` 中读入数据，并测试你的代码，并将你的测试结果输出到 `entropy.out` 文件中。

