# 题目描述


<p>
<b>【问题描述</b>】
</p>
<div>
在组合数学中排列是一个非常重要的内容。例如，1 2 3 4 5 and 1 3 5 4 2 是两个5的排列．<br/>
众所周知，n的排列数是n!<br/>
根据它们的数量关系，如果我们可以在每对相邻的排列数之间插入符号“&lt;”或“&gt;”，我们能得到一个符号排列。<br/>
例如，1 2 3 4 5 能变成 1&lt;2&lt;3&lt;4&lt;5，<br/>
1 3 5 4 2 能变成 1&lt;3&lt;5&gt;4&gt;2．
</div>
<div>
现在你的任务是计算有多少个用k个“&lt;”组成的n排列
</div>
<div>
【输入格式】
</div>
<div>
<span><span> 输入文件由多组测试数据组成，每一测试数据占一行，包括两个整数n，k(0&lt;n≤100,0≤k≤100 )，输入文件由EOF结束。</span></span> 
</div>
<div>
【输出格式】
</div>
<p>
 每个测试数据输出一个结果，计算结果为一个非负数，即符合要求的排列数除以2007的余数。
</p>
<div>
【输入样例】
</div>
<div>
输入文件名：<span> permutation.in</span> 
</div>
<div>
5 2
</div>
<div>
输出文件名：<span> <span>permutation.out</span></span> 
</div>
<div>
<span>66</span> 
</div>
