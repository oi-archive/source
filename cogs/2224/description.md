# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
求有多少种长度为 \( n \) 的序列 \( A \)，满足以下条件：
</p>
<ul>
<li>
\( 1 \) ~ \( n \) 这 \( n \) 个数在序列中各出现了一次
</li>
<li>
若第 \( i \) 个数 \( A[i] \) 的值为 \( i \)，则称 \( i \) 是稳定的。序列恰好有 \( m \) 个数是稳定的
</li>
</ul>
<p>
满足条件的序列可能很多，序列数对 \( 10 ^ 9 + 7 \) 取模。
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
第一行一个数 \( T \)，表示有 \( T \) 组数据。<br/>
接下来 \( T \) 行，每行两个整数 \( n \)、\( m \)。
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
输出 \( T \) 行，每行一个数，表示求出的序列数。
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
5
</p>
<p>
1 0
</p>
<p>
1 1
</p>
<p>
5 2
</p>
<p>
100 50
</p>
<p>
10000 5000
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
0
</p>
<p>
1
</p>
<p>
20
</p>
<p>
578028887
</p>
<p>
60695423
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
测试点 1 ~ 3：\( T = 1000 \)，\( n \leq 8 \)，\( m \leq 8 \)；<br/>
测试点 4 ~ 6：\( T = 1000 \)，\( n \leq 12 \)，\( m \leq 12 \)；<br/>
测试点 7 ~ 9：\( T = 1000 \)，\( n \leq 100 \)，\( m \leq 100 \)；<br/>
测试点 10 ~ 12：\( T = 1000 \)，\( n \leq 1000 \)，\( m \leq 1000 \)；<br/>
测试点 13 ~ 14：\( T = 500000 \)，\( n \leq 1000 \)，\( m \leq 1000 \)；<br/>
测试点 15 ~ 20：\( T = 500000 \)，\( n \leq 1000000 \)，\( m \leq 1000000 \)。
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
