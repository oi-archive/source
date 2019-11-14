
# Description

<div class="content"><div>排排坐，吃果果，生果甜嗦嗦，大家笑呵呵。你一个，我一个，大的分给你，小的留给我，吃完果果唱支歌，大家</div>
<div>乐和和。红星幼儿园的小朋友们排起了长长地队伍，准备吃果果。不过因为小朋友们的身高有所区别，排成的队伍</div>
<div>高低错乱，极不美观。设第i个小朋友的身高为hi，我们定义一个序列的杂乱程度为：满足ihj的(i,j)数量。幼儿</div>
<div>园阿姨每次会选出两个小朋友，交换他们的位置，请你帮忙计算出每次交换后，序列的杂乱程度。为方便幼儿园阿</div>
<div>姨统计，在未进行任何交换操作时，你也应该输出该序列的杂乱程度。</div></div>

# Input

<div class="content"><div>第一行为一个正整数n，表示小朋友的数量；</div>
<div>第二行包含n个由空格分隔的正整数h1,h2,…,hn，依次表示初始队列中小朋友的身高；</div>
<div>第三行为一个正整数m，表示交换操作的次数；</div>
<div>以下m行每行包含两个正整数ai和bi，表示交换位置ai与位置bi的小朋友。</div>
<div>1≤m≤2*10^3，1≤n≤2*104，1≤hi≤109，ai≠bi，1≤ai,bi≤n。</div></div>

# Output

<div class="content"><p>输出文件共m行，第i行一个正整数表示交换操作i结束后，序列的杂乱程度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入】<br/>
3<br/>
130 150 140<br/>
2<br/>
2 3<br/>
1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
3<br/>
【样例说明】<br/>
未进行任何操作时，(2,3)满足条件；<br/>
操作1结束后，序列为130 140 150，不存在满足i<j且hi>hj的(i,j)对；<br/>
操作2结束后，序列为150 140 130,(1,2)，(1,3)，(2,3)共3对满足条件的(i,j)</j且hi></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

