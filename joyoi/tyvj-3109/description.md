# 

 
 # 题目描述 
<p>
关于负进制：<br><br><img src="/source/joyoi/tyvj-3109/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEwOS9wcm9ibGVtc19pbWFnZXMvMTMxMC8xLmJtcA==.bmp"></img><br><br>问题求解   <br>　　设计一个程序，读入一个十进制数和一个负进制数的基数, 并将此十进制数转换为此负进制下的数：<br>　　－Ｒ∈｛－２，－３，－４，．．．，－２０｝　<br><br>【输入】   <br>　　输入的每行有两个输入数据。<br>　　第一个是十进制数Ｎ（－32768 ＜＝ Ｎ ＜＝ 32767）；  第二个是负进制数的基数－Ｒ。<br><br>【输出】   <br>　　结果显示在屏幕上，相对于输入，应输出此负进制数及其基数，若此基数超过１０，则参照１６进制的方式处理。<br><br>【样例输入】<br>30000　-2<br>-20000　-2<br>28800　-16<br>-25000　-16<br><br>【样例输出】<br>30000=１１０１１０１０１０１１１００００（-2）<br>-20000=１１１１０１１０００１０００００（-2）<br>28800=19180（-16）<br>-25000=7FB8（-16）<br><br>注意：实际输入输出格式见样例！<br><br></p> 

 
 # 输入格式 
<p>
</p> 

 
 # 输出格式 
<p>
</p> 
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
<tr><td>-25000　-16   {两数之间有一个空格}</td><td>7FB8（-16）</td></tr></table>
