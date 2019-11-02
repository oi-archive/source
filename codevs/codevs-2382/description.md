<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>“珠缀花蕊，人间几多酸泪”…… <br>挂缀在很早就被人们作为一种装饰品，垂坠的风韵，华丽摇曳的摆动，展现出一种与众不同的优雅与高贵。而我们的主人公小Q，正想买一条漂亮的挂缀放在寝室里作为装饰。 <br>挂坠的构成，是由若干粒缀珠相互连接而成。每一个缀珠由三部分组成：分别是珠子、珠子上方的连接环与珠子下方的挂钩（如下图） 。我们可以简单的认为从上往下数的第 i 个缀珠是将它的连接环套在其上方（也就是第 i-1 个）缀珠的挂钩之上（第一个除外） 。小 Q想买一根足够长的挂缀，这样显得更有韵味☺ <br> <br>然而商店的老板告诉小Q，挂缀是不可能做到任意长的，因为每一个珠子都受到重力作用，对其上方的挂钩有一定的拉力，而挂钩的承受能力是有限的。老板还告诉小 Q，他一共拥有 N 个珠缀（假设每一个珠缀都很漂亮，小 Q 都很喜欢） ，每个珠缀都有其各自的重量与承受能力。一个挂缀是稳定的，当且仅当对于其上的每一个珠缀，它下方所有珠缀的重量和（不包含自身）不超过其挂钩的承受能力。 <br> 小Q希望她的挂缀尽量长，你能帮她计算出最长可能的稳定挂缀么？当然，如果有多个可选方案，小Q希望总重量最小的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 第一行包含一个正整数 N，表示商店拥有的珠缀数目。<br>接下来 N行，每行两个整数(Ci , Wi)，分别表示第i 个珠缀的承受能力与重量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包行两行。第一行包含一个整数L，表示可以找到的最长稳定挂缀长度。</p>
<p>第二行包含一个整数 W，表示可以找到的长度为 L 的稳定挂缀中的最小重量和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 <br>3 5 <br>5 1 <br>3 2 <br>4 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 <br>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据，N ≤ 10000； <br>对于 100%的数据，N ≤ 200000； <br>对于所有的数据，Wi, Ci不超过2<sup>31</sup><br>。</p>
</div>
</div>