# 

 
 # 题目背景 
<p>&nbsp;&nbsp;&nbsp;&nbsp;马克沃特尼与其他五位宇航员遭遇巨型风暴，外太空之旅只能提前结束。他因为被风暴中的石头砸中，被误认为无法生还而被留在火星。幸运的是，他在火星上得以生还，但他却成了太空鲁宾逊。为了生存并引起NASA的关注，他需要破译同行的刘易斯中校的电脑密码，获得其中的音乐和管理资料。但是，在刘易斯中校的电脑提示中，只有一个字符串。经过研究，这里的字符串是一个和堆有着紧密联系的字符串。</p> 

 
 # 题目描述 
<p>这里的堆是一个无限大的二叉树，有性质：每一个节点有且仅有二个子节点：左、右子节点；每个节点有个数字标点，根节点标号为1，标号为X的左子节点标号为2*X；右子节点标号为2*X+1。</p>

<p>一次在堆上的行走由根出发，经过多次步骤组成，每个步骤用一个字母表示，&rsquo;L&rsquo;或&rsquo;R&rsquo;或&rsquo;P&rsquo;：&lsquo;L&rsquo;表示跳到左子节点；&rsquo;R&rsquo;表示跳到右子节点；&rsquo;P&rsquo;表示暂停一次。行走结束时，最后所停在的节点上的标号就是这次行走的价值。例如：行走：LR的价值是5、RPP的价值是3。一类行走的集合可以用字符&rsquo;L&rsquo;、&rsquo;R&rsquo;、&rsquo;P&rsquo;和&rsquo;*&rsquo;组成的字符串表示，一个&rsquo;*&rsquo;字符表示这次步骤有&rsquo;L&rsquo;、&rsquo;R&rsquo;和&rsquo;P&rsquo;三种选择。这个集合由所有可能的行走组成。例如：集合：L*R，包括3个行走：LLR、LRR和LPR。集合：**，包括：LL、LR、LP、RL、RR、RP、PL、PR和PP。编程求出<strong>给定的一个集合中，所有可能行走的价值之和。</strong></p> 

 
 # 输入格式 
<p>一个长度不超过10000的字符串，仅由&rsquo;L&rsquo;、&rsquo;R&rsquo;、&rsquo;P&rsquo;和&rsquo;*&rsquo;四种字符组成。</p> 

 
 # 输出格式 
<p>输出只有一行，输出一个正整数，表示这个价值和，即刘易斯少校的电脑密码。由于结果太大，请对10007取模。</p> 

 
 # 提示 
<p>对于30%的数据，N&le;100；</p>

<p>对于100%的数据，N&le;10<sup>4</sup>。</p> 
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
<tr><td>L*R</td><td>25</td></tr><tr><td>**</td><td>33</td></tr></table>
