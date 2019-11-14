# 题目描述

<p>小 L 计划进行 $n$ 场游戏，每场游戏使用一张地图，小 L 会选择一辆车在该地图上完成游戏。</p>
<p>小 L 的赛车有三辆，分别用大写字母 A、B、C 表示。地图一共有四种，分别用小写字母 x、a、b、c 表示。其中，赛车 A 不适合在地图 a 上使用，赛车 B 不适合在地图 b 上使用，赛车 C 不适合在地图 c 上使用，而地图 x 则适合所有赛车参加。适合所有赛车参加的地图并不多见，最多只会有 d 张。</p>
<p>$n$ 场游戏的地图可以用一个小写字母组成的字符串描述。例如：$\underline{S=xaabxcbc}$ 表示小 L 计划进行 8 场游戏，其中第 1 场和第 5 场的地图类型是 x，适合所有赛车，第 2
场和第 3 场的地图是 a，不适合赛车 A，第 4 场和第 7 场的地图是 b，不适合赛车 B，第 6 场和第 8 场的地图是 c，不适合赛车 C。</p>
<p>小 L 对游戏有一些特殊的要求，这些要求可以用四元组 $(i,h_i , j,h_j )$ 来描述，表示若在第 $i$ 场使用型号为 $h_i$ 的车子，则第 $j$ 场游戏要使用型号为 $h_j$ 的车子。</p>
<p>你能帮小 L 选择每场游戏使用的赛车吗？如果有多种方案，输出任意一种方案。如果无解，输出 “<samp>-1</samp>”（不含双引号）。</p>

# 输入格式


<p>输入第一行包含两个非负整数 $n,d$。</p>
<p>输入第二行为一个字符串 $S$ 。</p>
<p>$n,d,S$ 的含义见题目描述，其中 $S$ 包含 $n$ 个字符，且其中恰好 $d$ 个为小写字母 $x$。</p>
<p>输入第三行为一个正整数 $m$ ，表示有 $m$ 条用车规则。接下来 $m$ 行，每行包含一个四元组 $i,h_i,j,h_j$ ，其中 $i,j$ 为整数，$h_i,h_j$ 为字符 A 、B 或 C，含义见题目描述。</p>

# 输出格式


<p>输出一行。</p>
<p>若无解，输出 “<samp>-1</samp>”（不含双引号）。</p>
<p>若有解，则包含一个长度为 $n$ 的仅包含大写字母 A、B、C 的字符串，表示小 L 在这 $n$ 场游戏中如何安排赛车的使用。如果存在多组解，输出其中任意一组即可。</p>

# 样例一


<h4>input</h4>
<pre>3 1
xcc
1
1 A 2 B

</pre>

<h4>output</h4>
<pre>ABA

</pre>

<h4>explanation</h4>
<p>小 L 计划进行 3 场游戏，其中第 1 场的地图类型是 x，适合所有赛车，第 2 场和第 3 场的地图是 c，不适合赛车 C。</p>
<p>小 L 希望：若第 1 场游戏使用赛车 A，则第 2 场游戏使用赛车 B。</p>
<p>那么为这 3 场游戏分别安排赛车 A、B、A 可以满足所有条件。</p>
<p>若依次为 3 场游戏安排赛车为 BBB 或 BAA 时，也可以满足所有条件，也被视为正确答案。但依次安排赛车为 AAB 或 ABC 时，因为不能满足所有条件，所以不被视为正确答案。</p>

# 样例二


<p>见下载文件中的 <em>ex_game2.in</em> 与 <em>ex_game2.ans</em>。</p>

# 限制与约定


<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$d$</th><th rowspan="1">$m$</th><th rowspan="1">其他性质</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="2">$\le 2$</td><td rowspan="1">$0$</td><td rowspan="2">$\le 4$</td><td rowspan="6">无</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$\le n$</td></tr><tr><td rowspan="1">3</td><td rowspan="2">$\le 5$</td><td rowspan="1">$0$</td><td rowspan="2">$\le 10$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$\le n$</td></tr><tr><td rowspan="1">5</td><td rowspan="2">$\le 10$</td><td rowspan="1">$0$</td><td rowspan="2">$\le 20$</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$\le 8$</td></tr><tr><td rowspan="1">7</td><td rowspan="4">$\le 20$</td><td rowspan="2">$0$</td><td rowspan="4">$\le 40$</td><td rowspan="1">S中只包含c</td></tr><tr><td rowspan="1">8</td><td rowspan="1">无</td></tr><tr><td rowspan="1">9</td><td rowspan="2">$\le 8$</td><td rowspan="1">S中只包含x或c</td></tr><tr><td rowspan="1">10</td><td rowspan="1">无</td></tr><tr><td rowspan="1">11</td><td rowspan="4">$\le 100$</td><td rowspan="2">$0$</td><td rowspan="4">$\le 200$</td><td rowspan="1">S中只包含c</td></tr><tr><td rowspan="1">12</td><td rowspan="1">无</td></tr><tr><td rowspan="1">13</td><td rowspan="2">$\le 8$</td><td rowspan="1">S中只包含x或c</td></tr><tr><td rowspan="1">14</td><td rowspan="2">无</td></tr><tr><td rowspan="1">15</td><td rowspan="3">$\le 5000$</td><td rowspan="1">$0$</td><td rowspan="3">$\le 10000$</td></tr><tr><td rowspan="1">16</td><td rowspan="2">$\le 8$</td><td rowspan="1">S中只包含x或c</td></tr><tr><td rowspan="1">17</td><td rowspan="2">无</td></tr><tr><td rowspan="1">18</td><td rowspan="3">$\le 50000$</td><td rowspan="1">$0$</td><td rowspan="3">$\le 100000$</td></tr><tr><td rowspan="1">19</td><td rowspan="2">$\le 8$</td><td rowspan="1">S中只包含x或c</td></tr><tr><td rowspan="1">20</td><td rowspan="1">无</td></tr></tbody></table><p><strong>时间限制：</strong><del>1s</del> $2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=317">样例数据下载</a></p>
