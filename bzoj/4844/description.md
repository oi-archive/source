
# Description

<div class="content"><div>ls是一名集邮爱好者，他专门有一个栈来存放他的所有的邮票，但ls同时也是一名很粗心的人，有一些邮票可能放</div>
<div>反了（上下颠倒），有一天他想把他的邮票拿出来向他的妹子炫耀，但因为有一些邮票可能反了，于是ls就想把那</div>
<div>些邮票矫正方向，但ls特别懒，他觉得一张一张矫正太费时间了，即使是要给妹子看的，他也不想费太多时间，于</div>
<div>是ls就想出了一种奇迹淫巧：</div>
<div>1.假设栈中还剩n张邮票，他每次从1到n中随机取一个整数k，然后取出栈中最上面的k张。</div>
<div>2.他会查看这k张中最上面的一张，如果它放反了，那么他就直接把这k张全部倒过来。</div>
<div>3.他直接把这k张放到桌上，然后准备给妹子炫耀，并且之后对这k张不做任何操作。</div>
<div>4.如果栈中还剩余邮票，那么回到步骤1。</div>
<div>当然，这毕竟是奇迹淫巧，而且是ls想出来的，桌上还是有可能有一些邮票放反了</div>
<div>那么ls想询问期望有多少张邮票放反了？</div>
<p></p></div>

# Input

<div class="content"><div>输入仅一行一个字符串，长度len&lt;=1000000</div>
<div>第i位为&#34;C&#34;则表示从栈顶数第i张放的顺序是正确的，是&#34;W&#34;则表示从栈顶数第i张放的顺序是错误的。</div>
<p></p></div>

# Output

<div class="content"><div>输出仅一行一个实数，表示放反的邮票的期望张数，相对或绝对误差不得超过1e-9。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">WWCWCCW<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.333333333333</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yts1999提供SPJ">鸣谢yts1999提供SPJ</a></p></div>

