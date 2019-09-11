# 题目描述


<h3>
【题目描述】
</h3>
<p>
Alice 和 Bob 在玩一个游戏。
</p>
<p>
游戏在一棵有 \( n \) 个点的树上进行。最初，每个点上都只有一个数字，那个数字是 \( 123456789123456789 \)。<br/>
有时，Alice 会选择一条从 \( s \) 到 \( t \) 的路径，在这条路径上的每一个点上都添加一个数字。对于路径上的一个点 \( r \)，若 \( r \) 与 \( s \) 的距离是 \( dis \)，那么 Alice 在点 \( r \) 上添加的数字是 \( a \times dis + b \)。<br/>
有时，Bob 会选择一条从 \( s \) 到 \( t \) 的路径。他需要先从这条路径上选择一个点，再从那个点上选择一个数字。<br/>
Bob 选择的数字越小越好，但大量的数字让 Bob 眼花缭乱。Bob 需要你帮他找出他能够选择的最小的数字。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个数字 \( n \)、\( m \)，表示树的点数和进行的操作数。
</p>
<p>
接下来 \( n - 1 \) 行，每行三个数字 \( u \)、\( v \)、\( w \)，表示树上有一条连接 \( u \)、\( v \) 的边，长度是 \( w \)。<br/>
接下来 \( m \) 行。每行第一个数字是 \( 1 \) 或 \( 2 \)。<br/>
若第一个数是 \( 1 \)，表示 Alice 进行操作，接下来四个数字 \( s \)、\( t \)、\( a \)、\( b \)。<br/>
若第一个数是 \( 2 \)，表示 Bob 进行操作，接下来四个数字 \( s \)、\( t \)。
</p>
<h3>
【输出格式】
</h3>
<p>
每当 Bob 进行操作，输出一行一个数，表示他能够选择的最小的数字。
</p>
<h3>
【样例输入】
</h3>
<p>
3 5
</p>
<p>
1 2 10
</p>
<p>
2 3 20
</p>
<p>
2 1 3
</p>
<p>
1 2 3 5 6
</p>
<p>
2 2 3
</p>
<p>
1 2 3 -5 -6
</p>
<p>
2 2 3
</p>
<h3>
【样例输出】
</h3>
<p>
123456789123456789
</p>
<p>
6
</p>
<p>
-106
</p>
<h3>
【提示】
</h3>
<p>
测试点 1 ~ 2：\( n \leq 10 \)，\( m \leq 10 \)，\( \mid a \mid \leq 10000 \)；
</p>
<p>
测试点 3 ~ 4：\( n \leq 1000 \)，\( m \leq 1000 \)，\( \mid a \mid \leq 10000 \)；<br/>
测试点 5：\( n \leq 100000 \)，\( m \leq 100000 \)，\( a = 0 \)，树是一条链；<br/>
测试点 6 ~ 7：\( n \leq 100000 \)，\( m \leq 100000 \)，\( a = 0 \)；<br/>
测试点 8：\( n \leq 100000 \)，\( m \leq 100000 \)，\( a = 1 \)，树是一条链；<br/>
测试点 9 ~ 10：\( n \leq 100000 \)，\( m \leq 100000 \)，\( a = 1 \)；<br/>
测试点 11 ~ 13：\( n \leq 100000 \)，\( m \leq 100000 \)，\( \mid a \mid \leq 10000 \)，树是一条链；<br/>
测试点 14 ~ 20：\( n \leq 100000 \)，\( m \leq 100000 \)，\( \mid a \mid \leq 10000 \)。
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
