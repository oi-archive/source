
# Description

<div class="content">
幼儿园里有n个小朋友打算通过投票来决定睡不睡午觉。对他们来说，这个问题并不是很重要，于是他们决定发扬谦让精神。虽然每个人都有自己的主见，但是为了照顾一下自己朋友的想法，他们也可以投和自己本来意愿相反的票。我们定义一次投票的冲突数为好朋友之间发生冲突的总数加上和所有和自己本来意愿发生冲突的人数。
我们的问题就是，每位小朋友应该怎样投票，才能使冲突数最小？

</div>

# Input

<div class="content">第一行只有两个整数n，m，保证有2≤n≤300，1≤m≤n(n-1)/2。其中n代表总人数，m代表好朋友的对数。文件第二行有n个整数，第i个整数代表第i个小朋友的意愿，当它为1时表示同意睡觉，当它为0时表示反对睡觉。接下来文件还有m行，每行有两个整数i，j。表示i，j是一对好朋友，我们保证任何两对i，j不会重复。

</div>

# Output

<div class="content">只需要输出一个整数，即可能的最小冲突数。
</div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 0 0<br/>
1 2<br/>
1 3<br/>
3 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p>在第一个例子中，所有小朋友都投赞成票就能得到最优解</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

