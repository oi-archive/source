# 题目描述


<h3>
【题目描述】
</h3>
<div>
<p>
A factory produces products packed in square packets of the same height h and of the sizes 1*1, 2*2, 3*3, 4*4, 5*5, 6*6. These products are always delivered to customers in the square parcels of the same height h as the products have and of the size 6*6. Because of the expenses it is the interest of the factory as well as of the customer to minimize the number of parcels necessary to deliver the ordered products from the factory to the customer. A good program solving the problem of finding the minimal number of parcels necessary to deliver the given products according to an order would save a lot of money. You are asked to make such a program.
</p>
<p>
<br/>
</p>
<p>
一个工厂生产了一些一样高h，且长*宽是1*1或2*2或3*3或4*4或5*5或6*6规格的产品。这些产品通常用高为h(和产品一样)，且长*宽是6*6的包裹打包起来邮给顾客。由于工厂包邮的所以说他们希望邮费尽可能少，顾客也希望拿包裹更加方便，因此他们共同希望包裹的数目尽可能少。给你每种规格产品的数目，写一个程序求装下这些产品需要的最小包裹数。
</p>
<p>
<br/>
</p>
</div>
<h3>
【输入格式】
</h3>
<div>
<p>
The input file consists of several lines specifying orders. Each line specifies one order. Orders are described by six integers separated by one space representing successively the number of packets of individual size from the smallest size 1*1 to the biggest size 6*6. The end of the input file is indicated by the line containing six zeros.
</p>
<p>
<br/>
</p>
<p>
输入文件包括多组数据，每组数据一行，每行由六个由空格分开的整数组成，分别描述六种规格(顺序为从1*1到6*6)产品的数目。文件由&#39;0 0 0 0 0 0&#39;结尾。(共计N行)
</p>
<p>
<br/>
</p>
</div>
<h3>
【输出格式】
</h3>
<div>
<p>
The output file contains one line for each line in the input file. This line contains the minimal number of parcels into which the order from the corresponding line of the input file can be packed. There is no line in the output file corresponding to the last ``null&#39;&#39; line of the input file.
</p>
<p>
<br/>
</p>
<p>
对于输出文件，每组数据输出一行，每行一个整数，表示装下对应输入文件中的产品所需要的最小包裹数。(输入文件中的&#39;0 0 0 0 0 0&#39;应被忽略，则输出文件共计N-1行)
</p>
<p>
<br/>
</p>
</div>
<h3>
【样例输入】
</h3>
<pre class="sio">0 0 4 0 0 1
7 5 1 0 0 0
0 0 0 0 0 0 </pre>
<h3>
【样例输出】
</h3>
<pre class="sio">2
1 </pre>
<h3>
【提示】
</h3>
<div>
<a href="searchproblem?field=source&amp;key=Central+Europe+1996">Central Europe 1996</a> 
</div>
<h3>
【来源】
</h3>
<p>
POJ 1017
</p>
<p>
译byKZFFFFFFFF
</p>
