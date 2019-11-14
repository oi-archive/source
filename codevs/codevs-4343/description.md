<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>jrMz 很喜欢动漫《叛逆的鲁鲁修》(额= =不知道是不是因为他盯上了动画片里的 MM),他<br>准备以一种神奇的方式降临《叛逆的鲁鲁修》世界,所以他先从《变形金刚》里把大黄蜂拐<br>了出来,然后成功加入了黑色骑士团。不过比较坑的事情出现了,正在与机甲激烈战斗中的<br>大黄蜂突然 WA 了,只有输入密码才能使它 AC,不幸的是 jrMz 已经忘记了密码。大黄蜂<br>的密码是一个 N 位的十进制非负整数(允许前缀 0),为了防止遗忘, jrMz 曾经将密码记了<br>下来。出于保密他没有将密码按原样记录(作死啊= =),于是他将他的密码乘以 E,其中<br>E=233……3(共 N-1 个 3),然后将结果的最后 N 位(保留前缀 0)进行记录。看着本来正<br>在欣赏他飒爽风姿的 MM(此仅仅是举例,举例!比如说鲁鲁修的妹妹什么的……), jrMz<br>只好紧握住你的双手向你求助了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一行,一个 N 位的十进制非负整数,表示密码与 E 的乘积的最后 N 位。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行,一个 N 位的十进制非负整数,表示密码。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>178</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>666</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【 Sample Explanation】<br>在所有三位十进制非负整数中,只有 666,满足其与 233 的乘积( 155178)的最后 3 位是 178。<br>【 Data Size】<br>对于 30%的数据, N&lt;=7;<br>对于 60%的数据, N&lt;=1,000;<br>对于 100%的数据, 3&lt;=N&lt;=1,000,000。</p>
</div>
</div>