<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小D 被邀请到实验室，做一个跟图片质量评价相关的主观实验。实验用到的图片集一共有 N 张图片，编号为 1 到 N。实验分若干轮进行，在每轮实验中，小 D会被要求观看某两张随机选取的图片， 然后小D 需要根据他自己主观上的判断确定这两张图片谁好谁坏，或者这两张图片质量差不多。 用符号“&lt;”、“&gt;”和“=”表示图片 x和y（x、y为图片编号）之间的比较：如果上下文中 x 和 y 是图片编号，则 x&lt;y 表示图片 x“质量优于”y，x&gt;y 表示图片 x“质量差于”y，x=y表示图片 x和 y“质量相同”；也就是说，这种上下文中，“&lt;”、“&gt;”、“=”分别是质量优于、质量差于、质量相同的意思；在其他上下文中，这三个符号分别是小于、大于、等于的含义。图片质量比较的推理规则（在 x和y是图片编号的上下文中）：（1）x &lt; y等价于 y &gt; x。（2）若 x &lt; y 且y = z，则x &lt; z。（3）若x &lt; y且 x = z，则 z &lt; y。（4）x=y等价于 y=x。（5）若x=y且 y=z，则x=z。 实验中，小 D 需要对一些图片对(x, y)，给出 x &lt; y 或 x = y 或 x &gt; y 的主观判断。小D 在做完实验后， 忽然对这个基于局部比较的实验的一些全局性质产生了兴趣。在主观实验数据给定的情形下，定义这 N 张图片的一个合法质量序列为形如“x1 R1 x2 R2 x3 R3 …xN-1 RN-1 xN”的串，也可看作是集合{ xi Ri xi+1|1&lt;=i&lt;=N-1}，其中 xi为图片编号，x1,x2,…,xN两两互不相同（即不存在重复编号），Ri为&lt;或=，“合法”是指这个图片质量序列与任何一对主观实验给出的判断不冲突。 例如： 质量序列3 &lt; 1 = 2 与主观判断“3 &gt; 1，3 = 2”冲突（因为质量序列中 3&lt;1 且1=2，从而3&lt;2，这与主观判断中的 3=2 冲突；同时质量序列中的 3&lt;1 与主观判断中的 3&gt;1 冲突） ，但与主观判断“2 = 1，3 &lt; 2”  不冲突；因此给定主观判断“3&gt;1，3=2”时，1&lt;3=2 和1&lt;2=3 都是合法的质量序列，3&lt;1=2 和1&lt;2&lt;3都是非法的质量序列。由于实验已经做完一段时间了，小D 已经忘了一部分主观实验的数据。对每张图片 i，小 D 都最多只记住了某一张质量不比 i 差的另一张图片 Ki。这些小 D 仍然记得的质量判断一共有 M 条（0 &lt;= M &lt;= N），其中第i 条涉及的图片对为(KXi, Xi)，判断要么是KXi   &lt; Xi  ，要么是KXi = Xi，而且所有的Xi互不相同。小D 打算就以这M 条自己还记得的质量判断作为他的所有主观数据。现在，基于这些主观数据，我们希望你帮小 D 求出这 N 张图片一共有多少个不同的合法质量序列。我们规定：如果质量序列中出现“x = y”，那么序列中交换 x和y的位置后仍是同一个序列。因此： 1&lt;2=3=4&lt;5 和1&lt;4=2=3&lt;5 是同一个序列， 1 &lt; 2 = 3 和 1 &lt; 3 = 2 是同一个序列，而1 &lt; 2 &lt; 3 与1 &lt; 2 = 3是不同的序列，1&lt;2&lt;3和2&lt;1&lt;3 是不同的序列。由于合法的图片质量序列可能很多， 所以你需要输出答案对10^9 + 7 取模的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数N,M，分别代表图片总数和小D仍然记得的判断的条数；</p><p>接下来M行，每行一条判断，每条判断形如”x &lt; y”或者”x = y”（不含引号，注意有空格）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行 ，包含一个正整数表示合法质量序列的目对 10^9 + 7取模的结果。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4</p><p>1 &lt; 2</p><p>1 &lt; 3</p><p>2 &lt; 4</p><p>1 = 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】<br></p><p>不同的合法序列共5个，如下所示：</p><p>1 = 5 &lt; 2 &lt; 3 &lt; 4</p><p>1 = 5 &lt; 2 &lt; 4 &lt; 3</p><p>1 = 5 &lt; 2 &lt; 3 = 4</p><p>1 = 5 &lt; 3 &lt; 2 &lt; 4</p><p>1 = 5 &lt; 2 = 3 &lt; 4</p><p><br></p><p>【数据范围】</p><p>N&lt;=100</p>
</div>
</div>