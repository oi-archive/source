<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A ﬁsh-ﬁnder is a device used by anglers to ﬁnd ﬁsh in a lake. If the ﬁsh-ﬁnder ﬁnds a ﬁsh, it will sound an alarm. It uses depth readings to determine whether to sound an alarm. For our purposes, the ﬁsh-ﬁnder will decide that a ﬁsh is swimming past if:</p>
<p>fish-finder是一个神奇的装置供垂钓者使用区在护理钓鱼。如果一个f-f找到了一条鱼，他会响起声音警报。它用鱼的深度来决定是否响警报。我们的目的就是要决定鱼是否通过，具体如下：</p>
<p><br>• there are four consecutive depth readings which form a strictly increasing sequence (such as 3 4 7 9) (which we will call “Fish Rising”), or</p>
<p>如果连续的四个深度读入是严格递增的序列，我们可以叫它 Fish Rising 。</p>
<p><br>• there are four consecutive depth readings which form a strictly decreasing sequence (such as 9 6 5 2) (which we will call “Fish Diving”), or</p>
<p>如果连续的四个深度读入是严格递减的序列，我们可以叫它 Fish Diving 。</p>
<p><br>• there are four consecutive depth readings which are identical (which we will call “Constant Depth”).<br>All other readings will be considered random noise or debris, which we will call “No Fish.”<br>Your task is to read a sequence of depth readings and determine if the alarm will sound.</p>
<p>如果连续的四个深度读入是一样的，那就是“Fish At Constant Depth”。如果都不是，就是“No Fish”。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The input will be four positive integers, representing the depth readings. Each integer will be on its own line of input.</p>
<p>输入会是四个正整数，代表深度读入。每个整数会占一行。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The output is one of four possibilities. If the depth readings are increasing, then the output should be Fish Rising. If the depth readings are decreasing, then the output should be Fish Diving. If the depth readings are identical, then the output should be Fish At Constant Depth. Otherwise, the output should be No Fish.</p>
<p>输出就是四种情况。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>30 10 20 20</p>
<p>样例2：</p>
<p>1 10 12 13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>No Fish</p>
<p>样例2：</p>
<p>Fish Rising</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据很小</p>
</div>
</div>