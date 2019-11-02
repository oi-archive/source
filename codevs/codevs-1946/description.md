<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>阿狸喜欢收藏各种稀奇古怪的东西，最近他淘到一台老式的打字机。打字机 上只有 28 个按键，分别印有 26 个小写英文字母和'B'、'P'两个字母。 经阿狸研究发现，这个打字机是这样工作的：</p>
<p> 输入小写字母，打字机的一个凹槽中会加入这个字母(按 P 前凹槽中至 少有一个字母)。</p>
<p> 按一下印有'B'的按键，打字机凹槽中最后一个字母会消失。</p>
<p> 按一下印有'P'的按键，打字机会在纸上打印出凹槽中现有的所有字母并 换行，但凹槽中的字母不会消失（保证凹槽中至少有一个字母）。</p>
<p>例如，阿狸输入 aPaPBbP，纸上被打印的字符如下： a aa ab 我们把纸上打印出来的字符串从 1 开始顺序编号，一直到 n。打字机有一个 非常有趣的功能，在打字机中暗藏一个带数字的小键盘，在小键盘上输入两个数 (x,y)（其中 1≤x,y≤n），打字机会显示第 x 个打印的字符串在第 y 个打印的字符串 中出现了多少次。 阿狸发现了这个功能以后很兴奋，他想写个程序完成同样的功能，你能帮助 他么？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个字符串，按阿狸的输入顺序给出所有阿狸输入的字符。 第二行包含一个整数 m，表示询问个数。 接下来 m 行描述所有由小键盘输入的询问。其中第 i 行包含两个整数 x, y， 表示第 i 个询问为(x, y)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出 m 行，其中第 i 行包含一个整数，表示第 i 个询问的答案。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>aPaPBbP</p>
<p>3</p>
<p>1 2</p>
<p>1 3</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1</p>
<p>0 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤n≤ 10<sup>5</sup>，1≤m≤ 105<sup>5</sup></p>
</div>
</div>