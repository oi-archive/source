<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>年轻的探险家来到了一个印第安部落里。在那里他和酋长的女儿相爱了，于是便向酋长去求亲。酋长要他用<span style="font-family: 'Times New Roman';">10000</span><span style="">个金币作为聘礼才答应把女儿嫁给他。探险家拿不出这么多金币，便请求酋长降低要求。酋长说：“嗯，如果你能够替我弄到大祭司的皮袄，我可以只要</span><span style="font-family: 'Times New Roman';">8000</span><span style="">金币。如果你能够弄来他的水晶球，那么只要</span><span style="font-family: 'Times New Roman';">5000</span><span style="">金币就行了。”探险家就跑到大祭司那里，向他要求皮袄或水晶球，大祭司要他用金币来换，或者替他弄来其他的东西，他可以降低价格。探险家于是又跑到其他地方，其他人也提出了类似的要求，或者直接用金币换，或者找到其他东西就可以降低价格。不过探险家没必要用多样东西去换一样东西，因为不会得到更低的价格。探险家现在很需要你的帮忙，让他用最少的金币娶到自己的心上人。另外他要告诉你的是，在这个部落里，等级观念十分森严。地位差距超过一定限制的两个人之间不会进行任何形式的直接接触，包括交易。他是一个外来人，所以可以不受这些限制。但是如果他和某个地位较低的人进行了交易，地位较高的的人不会再和他交易，他们认为这样等于是间接接触，反过来也一样。因此你需要在考虑所有的情况以后给他提供一个最好的方案。</span></p>
<p>为了方便起见，我们把所有的物品从<span style="font-family: 'Times New Roman';">1</span><span style="">开始进行编号，酋长的允诺也看作一个物品，并且编号总是</span><span style="font-family: 'Times New Roman';">1</span><span style="">。每个物品都有对应的价格</span><span style="font-family: 'Times New Roman';">P</span><span style="">，主人的地位等级</span><span style="font-family: 'Times New Roman';">L</span><span style="">，以及一系列的替代品</span><span style="font-family: 'Times New Roman';">Ti</span><span style="">和该替代品所对应的“优惠”</span><span style="font-family: 'Times New Roman';">Vi</span><span style="">。如果两人地位等级差距超过了</span><span style="font-family: 'Times New Roman';">M</span><span style="">，就不能“间接交易”。你必须根据这些数据来计算出探险家最少需要多少金币才能娶到酋长的女儿。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包括了多个测试数据。每个测试数据的第一行是两个整数<span style="font-family: 'Times New Roman';">M</span><span style="">，</span><span style="font-family: 'Times New Roman';">N</span><span style="">（</span><span style="font-family: 'Times New Roman';">1&lt;=N&lt;=100</span><span style="">），依次表示地位等级差距限制和物品的总数。接下来按照编号从小到大依次给出了</span><span style="font-family: 'Times New Roman';">N</span><span style="">个物品的描述。每个物品的描述开头是三个非负整数</span><span style="font-family: 'Times New Roman';">P</span><span style="">、</span><span style="font-family: 'Times New Roman';">L</span><span style="">、</span><span style="font-family: 'Times New Roman';">X</span><span style="">（</span><span style="font-family: 'Times New Roman';">X&lt;N</span><span style="">），依次表示该物品的价格、主人的地位等级和替代品总数。接下来</span><span style="font-family: 'Times New Roman';">X</span><span style="">行每行包括两个整数</span><span style="font-family: 'Times New Roman';">T</span><span style="">和</span><span style="font-family: 'Times New Roman';">V</span><span style="">，分别表示替代品的编号和“优惠价格”。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每个测试数据，在单独一行内输出最少需要的金币数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 4</p>
<p>10000 3 2                             //酋长的允诺</p>
<p>2 8000</p>
<p>3 5000</p>
<p>1000 2 1                              //大祭司的皮袄</p>
<p>4 200</p>
<p>3000 2 1                              //大祭司的水晶球</p>
<p>4 200</p>
<p>50 2 0                               // 其他某件物品</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>5250</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>