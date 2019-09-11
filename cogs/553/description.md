# 题目描述


<div>
描述
</div>
<div>
给定4个矩形块，找出一个最小的封闭矩形将这4个矩形块放入，但不得相互重叠。所谓最小矩形指该矩形面积最小。
</div>
<div>
</div>
<div>
</div>
<div>
</div>
<div>
</div>
<div>
<img src="/images/packrec.JPG" width="500" height="110" alt=""/> 
</div>
<div>
</div>
<div>
</div>
<div>
</div>
<p>
所有4个矩形块的边都与封闭矩形的边相平行，图1示出了铺放4个矩形块的6种方案。这6种方案是仅可能的基本铺放方案。因为其它方案能由基本方案通过旋转和镜像反射得到。
</p>
<p>
可能存在满足条件且有着同样面积的各种不同的封闭矩形，你应该输出所有这些封闭矩形的边长。
</p>
<p>
（分类注解：这里的分类依据可以视为是不同的面积计算公式。）
</p>
<div>
格式
</div>
<div>
PROGRAM NAME: packrec
</div>
<div>
INPUT FORMAT:
</div>
<div>
(file packrec.in)
</div>
<div>
共有4行。每一行用两个正整数来表示一个给定的矩形块的两个边长。矩形块的每条边的边长范围最小是1，最大是50。
</div>
<div>
OUTPUT FORMAT:
</div>
<div>
(file packrec.out)
</div>
<div>
总行数为解的总数加1。第一行是一个整数，代表封闭矩形的最小面积（子任务A）。接下来的每一行都表示一个解，由数P和数Q来表示，并且P≤Q（子任务B）。这些行必须根据P的大小按升序排列，P小的行在前，大的在后。且所有行都应是不同的。
</div>
<div>
SAMPLE INPUT
</div>
<div>
1 2
</div>
<div>
2 3
</div>
<div>
3 4
</div>
<div>
4 5
</div>
<div>
SAMPLE OUTPUT
</div>
<div>
40
</div>
<div>
4 10
</div>
<div>
5 8
</div>
<div>
</div>
