
# Description

<div class="content"><div>给出一个 N 行 M 列的矩阵A, 保证满足以下性质:</div>
<div>M&gt;N。</div>
<div>矩阵中每个数都是 [0,N] 中的自然数。</div>
<div>每行中, [1,N] 中每个自然数都恰好出现一次。这意味着每行中 0 恰好出现 M−N 次。</div>
<div>每列中，[1,N] 中每个自然数至多出现一次。</div>
<div>现在我们要在每行中选取一个非零数，并把这个数之后的数赋值为这个数。我们希望保持上面的性质4，即每列中，[1,N] 中每个自然数仍然至多出现一次。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数 T，表示数据组数。</div>
<div>后面包含 T 组数据，各组数据之间无空行。每组数据以两个正整数 N,M 开始，接下来 N 行，每行 M 个用空格隔开的整数，意义如题所述。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一行。如果有解，则输出 N 个整数，依次表示每一行取的数是多少。（这应该是一个 1 到 N 的排列）如果无解，则输出任意卖萌表情。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 10<br/>
0 1 0 2 3 0 0 4 0 5<br/>
2 0 3 0 0 1 0 5 4 0<br/>
4 2 1 0 0 0 3 0 5 0<br/>
0 3 0 4 0 5 0 1 2 0<br/>
1 0 0 3 2 4 5 0 0 0<br/>
5 10<br/>
0 1 0 2 3 0 0 4 0 5<br/>
2 0 3 0 0 1 0 5 4 0<br/>
4 2 1 0 0 0 3 0 5 0<br/>
0 3 0 4 0 5 0 1 2 0<br/>
1 0 0 3 2 4 5 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 5 3 1 2<br/>
5 4 3 1 2<br/>
<br/>
explanation<br/>
<br/>
两组输入数据是相同的。由于结果不唯一，你可以给出任意一组合法答案</span></div>

# Hint

<div class="content"><p></p><div>对于 100% 的数据，N&lt;200,M&lt;400,T&lt;50。</div><br/>
<div></div><br/>
<div>卖萌表情包括但不限于“\(^o^)/” (不含引号).</div><br/>
<div></div><br/>
<div>由于输入数据较大, 请自行优化输入方法.</div><br/>
<div></div><br/>
<div>请不要提交，期待SPJ</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

