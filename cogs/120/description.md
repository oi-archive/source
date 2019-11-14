# 题目描述


<p>
【问题描述】 <br/>
 给定A,B,C三根足够长的细柱，在A柱上放有2n个中间有空的圆盘，共有n个不同的尺寸，每个尺寸都有两个相同的圆盘，注意这两个圆盘是不加区分的(下图为n=3的情形）。现要将这些圆盘移到C柱上，在移动过程中可放在B柱上暂存。要求:
</p>
<p>
<img alt="" src="/upload/image/20150907/20150907091505_76248.jpg"/><br/>
(1)每次只能移动一个圆盘； <br/>
(2)A、B、C三根细柱上的圆盘都要保持上小下大的顺序； <br/>
任务：设An为2n个圆盘完成上述任务所需的最少移动次数，对于输入的n，输出An。
</p>
<div>
<span lang="EN-US" style="font-family:; font-size: 10.5pt;" courier="" new";"=""> <span lang="EN-US" style="font-family:; font-size: 10.5pt;" courier="" new";"=""></span></span> 
</div>
<div>
【输入】 <br/>
输入文件hanoi.in为一个正整数n，表示在A柱上放有2n个圆盘。 <br/>
<br/>
【输出】 <br/>
输出文件hanoi.out仅一行，包含一个正整数，为完成上述任务所需的最少移动次数An。 <br/>
<br/>
【输入输出样例1】 <br/>
hanoi.in
</div>
<div>
1
</div>
<div>
hanoi.out <br/>
2 <br/>
<br/>
【输入输出样例2】 <br/>
hanoi.in
</div>
<div>
2 <br/>
hanoi.out <br/>
6 <br/>
【限制】 <br/>
对于50％的数据，1&lt;=n&lt;=25 <br/>
对于100％的数据，l&lt;=n&lt;=200
</div>
<div>
 
</div>
<div>
【提示】
</div>
<div>
 
</div>
<div>
设法建立An与An-1的递推关系式。
</div>
