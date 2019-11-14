# 

 
 # 题目描述 
<p>Alice和Bob正在悄悄地给对方发信息，信息都是由英文小写字母组成的，他们约定，所有的字母都得经过一个字母表进行变换，以防泄漏。另一方面John却在监听。</p>

<p>John发现，Alice和Bob通信的时候，总是先发送加密后的密文，然后紧接着发送原文。</p>

<p>但是Alice和Bob似乎也意识到了似乎有人监听，有时候会随意中断了他们的通信。不过每次都是在发送完密文之后才停止传送的。也就是说，John截获到的信息是密文的全文以及前一部分原文。原文可能一个字符都没有，也可能原文的全文都被截获。</p>

<p>现在John比较头疼，他虽然已经得到了他们两个人通信的加密字母表，但是分不清楚什么地方是密文和明文的分界线。你能帮他还原回完整的传输内容吗？</p>

<p>如果有多种可能时，John认为那个最短的信息才是原始的。</p> 

 
 # 输入格式 
<p>第一行是密码表格，包含26个小写字母，依次表示a-z加密后的字母。</p>

<p>第二行是John截获到的通信信息。</p> 

 
 # 输出格式 
<p>包含一行，表示还原后的通信信息。</p> 

 
 # 提示 
<p>通信长度L&lt;=100000。</p> 
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
<tr><td>abcdefghijklmnopqrstuvwxyz
abcdab</td><td>abcdabcd</td></tr><tr><td>qwertyuiopasdfghjklzxcvbnm
qwertabcde</td><td>qwertabcde</td></tr></table>
