# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
挑兮达兮，在城阙兮。一日不见，如三月兮。
</p>
<p>
 聪明的cl已经成功解决了他们遇到的难题。于是他们在月下观落英余息，花凋未散。对于每一朵花，按一定顺序排列，并有一个编号，每一个编号均小于2147483647。共有两排这样的花，依次种在河畔，对于其中的一排，各个编号各不相同，但是对于排与排之间，编号可能相同。聪明的cl想要和叶子玩一个采花游戏，cl在第一排的花中依次选出几个花朵，叶子在另一排中依次选择跟cl同编号的花朵。
</p>
<p>
比如，第一排花朵是编号分别是1,3,233,5,4,6.第二排编号为5,3,19,4,7,6,10,9.cl可以选{3,4,6}，这样叶子可以在第二排中挑选出{3,4,6}。但是cl不能挑选{1,3,4,6}(因为第二排3前没有1)或者{3,5,4,6}(因为第二排虽然有5但是跟第一排的相对位置不同)。
</p>
<p>
现在可爱的叶子想要为难一下cl，于是问cl他应该怎么选使剩下的花儿最少，聪明的cl想了1s，就想出来了。但是他想考一考你，让你也来做一做这么有趣的题目。
</p>
<p>
ps:第二排花朵中第一个编号保证一定在第一排中存在。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行两个数m,n
</p>
<p>
第二行m个数表示第一排花的编号
</p>
<p>
第三行n个数表示第二排花的编号
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
一行一个数x,表示剩下的花最少的数量
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
<p>
【样例输入1】
</p>
<p>
6 8
</p>
<p>
1 3 233 5 4 6
</p>
<p>
5 3 19 4 7 6 10 9
</p>
<p>
 【样例输出1】
</p>
<p>
8
</p>
<p>
 【样例输入2】
</p>
<p>
7 8
</p>
<p>
1 7 5 4 8 3 9
</p>
<p>
1 4 3 5 6 2 8 9
</p>
<p>
【样例输出2】
</p>
<p>
 7
</p>
<br/>
</h3>
<h3>
<p>
【数据范围】
</p>
<p>
 对于前30%的数据n,m&lt;=10
</p>
<p>
 对于另40%的数据n,m&lt;=3000
</p>
<p>
 对于另30%的数据n,m&lt;=50000
</p>
<p>
【重要提示】
</p>
<p>
 对于所有数据总保证在两个数列中第一个数是相同的
</p>
</h3>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
cl
</p>