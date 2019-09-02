

# 读者请注意，原题中的一些词语已经被改成了有关奶牛的双关语。



# 相邻两项的


<p>
<span style="font-family:Times New Roman, Times, serif;"><br/>
</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;"><img src="/upload/image/20131031/20131031211305_69210.png" alt=""/><br/>
</span> 
</p>
<p>
<br/>
</p>
<p>
<img src="/upload/image/20131031/20131031211325_75944.png" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">计算并确定最佳齿轮组合（其中 F 个前齿轮，R 个后齿轮），使方差最小（传动比率至少是 3x）。</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;font-size:medium;"><b>PROGRAM NAME: cowcycle</b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;font-size:medium;"><b>INPUT FORMAT(file cowcycle.in)</b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">第一行是 F 和 R，表示前齿轮和后齿轮的数量。第二行包括 4 个数字：F1，F2（25 &lt;= F1 &lt; F2 &lt;= 80），R1，R2（5 &lt;= R1 &lt; R2 &lt;= 40）。从 F1 到 F2 型号的前齿轮都是可用的；从 R1 到 R2 型号的后齿轮都是可用的。至少会有一组合法的解。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;"><b><span style="font-size:medium;">OUTPUT FORMAT(file cowcycle.out)</span></b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">在第一行从小到大输出前齿轮的型号，用空格分开。在第二行从小到大输出后齿轮的型号，同样用空格分开。当然，齿轮的齿数一定是整数。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">如果有多个解，输出前齿轮齿数最小的那一个（第一个齿轮齿数最小的，若第一个齿轮齿数相等，输出第二个齿轮齿数最小的……依此类推）。如果所有的前齿轮齿数都相等，照着上面的办法处理后齿轮（其实就是把第一个，第二个……齿轮分别设为第一，第二……个关键字来排序）。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;"><b><span style="font-size:medium;">SAMPLE INPUT (file cowcycle.in)</span></b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">2 5<br/>
39 62 12 28</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;"><b><span style="font-size:medium;">SAMPLE OUTPUT (file cowcycle.out)</span></b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">39 53<br/>
12 13 15 23 27</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;font-size:medium;"><b>Comment</b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;font-size:medium;"><b>注释</b></span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">这个问题最大的挑战就是“读懂题目”。慢慢读，不要想一步登天。如果你读不懂题目，还是得一遍一遍的把它读进去。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">问题要我们找出“最佳齿轮组合”，即传动比率最接近平均数的组合。考虑下面的测试数据： </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">2 5<br/>
39 62 12 28<br/>
这意味着有 2 个前齿轮，型号范围在 39..62 ；5个后齿轮，型号范围在 12..28。程序必须检查所有前齿轮组成的有序对（共 62-39+1=24 种齿轮），和所有后齿轮组成的五元组（共 28-12+1=17 种齿轮）。根据组合数学原理，总共有 24!/22!/2! x 17!/5!/12! = 656,880 种可能（我是这么认为的）。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">对于每一种可能，做下面的计算。举个例子来说，对于枚举到的第一种情况：前齿轮是 39 和 40，后齿轮是 12，13，14，15 和 16。 </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">首先，计算所有可能的传动比率： </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">39/12 = 3.25000000000000000000<br/>
39/13 = 3.00000000000000000000<br/>
39/14 = 2.78571428571428571428<br/>
39/15 = 2.60000000000000000000<br/>
39/16 = 2.43750000000000000000<br/>
40/12 = 3.33333333333333333333<br/>
40/13 = 3.07692307692307692307<br/>
40/14 = 2.85714285714285714285<br/>
40/15 = 2.66666666666666666666<br/>
40/16 = 2.50000000000000000000</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">然后，对它们进行排序： </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">39/16 = 2.43750000000000000000<br/>
40/16 = 2.50000000000000000000<br/>
39/15 = 2.60000000000000000000<br/>
40/15 = 2.66666666666666666666<br/>
39/14 = 2.78571428571428571428<br/>
40/14 = 2.85714285714285714285<br/>
39/13 = 3.00000000000000000000<br/>
40/13 = 3.07692307692307692307<br/>
39/12 = 3.25000000000000000000<br/>
40/12 = 3.33333333333333333333</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">然后，计算差的绝对值： </span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">2.43750000000000000000 - 2.50000000000000000000 = 0.06250000000000000000<br/>
2.50000000000000000000 - 2.60000000000000000000 = 0.10000000000000000000<br/>
2.60000000000000000000 - 2.66666666666666666666 = 0.06666666666666666666<br/>
2.66666666666666666666 - 2.78571428571428571428 = 0.11904761904761904762<br/>
2.78571428571428571428 - 2.85714285714285714285 = 0.07142857142857142857<br/>
2.85714285714285714285 - 3.00000000000000000000 = 0.14285714285714285715<br/>
3.00000000000000000000 - 3.07692307692307692307 = 0.07692307692307692307<br/>
3.07692307692307692307 - 3.25000000000000000000 = 0.17307692307692307693<br/>
3.25000000000000000000 - 3.33333333333333333333 = 0.08333333333333333333</span> 
</p>
<p>
<span style="font-family:Times New Roman, Times, serif;">然后计算平均数和方差。平均数是（我是这么认为的）0.0995370370370370370366666.。方差大约是 0.00129798488416722。 找出使方差最小的齿轮组合。</span> 
</p>
<p>
 
</p>
