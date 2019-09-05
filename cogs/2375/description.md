# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
请大家尊重出题构数据的同学，不要用不正确的算法水过
</p>
<p>
<br/>
</p>
<p>
在水平桌面上放着一个光滑的管道，管道中有一堆光滑的球，球的直径和管道的直径相等，所以球只能在一条直线上运动，所有球速度均为1，球是匀速运动的而且球很弹，两个球相撞后两个球的运动方向都会变为和原来相反的方向，但是速率不会变但是速率不会变但是速率不会变，管道两边开口所以有些球会掉出来，忽略一切摩擦力和能量损耗，忽略空气助力，球被视为质点，即忽略球的直径，给出球的数量，他们初始的位置，速度方向和速率，现在想问你在某些时刻球的位置
</p>
<p>
几个名词的解释：光滑：没有任何摩擦力；速率：速度由方向和大小组成，速率即为速度的大小；质点：忽略物体的形状大小，只考虑它的质量，受力情况和运动方向
</p>
<p>
关于两球相撞的情况：（左边的数是位置，右边是方向）酱紫两个球：（11,0）（13,1），一个单位时间后这两个球都会在12上，并且掉头，状态是酱紫（12,1）（12,0）
</p>
<p>
在如酱紫两个球（11,0）（12,1），半个单位时间后这两个球会碰上，半个单位时间弹回去，一个单位时间后状态是酱紫（11,1）（12,0）
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
第一行两个用空格隔开的整数N，L，表示有N个球，管的长度为L，坐标从1开始，到L结束
</p>
<p>
接下来n行，每行两个用空格隔开的整数，分别表示每个球开始的坐标，方向，第二个整数为1时球的运动方向向左，为0是向右，第二个整数为1时球的运动方向向左，为0是向右，第二个整数为1时球的运动方向向左，为0是向右，数据保证开始时没有球在管外，没有两个球坐标相等
</p>
<p>
接下来一个整数m，表示有m个询问
</p>
<p>
接下来m行，每行1个整数t，表示询问t个单位时间后每个球所在的位置，开始时间为0
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
共M行，每行N个用空格隔开的整数（如果球没掉的话），如果球掉了，输出”fire in the hole”（不输出引号），并且也要用空格隔开
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>3 10
2 1
8 1
4 0
2
2
1
</pre>
<h3>
【样例输出】
</h3>
<pre>fire in the hole 6 6
1 7 5
</pre>
<h3>
【提示】
</h3>
<pre> 




<p>
<span style="font-family:微软雅黑;font-size:11pt;">数据量：</span> 
</p>

<p>
<span style="font-family:微软雅黑;font-size:11pt;">数据组数</span><span style="font-family:Tahoma;font-size:11pt;"> </span><span style="font-family:Tahoma;font-size:11pt;"> </span><span style="font-family:Tahoma;font-size:11pt;">N</span><span style="font-family:Tahoma;font-size:11pt;"> </span><span style="font-family:Tahoma;font-size:11pt;">L</span><span style="font-family:Tahoma;font-size:11pt;"> </span><span style="font-family:Tahoma;font-size:11pt;">M</span><span style="font-family:Tahoma;font-size:11pt;"> </span><span style="font-family:微软雅黑;font-size:11pt;">特殊情况</span> 
</p>

<p>
<span style="font-family:Tahoma;font-size:11pt;">1-</span><span style="font-family:微软雅黑;font-size:11pt;">2                1</span><span style="font-family:Tahoma;font-size:11pt;">   </span><span style="font-family:微软雅黑;font-size:11pt;"> </span><span style="font-family:Tahoma;font-size:11pt;">   </span><span style="font-family:微软雅黑;font-size:11pt;">20</span><span style="font-family:Tahoma;font-size:11pt;">        1             M=1</span> 
</p>

<p>
<span style="font-family:微软雅黑;font-size:11pt;">3</span><span style="font-family:Tahoma;font-size:11pt;">              </span><span style="font-family:微软雅黑;font-size:11pt;">   50      100        1              M=1</span> 
</p>

<p>
<span style="font-family:Tahoma;font-size:11pt;">4-5             400    1000        50           </span><span style="font-family:微软雅黑;font-size:11pt;">所有球的方向都一样</span> 
</p>

<p>
<span style="font-family:Tahoma;font-size:11pt;">6                 500     1500      50             T&lt;=2</span> 
</p>

<p>
<span style="font-family:Tahoma;font-size:11pt;">7-10             1500      4000     100            </span><span style="font-family:微软雅黑;font-size:11pt;">无</span> 
</p>

<p>
<span style="font-family:微软雅黑;font-size:11pt;">考虑到作为<span>T1</span><span>本题难度过大，出题的同学不忍心看你们被虐，特别在这里提示一下：因为所有球的速率都为</span><span>1</span><span>且碰撞后球的速率不会变，所以可以把两球相撞“看成”互相穿过，而且球的相对位置是不会变的</span></span> 
</p>
</pre>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
