
# Description

<div class="content"><div>在OI界，有一个无人不知无人不晓，OI水平前无古人后无来者的胡策，江湖人称一眼秒题胡大爷！</div>
<div>今天胡策正在研究一个远古传下来的数列：a[0]=... , a[1]=... ,对i&gt;1，有 25a[i]+20a[i-1]=12a[i-2]。因为流传的时间太过久远，a[0]和a[1]的值都已经看不清了，但是在最后还记载着，这个数列有一个特别的性质：对于任意的i&gt;=0，都有a[i]&gt;=0。</div>
<div>然而胡大爷已经看穿了一切：对于任意一个正数a[0]，这个数列都是唯一的！但是，他想拿这个问题考一考拜胡大爷为师的你。</div>
<div>具体来说，胡大爷会给你一个长度为n的表格，一开始每个格子都写着0。有时他会让你将a[0]=t 时数列从第p项开始的一段写入表格中第 l 到第 r 格（覆盖原有的值），有时他会询问表格中某一段连续的格子中的数的和。</div>
<div>当然，作为胡大爷的弟子，你必须在胡大爷提出一个询问的时候马上作出回应。</div>
<div></div>
<div>因为这是一个远古的问题，胡大爷只给了你一台远古的计算机，它只有64MB的内存。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,m。分别表示表格的长度和操作个数。</div>
<div>接下来m行，每行描述一个操作。每行的第一个整数type描述了操作的类型，type=1表示是修改操作，type=2表示是询问操作。</div>
<div>如果是修改操作，接下来有四个整数l,r,t,p，意义如上所述。</div>
<div>如果是询问操作，接下来有两个整数l,r，意义如上所述。</div>
<div>为了体现在线，实际的l,r为输入的l,r对lastans取异或后的答案。lastans表示上一次询问操作的答案，初始为0。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对每个询问操作输出一行，表示询问的答案。</div>
<div>为了避免实数，输出对10^9+9取模。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 1 3 2 3<br/>
1 2 2 4 5<br/>
2 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">867840008</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1&lt;=n&lt;=10^9，1&lt;=m&lt;=10^5，1&lt;=t&lt;=10^9，1&lt;=p&lt;=10^9，1&lt;=l&lt;=r&lt;=n。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测">2015年集训队互测</a></p></div>

