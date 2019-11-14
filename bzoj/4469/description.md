
# Description

<div class="content"><p>【故事背景】 <br/>
JYY 特别喜欢到游戏厅玩打地鼠游戏——拿起两个锤子用力敲打不断冒出<br/>
来的地鼠。打到不同的地鼠有不同的得分，JYY想知道怎样才能得到最高的分<br/>
数。 <br/>
【问题描述】 <br/>
游戏里一共会冒出来 N 个地鼠，这些地鼠冒出来的位置都分布在一条直线<br/>
上。第i 个地鼠会在 Ti时刻在Xi位置冒出来，打到第 i 个地鼠的得分是 Pi。 <br/>
当游戏开始时（也就是 0 时刻），JYY 左手的位置为 XLEFT，右手的位置为<br/>
XRIGHT。JYY的手的最大移动速度是 V（每单位时刻最多移动的距离为 V） 。 <br/>
地鼠会在瞬间冒出来然后消失。如果在对应的时刻 JYY 的一只手恰好也在<br/>
地鼠冒出来的位置，那么 JYY 就可以在瞬间完成击打动作并得到对应的分数；<br/>
否则，JYY就只能错过这只地鼠了。 <br/>
JYY两只手都拿着锤子，所以两只手是可以同时打地鼠的。 <br/>
然而， 如果在游戏过程中 JYY的两只手交叉的话， JYY会感到很不舒服 （这<br/>
个动作确实很别扭，而且两只手可能会互相阻碍而影响移动速度） ，所以 JYY希<br/>
望在整个游戏过程中左手的位置 XLEFT永远严格小于右手的位置XRIGHT。 <br/>
JYY想知道，他最多能得多少分呢？</p></div>

# Input

<div class="content"><p>第一行包含四个整数N，V，XLEFT和XRIGHT； <br/>
接下来 N 行，分别描述 N 个可能出现的地鼠； <br/>
其中第 i 行包含三个整数 Xi，Ti，Pi。 <br/>
数据保证在同一个时刻不会有两个地鼠出现在同样的位置。</p></div>

# Output

<div class="content"><p>输出一行一个整数，表示JYY最多能够得到的分数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 10 150 250<br/>
100 20 123<br/>
201 10 67<br/>
202 10 45</span></div>

# Sample Output

<div class="content"><span class="sampledata">190</span></div>

# Hint

<div class="content"><p></p><p>1 &lt; =  N &lt; =  3000,1 &lt; =  XLEFT &lt; XRIGHT &lt; =  10^5， 1 &lt; =  Ti &lt; =  10^5<br/><br/>
1 &lt; =  Pi &lt; = 10^5，1 &lt; =  Xi &lt; =  10^5，1 &lt; =  V &lt; =  10^4</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

