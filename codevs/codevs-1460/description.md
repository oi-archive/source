<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在Starcraft某个古怪的操作地图中，你被要求在一个狭窄的高低上用一个marine来打败两只zergling。由于你认为这是不可能完成的任务，你打算编程验证这一点。</p>
<p>为了方便处理，你抽象出了这样一个模型：<br>    作为战场的狭窄高地可以认为是一个<strong>5×5的方格阵</strong>，每个方格可能是“<strong>可通过</strong>”或“<strong>不可通过</strong>”两种情况。marine和zergling<strong>总是占据其中一个可通过方格</strong>。两个zergling可以处于同一方格，但在任一时刻marine不能和任一未死亡的zergling处于同一方格。marine和zergling均拥有生命值（HP），marine的初始生命值为m，所有zergling的初始生命值为z。<br>    游戏可以抽象为回合制。在每个回合中，marine首先行动。marine可以选择沿竖直或水平方向移动一格，或站在原地朝某只zergling开枪（由于高地非常狭窄，marine可以击中处于高地任何位置的zergling）。marine的每一枪会减少目标zergling的生命值1点，当一只zergling的生命值降低到0点或以下时会死亡。<br>    marine行动完毕后，所有尚未死亡的zergling会同时行动。如果某只zergling和marine相邻，他会攻击marine，否则他会沿着自己当前位置到marine的最短路前进一格。如果有多条最短路，zergling会按左、上、右、下的顺序依次尝试行动（例如如果左、上都是最短路，zergling会向左走）。如果两只zergling在同一格攻击marine，marine的生命值只会减少1点，否则每只zergling的攻击都会使marine的生命值减少1点。<br>    当某个回合结束时，若zergling全部死亡则认为游戏胜利，若marine生命值降低到0点或以下，或者游戏进行了34个回合但仍未胜利则认为游戏失败。<br>    你需要判定游戏是否可能取得胜利，如果可能，输出取得胜利需要的最少回合数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共6行。<br>输入文件的前5行每行有5个字符，表示战场每个方格的情况。<br>字符只可能出现“M”,“Z”,“z”，“1”,“0”<br>字符“1”表示对应方格，其他字符表示对应方格可通过。大写字母“M”表示marine的初始位置，大写字母“Z”和小写字母“z”表示两只zergling的初始位置。<br>输入文件的第6行有两个正整数m，z（1≤m≤16,1≤z≤99），分别表示marine的初始生命值和zergling的初始生命值。<br><strong><span style="text-decoration: underline;">注：战场地图可能出现由“1”围出的封闭区域</span></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行<br />如果游戏可以取得胜利，输出取得胜利需要的最少回合数<br />如果游戏不可能取得胜利，<strong>只输出&ldquo;LOSE&rdquo;（不用输出引号）。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>zZ000<br>11110<br>00M10<br>01110<br>00000<br>15 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：marine只需在原地对两只zergling不断攻击即可胜利<br>共5个测试点，每个测试点1s</p>
</div>
</div>