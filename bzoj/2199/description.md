
# Description

<div class="content">由于对Farmer John的领导感到极其不悦，奶牛们退出了农场，组建了奶牛议会。议会以“每头牛
都可以获得自己想要的”为原则，建立了下面的投票系统：

   M只到场的奶牛 (1 &lt;= M &lt;= 4000) 会给N个议案投票(1 &lt;= N &lt;= 1,000) 。每只
   奶牛会对恰好两个议案 B_i and C_i (1 &lt;= B_i &lt;= N; 1 &lt;= C_i &lt;= N)投
   出“是”或“否”（输入文件中的&#39;Y&#39;和&#39;N&#39;）。他们的投票结果分别为VB_i 
   (VB_i in {&#39;Y&#39;, &#39;N&#39;}) and VC_i (VC_i in {&#39;Y&#39;, &#39;N&#39;})。

   最后，议案会以如下的方式决定：每只奶牛投出的两票中至少有一票和最终结果相符合。
   例如Bessie给议案1投了赞成&#39;Y&#39;，给议案2投了反对&#39;N&#39;，那么在任何合法的议案通过
   方案中，必须满足议案1必须是&#39;Y&#39;或者议案2必须是&#39;N&#39;（或者同时满足）。

给出每只奶牛的投票，你的工作是确定哪些议案可以通过，哪些不能。如果不存在这样一个方案，
输出&#34;IMPOSSIBLE&#34;。如果至少有一个解，输出：

    Y  如果在每个解中，这个议案都必须通过
    N  如果在每个解中，这个议案都必须驳回
    ?  如果有的解这个议案可以通过，有的解中这个议案会被驳回

考虑如下的投票集合：

       - - - - - 议案 - - - - -
         1        2        3
奶牛 1   YES      NO
奶牛 2   NO       NO
奶牛 3   YES               YES
奶牛 4   YES      YES

下面是两个可能的解：
    * 议案 1 通过（满足奶牛1，3，4）
    * 议案 2 驳回（满足奶牛2）
    * 议案 3 可以通过也可以驳回（这就是有两个解的原因）

事实上，上面的问题也只有两个解。所以，输出的答案如下：

YN?

</div>

# Input

<div class="content">* 第1行：两个空格隔开的整数：N和M

* 第2到M+1行：第i+1行描述第i只奶牛的投票方案：B_i, VB_i, C_i, VC_i

</div>

# Output

<div class="content">
* 第1行：一个含有N个字符的串，第i个字符要么是&#39;Y&#39;（第i个议案必须通过），或者是&#39;N&#39;
（第i个议案必须驳回），或者是&#39;?&#39;。
如果无解，输出&#34;IMPOSSIBLE&#34;。
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 4<br/>
1 Y 2 N<br/>
1 N 2 N<br/>
1 Y 3 Y<br/>
1 Y 2 Y<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YN?<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

