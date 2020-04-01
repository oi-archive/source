<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">动物王国中有三类动物 A,B,C，这三类动物的食物链构成了有趣的环形。A吃B，B吃C，C吃A。 　　</span></p>
<p><span style="">现有N个动物，以1－N编号。每个动物都是A,B,C中的一种，但是我们并不知道它到底是哪一种。 　　</span></p>
<p><span style="">有人用两种说法对这N个动物所构成的食物链关系进行描述： 　　</span></p>
<p><span style="">第一种说法是“1 X Y”，表示X和Y是同类。 　　</span></p>
<p><span style="">第二种说法是“2 X Y”，表示X吃Y。 　　</span></p>
<p><span style="">此人对N个动物，用上述两种说法，一句接一句地说出K句话，这K句话有的是真的，有的是假的。当一句话满足下列三条之一时，这句话就是假话，否则就是真话。 　　</span></p>
<p><span style="">1） 当前的话与前面的某些真的话冲突，就是假话； 　　</span></p>
<p><span style="">2） 当前的话中X或Y比N大，就是假话； 　　</span></p>
<p><span style="">3） 当前的话表示X吃X，就是假话。 　　</span></p>
<p><span style="">你的任务是根据给定的N（1&lt;=N&lt;=50,000）和K句话（0&lt;=K&lt;=100,000），输出假话的总数。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行是两个整数N和K，以一个空格分隔。 　　</span></p>
<p><span style="">以下K行每行是三个正整数D，X，Y，两数之间用一个空格隔开，其中 D 表示说法的种类。 　　</span></p>
<p><span style="">若D=1，则表示X和Y是同类。 　　</span></p>
<p><span style="">若D=2，则表示X吃Y。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个整数，表示假话的数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>100 7</p>
<p>1 101 1</p>
<p>2 1 2</p>
<p>2 2 3</p>
<p>2 3 3</p>
<p>1 1 3</p>
<p>2 3 1</p>
<p>1 5 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入文件  </p>
<p> 对7句话的分析 100 7</p>
<p>1 101 1　　假话</p>
<p>2 1 2　　  真话</p>
<p>2 2 3　　  真话</p>
<p>2 3 3　　  假话</p>
<p>1 1 3　　  假话</p>
<p>2 3 1　　  真话</p>
<p> 1 5 5　　  真话</p>
<p>NOI 2001 食物链(eat)</p>
</div>
</div>