
# Description

<div class="content"><p>幽香是幻想乡中一个非常有地位的人。她日理万机，事务繁多，反倒自己已经快管理不过来了。于是他决定开发一个日程管理软件来帮助自己管理任务。 </p>
<div>对于每个任务i有一个对应的截止日期ti以及收益pi，表示若幽香能在不晚于第ti天完成这个任务，便可以得到pi的收益。幽香办事的能力非常强，任何任务都可以用恰好一天的时间做完。但由于任务实在太多了，有时候并不能完成所有任务，于是幽香会想知道这个情况下，完成任务可以给她带来的最大的累积收益是多少。 </div>
<div>由于幻想乡的人们十分善变，任务总是不断发生着变化。幽香希望这个管理软件还能够支持插入一个任务，和删除一个任务的操作。 </div>
<div>具体的说，幽香希望支持以下2个操作： </div>
<div>1.ADD t p：表示新添一个截止日期为t，收益为p的任务。 </div>
<div>2.DEL t p：表示删除一个截止日期为t，收益为p的任务。如果有多个这样的任务，只删除一个。数据保证这样的任务一定存在。 </div>
<div>在每次操作执行完毕后，你都需要输出能够完成的任务的最大收益和。 </div>
<div>幽香一共有T天需要安排，从第1天到第T天。你能帮助他写出这个高效率的软件吗？ </div></div>

# Input

<div class="content"><p>第一行有两个证书T和Q，表示天数和操作的个数。 </p>
<div>接下来Q行，其中第i行表示第i个操作，形式为ADD t p或DEL t p，其具体意义如题面所述。 </div></div>

# Output

<div class="content"><p>对每一次操作，输出一个整数在执行完该操作后幽香能够获得的最大收益和。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
ADD 1 5811<br/>
ADD 3 5032<br/>
DEL 3 5032<br/>
ADD 3 5550<br/>
ADD 5 3486<br/>
DEL 1 5811<br/>
DEL 3 5550<br/>
ADD 4 5116<br/>
ADD 3 9563<br/>
ADD 5 94</span></div>

# Sample Output

<div class="content"><span class="sampledata">5811<br/>
10843<br/>
5811<br/>
11361<br/>
14847<br/>
9036<br/>
3486<br/>
8602<br/>
18165<br/>
18259</span></div>

# Hint

<div class="content"><p></p><p><span style="font-family: 幼圆; line-height: 24px; background-color: rgb(205, 237, 226);">T&lt;=300000，Q&lt;=300000</span></p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

