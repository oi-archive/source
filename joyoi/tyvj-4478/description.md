# 

 
 # 题目描述 
<p>物理学家栋栋最近在研究一个能量场。在这个能量场中有n个粒子，每个粒子都有两个属性：质量m和结合系数c。&nbsp;</p>

<p>栋栋发现，在这个能量场中，每个粒子都有两极，N极和S极。两个粒子相遇时，符合&ldquo;同极相斥，异极相吸&rdquo;的原则，只能是一个粒子的N极和另一个粒子的S极连接到一起。当质量为m<sub>a</sub>，结合系数为c<sub>a</sub>的粒子a的N极与另一个质量为m<sub>b</sub>，结合系数为c<sub>b</sub>的粒子b的S极直接连接时，可以产生大小为m<sub>a</sub>m<sub>b</sub>(c<sub>a</sub>&nbsp;&ndash;&nbsp;c<sub>b</sub>)的结合能量。<br />
请解决以下两个问题：&nbsp;</p>

<p>1.&nbsp;在能量场的n个粒子中哪两个粒子直接连接的能量最大。&nbsp;</p>

<p>2.&nbsp;栋栋发明了一种方法，能选择其中的任意k个粒子p1,&nbsp;p2,&nbsp;&hellip;,&nbsp;pk，将pi的<br />
N极与pi+1的S极连接(1&nbsp;&le;&nbsp;i&nbsp;&lt;&nbsp;k)，&nbsp;pk的N极与p1的S极连接，&nbsp;其中p1,&nbsp;p2,&nbsp;&hellip;,&nbsp;pk两两不同。k可以在1至n中任意取值，如使用栋栋的这种方法连接，选择哪些粒子可以得到最大的能量。</p> 

 
 # 输入格式 
<p>第一行包含一个整数n，表示粒子的个数。&nbsp;</p>

<p>接下来n行，每行两个实数，第i+1行的两个实数表示第i个粒子的质量mi和结合系数ci。(0&lt;&nbsp;mi,&nbsp;ci&nbsp;&lt;10<sup>5</sup>)&nbsp;</p> 

 
 # 输出格式 
<p>第一行包含两个整数a,&nbsp;b，表示将粒子a的N极与粒子b的S极连接可以得到最大的能量。&nbsp;</p>

<p>第二行包含一个整数k，表示第二问中要得到最大的能量需要多少个粒子。</p>

<p>第三行包含k个整数，表示p1,&nbsp;p2,&nbsp;&hellip;,&nbsp;pk，即第二问中的最优方案。</p> 

 
 # 提示 
<h3>样例说明</h3>

<p>对于第一问，第三个粒子的N极与第二个粒子的S极连接，能得到的能量为5*3*(4&ndash;1)&nbsp;=&nbsp;45。&nbsp;</p>

<p>对于第二问，顺次连接1,&nbsp;3,&nbsp;2号粒子，能量为&nbsp;<br />
1*5*(2&ndash;4)&nbsp;+&nbsp;5*3*(4&ndash;1)&nbsp;+&nbsp;3*1*(1&ndash;2)&nbsp;=&nbsp;32。</p>

<h3>数据规模</h3>

<p>10%的数据，n&nbsp;&le;&nbsp;8；</p>

<p>20%的数据，n&nbsp;&le;&nbsp;15；</p>

<p>40%的数据，n&nbsp;&le;&nbsp;1&nbsp;000；</p>

<p>50%的数据，n&nbsp;&le;&nbsp;5&nbsp;000；</p>

<p>100%的数据，n&nbsp;&le;&nbsp;50&nbsp;000。</p>

<h3>SPJ</h3>

<p>此题使用了spj，评分标准如下：</p>

<blockquote>
<p>此题可能有多解，如果用你的解产生的能量与参考答案的绝对误差或相对误差小于10<sup>&ndash;5</sup>，则得满分。否则不得分。&nbsp;</p>

<p>对于本题，每问的分数各占50%。如果你的输出任何一问的格式或结果不正确，则不得分；否则如果其中的一问正确，则得到该测试点50%的分数；如果两问都正确，得到该测试点100%的分数。</p>
</blockquote> 
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
<tr><td>4 
1.0 2.0 
3.0 1.0 
5.0 4.0 
2.0 2.0</td><td>3 2 
3 
1 3 2</td></tr></table>
