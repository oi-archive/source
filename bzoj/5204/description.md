
# Description

<div class="content"><div>为了总结过去一段时间的命题工作，王队长组织了“我最喜欢的题目”评选活动，并邀请各位选手给题目进行投票</div>
<div>。具体来说，每道题目有一个正整数作为它的编号，一共有n名选手给它们进行投票，每位选手投且仅投给一道题</div>
<div>，其中第i位选手所投票的题目编号为ai,由于投票的选手众多，所以王队长请你来帮忙统计得票数。你需要找出收</div>
<div>获选手投票最多的题目数量与他们的编号，并按从小到大的顺序列出这些编号。但这里有一个例外情况：如果所有</div>
<div>被投票的题目得票数都相同，则王队长认为这次活动比较失败，你应该输出-1。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入数据第一行包含一个正整数T，表示测试数据的组数，各组数据之间没有空行。</div>
<div>接下来2T行，依次描述每组数据：</div>
<div>每组数据包含两行，其中第一行包含一个正整数n，表示参与这次活动的选手人数。</div>
<div>第二行包含n个由空格隔开的正整数a1～an，其中第i个数ai表示第i位选手所投票的题目编号。</div>
<div>N&lt;=100000,Ai&lt;=10^9</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出应由T组数据组成，各组数据之间没有空行。对于每一组数据：</div>
<div>若没有出现题面所述的例外情况，则这组测试数据输出两行，</div>
<div>其中第一行输出一个正整数m，表示收获选手投票最多的题目数量，</div>
<div>第二行按从小到大的顺序输出m个正整数，表示这些题目的编号。</div>
<div>若出现题面所述的例外情况，则这组测试数据输出一行，请输出-1。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
10<br/>
2 6 1 2 1 1 2 6 7 1<br/>
10<br/>
10 3 6 6 3 10 6 6 6 2<br/>
10<br/>
8 8 10 10 10 10 8 5 8 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1<br/>
6<br/>
1<br/>
8</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 3 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/何昊天　命题/何昊天　验题/丁子钧</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus3</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

