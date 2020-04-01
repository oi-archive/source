<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　上课的时候总有一些同学和前后左右的人交头接耳，这是令小学班主任十分头疼的一件事情。不过，班主任小雪发现了一些有趣的现象，当同学们的座次确定 下来之后，只有有限的D对同学上课时会交头接耳。同学们在教室中坐成了M行N列，坐在第i行第j列的同学的位置是（i，j），为了 方便同学们进出，在教室中设置了K条横向的通道，L条纵向的通道。于是，聪明的小雪想到了一个办法，或许可以减少上课时学生交头接耳的问题：她打算重新摆 放桌椅，改变同学们桌椅间通道的位置，因为如果一条通道隔开了两个会交头接耳的同学，那么他们就不会交头接耳了。<br/>
　　请你帮忙给小雪编写一个程序，给 出最好的通道划分方案。在该方案下，上课时交头接耳的学生对数最少。</div>
# 输入格式

<div class="pdcont">　　输入的第一行，有5个用空格隔开的整数，分别是M，N，K，L，D（2&lt;=N，M&lt;=1000，0&lt;=K&lt; M，0&lt;=L&lt;N，D&lt;=2000）。<br/>
　　接下来D行，每行有4个用空格隔开的整数，第i行的4个整数Xi，Yi，Pi，Qi，表 示坐在位置(Xi,Yi)与(Pi,Qi)的两个同学会交头接耳（输入保证他们前后相邻或者左右相邻）。<br/>
　　输入数据保证最优方案的唯一性。</div>
# 输出格式

<div class="pdcont">　　输出共两行。<br/>
　　第一行包含K个整数，a1a2……aK，表示第a1行和a1+1行之间、第a2行和第a2+1行之间、…、第 aK行和第aK+1行之间要开辟通道，其中ai&lt; ai+1，每两个整数之间用空格隔开（行尾没有空格）。<br/>
　　第二行包含L个整 数，b1b2……bk，表示第b1列和b1+1列之间、第b2列和第b2+1列之间、…、第bL列和第bL+1列之间要开辟通道，其中bi&lt;  bi+1，每两个整数之间用空格隔开（行尾没有空格）。</div>
# 样例输入

<div class="pddata">4 5 1 2 3<br/>
4 2 4 3<br/>
2 3 3 3<br/>
2 5 2 4</div>
# 样例输出

<div class="pddata">2<br/>
2 4<br/>
解释：<br/>
<img width="412" height="314" src="source/tsinsen/A1164/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9WThxZUZqUW0=.do"/><br/>
<img src="source/tsinsen/A1164/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9BMTE2NC9odHRwOi8vb2oudHNpbnNlbi5jb20vUmVxdWlyZUZpbGUuZG8_ZmlkPUxyQWdUOXE2.do"/><br/>
上图中用符号*、※、+ 标出了3对会交头接耳的学生的位置，图中3条粗线的位置表示通道，图示的通道划分方案是唯一的最佳方案。</div>
# 数据规模和约定



</div>