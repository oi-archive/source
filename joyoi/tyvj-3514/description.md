# 

 
 # 题目描述 
<p>
<br>某人有一套玩具，并想法给玩具命名。首先他选择WING四个字母中的任意一个字母作为玩具的基本名字。然后他会根据自己的喜好，将名字中任意一个字母用“WING”中任意两个字母代替，使得自己的名字能够扩充得很长。<br>现在，他想请你猜猜某一个很长的名字，最初可能是由哪几个字母变形过来的。<br><br></p> 

 
 # 输入格式 
<p>
第一行四个整数W、I、N、G。表示每一个字母能由几种两个字母所替代。<br>接下来W行，每行两个字母,表示W可以用这两个字母替代。<br>接下来I行，每行两个字母,表示I可以用这两个字母替代。<br>接下来N行，每行两个字母,表示N可以用这两个字母替代。<br>接下来G行，每行两个字母,表示G可以用这两个字母替代。<br>最后一行一个长度不超过Len的字符串。表示这个玩具的名字。<br><br></p> 

 
 # 输出格式 
<p>
一行字符串，该名字可能由哪些字母变形而得到。（按照WING的顺序输出）<br>如果给的名字不能由任何一个字母变形而得到则输出“The name is wrong!”<br><br></p> 

 
 # 提示 
<p>
W可以变成II所以IIII可以缩成WW<br>IN均能变成WW所以WW又可以缩成I或者N<br>所以最终答案应该按照“WING”的顺序输出IN<br><br>[数据范围]<br>30%数据满足Len<=20，W、I、N、G<=6 <br>100%数据满足Len<=200，W、I、N、G<=16<br></p> 
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
<tr><td>1 1 1 1
II
WW
WW
IG
IIII

</td><td>IN</td></tr></table>
