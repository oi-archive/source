
# Description

<div class="content"><div>勤劳的JYY在花园里面种了好多胡萝卜！可是，今天早上JYY发现一大群从JSOI王国里面跑来的兔子把他的花园全部</div>
<div>占满了！兔子们把胡萝卜吃光了，JYY靠什么过冬呢！忍无可忍的JYY决定取出他的强力猎枪来消灭这些兔子。JYY</div>
<div>的花园是一个由N个块小菜地顺次连接所形成的圆环。菜地由1到N编号。第i号菜地和第i+1号菜地是相邻的。由于</div>
<div>是环形的花园，所以1号菜地和N号菜地也是相邻的。现在，第i号菜地上有Ri只兔子。JYY的猎枪有K发子弹，每次J</div>
<div>YY可以选择一块菜地打一枪，然后这块菜地上的兔子就全部都被消灭了。但是由于JYY的猎枪威力太大，会吓到相</div>
<div>邻菜地上的兔子，所以，如果JYY朝i号菜地打了一枪，那么i+1号菜地上的兔子就会跑到i+2号菜地上去，同样的，</div>
<div>i-1号菜地上的兔子也会跑到i-2号菜地上去。JYY想知道，如何用这K发子弹，消灭尽量多的兔子呢？</div></div>

# Input

<div class="content"><p> 输入文件的第一行包含两个整数N和K；</p>
<div>接下来一行N个整数，第i个整数为Ri。</div>
<div>3≤N≤4000，0≤K≤4000，0≤Ri≤10^5。</div></div>

# Output

<div class="content"><p> 输出一行一个整数，表示JYY最多可以消灭的兔子个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
6 1 5 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">13<br/>
【样例说明】<br/>
首先JYY朝1号菜地打一枪，然后菜地里面的兔子数量就变成了<br/>
0 0 6 7 0<br/>
接着JYY再朝4号菜地打一枪就可以一共消灭13只兔子了<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round1">Round1</a></p></div>

