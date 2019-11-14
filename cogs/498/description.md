# 题目描述


<div><span style="font-size: 15pt">Description</span></div>
<div style="text-indent: 21pt">出于某些方面的需求，我们要把一块N×M的木板切成一个个1×1的小方块。</div>
<div style="text-indent: 21pt">对于一块木板，我们只能从某条横线或者某条竖线（要在方格线上），而且这木板是不均匀的，从不同的线切割下去要花不同的代价。而且，对于一块木板，切割一次以后就被分割成两块，而且不能把这两块木板拼在一起然后一刀切成四块，只能两块分别再进行一次切割。</div>
<div style="text-indent: 21pt">现在，给出从不同的线切割所要花的代价，求把整块木板分割成1×1块小方块所需要耗费的最小代价。</div>
<div><span style="font-size: 15pt">Input Format</span></div>
<div style="text-indent: 21pt">输入文件第一行包括N和M，表示长N宽M的矩阵。</div>
<div style="text-indent: 21pt">第二行包括N-1个非负整数，分别表示沿着N-1条横线切割的代价。</div>
<div style="text-indent: 21pt">第三行包括M-1个非负整数，分别表示沿着M-1条竖线切割的代价。</div>
<div><span style="font-size: 15pt">Output Format</span></div>
<div style="text-indent: 21pt">输出一个整数，表示最小代价。</div>
<div><span style="font-size: 15pt">Sample Input</span></div>
<div style="text-indent: 21pt">2 2</div>
<div style="text-indent: 21pt">3</div>
<div style="text-indent: 21pt">3</div>
<div><span style="font-size: 15pt">Sample Output</span></div>
<div style="text-indent: 21pt">9</div>
<div><span style="font-size: 15pt">Data Limit</span></div>
<div style="text-indent: 21pt">对于60%的数据，有1 ≤ N ,M≤ 100；</div>
<div style="text-indent: 21pt">对于100%的数据，有1 ≤ N,M ≤ 2000。</div>
