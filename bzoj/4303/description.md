
# Description

<div class="content"><div>有一列元素，每一个元素有三个属性:标号、标识符、数值。这些元素按照标号从1~n排列，标识符也是1~n的一个排列，初始时数值为0。当然我们可以把每个元素看成一个多维数字，那么这列元素就是一个数列。 </div>
<div>现在请你维护这个数列，使其能支持以下两种操作：1.将标号为l~r的所有元素的数值先乘上x，再加上y；2.将标识符为l~r的所有元素的数值先乘上x，再加上y。当然你还得回答某些询问：1.标号为l~r的所有元素的数值的和；2.标识符为l~r的所有元素的数值的和。 </div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行有两个正整数n、m，分别表示数列长度和操作与询问个数的总和。第二行有n个正整数，表示每个元素的标识符，保证这n个数是1~n的一个排列。接下来m行，每行的第一个数字为op。若op为0，则表示要进行第一个操作，接下去四个数字表示l,r,x,y;若op为1，则表示要进行第二个操作，接下去四个数字表示l,r,x,y;若op为2，则表示要回答第一个询问，接下去两个数字表示l,r;若op为3，则表示要回答第二个询问，接下去两个数字表示l,r。 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>包含若干行，每行表示一个询问的答案。由于答案可能很大，只要请你输出答案对536870912取模后的值即可。 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 <br/>
2 1 4 3 <br/>
0 2 3 4 5 <br/>
1 1 3 4 7 <br/>
2 1 1 <br/>
3 1 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">7 <br/>
27 </span></div>

# Hint

<div class="content"><p></p><div>第一次操作后，数列变为0 5 5 0 </div><br/>
<div>第二次操作后，数列变为7 27 5 7 </div><br/>
<div>N,M&lt;=50000, 1&lt;=L&lt;=R&lt;=N 0&lt;=X,Y&lt;=2^31-1</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

