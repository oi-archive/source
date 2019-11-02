# 

 
 # 题目描述 
<p>Hanks&nbsp;博士是BT&nbsp;(Bio-Tech，生物技术)&nbsp;领域的知名专家。现在，他正在为一个细胞实<br />
验做准备工作：培养细胞样本。<br />
Hanks&nbsp;博士手里现在有N&nbsp;种细胞，编号从1~N，一个第i&nbsp;种细胞经过1&nbsp;秒钟可以分裂为<br />
Si&nbsp;个同种细胞（Si&nbsp;为正整数）。现在他需要选取某种细胞的一个放进培养皿，让其自由分裂，<br />
进行培养。一段时间以后，再把培养皿中的所有细胞平均分入M&nbsp;个试管，形成M&nbsp;份样本，<br />
用于实验。Hanks&nbsp;博士的试管数M&nbsp;很大，普通的计算机的基本数据类型无法存储这样大的<br />
M&nbsp;值，但万幸的是，M&nbsp;总可以表示为m1&nbsp;的m2&nbsp;次方，即2<br />
1<br />
M&nbsp;=&nbsp;m1^m2&nbsp;，其中m1，m2&nbsp;均为基本<br />
数据类型可以存储的正整数。<br />
注意，整个实验过程中不允许分割单个细胞，比如某个时刻若培养皿中有4&nbsp;个细胞，<br />
Hanks&nbsp;博士可以把它们分入2&nbsp;个试管，每试管内2&nbsp;个，然后开始实验。但如果培养皿中有5<br />
个细胞，博士就无法将它们均分入2&nbsp;个试管。此时，博士就只能等待一段时间，让细胞们继<br />
续分裂，使得其个数可以均分，或是干脆改换另一种细胞培养。<br />
为了能让实验尽早开始，Hanks&nbsp;博士在选定一种细胞开始培养后，总是在得到的细胞&ldquo;刚<br />
好可以平均分入M&nbsp;个试管&rdquo;时停止细胞培养并开始实验。现在博士希望知道，选择哪种细<br />
胞培养，可以使得实验的开始时间最早。</p> 

 
 # 输入格式 
<p>输入文件名为&nbsp;cell.in，共有三行。<br />
第一行有一个正整数&nbsp;N，代表细胞种数。<br />
第二行有两个正整数&nbsp;m1，m2，以一个空格隔开,m1^m2即表示试管的总数M。<br />
第三行有&nbsp;N&nbsp;个正整数，第i&nbsp;个数Si&nbsp;表示第i&nbsp;种细胞经过1&nbsp;秒钟可以分裂成同种细胞的个<br />
数。</p> 

 
 # 输出格式 
<p>输出文件&nbsp;cell.out&nbsp;共一行，为一个整数，表示从开始培养细胞到实验能够开始所经过的<br />
最少时间（单位为秒）。<br />
如果无论&nbsp;Hanks&nbsp;博士选择哪种细胞都不能满足要求，则输出整数-1。</p> 

 
 # 提示 
<p>NOIP2009普及组&nbsp;第三题&nbsp;1&lt;=N&lt;=10000,1&lt;=m1&lt;=30000,1&lt;=m2&lt;=10000,1&lt;=Si&lt;=2000000000;</p> 
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
2 1
3</td><td>-1</td></tr></table>
