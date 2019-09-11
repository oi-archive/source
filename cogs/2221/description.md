# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
有 \( n \) 种数字，第 \( i \) 种数字是 \( a_i \)、有 \( b_i \) 个，权值是 \( c_i \)。
</p>
<p>
若两个数字 \( a_i \)、\( a_j \) 满足，\( a_i \) 是 \( a_j \) 的倍数，且 \( \frac{a_i}{a_j} \) 是一个质数，那么这两个数字可以配对，并获得 \( c_i \times c_j \) 的价值。
</p>
<p>
一个数字只能参与一次配对，可以不参与配对。<br/>
在获得的价值总和不小于 \( 0 \) 的前提下，求最多进行多少次配对。
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
第二行 \( n \) 个整数 \( a_1 \)、\( a_2 \)、……、\( a_n \)。<br/>
第三行 \( n \) 个整数 \( b_1 \)、\( b_2 \)、……、\( b_n \)。<br/>
第四行 \( n \) 个整数 \( c_1 \)、\( c_2 \)、……、\( c_n \)。
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
一行一个数，最多进行多少次配对。
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
3
</p>
<p>
2 4 8
</p>
<p>
2 200 7
</p>
<p>
-1 -2 1
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
4
</p>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
测试点 1 ~ 3：\( n \leq 10 \)，\( a_i \leq 10 ^ 9 \)，\( b_i = 1 \)，\( \mid c_i \mid \leq 10 ^ 5 \)；<br/>
测试点 4 ~ 5：\( n \leq 200 \)，\( a_i \leq 10 ^ 9 \)，\( b_i \leq 10 ^ 5 \)，\( c_i = 0 \)；<br/>
测试点 6 ~ 10：\( n \leq 200 \)，\( a_i \leq 10 ^ 9 \)，\( b_i \leq 10 ^ 5 \)，\( \mid c_i \mid \leq 10 ^ 5 \)。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
SDOI2016 Round1 Day1
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
