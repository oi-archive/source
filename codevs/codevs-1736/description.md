<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>公元11380年，一颗巨大的陨石坠落在南极。于是，灾难降临了，地球上出现了一系列反常的现象。当人们焦急万分的时候，一支中国科学家组成的南极考察队赶到了出事地点。经过一番侦察，科学家们发现陨石上刻有若干行密文，每一行都包含5个整数：</p>
<p><strong>1 1 1 1 6</strong></p>
<p><strong>0 0 6 3 57</strong></p>
<p><strong>8 0 11 3 2845</strong></p>
<p>著名的科学家SS发现，这些密文实际上是一种复杂运算的结果。为了便于大家理解这种运算，他定义了一种SS表达式：</p>
<p>1．  SS表达式是仅由‘{’，‘}’，‘[’，‘]’，‘（’，‘）’组成的字符串。</p>
<p>2．  一个空串是SS表达式。</p>
<p>3．  如果A是SS表达式，且A中不含字符‘{’，‘}’，‘[’，‘]’，则(A)是SS表达式。</p>
<p>4．  如果A是SS表达式，且A中不含字符‘{’，‘}’，则[A]是SS表达式。</p>
<p>5．  如果A是SS表达式，则{A}是SS表达式。</p>
<p>6．  如果A和B都是SS表达式，则AB也是SS表达式。</p>
<p>例如</p>
<p><strong>()(())[]</strong></p>
<p><strong>{()[()]}</strong></p>
<p><strong>{{[[(())]]}}</strong></p>
<p>都是SS表达式。</p>
<p>而</p>
<p><strong>()([])()</strong></p>
<p><strong>[()</strong></p>
<p>不是SS表达式。</p>
<p> </p>
<p>一个SS表达式E的深度D(E)定义如下：</p>
<p>0 如果E是空串。</p>
<p>D(A) + 1 如果E是{A}或[A]或（A）其中A满足SS表达式</p>
<p>MAX（D(A), D(B)）如果E是AB，A、B满足SS表达式</p>
<p>例如(){()}[]的深度为2。</p>
<p> </p>
<p>密文中的复杂运算是这样进行的：</p>
<p>设密文中每行前4个数依次为L1，L2，L3，D，求出所有深度为D，含有L1对{}，L2对[]，L3对()的SS串的个数，并用这个数对当前的年份11380求余数，这个余数就是密文中每行的第5个数，我们称之为“神秘数”。</p>
<p>密文中某些行的第五个数已经模糊不清，而这些数字正是揭开陨石秘密的钥匙。现在科学家们聘请你来计算这个神秘数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共一行，4个整数L1，L2，L3，D。相邻两个数之间用一个空格分隔。</p>
<p>（0≤L1≤10，0≤L2≤10，0≤L3≤10，0≤D≤30）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共一行，包含一个整数，即神秘数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目描述中也有3组数据</p>
</div>
</div>