# 

 
 # 题目背景 
<p>&nbsp;</p>

<p><strike>/*</strike><strike>在神秘而遥远的LOI</strike><strike>国度生活着一群神奇的物种&mdash;&mdash;DQS</strike><strike>！</strike></p>

<p><strike>DQS</strike><strike>们有着独特的生活习惯，他们总是喜欢居住在tree</strike><strike>上，而且只有上层住了DQS</strike><strike>下层才能再住。并且每层住的DQS</strike><strike>最多不超过2n<sup>2</sup></strike><strike>个。。。</strike></p>

<p><strike>这一天，DQS</strike><strike>跳下来了！（也就是说刚才的条件一点用都没有~_~</strike><strike>）*/</strike></p>

<p>他们遇到了一只自称为S的dc。但是本身性质为S的DQS们不服，于是他们决定进行摔跤，摔跤获胜者成为王！</p>

<p>（由于DQS和dc们的精力无限，所以每一只DQS&amp;&amp;dc都会同另一部落的每一个人进行一次摔跤）两阵营分别有n，m只DQS和dc，并且每阵营按照1~n和1~m进行体力值分配（体力值同序号相同，LOI之神如是说）</p> 

 
 # 题目描述 
<p>进行比赛时，双方中体力值较大一方会减去另一方的体力值使之作为自己的新体力值，但由于DQS和dc们哲♂学实力雄厚，因此只有当双方的体力值相同时才会停止摔跤。如果此时双方的体力值是一个纯洁的数字，DQS和dc会很高兴地退场，并且将这个数作为这场比赛的得分~~~，但如果只是一般的数字，他们会不开心地退场导致这场比赛没有得分。因为DQS和DC作为LOI不可或缺的一员，所以获得的分数会加入LOI的总分（一场只有一个得分，不要以为两个人就可以得两遍分啊！！！）。</p>

<p>输出LOI最后获得的总分，数据有多组询问。</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20px;">注：纯洁的数字即最后的这个值没有次幂高于1的因子&mdash;&mdash;为了良心，再附上一个神秘的链接</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20px;">http://zh.wikipedia.org/wiki/%E6%97%A0%E5%B9%B3%E6%96%B9%E6%95%B0%E5%9B%A0%E6%95%B0%E7%9A%84%E6%95%B0</p> 

 
 # 输入格式 
<p>第一行一个正整数N表示一共N组数据，接下来N行每行两个正整数n，m</p> 

 
 # 输出格式 
<p>输出有N行，每行一个正整数，表示LOI的总分</p> 

 
 # 提示 
<p>【数据范围】<br />
30%的数据：N&lt;=10,n&lt;=m&lt;=1000<br />
60%的数据：&nbsp;N&lt;=300,n&lt;=m&lt;=600000<br />
100%的数据：&nbsp;N&lt;=10000,n&lt;=m&lt;=1500000</p>

<p>对于样例：</p>

<p>1&nbsp;代表一组数据；</p>

<p>下面1行两个数5&nbsp;5</p>

<p>1和1~5摔跤；2和1~5摔跤；3和1~5摔跤；4和1~5摔跤；5和1~5摔跤；</p>

<p>1和任何人摔跤返回的得分总是1，因为1是最小的。</p>

<p>2和1摔跤得1,2和2摔跤得2,2和3摔跤得1,2和4摔跤得2,2和5摔跤得1；</p>

<p>3和1摔跤得1；3和2摔跤得1；3和3摔跤得3；3和4摔跤得1；3和5摔跤得1；</p>

<p>4和1摔跤得1；4和2摔跤得2；4和3摔跤得1；4和4摔跤得4；5和4摔跤得1；</p>

<p>5和1摔跤得1；5和2摔跤得1；5和3摔跤得1；5和4摔跤得1；5和5摔跤得5；</p>

<p>最后把满足square&nbsp;free&nbsp;number的数加起来（4不是square&nbsp;free&nbsp;number）</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1
5 5</td><td>33</td></tr></table>
