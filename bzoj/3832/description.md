
# Description

<div class="content"><div>An annual bicycle rally will soon begin in Byteburg. The bikers of Byteburg are natural long distance cyclists. Local representatives of motorcyclists, long feuding the cyclists, have decided to sabotage the event.</div>
<div>There are   intersections in Byteburg, connected with one way streets. Strangely enough, there are no cycles in the street network - if one can ride from intersection U to intersection V , then it is definitely impossible to get from V to U.</div>
<div>The rally&#39;s route will lead through Byteburg&#39;s streets. The motorcyclists plan to ride their blazing machines in the early morning of the rally day to one intersection and completely block it. The cyclists&#39; association will then of course determine an alternative route but it could happen that this new route will be relatively short, and the cyclists will thus be unable to exhibit their remarkable endurance. Clearly, this is the motorcyclists&#39; plan - they intend to block such an intersection that the longest route that does not pass through it is as short as possible.</div>
<div></div>
<div>
<div>给定一个N个点M条边的有向无环图，每条边长度都是1。</div>
<div>请找到一个点，使得删掉这个点后剩余的图中的最长路径最短。</div>
<div></div>
</div>
<p></p></div>

# Input

<div class="content"><div>In the first line of the standard input, there are two integers, N and M(2&lt;=N&lt;=500 000,1&lt;=M&lt;=1 000 000), separated by a single space, that specify the number of intersections and streets in Byteburg. The intersections are numbered from   to  . The   lines that follow describe the street network: in the  -th of these lines, there are two integers, Ai, Bi(1&lt;=Ai,Bi&lt;=N,Ai&lt;&gt;Bi), separated by a single space, that signify that there is a one way street from the intersection no. Ai to the one no. Bi.</div>
<div>
<div></div>
<div>
<div>第一行包含两个正整数N,M(2&lt;=N&lt;=500 000,1&lt;=M&lt;=1 000 000)，表示点数、边数。</div>
<div>接下来M行每行包含两个正整数A[i],B[i](1&lt;=A[i],B[i]&lt;=N,A[i]&lt;&gt;B[i])，表示A[i]到B[i]有一条边。</div>
<div></div>
</div>
</div>
<p></p></div>

# Output

<div class="content"><div>The first and only line of the standard output should contain two integers separated by a single space. The first of these should be the number of the intersection that the motorcyclists should block, and the second - the maximum number of streets that the cyclists can then ride along in their rally. If there are many solutions, your program can choose one of them arbitrarily.</div>
<div></div>
<div>
<div>包含一行两个整数x,y，用一个空格隔开，x为要删去的点，y为删除x后图中的最长路径的长度，如果有多组解请输出任意一组。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 5<br/>
1 3<br/>
1 4<br/>
3 6<br/>
3 4<br/>
4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供SPJ及译文">鸣谢Claris提供SPJ及译文</a></p></div>

