# 题目描述


<div>
<span style="font-size:15pt;">Description</span> 
</div>
<div>
<span style="font-size:15pt;">      </span>这次的任务很简单，给出了一张有N个点M条边的加权有向无环图，接下来有Q个询问，每个询问包括2个节点X和Y，要求算出从X到Y的一条路径，使得密度最小（密度的定义为，路径上边的权值和除以边的数量）。
</div>
<div>
<span style="font-size:15pt;">Input Format</span> 
</div>
<div>
<span style="font-size:15pt;">      </span>第一行包括2个整数N和M。
</div>
<div>
<span>       </span>以下M行，每行三个数字A、B、W，表示从A到B有一条权值为W的有向边。
</div>
<div>
<span>       </span>再下一行有一个整数Q。
</div>
<div>
<span>       </span>以下Q行，每行一个询问X和Y，如题意所诉。
</div>
<div>
<span style="font-size:15pt;">Output Format</span> 
</div>
<div>
<span style="font-size:15pt;">      </span>对于每个询问输出一行，表示该询问的最小密度路径的密度（保留3位小数），如果不存在这么一条路径输出“OMG!”（不含引号）。
</div>
<pre><span style="font-size:15pt;">Sample Input</span></pre>
<div style="margin:0cm 0cm 0pt 21pt;">
3 3
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
1 3 5
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
2 1 6
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
2 3 6
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
2
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
1 3
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
2 3
</div>
<div>
<span style="font-size:15pt;">Sample Output</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
5.000
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
5.500
</div>
<div>
<span style="font-size:15pt;">Data Limit</span> 
</div>
<div style="text-indent:21pt;">
对于60%的数据，有1 ≤ N ≤ 10，1 ≤ M ≤ 100，1 ≤ W≤ 1000，1 ≤ Q ≤ 1000；
</div>
<div style="text-indent:21pt;">
对于100%的数据，有1 ≤ N ≤ 50，1 ≤ M ≤ 1000，1 ≤ W ≤ 100000，1 ≤ Q ≤ 100000。
</div>
