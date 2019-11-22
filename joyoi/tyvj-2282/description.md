# 

 
 # 题目描述 
<p>
在编译器理论中，一个表达式是使用一棵树来表示的，其实根为运算符，子节点为分解出的子表达式。在实际编译时，一个运算符只有当它所有子节点代表的表达式都求出以后，它才能够做相应的运算。<br>编译的时候，内存里有一种特殊的储存器“Register”，如果将得出的表达式储存到Register中，可以加快存取速度，但是由于Register数量有限，不能存入的表达式就只好用主Memory来存储，这样的话就会造成时间上的浪费。所以决定如何使用Register可以提高编译的效率。<br>具体的编译过程如下：<br><br>1．	对于一个非叶子节点，选任意一个子节点，进行运算（递归）<br>2．	计算完以后，对于计算出的数值，可以选择存入Register或者存入主Memory。<br>a)	 若存入Register，那么存取时间不计，但是在计算其他子节点表达式时，这个Register是不可用的。<br>b)	若存入主Memory，存入需要Cs的时间，以后如果要调用这个值，还需要Cl的时间来调用。<br>3．重新返回1，直到所有的子节点表达式都处理完毕。<br>4．这个时候，将所有存入主Memory的数值从主Memory中读入到Register中，一个数值占用一个Register。<br>5．将所有Register中的数值按照根节点代表的运算符进行运算，得出结果。<br>6．然后将所有使用到的Register清空。<br><br>所有的叶子节点代表的是数值，且必须从主Memory中读入，每种运算符计算时使用的时间各有不同。现要你决定编译的顺序和Register的使用，使得总运算时间最少。<br><br><br></p> 

 
 # 输入格式 
<p>
N（Register个数）<br>Cl,Cs<br>一个数Kx，表示根节点的子节点个数。<br>如果Kx>0，那么x就是一个非叶子节点，代表一个运算符，接下来一个数Cx代表这个运算符要使用的时间。<br>然后接下来就使用相同的格式来描述x的Kx个子节点。<br><br></p> 

 
 # 输出格式 
<p>
总计算时间<br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2282/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI4Mi9wcm9ibGVtc19pbWFnZXMvMjY1My8xMzc0XzEuanBn.jpg"></p> 
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
<tr><td>2
3 2
2
10
2
15
0
0
2
5
0
0

</td><td>47</td></tr></table>
