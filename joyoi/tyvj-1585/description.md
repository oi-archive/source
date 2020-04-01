# 

 
 # 题目描述 
&nbsp;阿狸喜欢收藏各种稀奇古怪的东西，最近他淘到一台老式的打字机。打字机上只有28个按键，分别印有26个小写英文字母和'B'、'P'两个字母。&nbsp;经阿狸研究发现，这个打字机是这样工作的：<BR>&nbsp;输入小写字母，打字机的一个凹槽中会加入这个字母(按P前凹槽中至少有一个字母)。<BR>&nbsp;按一下印有'B'的按键，打字机凹槽中最后一个字母会消失。<BR>&nbsp;按一下印有'P'的按键，打字机会在纸上打印出凹槽中现有的所有字母并换行，但凹槽中的字母不会消失（保证凹槽中至少有一个字母）。<BR>例如，阿狸输入aPaPBbP，纸上被打印的字符如下：<BR>a<BR>aa<BR>ab<BR>&nbsp;我们把纸上打印出来的字符串从1开始顺序编号，一直到n。打字机有一个非常有趣的功能，在打字机中暗藏一个带数字的小键盘，在小键盘上输入两个数(x,y)（其中1≤x,y≤n），打字机会显示第x个打印的字符串在第y个打印的字符串中出现了多少次。<BR>&nbsp;阿狸发现了这个功能以后很兴奋，他想写个程序完成同样的功能，你能帮助他么？<BR> 

 
 # 输入格式 
从文件type.in中读入数据。<BR>输入的第一行包含一个字符串，按阿狸的输入顺序给出所有阿狸输入的字符。&nbsp;<BR>第二行包含一个整数m，表示询问个数。&nbsp;<BR>接下来m行描述所有由小键盘输入的询问。其中第i行包含两个整数x,&nbsp;y，表示第i个询问为(x,&nbsp;y)。<BR> 

 
 # 输出格式 
输出到文件type.out中。&nbsp;<BR>输出m行，其中第i行包含一个整数，表示第i个询问的答案。<BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1585/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTU4NS9Qcm9ibGVtSW1nLzE1ODUuanBn.jpg" border=0 align=middle><BR> 
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
<tr><td>aPaPBbP
3
1 2
1 3
2 3
</td><td>2
1
0
</td></tr></table>
