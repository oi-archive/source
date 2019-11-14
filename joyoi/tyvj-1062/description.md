# 

 
 # 题目背景 
从前有一堆傻子，钟某人要合并他们~<BR>但是，合并傻子是要掉RP的...... 

 
 # 题目描述 
在一个园形操场的四周站着N个傻子,现要将傻子有次序地合并成一堆.规定每次只能选相邻的2个傻子合并成新的一个傻子，并将新的一个傻子的RP数，记为该次合并的RP数。<BR>（合并方法与NOI1999石子合并（本题库的沙子合并）相同，请大家参考上题合并方法）<BR>将N个傻子合并成1个的最小RP数为RPn和最大RP数为RPx.<BR>钟某人要合并他们，钟某人现在的RP为m,但是他要小心....<BR>if&nbsp;m&gt;RPx&nbsp;then&nbsp;钟某人能很轻松的合并他们，并说出&nbsp;‘It&nbsp;is&nbsp;easy’<BR>else&nbsp;if&nbsp;m&lt;RPn&nbsp;钟某人很担心，因为他必然由此变成一个沙茶，这时他要说：‘I&nbsp;am..Sha...X’（以便提升RP）<BR>else&nbsp;&nbsp;&nbsp;钟某人仍然担心自己可能成为一个沙茶，所以他要金蝉脱壳说：‘I&nbsp;will&nbsp;go&nbsp;to&nbsp;play&nbsp;WarIII’ 

 
 # 输入格式 
数据的第1行试正整数n和m(1≤N≤100,m在longint范围之内）表示有N个傻子.第2行有N个数,分别表示合并每个傻子的所掉的RP数<BR> 

 
 # 输出格式 
输出文件仅一行包含一个句子表示钟某人说的话。 

 
 # 提示 
傻子+傻子=? 
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
<tr><td>4 -9999
4 4 5 9</td><td>I am..Sha...X</td></tr></table>
