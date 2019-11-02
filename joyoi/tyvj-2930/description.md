# 

 
 # 题目描述 
<p>
<br><img src="/source/joyoi/tyvj-2930/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkzMC9wcm9ibGVtc19pbWFnZXMvMzUwMS9wZy5qcGc=.jpg"></img><br><br><img src="/source/joyoi/tyvj-2930/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkzMC9wcm9ibGVtc19pbWFnZXMvMzUwMS9wZzIuanBn.jpg"></img></p> 

 
 # 输入格式 
<p>
文件deskmate.in 第一行为两个整数N 和M，表示电脑的行、列数。<br>以下有N行，每行有M 个由一个空格分隔的仅含大写字母的字符串，分别表示每台电脑前的oier<br>的信息。<br>其中第一行表示最前面一排，第N 行表示最后面一排。<br>这个字符串要么是一个单独的X，表示此位置没有人；要么为大写字母F,B,L,R 的组合(每个<br>至多一个)，分别表示这个人能够和前、后、左、右的人进行“问旁边的”。字符串长度最少为1。<br>比如：FL 表示可以问前、左的人。RBF 则表示可以问右、后、前的人。</p> 

 
 # 输出格式 
<p>
文件deskmate.out 应该只有一行，为一个整数，表示最多有多少oier 可以“问旁边的”。<br></p> 

 
 # 提示 
<p>
样例1 解释<br>"R"和"F"中有一个无法“问旁边的”，其余的6 个都可以。<br>另外可以注意到数据中可能有无效的，比如第一排第二个的"F"和"R"都是无效的，因为那里根<br>本没有人。<br>数据规模<br>共8 个测试点，37%的数据满足N,M<33，100%的数据满足2 < N, M < 101。</p> 
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
<tr><td>样例1 输入
3 3
RB LFR X
FB R LB
FR X F
样例2 输入
3 4
R L X B
B R L F
F X BR L</td><td>样例1 输出
6
样例2 输出
10</td></tr></table>
