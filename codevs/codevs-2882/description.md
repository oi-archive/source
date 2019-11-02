<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某超市设有仓库管理员，他非常负责地记录每次从仓库中发给超市的各种货物的数量。仓库的货物由采购员从外面采购再存入仓库。采购员总会去仓库了解各种货物的剩余数量并记录，以便及时发现短缺的货物并马上去采购。</p>
<p>采购员由于长期在外地跑所以比较忙，他总是把仓库剩余货物的数量随便记录在不同的本子上。某天，采购员突然发现他用于记录货物数量某些本子找不到了，所幸他还大致记得那些本子上记录的货物剩余数量，但他无法确定哪些货物数量是正确，哪些是错误的。</p>
<p>万幸的是仓库管理员比较尽职，他详细地记录了每种货物的编号以及对应的发货数量。已知每种货物一开始总数都是100。现在希望根据仓库管理员记录的发货编号和发货数量（绝对正确）以及采购员记得的一些剩余数量，来核查到底哪些货物的剩余数量是错误的。由于问题比较复杂，请你帮忙编程解决这个问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为一个正整数n，表示所有货物的总类。第二行是n个用一个空格分隔的整数，依次表示仓库管理员记录的第1种货物，第2种货物，。。。，第n种货物的发货数量。第三行为采购员记录的n种货物的剩余数量（无法保证编号和数量是对应的，也无法知道到底哪种货物数量是正确的）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果核查发现每种货物的剩余数量都是正确的，则只输出一行一个数值0（表示没有记录错误的货物），如果发现有x种货物剩余数量记录错误，则第一行输出整数x，表示一共发现有x种货物的剩余数量错误。第二行按编号从小到大的顺序依次输出剩余数量错误的货物编号，这个货物编号应该是按照仓库保管员记录的编号给出（每2个数值之间用一个空格分隔）。注意，如果仓库管理员记录的某2种货物发货数量相同，如果在采购员剩余数量中只找到1个数值匹配，则我们认为是编号大的货物剩余数量是错误的（详细可见样例数据2）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】</p>
<p>5</p>
<p>43 54 37 66 89</p>
<p>11 63 56 33 46</p>
<p>【输入样例2】</p>
<p>4</p>
<p>33 54 33 91</p>
<p>46 9 67 68</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p>
<p>2</p>
<p>1 4</p>
<p>【输出样例2】</p>
<p>1</p>
<p>3</p>
<p>样例数据1说明：输入数据中第二行说明各种货物正确的编号和发货数量分别是：</p>
<p>1号：43   2号：54    3号：37     4号：66    5号：89</p>
<p>利用计算式：剩余数量=100-发货数量   可依次在采购员记录的数据中找到下列货物正确的剩余数量：</p>
<p>2号（剩余数量）：46（第三行最后一个数值）</p>
<p>3号（剩余数量）：63（第三行第二个数值）</p>
<p>5号（剩余数量）：11（第三行第一个数值）</p>
<p>但1号货物的正确剩余数量（应该为57）和4号货物的正确剩余数量（应该为34）始终在第三行数值中无法找到。说明采购员记录的第1、4号货物剩余数量记录是错误的。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=n&lt;=100，每个整数都小于100</p>
</div>
</div>