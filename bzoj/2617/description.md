
# Description

<div class="content"><p><span style="font-size: medium">考古学家 Benjamas 考察了神秘的鳄鱼地下宫殿之后需要设法逃离。这个地下宫殿包含<br/>
N 个洞穴和 M 条双向的通道。每条通道连接一对不同的洞穴，两个洞穴之间最多只有一条<br/>
通道，在不同的通道上行走可能需要不同的时间。N 个洞穴中有 K 个洞穴是出口洞穴，<br/>
Benjamas 可以从出口洞穴逃离。Benjamas 从 0 号洞穴出发，她希望尽快地到达一个出口洞<br/>
穴。<br/>
鳄鱼门卫要阻止 Benjamas 逃离宫殿。它可以通过机关来堵住任意一个的通道（任意时<br/>
刻，只能堵住一个通道）。即无论何时，鳄鱼门卫堵住一个新的通道，则之前堵住的通道就<br/>
会被打开。<br/>
Benjamas 逃离过程可以描述如下：每次她试图离开一个洞穴时，鳄鱼门卫都会封闭一<br/>
条连接该洞穴的通道。Benjamas 只能选择没有被封闭的通道走到下一个洞穴。Benjamas 一<br/>
旦进入一条通道，在她到达该通道的另一端前，鳄鱼门卫不能封闭这条通道。当 Benjamas<br/>
到达下一个洞穴，鳄鱼门卫可以选择再封闭一条通道（可以是 Benjamas 刚刚走过的那条通<br/>
道）。<br/>
Benjamas 需要设计一个逃生计划，确切地说，她希望有一系列指令告诉她如何逃生。<br/>
设 A 是一个洞穴，如果 A 是出口洞穴，Benjamas 可以直接逃生。否则，对洞穴 A，指令是<br/>
下列形式中的一种：<br/>
? 在洞穴 A，优先选择一条通道到洞穴 B。如果该通道被封堵，则选择另一通道去洞穴<br/>
C。<br/>
? 不用考虑洞穴 A，按照逃生计划不会到达 A。<br/>
注意：数据保证不管鳄鱼门卫如何封闭通道，总能找到一个好的逃生计划保证 Benjamas<br/>
在有限时间内可以到达一个出口洞穴。在所有逃生计划中，在最坏情况下用时最短的逃生计<br/>
划所用的时间定义为 T。<br/>
保证有解<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行三个整数 N M K<br/>
接下来M行 每行三个整数 表示一条无向边的两端和长度（无重边）<br/>
接下来K个整数 表示出口洞穴<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">一个整数 最小时间T<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">13 12 9<br/>
0 1 1<br/>
0 2 4<br/>
0 3 11<br/>
1 4 11<br/>
1 5 7<br/>
1 6 15<br/>
2 7 3<br/>
2 8 13<br/>
2 9 23<br/>
3 10 3<br/>
3 11 1<br/>
3 12 2<br/>
4 5 6 7 8 9 10 11 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

