
# 题目描述

**这是一道交互题。**

HB 的 OIer 们约好了一起面基，但是 wjyyy 没有来，因为 wjyyy 是一只鸽子。

因为 wjyyy 注定会咕，所以他记的时间从来都和大家不一样，因此你想要知道 wjyyy 记的时间是多少，以便下次去蹲他。

你每次可以告诉 wjyyy 现在几点了，如果这个时间早于他所记的之间，他就会说“在鹿上”，即输出一行 `deer`；否则，他会说“鸽了”，即输出一行 `pigeon`。

但是当问的次数超过 $32$ 次时，wjyyy 就会生气，对你的印象会减半，因此这个测试点你只能得到一半的分数；当问的次数超过 $100$ 次，或者你确定的时间与 wjyyy 记的时间不一致，wjyyy 就会把你的询问鸽掉，这个测试点计 $0$ 分。

# 输入格式

**在你的每次询问后，你的程序会从标准读入中读到交互器给出的信息：**

- `deer` 表示你输出的时间早于 wjyyy 所记的时间；
- `pigeon` 表示你输出的时间不早于 wjyyy 所记的时间。

# 输出格式

**你的程序向交互器的输出格式有以下几种：**

- `ask x`，$x$ 是一个正整数，表示向 wjyyy 询问这个时间；
- `orz x`，$x$ 是一个正整数，表示 wjyyy 记住的时间。当你输出 `orz x` 之后，交互器会向评测端返回你的答案是否正确，交互程序结束。此时你的程序也应该结束，否则接下来发生的对成绩造成影响的事情后果自负。

输出注意事项详见“数据范围与提示”。

# 样例



# 数据范围与提示

wjyyy 所记的时间是一个不超过 $10^9$ 的正整数。

如果你使用 `C++`，可以用

`fflush(stdout)` 或 `cout.flush()` 或 `cout<<endl` 来刷新缓存；

如果你使用 `Java`，可以用

`System.out.flush()`；

如果你使用 `Pascal`，可以用

`flush(output)`；

如果你使用 `Python`，可以用

`stdout.flush()`

详见 [Codeforces 交互题指南](https://codeforces.com/blog/entry/45307)。

如果不刷新缓存会导致 <span class="status time_limit_exceeded"> <i class="icon clock"> </i>Time Limit Exceeded</span> 等不可预料的后果。

如果发现其他问题请注意输出格式或联系[题目提供者](http://hboj.icu/user/3)。

