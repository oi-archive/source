
# Description

<div class="content"><p><span style="font-size: medium"> 阿狸和桃子养了n个小阿狸, 小阿狸们每天都在一起玩的很开心. 作为工程师的阿狸在对小阿狸们之间的关系进行研究以后发现了小阿狸的人际关系由某种神奇的相互作用决定,  阿狸称之为“键”. 每个键有一个频率, 称为键频率, 是一个整数(单位Hz).<br/>
 由于小阿狸们每天成集团地黏在一起, 桃子希望他们能够分成更加独立的几团. 阿狸发现, 一旦小阿狸们分开, 独立的一块连在一起的几个小阿狸就会形成一个家族, 而家族的类型由这个家族的小阿狸的数量唯一确定(比如说只有一个小阿狸的家族显然就是单身码农, 两个小阿狸的显然是一对小阿狸恋人, 三个小阿狸的就是三口之家等等). 显然, 一个小阿狸和另一个小阿狸处于同一家族, 当且仅当两个小阿狸之间存在直接或间接的键组成的路径.<br/>
 桃子对每种小阿狸家族都有自己的喜好程度, 她希望所有的小阿狸家族喜好程度之和大于等于K.<br/>
 为了让小阿狸们分开来, 阿狸决定让某些键断裂, 只保留某一段频率的键, 比如说100Hz到140Hz频率的键, 这时频段宽度为40Hz. 当然, 阿狸希望频段宽度越小越好, 但至少要有一个小键. 你的任务就是求出最小的频段宽度.<br/>
 注意, 输入不保证全部键都有效时只有一个小阿狸家族.</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"> 第一行3个整数n(&lt;=1000), m(&lt;=5000), K(0~2^31-1).<br/>
 接下来1行n个整数, 第k的整数表示桃子对大小为k的小阿狸家族的喜爱程度.<br/>
 接下来m行, 每行3个整数, u, v, f. 表示u小阿狸和小阿狸v之间存键, 频率f Hz.</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"> 一个整数, 即最窄的频段宽度(不存在可行频段, 输出&#34;T_T&#34;, 不含引号).</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"> 4 4 52<br/>
 1 50 2 9<br/>
 1 2 6<br/>
 2 3 8<br/>
 3 4 4<br/>
 1 4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 0<br/>
 (解释:频段3Hz~3Hz或4Hz~4Hz或6Hz~6Hz或8Hz~8Hz)<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据, n &lt;=1000 , m &lt;=3000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

