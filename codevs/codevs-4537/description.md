<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小铭铭最近获得了一副新的桌游，游戏中需要用m 个骑士攻占n 个城池。</p><p>这n 个城池用1 到n 的整数表示。除1 号城池外，城池i 会受到另一座城池fi 的管辖，</p><p>其中fi &lt; i。也就是说，所有城池构成了一棵有根树。这m 个骑士用1 到m 的整数表示，其</p><p>中第i 个骑士的初始战斗力为si，第一个攻击的城池为ci。</p><p>每个城池有一个防御值hi，如果一个骑士的战斗力大于等于城池的生命值，那么骑士就可</p><p>以占领这座城池；否则占领失败，骑士将在这座城池牺牲。占领一个城池以后，骑士的战斗力</p><p>将发生变化，然后继续攻击管辖这座城池的城池，直到占领1 号城池，或牺牲为止。</p><p>除1 号城池外，每个城池i 会给出一个战斗力变化参数ai; vi。若ai = 0，攻占城池i 以后</p><p>骑士战斗力会增加vi；若ai = 1，攻占城池i 以后，战斗力会乘以vi。</p><p>注意每个骑士是单独计算的。也就是说一个骑士攻击一座城池，不管结果如何，均不会影</p><p>响其他骑士攻击这座城池的结果。</p><p>现在的问题是，对于每个城池，输出有多少个骑士在这里牺牲；对于每个骑士，输出他攻</p><p>占的城池数量。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1 行包含两个正整数n;m，表示城池的数量和骑士的数量。</p><p>第2 行包含n 个整数，其中第i 个数为hi，表示城池i 的防御值。</p><p>第3 到n + 1 行，每行包含三个整数。其中第i + 1 行的三个数为fi; ai; vi，分别表示管辖</p><p>这座城池的城池编号和两个战斗力变化参数。</p><p>第n + 2 到n + m + 1 行，每行包含两个整数。其中第n + i 行的两个数为si; ci，分别表</p><p>示初始战斗力和第一个攻击的城池。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出n + m 行，每行包含一个非负整数。其中前n 行分别表示在城池1 到n 牺牲的骑士</p><p>数量，后m 行分别表示骑士1 到m 攻占的城池数量。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p><p>50 20 10 10 30</p><p>1 1 2</p><p>2 0 5</p><p>2 0 -10</p><p>1 0 10</p><p>20 2</p><p>10 3</p><p>40 4</p><p>20 4<br></p><p>35 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>2</p><p>0</p><p>0</p><p>0</p><p>1</p><p>1</p><p>3</p><p>1</p><p>1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20% 的数据，0 &lt; n;m  3000。</p><p>对于20% 的数据，保证对于所有的城池i，fi = i</p>
</div>
</div>