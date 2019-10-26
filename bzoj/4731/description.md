
# Description

<div class="content"><div>有这样一段魔法的程序：（其中所有的数组下标从0 开始，所有的除法的结果为整数，且向0取整）</div>
<div><img src="/source/bzoj/4731/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC92MS5wbmc=.png" width="465" height="368" alt=""/></div>
<div>这个程序目前十分低效（显然时间复杂度至少是平方量级的），无法快速完成百万级别的计算，但我们现在的任务</div>
<div>不仅是优化它。现在我们给出这段程序的输出，你需要完成一个“非确定机”的工作，给出一个可能的输入。请注</div>
<div>意本题的空间限制。</div></div>

# Input

<div class="content"><div>第一行输入a的长度。第二行输入一些空格隔开的正整数，依次表示 a的每一项。</div>
<div>
<div>第三行输入c的长度。第四行输入一些空格隔开的整数，依次表示c的每一项。</div>
<div>每一行相邻的两个数，恰好用一个空格隔开。</div>
<div>a 的长度不会超过 10^4。a 的每一个元素不会超过10^9。</div>
<div>c 的长度不会超过 10^6。对c的元素的范围没有直接的保证</div>
<div>但是保证存在一个解 b，使得 b 的每一个元素的绝对值都不超过 10^9。</div>
<div>a 和 c 都至少拥有一个元素。</div>
<div>我们设 n 为 c 的长度，设 m 为 a 的长度，则：</div>
<div>子任务1：n = 1，m ≤100；</div>
<div>子任务2：n ≤100，m ≤100；</div>
<div>子任务3：n ≤1000，m≤1000；</div>
<div>子任务4：n≤10^4；</div>
<div>子任务5：n = 2^m，a 中所有元素均为2；</div>
<div>子任务6：a 中所有元素均为 2。</div>
<div>子任务7：m = 1；</div>
<div>子任务8：m ≤20；</div>
<div>子任务9：没有特殊的约定。</div>
</div>
<div></div></div>

# Output

<div class="content"><div>第一行输出 a 的长度。第二行输入一些空格隔开的正整数，依次表示 a 的每一项。</div>
<div>第三行输出 b 的长度。第四行输入一些空格隔开的整数，依次表示 b 的每一项。</div>
<div>每一行相邻的两个数，恰好用一个空格隔开。</div>
<div>你必须保证你输出的 b 的每一个元素的绝对值都不超过 10^9。</div>
<div>保证存在一个可行的解满足这个条件。如果有多个可行的解，你可以输出任意一个。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 3 3<br/>
10<br/>
1 0 2 9 3 8 4 7 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2 3 3<br/>
10<br/>
1 -1 1 8 1 -2 3 4 0 -10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

