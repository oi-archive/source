# 

 
 # 题目背景 
<h2>版权</h2>

<p style="line-height: 20.8px;">GZEZ拥有本资料的所有版权！</p> 

 
 # 题目描述 
<p>伟哥去了澳门赌场。(ps.大家没事不要去赌场(⊙o⊙)哦)由于他运气太好赢了很多，赌场老板拿出了撒搜剑，派出一头灰熊（外号），十分凶猛。灰熊带了十几个保安来到伟哥面前，要求跟伟哥赌一把。规则如下：给出一堆筹码共n个，每一次可以取2＾k（0&le;k&le;log2(n)）,最后取完者胜。如果伟哥赢了就可以将所有筹码换为rmb带回家，否则&hellip;&hellip;,这时伟哥不知如何是好，便打电话找到了聪明机智的你，你能帮他解决问题吗？</p>

<p>注意：双方都用最佳方案。</p> 

 
 # 输入格式 
<p>第一行有一个整数n。</p>

<p>第二行一个字符串，若为&ldquo;Wei&nbsp;Ge&rdquo;则伟哥先取，若为<span style="line-height: 20.8px;">&ldquo;</span><span style="line-height: 1.6em;">Hui&nbsp;Xiong</span><span style="line-height: 20.8px;">&rdquo;</span><span style="line-height: 1.6em;">则灰熊先取。</span></p> 

 
 # 输出格式 
<p>如果伟哥先取获胜则输出&ldquo;Win!&rdquo;与第一次取的最小的个数。</p>

<p>如果伟哥后取获胜则输出&ldquo;Win!&rdquo;.</p>

<p>如果伟哥无法获胜则输出&ldquo;Lost!&rdquo;。</p>

<p>（标点全部用英文。注意！与!的区别。）</p> 

 
 # 提示 
<h2><span style="line-height: 1.2em;">数据范围</span></h2>

<p>对于30%的数据&nbsp;1&le;n&le;10000</p>

<p>对于60%的数据1&le;n&le;1000000</p>

<p>对于100%的数据1&le;n&le;100000000</p>

<p>&nbsp;</p> 
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
<tr><td>3
Wei Ge</td><td>Lost!</td></tr><tr><td>10
Wei Ge</td><td>Win! 1</td></tr></table>
