# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
* 第 1 行: 用空格隔开的两个整数N和P

 
 # 输出格式 
<p>
第 1 行: 一个整数, 所需要的总时间(包含和在你所在的牧场的奶牛的两次谈话时间).
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
<tr><td>5 7
10
10
20
6
30
1 2 5
2 3 5
2 4 12
3 4 17
2 5 15
3 5 6
4 5 12

输入解释:

              +-(15)-+
             /        \
            /          \
     1-(5)-2-(5)-3-(6)--5
            \   /(17)  /
         (12)\ /      /(12)
              4------+

</td><td>
176
输出解释:

保持这些路径:

     1-(5)-2-(5)-3      5
            \          /
         (12)\        /(12)
             *4------+

从牧场4起床, 然后按照 4, 5, 4, 2, 3, 2, 1, 2, 4 的顺序来访问奶牛们, 总共
需要176个单位的时间.
</td></tr></table>