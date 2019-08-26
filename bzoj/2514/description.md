
# Description

<div class="content"><div style="text-indent: 21pt; line-height: 150%"><span style="font-size: medium">A公司正在举办一个智力双人游戏比赛 --- 取石子游戏，游戏的获胜者将会获得A公司提供的丰厚的奖金，因此吸引了来自许多全国各地许多聪明的选手前来参加。</span></div>
<div style="text-indent: 21pt; line-height: 150%"><span style="font-size: medium">和经典的取石子游戏规则相比，A公司这次的取石子游戏规则复杂了很多：</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt; line-height: 150%"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">       </span>总共有<i>N</i>堆石子依次排成一行，第<i>i</i>堆石子有<i>a<sub>i</sub></i>个石子。</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt; line-height: 150%"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">       </span>初始的时候有一些石子堆已经被A公司故意拿走。</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt; line-height: 150%"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">       </span>两个玩家轮流来取石子，每次每个玩家可以取走一堆中的所有石子，但是有一个限制条件：<b>一个玩家如果要取走一堆石子，必须这堆石子相邻的某一堆石子已经被取走</b>(被某一个玩家取走或者初始的时候已经被拿走)。注意第1堆石子只和第2堆石子相邻，第<i>N</i>堆石子只和第<i>N</i>-1堆石子相邻，其余的第<i>i</i>堆石子与第<i>i</i>-1堆和第<i>i</i>+1堆石子相邻。</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt; line-height: 150%"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">       </span>当所有石子都被取走，游戏结束。谁最后取得的总石子数最多，谁就获得了这场游戏的胜利。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; line-height: 150%"><span style="font-size: medium">作为这次比赛的参赛者之一，同样绝顶聪明的你，想知道对于任何一场比赛，如果先手</span></div>
<div style="line-height: 150%"><span style="font-size: medium">者和后手者都使用最优的策略，最后先手和后手分别能够取得的总石子数是多少。</span></div>
<div style="text-indent: 21pt; line-height: 150%" align="left"></div></div>

# Input

<div class="content"><div style="text-indent: 21pt; line-height: 150%" align="left"><span style="font-size: medium">输入文件第一行是一个正整数<i>N</i>，表示石子的堆数。</span></div>
<div style="text-indent: 21pt; line-height: 150%" align="left"><span style="font-size: medium">第二行包含<i>N</i>个非负整数<i>a<sub>i</sub></i>，分别表示每一堆石子的石子数，其中如果<i>a<sub>i</sub></i>=0表示这一堆石子已经在最开始被A公司故意拿走。</span></div>
<div style="line-height: 150%"></div></div>

# Output

<div class="content"><div style="line-height: 150%"><span style="font-size: medium">       输出文件只有一行，两个整数用空格隔开，分别表示在最优决策下先手能够取得的总石子数和后手能够取得的总石子数。</span></div>
<div style="text-indent: 22pt" align="left"></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 2 0 3 7 4 0 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 17 9<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例说明<br/><br/>
       两个玩家在最优决策下取石子的顺序依次为9, 2, 1, 4, 7, 3，因此先手取得了9 + 1 + 7 = 17个石子，后手取得了2 + 4 + 3 = 9个石子。<br/><br/>
数据范围<br/><br/>
30%的数据中，2 ≤ N ≤ 100；。<br/><br/>
100%的数据中，2 ≤ N ≤ 1,000,000，0 ≤ ai≤ 100,000,000，并且至少有一堆石子ai=0。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2010福建集训">2010福建集训</a></p></div>

