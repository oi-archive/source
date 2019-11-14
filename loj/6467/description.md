
# 题目描述

（本题参考功能相同的 <https://wgreenberg.github.io/quine.zip/> 而编写。请注意，本题中对命令合法性的检查比网页中的严格。）

**与一般的 [Quine](https://loj.ac/problem/4) 相同的是，你需要一个输出自己源代码的程序，而不同的是，这不是你熟悉的什么语言：你只有两个命令可用：`print` 和 `repeat`。**

- `print count`：程序以下 $count$ 行不执行，直接复制文本到输出。
- `repeat count index`：从程序**输出**的**倒数**第 $index$ 行（从最后一行是 $1$ 开始计数）开始**复制** $count$ 行到输出。**`repeat` 命令自己可以复制自己的输出。**

（注意，`repeat` 命令其实并不复杂，但是有一点拗口，请参照描述，代码实现和样例仔细理解。）

使用 C++ 描述的话，将所有的输出储存在 `vector<string> all_output` 中，`print` 的实现如下：

```cpp
for (int i = 0; i < count; i ++) {
    string ol;
    getline(input_file, ol)
    all_output.push_back(ol);
}
```

`repeat` 的实现如下（注意此处 `start + count` **不一定小于** `all_output.size()`。）

```cpp
int start = all_output.size() - index;

for (int i = start; i < start + count; i ++)
    all_output.push_back(all_output[i]);
```

---

原网页上对此问题的描述：

> 这里选用 `print` 和 `repeat` 两个命令是基于 ZIP 文件格式中使用的 LZ77 压缩算法的格式。简单来说，每个 ZIP 文件都是由二进制字节表示的这两个命令组成的。既然我们可以使用这两个命令写出一个 Quine，那么我们也可以写出一个 ZIP 文件使其解压得到……自己。赞！

[其中描述的 ZIP 文件是真实存在的](https://alf.nu/ZipQuine)。

# 输入格式

提交的文件名是 `zipquine.txt`，应包含如下内容：

每行一个命令，是空格分隔的 `print` 和一个数字，或者 `repeat` 和两个数字。

请不要输入多余的空格和换行；按照一般规范，文件末尾应有一个换行符。

程序至少包含一行命令。

对于 `print count`，应有 $count \geq 0$，且输入文件在这之后中包含至少 $count$ 行。

对于 `repeat count index`，应有 $count \geq 0$，且 $0 < index \leq N$，其中 $N$ 是执行本 `repeat` 命令**之前**的程序**输出**的行数。

# 输出格式



# 样例

以下是一个程序及其输出和解释，它不是本题的解答：

#### 程序

```plain
print 0
print 2
print 1
print 2
repeat 3 2
```

#### 输出

```plain
print 1
print 2
print 1
print 2
print 1
```

#### 解释

- `print 0` 没有从输入文件复制任何输出，所以没有输出。
- `print 2` 从输入文件复制了其后两行 `print 1` 和 `print 2` 到输出。
- `repeat 3 2` 从输出的倒数第 $2$ 行，也就是 `print 1` 开始复制，共 $3$ 行：（标注 "\*" 表示本次应当复制的行）
  1. 全部输出：\*`print 1`, `print 2`，复制 `print 1` 到输出。
  2. 全部输出：`print 1`, *`print 2`, `print 1`，复制 `print 2` 到输出。
  3. 全部输出：`print 1`, `print 2`, *`print 1`, `print 2`，复制 `print 1` 到输出。
- 所以最终输出是 `print 1`, `print 2`, `print 1`, `print 2`, `print 1`，与程序不同，不是本题的解答。

# 数据范围与提示

手玩请用网页版：<https://wgreenberg.github.io/quine.zip/>。请注意，本题中对命令合法性的检查比网页中的严格。

本题的检查器 `zipquine.cpp` 在“测试数据”中提供，可供下载参考。[按照这里所述](https://loj.ac/help)，检查器从 `user_ans` 文件读取输入，将得分输出到 `stdout`，将其它信息输出到 `stderr`。

