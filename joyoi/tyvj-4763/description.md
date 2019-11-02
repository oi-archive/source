# 

 
 # 题目描述 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">Kiana最近沉迷于一款神奇的游戏无法自拔。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">简单来说，这款游戏是在一个平面上进行的。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">有一架弹弓位于（0,0)处，每次Kiana可以用它向第一象限发射一只红色的小鸟，小鸟们的飞行轨迹均为形如y=ax^2+bx的曲线，其中a,b是Kiana指定的参数，且必须满足a&lt;0。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">当小鸟落回地面（即x轴）时，它就会瞬间消失。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">在游戏的某个关卡里，平面的第一象限中有n只绿色的小猪，其中第i只小猪所在的坐标为(xi,yi)。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">如果某只小鸟的飞行轨迹经过了(xi,yi),那么第i只小猪就会被消灭掉，同时小鸟将会沿着原先的轨迹继续飞行；</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">如果一只小鸟的飞行轨迹没有经过(xi,yi)，那么这只小鸟飞行的全过程就不会对第i只小猪产生任何影响。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">例如，若两只小猪分别位于（1,3)和（3,3)，Kiana可以选择发射一只飞行轨迹为y=-x^2+4x的小鸟，这样两只小猪就会被这只小鸟一起消灭。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">而这个游戏的目的，就是通过发射小鸟消灭所有的小猪。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">这款神奇游戏的每个关卡对Kiana来说都很难，所以Kiana还输入了一些神秘的指令，使得自己能更轻松地完成这个游戏。这些指令将在【输入格式】中详述。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">假设这款游戏一共有T个关卡，现在Kiana想知道，对于每一个关卡，至少需要发射多少只小鸟才能消灭所有的小猪。由于她不会算，所以希望由你告诉她。</p> 

 
 # 输入格式 
<p><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81); font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">输入格式：</span></p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&nbsp;</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第一行包含一个正整数T，表示游戏的关卡总数。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">下面依次输入这T个关卡的信息。每个关卡第一行包含两个非负整数n,m，分别表示该关卡中的小猪数量和Kiana输入的神秘指令类型。接下来的n行中，第i行包含两个正实数(xi,yi)，表示第i只小猪坐标为(xi,yi)。数据保证同一个关卡中不存在两只坐标完全相同的小猪。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">如果m=0，表示Kiana输入了一个没有任何作用的指令。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">如果m=1，则这个关卡将会满足：至多用<img src="/source/joyoi/tyvj-4763/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XGxlZnQlMjBcbGNlaWwlMjBcZnJhY3tufXszfSUyMCslMjAxJTIwXHJpZ2h0JTIwXHJjZWls.latex" style="box-sizing: border-box; border: 0px; vertical-align: middle; max-width: 100%;" />只小鸟即可消灭所有小猪。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">如果m=2,则这个关卡将会满足：一定存在一种最优解，其中有一只小鸟消灭了至少<img src="/source/joyoi/tyvj-4763/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XGxlZnQlMjBcbGZsb29yJTIwXGZyYWN7bn17M30lMjBccmlnaHQlMjBccmZsb29y.latex" style="box-sizing: border-box; border: 0px; vertical-align: middle; max-width: 100%;" />只小猪。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">保证1&lt;=n&lt;=18，0&lt;=m&lt;=2，0&lt;xi,yi&lt;10，输入中的实数均保留到小数点后两位。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">上文中，符号<img src="/source/joyoi/tyvj-4763/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XGxlZnQlMjBcbGNlaWwlMjB4JTIwXHJpZ2h0JTIwXHJjZWls.latex" style="box-sizing: border-box; border: 0px; vertical-align: middle; max-width: 100%;" />和<img src="/source/joyoi/tyvj-4763/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XGxlZnQlMjBcbGZsb29yJTIweCUyMFxyaWdodCUyMFxyZmxvb3I=.latex" style="box-sizing: border-box; border: 0px; vertical-align: middle; max-width: 100%;" />分别表示对c向上取整和向下取整</p> 

 
 # 输出格式 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">对每个关卡依次输出一行答案。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">输出的每一行包含一个正整数，表示相应的关卡中，消灭所有小猪最少需要的小鸟数量</p>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#1：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
2
2&nbsp;0
1.00&nbsp;3.00
3.00&nbsp;3.00
5&nbsp;2
1.00&nbsp;5.00
2.00&nbsp;8.00
3.00&nbsp;9.00
4.00&nbsp;8.00
5.00&nbsp;5.00</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#1：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
1
1</pre>
</div>
</div>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#2：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
3
2&nbsp;0
1.41&nbsp;2.00
1.73&nbsp;3.00
3&nbsp;0
1.11&nbsp;1.41
2.34&nbsp;1.79
2.98&nbsp;1.49
5&nbsp;0
2.72&nbsp;2.72
2.72&nbsp;3.14
3.14&nbsp;2.72
3.14&nbsp;3.14
5.00&nbsp;5.00</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#2：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
2
2
3
</pre>
</div>
</div>

<div class="am-g" style="box-sizing: border-box; margin: 0px -1rem; width: auto; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">
<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: left; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输入样例#3：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
1
10&nbsp;0
7.16&nbsp;6.28
2.02&nbsp;0.38
8.33&nbsp;7.78
7.68&nbsp;2.09
7.46&nbsp;7.86
5.77&nbsp;7.44
8.24&nbsp;6.72
4.42&nbsp;5.11
5.42&nbsp;7.79
8.15&nbsp;4.99</pre>
</div>

<div class="am-u-md-6" style="box-sizing: border-box; width: 414.01px; padding-left: 1rem; padding-right: 1rem; float: right; position: relative;"><span style="box-sizing: border-box; font-weight: 700; color: rgb(81, 81, 81);">输出样例#3：</span>

<pre style="box-sizing: border-box; line-height: 1.6; margin-top: 1rem; margin-bottom: 1rem; font-size: 1.3rem; font-family: Monaco, Menlo, Consolas, &quot;Courier New&quot;, FontAwesome, monospace; background-color: rgb(248, 248, 248); padding: 1rem; word-break: break-all; color: rgb(85, 85, 85); border: 1px solid rgb(222, 222, 222); border-radius: 0px;">
6</pre>
</div>
</div>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">&nbsp;</p> 

 
 # 提示 
<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">【样例解释1】</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">这组数据中一共有两个关卡。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第一个关卡与【问题描述】中的情形相同，2只小猪分别位于（1.00,3.00)和&nbsp;(3.00,3.00)，只需发射一只飞行轨迹为y&nbsp;=&nbsp;-x^2&nbsp;+&nbsp;4x的小鸟即可消灭它们。</p>

<p style="box-sizing: border-box; margin: 1.6rem 0px; font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px;">第二个关卡中有5只小猪，但经过观察我们可以发现它们的坐标都在抛物线&nbsp;y&nbsp;=&nbsp;-x^2&nbsp;+&nbsp;6x上，故Kiana只需要发射一只小鸟即可消灭所有小猪。</p> 
