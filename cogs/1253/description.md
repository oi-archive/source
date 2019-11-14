# 题目描述


<h3>
【原版试题】
</h3>
<p>
<br/>
</p>
<p>
LITTLE SHOP OF FLOWERS
</p>
<p>
PROBLEM
</p>
<p>
You want to arrange the window of your flower shop in a most pleasant way. You have F bunches of flowers, each being of a different kind, and at least as many vases ordered in a row. The vases are glued onto the shelf and are numbered consecutively 1 through V, where V is the number of vases, from left to right so that the vase 1 is the leftmost, and the vase V is the rightmost vase. The bunches are moveable and are uniquely identified by integers between 1 and F. These id-numbers have a significance: They determine the required order of appearance of the flower bunches in the row of vases so that the bunch i must be in a vase to the left of the vase containing bunch j whenever i &lt; j. Suppose, for example, you have bunch of azaleas (id-number=1), a bunch of begonias (id-number=2) and a bunch of carnations (id-number=3). Now, all the bunches must be put into the vases keeping their id-numbers in order. The bunch of azaleas must be in a vase to the left of begonias, and the bunch of begonias must be in a vase to the left of carnations. If there are more vases than bunches of flowers then the excess will be left empty. A vase can hold only one bunch of flowers.
</p>
<p>
Each vase has a distinct characteristic (just like flowers do). Hence, putting a bunch of flowers in a vase results in a certain aesthetic value, expressed by an integer. The aesthetic values are presented in a table as shown below. Leaving a vase empty has an aesthetic value of 0.
</p>
<p>
V A S E S12345 Bunches1 (azaleas) 723-5-24162 (begonias) 521-4 10233 (carnations)-21 5-4-2020
</p>
<p>
According to the table, azaleas, for example, would look great in vase 2, but they would look awful in vase 4.
</p>
<p>
To achieve the most pleasant effect you have to maximize the sum of aesthetic values for the arrangement while keeping the required ordering of the flowers. If more than one arrangement has the maximal sum value, any one of them will be acceptable. You have to produce exactly one arrangement.
</p>
<p>
ASSUMPTIONS
</p>
<p>
· 1 ≤ F ≤ 100  where F is the number of the bunches of flowers. The bunches are numbered 1 through F.
</p>
<p>
· F ≤ V ≤ 100  where V is the number of vases.
</p>
<p>
· -50 ≤ Aij  ≤ 50 where Aij is the aesthetic value obtained by putting the flower bunch i into the vase j. INPUT
</p>
<p>
The input is a text file named flower.inp.
</p>
<p>
· The first line contains two numbers: F, V.
</p>
<p>
· The following F lines: Each of these lines contains V integers, so that Aij is given as the j’th number on the (i+1)’st line of the input file. OUTPUT
</p>
<p>
The output must be a text file named flower.out consisting of two lines:
</p>
<p>
· The first line will contain the sum of aesthetic values for your arrangement.
</p>
<p>
· The second line must present the arrangement as a list of F numbers, so that the k’th number on this line identifies the vase in which the bunch k is put.
</p>
<p>
EVALUATION
</p>
<p>
Your program will be allowed to run 2 seconds.
</p>
<p>
No partial credit can be obtained for a test case.
</p>
<p>
<br/>
</p>
<h3>
【题目描述】
</h3>
<p>
有F束花从左到右插在V个花瓶（1＜＝F＜＝V＜＝100）。花用1—F表示，花瓶用1-V表示，都为整数。花要按照花的标识递增排列，不同的花插在不同花瓶有不同的美学价值（-50--50）.求最大的美学价值的排放方式。
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行两个整数F,V(表示F束花,V个瓶子)
</p>
<p>
以下F行每行V个数表示花放在不同瓶的价值
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
两行,第一行为最大价值,第二行为花的排列方式
</p>
<h3>
【样例输入】
</h3>
<pre>样例1：
2 3
3 4 5
1 2 3
样例2：
3 5 
7 23 -5 -24 16
5 21 -4 10 23
-21 5 -4 -20 20
</pre>
<h3>
【样例输出】
</h3>
<pre>样例1：
7
2 3
样例2：
53 
2 4 5</pre>
<h3>
【来源】
</h3>
<p>
IOI1999 ： http://www.ioi99.org.tr/tasks/flower.html
</p>
