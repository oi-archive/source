
# Description

<div class="content"><div> SUPER M是一个很经典的游戏</div>
<div> 现在改一下规则</div>
<div> 有<span>N个城堡（0到n-1）</span></div>
<div> 每个城堡都有一个<span>KOOPA，注意：有些KOOPA会可能有1个FATHER-KOOPA</span></div>
<div> 公主在最后一个城堡内（<span>N-1）</span></div>
<div> 现在每次只能打一个城堡且必须在<span>T[I]时间内打完（否则游戏结束）</span></div>
<div> 如果（<span>N-1）号城堡打完</span></div>
<div> 游戏结束</div>
<div> 如果一个<span>KOOPA至少有2个SON-KOOPA被打败</span></div>
<div> 则必须马上去击败这个<span>KOOPA否则会因为愤怒而做掉公主</span></div>
<div> 现在求</div>
<div> 最长游戏时间</div>
<div> </div></div>

# Input

<div class="content"><div>若干组数据（<span>&lt;=10） </span></div>
<div>每组开始一个数<span>N</span></div>
<div>第二行<span>N个数表示T[I](&lt;=100)</span></div>
<div>第三行<span>N个数表示FATHER-KOOPA所在城堡编号（-1表示无FATHER-KOOPA）（最后一个数一定为-1）</span></div>
<div>数据以<span>0结尾</span></div>
<div> </div></div>

# Output

<div class="content"><div> </div>
<div>对于每组数据输出一个数，即最大游戏时间</div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
5 <br/>
1 2 3 4 5<br/>
4 4 4 4 -1<br/>
5<br/>
2 2 2 2 2<br/>
1 2 3 4 -1<br/>
0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
12<br/>
10<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据 n&lt;=100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

