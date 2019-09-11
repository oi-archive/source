# 题目描述


<p>
<span style="font-family:Microsoft YaHei;">【问题描述】</span><br/>
<span style="font-family:Microsoft YaHei;"> 若一个数（首位不为0）从左到右读与从右到左读都是一样，这个数就叫做回文数，例如12521就是一个回文数。</span><br/>
<span style="font-family:Microsoft YaHei;">     给定一个N进制正整数，把它的各位数字上数字倒过来排列组成一个新数，然后与原数相加，如果是回文数则停止，如果不是，则重复这个操作，直到和为回文数为止。例如：10进制87则有：</span><br/>
<span style="font-family:Microsoft YaHei;"> STEP1: 87+78=165</span><br/>
<span style="font-family:Microsoft YaHei;"> STEP2: 165+561=726</span><br/>
<span style="font-family:Microsoft YaHei;"> STEP3: 726+627=1353</span><br/>
<span style="font-family:Microsoft YaHei;"> STEP4: 1353+3531=4884</span><br/>
<span style="font-family:Microsoft YaHei;">    任务：写一个程序，给定一个N（2≤N≤10，N=16）进制数m（10~15用小写字母a~f表示），m的位数上限为20。求最少经过几步可以得到回文数。如果在30步以内（包括30步）不可能得到回文数，则输出“impossible”，否则输出该回文数及生成该回文数的最少步数。</span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入格式】</span><br/>
<span style="font-family:Microsoft YaHei;"> 文件有两行，每行一个数，即N和N进制整数m</span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出格式】</span><br/>
<span style="font-family:Microsoft YaHei;"> 如果输入文件给定的数据在30步以内（包括30步）不可能得到回文数，则输出文件只有一行，即输出“impossible”。</span><br/>
<span style="font-family:Microsoft YaHei;"> 否则输出文件为两行。第一行是由输入文件给定数据生成的回文数，第二行是生成该回文数的最少步数。</span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入输出样例】</span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;"> 输入</span><br/>
<span style="font-family:Microsoft YaHei;"> 10</span><br/>
<span style="font-family:Microsoft YaHei;"> 87</span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;"> 输出</span><br/>
<span style="font-family:Microsoft YaHei;"> 4884</span><br/>
<span style="font-family:Microsoft YaHei;"> 4</span> 
</p>
