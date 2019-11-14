# 

 
 # 题目背景 
<p>dC在澡堂里和DQS一起愉悦的捡肥皂时，发现dC的肥皂找不到了&hellip;&hellip;于是dC只能去找。</p> 

 
 # 题目描述 
<p>dC和DQS所在的澡堂是一位蒟蒻在闲得蛋疼时随机建造的，而且一共只有N个浴室，通过N-1条通道连接。dC会尝试以两个点X和Y为中心寻找，因为这两个点是dC和DQS曾经一起愉悦的地方，所以他认为肥皂与这两个点的距离均不超过K。但即使这样，他也感觉这些点太多了，于是他想让你帮他进行计算。</p> 

 
 # 输入格式 
<p>输入的第一行一个正整数N，表示这个澡堂的浴室数量。</p>

<p>之后的N-1行，每行三个正整数u、v、l，表示u号浴室与v号浴室之间有一条长度为l的走廊相连。</p>

<p>在之后一行，一个正整数q，表示询问的数量。</p>

<p>之后q行，每行三个正整数X、Y、K，含义见题目描述。</p>

<p>由于dC不想让别人知道自己的路线，于是所有的询问均经过加密，设输入的值为X&rsquo;、Y&rsquo;、K&rsquo;，上一次询问的答案为ans，则实际上的询问为：</p>

<p>X&nbsp;=&nbsp;X&rsquo;&nbsp;xor&nbsp;ans&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Y&nbsp;=&nbsp;Y&rsquo;&nbsp;xor&nbsp;ans&nbsp;&nbsp;&nbsp;&nbsp;K&nbsp;=&nbsp;K&rsquo;&nbsp;xor&nbsp;ans</p>

<p>其中xor为异或运算符。</p>

<p>第一次询问时，ans为0。</p> 

 
 # 输出格式 
<p>对于每次询问，输出一行，一个正整数，表示对应询问的答案。</p> 

 
 # 提示 
<p>对于20%的数据：&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;n，q&nbsp;&lt;=&nbsp;50。</p>

<p>对于30%的数据：&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;n，q&nbsp;&lt;=&nbsp;200。</p>

<p>对于60%的数据：&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;n，q&nbsp;&lt;=&nbsp;1000。</p>

<p>对于100%的数据：&nbsp;1&nbsp;&lt;=&nbsp;n，q&nbsp;&lt;=&nbsp;100000，&nbsp;1&nbsp;&lt;=&nbsp;u，v&nbsp;&lt;=&nbsp;n</p> 
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
1 2 2
2 3 2
2
1 2 4
1 0 1
</td><td>3
2
</td></tr></table>
