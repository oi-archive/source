
# Content

小明今天就满五岁了，隔壁的王叔叔送了他一支铅笔做生日礼物。小明还不到上小学的年龄，不知道这根长长的棍子是做什么用的，所以他把这支可怜的铅笔当棍子玩了。他把它叫“金箍棒”，这是前几天才从动画片里看到的词语。动画片里面孙大大就是用金箍棒打跑了一个个长得吓人的大怪物，想着自己也有了“金箍棒”，小明十分开心。

![.*](/source/lutece/ma-ma-wo-gou-bu-zhao-555/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY0LzIwMTQwMjAyMjI0OTE0MDU5MjQucG5n.png)

小明从来都是个爱突发奇想的孩子，他喜欢给自己出难题。拿着手中的“棍子”，他发现自己站在原地就可以够到离自己很远的东西。他把张阿姨送的糖果盒子打开然后把糖果洒在了地上，然后在原地站直了，尝试只是改变手和棍子的姿势把糖果重新收集起来放回盒子里。当然，小明站在原地是可以转动的。小明会很努力的不让自己的手臂弯曲的，所以你可以认为小明的手臂是一条线段。凡是被小明的铅笔碰到的都算被小明收集了，被手碰到的不算。
请你来告诉大家，小明能把所有的糖果重新收集起来吗？

# Standard Input

输入会给出小明以及糖果的信息。输入第一行是$T$。$T$表示测试部分的个数，每一部分都要求单独计算并按照要求输出结果。

接下来是每个测试部分。第一行给出$X$, $Y$, $L$, $R$, $N$，分别表示小明的位置的坐标是$(X,Y)$,小明手臂的长度为$L$,王叔叔送的铅笔长度为$R$，有$N$个糖果($0 < N\leq 10000$)。之后每行给出一个糖果的坐标$(x_i,y_i)$，$0\leq i < N$。
输入的所有数都是整型，且都在$0$到$10000$之间，详细情况请参照输入样例。

# Standard Output

对于每个测试部分，如果小明能够收集到全部的糖果，那么请输出`Oh yeah!`。如果小明一个也收集不到，请输出`Mom,I cannot touch it...555`。其他情况，请输出小明能收集到的糖果总数。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
0 0 3 2 5
1 0
0 2
1 3
2 2
5 0
0 0 3 2 6
1 0
0 2
1 3
2 2
5 0
100 100
0 0 3 2 2
100 100
10000 0</td><td>Oh yeah!
5
Mom,I cannot touch it...555</td></tr></table>


# Constraints



# Note

**为了避免发生不必要的错误，请把结果需要的输出文字直接拷贝。**

# Source


