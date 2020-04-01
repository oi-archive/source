<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>dxy has a collection of a series of books called "The
Stories of SDOI",There are n books in this series.Every book has a
number from 1 to n.</p><p><br><br>dxy puts these books in a book stack with the
order of their numbers increasing from top to bottom. dxy takes great care of
these books and no one is allowed to touch them.<br><br>One day Evensgn visited
dxy's home, because dxy was dating with his girlfriend, dxy let Evensgn stay at
home himself. Evensgn was curious about this series of books.So he took a look
at them. He found out there was a story about "Little E&amp;Little Q". While
losing himself in the story,he disrupted the order of the books.<br><br>Knowing
that dxy would be back soon,Evensgn needed to get the books ordered again.But
because the books were too heavy.The only thing Evensgn could do was to take out
a book from the book stack and and put it at the stack top. <br><br>Give you the
order of the disordered books.Could you calculate the minimum steps Evensgn
would use to reorder the books? If you could solve the problem for him,he will
give you a signed book "The Stories of SDOI 9: The Story of Little E" as a
gift.<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>There are several testcases.<br><br>There is an positive integer T
in the first line standing for the number of testcases.<br><br>For each
testcase, there is an positive integer n in the first line standing for the
number of books in this series.<br><br>Followed n positive integers separated
by space standing for the order of the disordered books,the i<sup>th</sup> integer stands
for the i<sup>th</sup> book's number(from top to bottom).<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>For each testcase,output one line for an integer
standing for the minimum steps Evensgn would use to reorder the books.</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>2
4
4 1 2 3
5
1 2 3 4 5</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>3
0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>Hint:</strong>For the first testcase,Moving in the order of book3,book2,book1,(4,1,2,3)→(3,4,1,2)→(2,3,4,1)→(1,2,3,4),and
this is the best way to reorder the books.<br>For the second testcase,It's
already ordered so there is no operation needed.</p><hr><p>50%n&lt;=10;</p><p>another30%n&lt;=1000;<br></p><p>100%n&lt;=100000<br></p>
</div>
</div>