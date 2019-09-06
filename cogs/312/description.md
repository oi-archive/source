# 题目描述


<p>
<strong>【问题描述】 </strong> 
</p>
<p align="left">
 对于一个给定的S={a<sub>1</sub>,a<sub>2</sub>,a<sub>3</sub>,…,a<sub>n</sub>},若有P={a<sub>x1</sub>,a<sub>x2</sub>,a<sub>x3</sub>,…,a<sub>xm</sub>}满足(x<sub>1</sub>&lt;x<sub>2</sub>&lt;…x<sub>m</sub>)且（a<sub>x1</sub>&lt;a<sub>x2</sub>&lt;…a<sub>xm</sub>)<x<sub><x<sub><a<sub><a<sub>。那么就称P为S的一个上升序列。如果有多个P满足条件，那么我们想求字典序最小的那个。 任务 给出S序列，给出若干询问。对于第i个询问，求出长度为Li的上升序列，如有多个，求出字典序最小的那个（即首先x<sub>1</sub>最小，如果不唯一，再看x<sub>2</sub>最小……），如果不存在长度为Li的上升序列，则打印Impossible.</a<sub></a<sub></x<sub></x<sub> 
</p>
<p align="left">
【输入格式】 <br/>
  第一行一个N，表示序列一共有N个元素
</p>
<p align="left">
第二行N个数，为a<sub>1</sub>,a<sub>2</sub>,…,a<sub>n</sub> 
</p>
<p align="left">
第三行一个M，表示询问次数。下面接M行每行一个数L，表示要询问长度为L的上升序列。
</p>
<p align="left">
【输出格式】 <br/>
对于每个询问，如果对应的序列存在，则输出，否则打印Impossible.
</p>
<p>
【输入样例】 <br/>
6<br/>
3 4 1 2 3 6<br/>
3<br/>
6<br/>
4<br/>
5
</p>
<p>
<br/>
【输出样例】 <br/>
Impossible<br/>
1 2 3 6<br/>
Impossible
</p>
<p>
【数据范围】
</p>
<p>
N&lt;=10000 M&lt;=1000
</p>
