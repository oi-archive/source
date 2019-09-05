# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
魔咒串由许多魔咒字符组成，魔咒字符可以用数字表示。例如可以将魔咒字符 \( 1 \)、\( 2 \) 拼凑起来形成一个魔咒串 \( [1, 2] \)。<br/>
一个魔咒串 \( S \) 的非空字串被称为魔咒串 \( S \) 的生成魔咒。<br/>
例如 \( S = [1, 2, 1] \) 时，它的生成魔咒有 \( [1] \)、\( [2] \)、\( [1, 2] \)、\( [2, 1] \)、\( [1, 2, 1] \) 五种。\( S = [1, 1, 1] \) 时，它的生成魔咒有 \( [1] \)、\( [1, 1] \)、\( [1, 1, 1] \) 三种。<br/>
最初 \( S \) 为空串。共进行 \( n \) 次操作，每次操作是在 \( S \) 的结尾加入一个魔咒字符。每次操作后都需要求出，当前的魔咒串 \( S \) 共有多少种生成魔咒。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行一个整数 \( n \)。<br/>
第二行 \( n \) 个数，第 \( i \) 个数表示第 \( i \) 次操作加入的魔咒字符。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出 \( n \) 行，每行一个数。第 \( i \) 行的数表示第 \( i \) 次操作后 \( S \) 的生成魔咒数量。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
7
</p>
<p>
1 2 3 3 3 1 2
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
<br/>
</p>
<p>
1
</p>
<p>
3
</p>
<p>
6
</p>
<p>
9
</p>
<p>
12
</p>
<p>
17
</p>
<p>
22
</p>
<p>
<br/>
</p>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于 \( 10\% \) 的数据，\( 1 \leq n \leq 10 \)。<br/>
对于 \( 30\% \) 的数据，\( 1 \leq n \leq 100 \)。<br/>
对于 \( 60\% \) 的数据，\( 1 \leq n \leq 1000 \)。<br/>
对于 \( 100\% \) 的数据，\( 1 \leq n \leq 100000 \)。
</p>
<p>
用来表示魔咒字符的数字 \( x \) 满足 \( 1 \leq x \leq 10 ^ 9 \)。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
SDOI2016 Round1 Day2
</p>
<style>span.math span { border-left-width: 0 !important; }</style>
<script type="text/x-mathjax-config">
if (typeof MathJaxListener !== 'undefined') {
  MathJax.Hub.Register.StartupHook('End', function () {
    MathJaxListener.invokeCallbackForKey_('End');
  });
}
</script>
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
