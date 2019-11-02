<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">    冒险岛是费老师新开发的一种情景模拟电脑的游戏，通过掷骰子（1~6个数字之间），让一种人物（棋子）在棋纸上从左至右的行走，从而模拟冒险的故事。棋纸上有一条从左至右的很长的路，整条路是一连串符号组成，表明路的状况，棋子必须在符号组成的路上行走。每掷一下骰子得到的数字，棋子就可以走掷得的数字所对应的步数，比如掷3，就可以走3步。</p><p style="">    路上有两种特殊符号可以改变棋子的行走。</p><p style="">    一种是“&gt;”符号，一旦棋子走完了掷骰子的步数，最终停留在这个符号上，后面有紧跟着2个以上“&gt;”，那么棋子就可以获得前进奖励，可以沿着“&gt;”一直一步步前进，直到遇到一个不是“&gt;”的符号位置停下来。</p><p style="">    还有一种是“*”符号，一旦棋子走完了掷骰子的步数，最终停留在这个符号上，后面又紧跟着两个以上“*”，就要受到后退惩罚，需要退后k步，这个k步就是从当前“*”开始的连续的“*”的数量。</p><p style="">    每次掷数后，奖励或惩罚至多一次，如果奖励或惩罚后棋子又落在第二种特殊符号上，则不能再受到奖励或惩罚。</p><p style="">    如果走的棋子超出棋纸右边界最后一个符号，则停在最后一个符号上；如果超出左边界，则停在第一个符号上。</p><p style="">    若干次掷骰子后，请问游戏中的人物（棋子）走到了哪步？离终点还差几步？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行为一个字符串s，字符串中的每个字符表示棋纸的路的状况。</p><p style="">第二行是一个n，表示掷了n次骰子。</p><p style="">第三行是n个整数（1~6的范围），表明掷了n次骰子得到的数字，数字之间有一个空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 只有两个数字，表明目前所在符号的序号和离终点符号的步数，数子中间有一个空格。<strong>注意输出末尾有换行。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>yhfA&gt;&gt;&gt;fhsdfa***&gt;&gt;&gt;foaoad</p><p>3</p><p>5 6 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>    在游戏中，第一次掷的是5，则走到第一个&gt;的位置，获得奖励前进至左起第二个f处。第二次掷的是6，则走到*的位置，受惩罚退3步，至d处。第三次掷的是6，则走至左起第四个&gt;号处，获奖励前进至f。最终棋子停留的符号是第20个（从左至右的数），离终点符号d（含）相差5步数。</p><p>【数据范围】</p><p>    对于50%的数据，1&lt;=s的长度&lt;=255,0&lt;=n&lt;=1000。</p><p>    对于100%的数据，256&lt;=s的长度&lt;=1000000,0&lt;=n&lt;=100000。</p>
</div>
</div>