<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　老师给你了一个小球序列A，每个小球上标有一个小写字母（’a’ ~ ’z’）。你不喜欢给定的这个排列方式，你想把它改成另外一个序列B。于是你制定了四种操作：<br/>
　　1、  在任意一个位置增加标有任意字母的小球。<br/>
　　2、  删掉任意一个位置的小球。<br/>
　　3、  将某个小球用任意一个其他的小球取代。<br/>
　　4、  交换相邻两个小球。<br/>
<br/>
　　老师对这四种操作给出了时间规定，即每种操作都需要一个确定的时间来完成。具体的，操作1用时ti，操作2用时td，操作3用时tr，操作4用时te。注意，所有数据保证2·<i>t<sub>e</sub></i> ≥ <i>t<sub>i</sub></i> + <i>t<sub>d</sub></i>。<br/>
　　请求出将序列A转化为序列B的最小用时。</div>
# 输入格式

<div class="pdcont">　　第一行：四个整数，依次为ti、td、tr、te（0 &lt; <i>t<sub>i</sub></i>, <i>t<sub>d</sub></i>, <i>t<sub>r</sub></i>, <i>t<sub>e</sub></i> ≤ 100）。<br/>
　　第二第三行各一个字符串，分别为序列A和序列B，长度均在1到4000之间。</div>
# 输出格式

<div class="pdcont">　　一个整数，将A转化为B所用的最少时间。<br/>
<br/>
<b>样例输入1</b><br/>
　　1 1 1 1<br/>
　　youshouldnot<br/>
　　thoushaltnot<br/>
<b>样例输出1</b><br/>
　　5<br/>
<b>样例输入2</b><br/>
　　2 4 10 3<br/>
　　ab<br/>
　　ba<br/>
<b>样例输出2</b><br/>
　　3<br/>
<b>样例输入3</b><br/>
　　1 10 20 30<br/>
　　a<br/>
　　za<br/>
<b>样例输出3</b><br/>
　　1<br/>
<br/>
<br/>
<b>样例解释</b><br/>
　　样例2，你可以先删掉1位置的’a’再在末尾填上’a’，总用时为6。然而也可以直接交换’a’和’b’，用时为3，可以验证这是最短的用时。</div>

</div>