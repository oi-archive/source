# 

 
 # 题目描述 
<p>
众所周知，Index数是指十进制表示每一位都由4和7组成的正整数。<br>【问题描述】<br><br>　　Index的一本魔导书中记录了这样一个问题。<br>　　有N条线段，第i条为[li，ri]，你每次可以将某个线段移至[li-1,ri-1]或[li+1,ri+1]，即左移或右移一个单位。<br>　　我们说数轴上的一个点x是index点当且仅当：<br>　　1.　x是index数，且<br>　　2.　被说有线段包含<br>　　现在给你这N条线段，允许你最多操作K次，使得index点的个数最多，并输出这个数目。<br></p> 

 
 # 输入格式 
<p>
第一行两个数N,K。<br>接下来N行，每行两个数li,ri。<br></p> 

 
 # 输出格式 
<p>
一个数，即最多的index点的个数。</p> 

 
 # 提示 
<p>
【数据规模】<br>有约25%较小的数据。<br>对于100%的数据有1≤N≤10^5,1≤K，li，ri≤10^18<br></p> 
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
<tr><td>样例输入1：
4 7
1 4
6 9
4 7

样例输入2：
3 5
2 7
40 45
47 74</td><td>样例输出1：
1

样例输出2：
2</td></tr></table>
