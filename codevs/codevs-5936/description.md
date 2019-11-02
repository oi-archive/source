<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>就当CJX玩的正起劲时，猥琐的服主Neno打开了<strong>开局金钱800</strong><br></p><p>已知CJX打了几回合的胜负情况（赢了加300）和杀敌情况（杀死一个敌人+300），以及买枪情况</p><p>请问回合结束时CJX的钱数</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为接下来输入动作表达式行数i</p><p>然后输入i个动作表达式</p><p><br></p><p>现在规定 每行表示CJX的一个动作，语法如下("[]"为可选参数）</p><p>动作序号 [买枪种类/杀敌个数]</p><p>动作序号：</p><p>a为回合结束，此时后面加上数据"杀敌个数"（杀死一个敌人+300）</p><p>b为回合开始并且上局获得胜利（此时金钱加2700）</p><p>c为买枪，买枪种类（有三种，分别为"AK-47"2500元，"B41"2000元，"M249"6000(套装价）)</p><p><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>动作结束后CJX的钱数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>b</p><p>a 3</p><p>c AK47</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1900<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong style="">1.开局金钱800</strong></p><p><strong style="">2.如果每回合结束，CJX在这回合没有杀敌 不会输入"a 0"</strong></p><p><strong style="">3.CS1.6中金钱上限16000</strong></p><p><strong style="">4.可以在一回合内不停地买枪</strong></p>
</div>
</div>