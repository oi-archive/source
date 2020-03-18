# 题目描述

<p>为了庆祝 UOJ Round #9 的成功开赛，主办方为大家准备了一桌包子晚宴。NOI出题人也被邀请参加了包子晚宴。</p>
<p>谁知包子晚宴吃到一半，突然主办方把面具一摘，露出他的真身 —— 奸笑熊：“还记得我吗？我就是因为你的寿司晚宴才没拿金牌的！”</p>
<p>NOI出题人大惊失色，原来这是鸿门宴！</p>
<p>奸笑熊一挥手，所有的门窗都被关闭了。奸笑熊掌心朝上，所有的包子都悬浮在了空中，再那么一指，所有的包子形成了一张大幕，朝NOI出题人飞去。</p>
<p>还好还好，NOI出题人玩过东方 Project，熟悉躲子弹的那一套理论。</p>
<p> </p>
<p>我们假设晚宴所在的房间是二维的，是一个宽度为 $w$ 高度为 $h$ 的矩形，NOI出题人可以抽象为一个<strong><u>没有大小的点</u></strong>，包子可以抽象为一个圆。</p>
<p>我们以<strong><u>矩形左上角</u></strong>为原点，宽为 $x$ 轴（<strong><u>正方向向右</u></strong>）高为 $y$ 轴（<strong><u>正方向向下</u></strong>）建立平面直角坐标系。</p>
<p>假设NOI出题人的位置在 $(x, y)$，那么NOI出题人的<strong><u>中弹范围</u></strong>是一个以 $(x, y)$ 为圆心，半径为 $r$ 的圆；NOI出题人的<strong><u>擦弹范围</u></strong>是一个以 $(x, y)$ 为圆心，半径为 $R$ 的圆。保证 $R &gt; r$。</p>
<p>一共 $n$ 个子弹，编号为 $1$ 到 $n$，其中第 $i$ 个子弹在 $t_{a_i}$ 时刻出现，在 $t_{b_i}$ 时刻后消失。出现时位置为 $(x_i, y_i)$，速度为 $(v_{x_i}, v_{y_i})$（表示一个单位时间内横向移动 $v_{x_i}$，纵向移动 $v_{y_i}$）。子弹将保持这一速度移动直至消失。</p>
<p>得分有两种途径：</p>
<ol><li>不中弹得分：有 $k$ 个时间区间 $[t_{s_i}, t_{e_i}]$。如果在 $t_{s_i} \sim t_{e_i}$ 这段时间内（包括首尾）没有任何一个子弹的圆与NOI出题人的<strong><u>中弹范围</u></strong>相交（包括外切、内切、内含），则获得 $s_i$ 的分数；</li>
<li>擦弹得分：每个子弹有一个擦弹得分 $g_i$，如果一个子弹的圆与NOI出题人的<strong><u>擦弹范围</u></strong>在某个时刻相交（包括外切、内切、内含），则获得 $g_i$ 的分数。<strong><u>若对同一个子弹多次擦弹，则只记一次</u></strong>。</li>
</ol><p>一个子弹的中弹和擦弹判定<strong><u>只在整数时刻</u></strong>进行，即时刻 $t_{a_i}, t_{a_i} + 1, \dots, t_{b_i}$。</p>
<p>在时刻 $i$，NOI出题人可以决定他时刻 $i$ 到时刻 $i + 1$ 这段时间内向哪一个方向移动，也可以选择不动（“<samp>S</samp>”）。可以选择的方向有 $8$ 种：上（“<samp>W</samp>”）、下（“<samp>X</samp>”）、左（“<samp>A</samp>”）、右（“<samp>D</samp>”）、左上（“<samp>Q</samp>”）、左下（“<samp>Z</samp>”）、右上（“<samp>E</samp>”）、右下（“<samp>C</samp>”）（后四种方向夹角均为 $45^{\circ}$）。NOI出题人在一个单位时间内移动的距离为定值 $d$。</p>
<p>NOI出题人<strong><u>不允许出房间</u></strong>，即NOI出题人的位置要在矩形内。</p>
<p>奸笑熊说只要NOI出题人获得的分数足够高就放他一马，于是现在NOI出题人想获得尽量高的得分。</p>

# 输入格式


<p>本题为提交答案题。所有输入数据 <samp>touhou1.in～touhou10.in</samp> 见数据下载。</p>
<p>对于每组数据，输入文件的第一行有七个数 $w, h, x_0, y_0, d, r, R$，分别表示矩形的宽度和高度、NOI出题人在时刻 $0$ 的初始位置、一个时刻内移动的距离、中弹和擦弹判定圆的半径。</p>
<p>第二行有一个正整数 $n$，表示出现的总子弹数。</p>
<p>接下来 $n$ 行，每行有八个数 $t_{a_i}, t_{b_i}, x_i, y_i, v_{x_i}, v_{y_i}, r_i, g_i$，分别表示每个子弹的出现和消失时间、出现时的位置、移动速度、半径和擦弹得分。</p>
<p>接下来一行有一个非负整数 $k$，表示结算分数的时间区间的数量。</p>
<p>接下来 $k$ 行，每行有三个数 $t_{s_i}, t_{e_i}, s_i$，分别表示每个时间区间的开始时刻、结束时刻和不中弹得分。</p>
<p>最后一行有一个数 $T$，表示游戏持续的总时间。</p>

# 输出格式


<p>针对给定的 $10$ 个输入文件 <samp>touhou1.in～touhou10.in</samp>，你需要分别给出你的输出文件 <samp>touhou1.out～touhou10.out</samp>。</p>
<p>对于每组数据，输出文件只有一行 $T$ 个字符，第 $i$ 个字符表示NOI出题人在时刻 $i − 1$ 到时刻 $i$ 的移动方向。</p>

# 样例一


<h4>input</h4>
<pre>10 10 0 0 3 1 2
2
1 2 1 0 2 0 1 5
3 3 4 2 0 0 1 5
2
0 2 10
2 3 10
3

</pre>

<h4>output</h4>
<pre>CDS

</pre>

<h4>explanation</h4>
<p>时刻 $0$，NOI出题人的位置在 $(0,0)$。</p>
<p>时刻 $1$，在位置 $(1,0)$ 出现了一个子弹，NOI出题人移动到位置 $(2.12132,2.12132)$。</p>
<p>此时NOI出题人与子弹距离为 $2.39945$，获得擦弹得分 $5$。</p>
<p>时刻 $2$，子弹移动到位置 $(3,0)$，NOI出题人移动到位置 $(5.12132,2.12132)$。此时NOI出题人与子弹距离为 $3$，仍然擦弹但不再得分，同时该子弹消失。</p>
<p>在时刻 $[0,2]$ 内NOI出题人未中弹，获得不中弹得分 $10$。</p>
<p>时刻 $3$，在位置 $(4,2)$ 出现了一个子弹，NOI出题人位置 $(5.12132,2.12132)$。此时NOI出题人与子弹距离 $1.12786$，NOI出题人中弹，同时获得擦弹得分 $5$。</p>
<p>在时刻 $[2,3]$ 内NOI出题人中弹，未能获得不中弹得分。</p>
<p>总得分为 $20$。</p>

# 评分方式


<p>对于每组测试数据，我们设置了 $9$ 个评分参数 $a_{10}, a_9, a_8, \dots, a_2$。如果你的输出不合法，则得 $0$ 分。否则，在你的方案中，若游戏得分为 $w_{user}$，你的分数将会由下表给出：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th><th>条件</th><th>得分</th><th>条件</th></tr></thead><tbody><tr><td>10</td><td>$w_{user} \geq a_{10}$</td><td>5</td><td>$w_{user} \geq a_5$</td></tr><tr><td>9</td><td>$w_{user} \geq a_9$</td><td>4</td><td>$w_{user} \geq a_4$</td></tr><tr><td>8</td><td>$w_{user} \geq a_8$</td><td>3</td><td>$w_{user} \geq a_3$</td></tr><tr><td>7</td><td>$w_{user} \geq a_7$</td><td>2</td><td>$w_{user} \geq a_2$</td></tr><tr><td>6</td><td>$w_{user} \geq a_6$</td><td>1</td><td>$w_{user} &gt; 0$</td></tr></tbody></table></div>

<p>如果同时满足多个条件，则取最高分作为你的分数。</p>

# 如何测试你的输出


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）</p>
<p><code>cd touhou</code></p>
<p>我们提供checker这个工具来测试你的输出文件是否是可接受的。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker_linux64 &lt;case_no&gt;</code></p>
<p>其中<code>case_no</code>是测试数据的编号。例如</p>
<p><code>./checker_linux64 3</code></p>
<p>将测试 <samp>touhou3.out</samp> 是否可以接受。（windows用户请使用<code>checker_win32 3</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的linux 32位版本：<code>checker_linux32</code>。如果linux用户发现无法运行程序，请尝试执行<code>chmod +x checker_linux64</code>或<code>chmod +x checker_linux32</code>后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node checker.js &lt;case_no&gt;</code> 运行checker。</p>
<p>在你调用这个程序后，checker将根据你给出的输出文件给出测试的结果。</p>
<p> </p>
<p>为了方便你调试，我们提供的 checker 中还增加了一些功能。你在使用 checker 时可以调用选项来获得一些额外的信息。可调用的选项包括：</p>
<ol><li><code>–p</code>：输出每个时刻角色所在的位置。</li>
<li><code>–m</code>：输出每次中弹的相关信息。</li>
<li><code>–g</code>：输出每次擦弹的相关信息（对同一个子弹多次擦弹只输出第一次）。</li>
<li><code>–t</code>：在每个时间区间结束时显示是否获得不中弹得分。</li>
<li><code>–x</code>：将调用以上四种选项所产生的信息不输出到屏幕上，而是输出到对应的 <samp>touhou*.log</samp> 文件中。</li>
</ol><p>调用选项的方法如下例所示:</p>
<p><code>./checker_linux64 3 –m –g –x</code></p>
<p>将检查 <samp>touhou3.out</samp> 是否可以接受。如果 <samp>touhou3.out</samp> 可以接受，则在输出得分的同时将每次中弹和擦弹的相关信息输出到 <samp>touhou3.log</samp> 中。</p>
<p>以上所有信息均按时间顺序输出。</p>
<p><strong>注意比赛时提交此题显示的成绩就是最终成绩。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=135">输入数据及checker下载</a></p>
