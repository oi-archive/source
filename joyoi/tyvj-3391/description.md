# 

 
 # 题目描述 
<p>
师生树（tree.pas\c\cpp）<br><br>【题目描述】<br>　　假设用<A,B>表示字符A，B有师生关系且B是A的1代学生（字符A~Z，0~9共36个）。若给出＜A,B＞，＜B,C＞则C是A的2代学生。若给出＜A,B＞，＜B,C＞，＜C,D＞，＜D,E＞，＜B,E＞，则E是A的2代学生，如果无最后一个关系＜B,E＞，则E是A的4代学生。如果某人没有老师，则称为师祖。所有具有师生关系的人组成一个师生树。<br>　　任务：从数据文件中输入一组关系，求出师生树的总数并分别输出各师生树的成员，输出各师生树的成员时，首先输出师祖，再依次输出各代学生，各代学生间用“，”分隔，同代学生中按ASCII码由小到大顺序输出。如果在求解的过程中找不出师生树则输出“NO answer!”。<br></p> 

 
 # 输入格式 
<p>
输入文件tree.in格式如下：<br>5                 ------表示有N组关系<br>＜A,B＞             ------每行有一组关系，共N行<br>＜B,C＞<br>＜A,E＞<br>＜B,E＞<br>＜D,E＞<br></p> 

 
 # 输出格式 
<p>
输出文件tree.out格式：<br>1：A，BE，C   ------ 表示该师生树成员表<br>2：D，E<br>total=2       ------ 表示师生树总数<br></p> 
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
<tr><td>5
＜A,B＞ 
＜B,C＞
＜A,E＞
＜B,E＞
＜D,E＞
</td><td>1：A，BE，C
2：D，E
total=2</td></tr></table>
