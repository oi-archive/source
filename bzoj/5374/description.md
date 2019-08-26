
# Description

<div class="content"><div>小D有n个std::queue&lt;int&gt;，他把它们编号为1到n。小D对每个队列有不同的喜爱程度，如果有他不怎么喜欢的队列</div>
<div>占用了太大的内存，小D就会不开心。具体地说，如果第i个队列的size()大于a_i，小D就会对这个队列一直执行</div>
<div>pop()直到其size()小等于a_i。现在这些队列都是空的，小D觉得太单调了，于是他决定做一些操作。</div>
<div>每次操作都可以用l r x来描述，表示对编号在[l,r]内的所有队列执行push(x)操作。</div>
<div>当然，每次操作结束后，小D都会用之前提到的方法来避免这些队列占用太大的内存。小D的队列很神奇，所以他能</div>
<div>用O(1)的时间执行每次操作。相信大家的队列都能做到，于是小D把这道题出给大家送分。为了证明你确实执行了</div>
<div>这些操作，你需要在每次操作后输出目前还在队列内的权值种数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n,m，分别表示队列个数和操作个数。</div>
<div>第二行n个正整数，第i个表示a_i。</div>
<div>接下来m行，每行三个正整数l r x，其中第i行表示第i次操作。</div>
<div>对于所有数据，n,m,a_i,x≤10^5。</div>
<p></p></div>

# Output

<div class="content"><div>输出共m行，每行一个非负整数，表示第i次操作结束后所有队列中的权值种数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 3<br/>
1 2 1<br/>
2 3 2<br/>
1 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
样例解释<br/>
第一次操作后，队列变成{1}{1}{}，还在队列内的权值有1，共1种。<br/>
第二次操作后，队列变成{1}{1,2}{2}，还在队列内的权值1,2，共2种。<br/>
第三次操作后，队列变成{3}{2,3}{2,3}，还在队列内的权值有2,3，共2种。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=day1">day1</a></p></div>

