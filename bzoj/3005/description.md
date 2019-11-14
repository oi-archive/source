
# Description

<div class="content"><div style="margin: 17pt 0cm 16.5pt" align="center"></div>
<div><span style="font-size: medium">       又是一节体育课的时间了，有n个同学排成了一排。他们都很讨厌排在第一个位置的同学，于是后面的同学中比第一个高的都会产生一个高兴值，这个高兴值等于他的身高减去第一个同学的身高。当然比第一个同学矮的同学产生兴奋值为0。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在体育老师来了，他拥有神奇的魔法，现在他能做如下的三件事：</span></div>
<div><span style="font-size: medium">       1：询问某段区间高兴值最大的那个是多少。</span></div>
<div><span style="font-size: medium">       2：把某两个同学交换一下位置。</span></div>
<div><span style="font-size: medium">       3：选取一段区间的人，把第一个人身高加上t，第二个加上2t，第三个加上3t以此类推。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">但是体育老师不会数数，于是他找到你了，对于每一个询问，他要你帮他求出那个值。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第一行两个整数n,m表示有n个人，有m个操作。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第二行n个整数，顺序输入每个人的身高。（身高&lt;=10^8）</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来m行，每行第一个数位一个type表示是做哪一件事情。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt"><span style="font-size: medium">如果type=1，那么接下来有两个整数l，r，表示询问这段区间的最大的高兴值</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt"><span style="font-size: medium">如果Type=2，接下来两个整数a，b，表示交换这两个位置的人</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: 21pt"><span style="font-size: medium">如果type=3，接下来三个整数l,r,t，表示把l个人的升高增加t,l+1个人增加2t…第r个人增加(r-l+1)t, (0&lt;=t&lt;= 10000)</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">对于每个询问按照顺序输出每个操作1的答案。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 7 <br/>
10 9 8 7 6 5 4 3 2 1 <br/>
1 4 7 <br/>
3 2 4 3 <br/>
1 2 3 <br/>
1 3 6 <br/>
2 1 10 <br/>
1 8 10 <br/>
1 2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
4<br/>
6<br/>
9<br/>
13<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100的数据：n,m&lt;=100000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

