# 题目描述


<h3>
【题目描述】
</h3>
<p>
有一个 \( n \) 行 \( m \) 列的表格，行从 \( 0 \) 到 \( n - 1 \) 编号，列从 \( 0 \) 到 \( m - 1 \) 编号。<br/>
每个格子都储存着能量。最初，第 \( i \) 行第 \( j \) 列的格子储存着 \( (i \ {\rm xor} \ j) \) 点能量。所以，整个表格储存的总能量是，
</p>
<p>
\[ \sum\limits_{i = 0} ^ {n - 1} \sum\limits_{j = 0} ^ {m - 1} (i \ {\rm xor} \ j) \]
</p>
<p>
随着时间的推移，格子中的能量会渐渐减少。一个时间单位，每个格子中的能量都会减少 \( 1 \)。显然，一个格子的能量减少到 \( 0 \) 之后就不会再减少了。<br/>
也就是说，\( k \) 个时间单位后，整个表格储存的总能量是，
</p>
<p>
\[ \sum\limits_{i = 0} ^ {n - 1} \sum\limits_{j = 0} ^ {m - 1} \max((i \ {\rm xor} \ j) - k, 0) \]
</p>
<p>
给出一个表格，求 \( k \) 个时间单位后它储存的总能量。<br/>
由于总能量可能较大，输出时对 \( p \) 取模。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数 \( T \)，表示数据组数。<br/>
接下来 \( T \) 行，每行四个整数 \( n \)、\( m \)、\( k \)、\( p \)。
</p>
<h3>
【输出格式】
</h3>
<p>
共 \( T \) 行，每行一个数，表示总能量对 \( p \) 取模后的结果。
</p>
<h3>
【样例输入】
</h3>
<pre>3
2 2 0 100
3 3 0 100
3 3 1 100
</pre>
<h3>
【样例输出】
</h3>
<pre>2
12
6
</pre>
<h3>
【提示】
</h3>
<p>
测试点 1 ~ 2：\( T = 5000 \)，\( n \leq 100 \)，\( m \leq 100 \)，\( k \leq 100 \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 3：\( T = 5000 \)，\( n \leq 10 ^ {18} \)，\( m \leq 10 ^ {18} \)，\( k = 0 \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 4：\( T = 5000 \)，\( n \leq 10 ^ {18} \)，\( m \leq 10 ^ {18} \)，\( k = 1 \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 5：\( T = 5000 \)，\( n \leq 10 \)，\( m \leq 10 ^ {18} \)，\( k \leq 10 \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 6：\( T = 1 \)，\( n \leq 10 ^ 5 \)，\( m \leq 10 ^ {18} \)，\( k \leq 10 ^ 5 \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 7：\( T = 1 \)，\( n \leq 10 ^ {18} \)，\( m \leq 10 ^ {18} \)，\( k \leq 10 ^ {18} \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 8：\( T = 100 \)，\( n \leq 10 ^ {18} \)，\( m \leq 10 ^ {18} \)，\( k \leq 10 ^ {18} \)，\( p \leq 10 ^ 9 \)；<br/>
测试点 9 ~ 10：\( T = 5000 \)，\( n \leq 10 ^ {18} \)，\( m \leq 10 ^ {18} \)，\( k \leq 10 ^ {18} \)，\( p \leq 10 ^ 9 \)。
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
