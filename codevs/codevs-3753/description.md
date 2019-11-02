<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>落冰从悬崖上被冲下，虽有落令的精魂保护大难不死，但已消耗了大半法力。此时的棂刚刚也连续经历了三场恶战，身负重伤。夜色中他们急于撤出迷雾丛林，途中却被拉尔法的磁阵困住。这个磁阵专门用来对付落冰，由于洛伦兹力的作用，为避免给自己造成伤害，落冰被迫把自身的电流降到接近0，也因此暂时失去了攻击能力。拉尔法得意地阴笑着，因为他看出了棂的重伤，并认为自己可以轻易战胜棂。<br></p><p><br></p><p>然而，身经百战的棂早已看穿了一切，他知道拉尔法用大脑控制磁阵。棂和拉尔法之间的磁阵可以看作一个a行b列的矩阵。（他们都在矩阵的外面）棂可以在短时间内控制少量的γ光子，这些光子可以从某一列的任何一个格子出发，到达下一列的任何一个格子，（当然光子一开始从棂出发，可到达第1列的任何一个格子；也可以从第b列——即最后一列——的任何一个格子出发到达拉尔法）当光子到达拉尔法所在的位置时，虽然伤害可以忽略不计，但光子可以对拉尔法的大脑造成扰动（大脑的思考是在量子层面的嘛），然后磁阵强度就会有一定程度的削弱。并且光子到达拉尔法的不同路径数越多，对拉尔法造成的扰动就越大，磁阵削弱得也越厉害。</p><p><br></p><p>这里一条路径指的是光子从棂出发经过b列之后到达拉尔法所经过的所有格子。光子只能从棂出发，经某一列到下一列，最后到达拉尔法。途中不能返回到前面的列，也不能在同一列的两个格子运动，更不能跳过某些列。</p><p><br></p><p><img src="/source/codevs/codevs-3753/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNzUzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDUwOTE1Mjg0M18zMzAucG5n.png" title=""></p><p><br></p><p>现在，棂想知道一共有多少种不同的路径，然后他就可以心算出光子对拉尔法造成的扰动和磁阵被削弱的程度，并挑选合适的符咒发动攻击。棂没带笔记本，因此他通过虚数空间把a和b的值告诉了梦中的晓筱。然而晓筱梦见了一个令人费解的数p，经过一番思索，她认为p也是棂告诉的，意思是把答案mod p，因为棂总是很关心她，不想麻烦她写高精。但晓筱参透了p的含义以后，剩余的脑细胞不足以计算出总路径数，于是她请精通OI的你来帮她。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只有一行，有3个整数a,b,p，含义同题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个整数，为总路径数mod p以后的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p><p>2 10 1000</p><p>样例输入2：</p><p>3 6 1000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：</p><p>24</p><p>样例输出2：</p><p>729<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，b &lt;= 10<sup>5</sup>;</p><p>对于40%的数据，b &lt;= 10<sup>50</sup>;</p><p>对于100%的数据，a,p &lt;= 10000; b &lt;= 10<sup>1000000</sup>;</p><p>数据全部随机；</p><p>（感觉这样的数据规模并不够大）</p>
</div>
</div>