# 

 
 # 题目描述 
<p>
栅栏的木料（fence.pas\c\cpp）<br><br>【题目描述】<br>　　农民John准备建一个栅栏来围住他的牧场。他已经确定了栅栏的形状，但是他在木料方面有些问题。当地的杂货储存商扔给John一些木板，而John必须从这些木板中找出尽可能多所需的木料。 <br>　　当然，John可以切木板。因此，一个9英尺的木板可以切成一个5英尺和一个4英尺的木料 (当然也能切成3个3英尺的，等等)。John有一把梦幻之锯，因此他在切木料时，不会有木料的损失。 <br>　　所需要的木料规格都已经给定。你不必切出更多木料，那没有用。<br></p> 

 
 # 输入格式 
<p>
　　输入文件fence.in:<br>　　第1行: N (1 <= N <= 50), 表示提供的木板的数目 <br>　　第2行到第N+1行: N行，每行包括一个整数，表示各个木板的长度。 <br>　　第N+2行: R (1 <= R <= 1023), 所需木料的数目 <br>　　第N+3行到第N+R+1行: R行，每行包括一个整数(1 <= ri <= 128)表示所需木料的长度。 <br></p> 

 
 # 输出格式 
<p>
　　输出文件fence.out只有一行，一个数字，表示能切出的最多的所需木料的数目。当然，并不是任何时候都能切出所有所需木料。 </p> 
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
30
40
50
25
10
15
16
17
18
19
20
21
25
24
30
</td><td>7</td></tr></table>
