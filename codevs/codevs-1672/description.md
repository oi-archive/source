<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>奶牛克鲁斯认为人类的加法算式太落后了。比如说有时候想要用加法计算+15*3.，只能写成+15+15+15。真是浪费精力啊！于是，克鲁斯决定开发出一种新的加法算式。当然新的算式也是建立在原本算式的基础上的，不同就在于上式可以直接写成+++15，当然对于 －15*3这样的算式可以写成―――15。一段时间后，克鲁斯有被那无穷多个+－号雷到了，于是他又将这个算式改进了一下。比如+15*3又可以写成+(3)15，当然，－15*3等价于－(3)15.但是从上面可以看出，对于乘数较小的情况，如+++15这样的表述还是很方便的，于是在新的算式中还是保留了这种丑陋的形式。 对于算式还有做一点特殊的说明：+15*3转换成鲁克斯型算式时可以写成+++15或+(3)15，但是不可以写成++(2)15这样的形式。 对于算式23+15*3－2可以表示为以下几种形式： 23+++15－2 23+(3)15－2 +23+++15－2 +23+(3)15－2 +(1)23+(3)15－(1)2 不会出现如下几种形式： (1)23+++15－2 +23++(2)15－(1)2 23+++15－2+(0)100 23－(－3)15－2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行，一个克鲁斯型算式。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，为运算结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>+(1)23+(3)15－(1)2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>66</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】 对于20%的数据，输入长度不超过10；</p>
<p>对于100%的数据，输入长度不超过200。</p>
</div>
</div>