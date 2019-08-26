
# Description

<div class="content"><p><span style="font-size: medium"><br/>
A和B两个人在玩一个游戏，这个游戏是他们轮流操作一对整数(x,y)。<br/>
初始时(x,y)=(1,0)，可以进行三种操作：<br/>
1. 将(x,y)变成(1,x+y)。<br/>
2. 将(x,y)变成(2x,y)。<br/>
3. 将(x,y)变成(3x,y)。<br/>
给定正整数n (n&lt;=30,000)，如果x+y&gt;=n时就不能进行后两种操作。<br/>
如果某个人操作后y&gt;=n，他就输掉了。<br/>
假如A为先手，问他是否有必胜策略。</span></p>
<p><span style="font-size: medium">这题是道交互题，需要包含cliclib.h头文件，有下面三个函数可以使用：<br/>
1. int inicjuj(); 开始时调用，返回n的值。<br/>
2. void alojzy(int x); A进行一次操作，x表示操作编号。<br/>
3. int bajtazar(); 获得B的操作编号。</span></p>
<p><span style="font-size: medium">例如下面的程序每次选择操作1：<br/>
#include &#34;cliclib.h&#34;<br/>
int main() {<br/>
  int n = inicjuj();<br/>
  while (true) {<br/>
    alojzy(1);<br/>
    int x = bajtazar();<br/>
  }<br/>
  return 0;<br/>
}<br/>
</span></p></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster">鸣谢Oimaster</a></p></div>

