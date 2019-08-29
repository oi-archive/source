<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　排排坐，吃果果，生果甜嗦嗦，大家笑呵呵。你一个，我一个，大的分给你，小的留给我，吃完果果唱支歌，大家乐和和。<br/>
　　红星幼儿园的小朋友们排起了长长地队伍，准备吃果果。不过因为小朋友们的身高有所区别，排成的队伍高低错乱，极不美观。设第i个小朋友的身高为h<sub>i</sub>，我们定义一个序列的杂乱程度为：满足i&lt;j且h<sub>i</sub>&gt;h<sub>j</sub>的(i,j)数量。幼儿园阿姨每次会选出两个小朋友，交换他们的位置，请你帮忙计算出每次交换后，序列的杂乱程度。为方便幼儿园阿姨统计，在未进行任何交换操作时，你也应该输出该序列的杂乱程度。</div>
# 输入格式

<div class="pdcont">　　第一行为一个正整数n，表示小朋友的数量；<br/>
　　第二行包含n个由空格分隔的正整数h<sub>1</sub>,h<sub>2</sub>,…,h<sub>n</sub>，依次表示初始队列中小朋友的身高；<br/>
　　第三行为一个正整数m，表示交换操作的次数；<br/>
　　以下m行每行包含两个正整数a<sub>i</sub>和b<sub>i­</sub>，表示交换位置a<sub>i</sub>与位置b<sub>i</sub>的小朋友。</div>
# 输出格式

<div class="pdcont">　　输出文件共m行，第i行一个正整数表示交换操作i结束后，序列的杂乱程度。</div>
# 样例输入

<div class="pddata">3<br/>
130 150 140<br/>
2<br/>
2 3<br/>
1 3</div>
# 样例输出

<div class="pddata">1<br/>
0<br/>
3</div>
# 样例说明

<div class="pdcont">　　未进行任何操作时，(2,3)满足条件；<br/>
　　操作1结束后，序列为130 140 150，不存在满足i&lt;j且h<sub>i</sub>&gt;h<sub>j</sub>的(i,j)对；<br/>
　　操作2结束后，序列为150 140 130,(1,2)，(1,3)，(2,3)共3对满足条件的(i,j)。</div>
# 数据规模和约定

<div class="pdcont">　　对于15%的数据，n,m≤15；<br/>
　　对于30%的数据，n,m≤200；<br/>
　　在剩下的70%数据中：<br/>
　　存在15%的数据，h<sub>i</sub>各不相同；<br/>
　　存在15%的数据，110≤h<sub>i</sub>≤160；<br/>
　　以上两类数据不存在交集。<br/>
　　对于100%的数据，1≤m≤2*10<sup>3</sup>，1≤n≤2*10<sup>4</sup>，1≤h<sub>i</sub>≤10<sup>9</sup>，a<sub>i</sub>≠b<sub>i</sub>，1≤a<sub>i</sub>,b<sub>i</sub>≤n。</div>

</div>