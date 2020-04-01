
# Description

<div class="content"><p>营业额统计 Tiger最近被公司升任为营业部经理，他上任后接受公司交给的第一项任务便是统计并分析公司成立以来的营业情况。 Tiger拿出了公司的账本，账本上记录了公司成立以来每天的营业额。分析营业情况是一项相当复杂的工作。由于节假日，大减价或者是其他情况的时候，营业额会出现一定的波动，当然一定的波动是能够接受的，但是在某些时候营业额突变得很高或是很低，这就证明公司此时的经营状况出现了问题。经济管理学上定义了一种最小波动值来衡量这种情况： 该天的最小波动值  当最小波动值越大时，就说明营业情况越不稳定。 而分析整个公司的从成立到现在营业情况是否稳定，只需要把每一天的最小波动值加起来就可以了。你的任务就是编写一个程序帮助Tiger来计算这一个值。 第一天的最小波动值为第一天的营业额。 	输入输出要求</p></div>

# Input

<div class="content"><div>第一行为正整数 ，表示该公司从成立一直到现在的天数，接下来的n行每行有一个整数(有可能有负数) ，表示第i</div>
<div>天公司的营业额。</div>
<div>天数n&lt;=32767,</div>
<div>每天的营业额ai &lt;= 1,000,000。</div>
<div>最后结果T&lt;=2^31</div>
<p></p></div>

# Output

<div class="content"><p>输出文件仅有一个正整数，即Sigma(每天最小的波动值) 。结果小于2^31 。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
5<br/>
1<br/>
2<br/>
5<br/>
4<br/>
6	</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
</span></div>

# Hint

<div class="content"><p></p><p>结果说明：5+|1-5|+|2-1|+|5-5|+|4-5|+|6-5|=5+4+1+0+1+1=12</p><br/>
<p>该题数据bug已修复.----2016.5.15</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

