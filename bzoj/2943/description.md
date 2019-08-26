
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 21pt"><span style="font-size: medium">一架三臂起重机正在把集装箱放进货车车箱。车箱由1至n编号，每节车箱上仅能放一个集装箱。一次移动，起重机能把三个集装箱从仓库里拿出并放进车箱i、i+p、i+p+q或i、i+q、i+p+q（p、q为大于等于1的常数）。起重机必须放满货车的前n节车箱（货车有n+p+q节车箱）。放置的方案由一系列说明组成，每条说明指示起重机的一次移动，用三个整数(x,y,z)表示这次接受集装箱的车箱的编号，其中1≤x＜y＜z≤n+p+q。如果在说明执行后，货车前n节车箱有且仅有一个箱子，则该方案是正确的。</span></div>
<div><span style="font-size: medium"><b>任务：</b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">编写一个程序完成下列工作：</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: medium">●<span style="font: 7pt &#39;Times New Roman&#39;">        </span>读入p、q和车箱总数n；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"><span style="font-size: medium">●<span style="font: 7pt &#39;Times New Roman&#39;">        </span>生成一个正确的放置方案；</span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -18pt"></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行仅包括三个正整数，用空格分开。它们是起重机恰当的参数p、q，需要装满的车箱数n。（1≤n≤300000,2≤p+q≤60000）</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第一行仅有一个整数m，表示生成方案中说明的条数。以下m行，每行有三个整数x、y、z，用空格分开，1≤x＜y＜z≤n+p+q，x≤n，y∈{x+p,x+q}，z=x+p+q，这些是一次移动中接受箱子的车箱的编号。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 10<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1 3 6<br/>
2 4 7<br/>
5 8 10<br/>
9 11 14</span></div>

# Hint

<div class="content"><p></p><p>不要提交！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

