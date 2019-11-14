
# Description

<div class="content">在很久很久以前的一个王国里，王国的财产开始变得越来越少。国王决定改变这种情况，然后他发明了一种新的系统。系统职员要求两两成对（为了避免行贿），每一对由一个职员及他的下属组成。你的任务就是在满足这种组成方式结构的前提下，计算出能够按照这种方式组成的最大的对数，和可能的方法数。

任务

这项任务是由George Skinflint领导的。每个职员都有0个,1个或者更多的下属，并且每个职员都只有一个单独的上司（除了George Skinglint）。职员的人数不会超过1 000。你的任务就是，按照由职员及他的下属组成的方法，计算出能够组成的对数的最大值。另外，你也要计算最大值可能的组成的方式有多少种。注意一些职员不需要成对。
</div>

# Input

<div class="content">

第一行包含一个数字N，表示职员的数目，1≤N≤1 000。职员按照特殊的ID号码进行标号，号码为1~N。Skinflint的号码为1。接下来N行对应相应的职员：包含其ID号和一个数字K表示他的下属的数目，0≤K≤999，接下来给出他的K个职员的ID号，中间由空格分隔。并且保证所有职员不会比他的上司先出现。

</div>

# Output

<div class="content">

输出包含两行。第一行包含一个单独的数字，代表职员能形成的最多的对数。第二行表示在多数最多的情况下，有多少种形成方式。

</div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 3 2 4 7<br/>
2 1 3<br/>
4 1 6<br/>
3 0<br/>
7 1 5<br/>
5 0<br/>
6 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

