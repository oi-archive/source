# 题目描述


<p>【题目描述】</p>
<p>  有N组学生，给出初始时每组中的学生个数，再给出每组学生人数的上界R和下届L(L&lt;=R)，每次你可以在某组中选出一个学生把他安排到另外一组中，问最少要多少次才可以使N组学生的人数都在[L,R]中。</p>
<p>【输入格式】</p>
<p>第一行一个整数N，表示学生组数； <br/>
第二行N个整数，表示每组的学生个数； <br/>
第三行两个整数 L，R，表示下界和上界</p>
<p>【输出格式】</p>
<p>一个数，表示最少的交换次数，如果不能满足题目条件输出-1</p>
<p>【输入样例】 <br/>
2<br/>
10 20<br/>
10 15</p>
<p>【输出样例】 <br/>
5</p>
<p>【数据规模】 <br/>
n&lt;=50   L&lt;=R   其他数在[1,1000000]中</p>