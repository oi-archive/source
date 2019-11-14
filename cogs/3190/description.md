# 题目描述


<h3>
【题目背景】
</h3>
<p>
  你与<strong>YF</strong>一起来到了<strong>YH教</strong>创立两周年庆典，只见这里锣鼓喧天，鞭炮齐鸣，红旗招展，人山人海，一下子，<strong>YF</strong>就眼红了，带着自己的武器，冲进了庆祝的人群中，开始大杀四方。
</p>
<p>
  而你一点也不担心，一方面<strong>YF</strong>承诺让你活着回家（虽然他很有可能会违背诺言），另一方面，你十分清楚，<strong>YH教</strong>中的成员个个都是人才，说话还好听，超喜欢呆在这里的，你相信其他的<strong>YH</strong>可以拖住发疯了的<strong>YF</strong>，所以你悠闲地进入场地，开始做你的事情。
</p>
<p>
<br/>
</p>
<p>
  <strong>YH教</strong>中的成员个个都是人才，你十分希望认识更多的<strong>YH</strong>，由于你并不是<strong>YF</strong>，不能一口气吃成个胖子，所以一次只能认识两个<strong>YH</strong>。
</p>
<p>
  同时每位<strong>YH</strong>都有一个幸运值$A$，所以你希望认识两个<strong>YH</strong>，但由于物以类聚，人以群分，你希望你认识的两个<strong>YH</strong>，他们的幸运值，与你的幸运值差值的绝对值最小以及次小。
</p>
<p>
  但在你认识<strong>YH</strong>的过程中，<strong>YF</strong>拿着武器在后面追杀，所以你只能认识标号比你大的YH。
</p>
<p>
  由于你十分热心，也是一位神犇Oler,所以你要帮助在场的所有<strong>YH</strong>寻找他们要认识的<strong>YH</strong>。
</p>
<h3>
【题目描述】
</h3>
<p>
  对于每一个<strong>YH</strong>,给定每一个<strong>YH</strong>的幸运值。
</p>
<p>
  求出标号大于该<strong>YH</strong>标号的两个<strong>YH</strong>，使两个<strong>YH</strong>的幸运值分别与当前<strong>YH</strong>幸运值差值的绝对值最小与次小。
</p>
<p>
  如果绝对值相等，视幸运值较小的为较小的值。
</p>
<h3>
【输入格式】
</h3>
<p>
  第一行一个整数 $N$，表示来参加庆典的<strong>YH</strong>数量。
</p>
<p>
  第二行 $N$ 个整数，表示 $N $个<strong>YH</strong>的幸运值$A$。
</p>
<h3>
【输出格式】
</h3>
<p>
  一共 $N$ 行，第$i$行两个整数表示，第 $i+1$ 到第 $N$ 个<strong>YH</strong>中满足，幸运值与当前<strong>YH</strong>的幸运值的绝对值，最小与次小的<strong>YH</strong>下标。
</p>
<p>
  如果不存在，则输出0.
</p>
<h3>
【样例输入】
</h3>
<pre>3
1 5 3</pre>
<h3>
【样例输出】
</h3>
<pre>3 2
3 0
0 0</pre>
<h3>
【提示】
</h3>
<p>
对于 30% 的数据，有 1≤N≤20
</p>
<p>
对于 40% 的数据，有 1≤N≤100
</p>
<p>
对于 50% 的数据，有 1≤N≤100
</p>
<p>
对于 70% 的数据，有 1≤N≤1,000
</p>
<p>
对于 100% 的数据，有 1≤N≤100,000
</p>
<p>
-1,000,000,000≤ Ai ≤1,000,000,000 数据保证 Ai 互不相同。
</p>
<h3>
【来源】
</h3>
<p>
LGLJ
</p>
