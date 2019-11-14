# 题目描述


<h3>
【题目描述】
</h3>
<p>
Pine 开始了从 \( S \) 地到 \( T \) 地的征途。
</p>
<p>
从 \( S \) 地到 \( T \) 地的路可以划分成 \( n \) 段，相邻两段路的分界点设有休息站。<br/>
Pine 计划用 \( m \) 天到达 \( T \) 地。除第 \( m \) 天外，每一天晚上 Pine 都必须在休息站过夜。所以，一段路必须在同一天中走完。<br/>
Pine 希望每一天走的路长度尽可能相近，所以他希望每一天走的路的长度的方差尽可能小。<br/>
帮助 Pine 求出最小方差是多少。
</p>
<p>
设方差是 \( v \)，可以证明，\( v \times m ^ 2 \) 是一个整数。为了避免精度误差，输出结果时输出 \( v \times m ^ 2 \)。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个数 \( n \)、\( m \)。
</p>
<p>
第二行 \( n \) 个数，表示 \( n \) 段路的长度。
</p>
<h3>
【输出格式】
</h3>
<p>
一个数，最小方差乘以 \( m ^ 2 \) 后的值。
</p>
<h3>
【样例输入】
</h3>
<p>
5 2
</p>
<p>
1 2 5 8 6
</p>
<h3>
【样例输出】
</h3>
<p>
36
</p>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于 \( 30\% \) 的数据，\( 1 \leq n \leq 10 \)。<br/>
对于 \( 60\% \) 的数据，\( 1 \leq n \leq 100 \)。<br/>
对于 \( 100\% \) 的数据，\( 1 \leq n \leq 3000 \)。<br/>
保证从 \( S \) 到 \( T \) 的总路程不超过 \( 30000 \)。
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
<p>
数据已由出题人修正
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
