
# Description

<div class="content"><div>
<div style="margin: 0cm -3pt 0pt 42pt; line-height: 12pt" align="left"><span style="font-size: medium"><span style="color: black">在一个忍者的帮派里，一些忍者们被选中派遣给顾客，然后依据自己的工作</span><span style="color: black">获取报偿。</span><span style="color: black">在这个帮派里，有一名忍者被称之为</span><span style="color: black"> Master</span><span style="color: black">。除了</span><span style="color: black"> Master</span><span style="color: black">以外，每名忍者</span><span style="color: black">都有且仅有一个上级。为保密，同时增强忍者们的领导力，所有与他们工作相关</span><span style="color: black">的指令总是由上级发送给他的直接下属，而不允许通过其他的方式发送。</span><span style="color: black">现在你要招募一批忍者，并把它们派遣给顾客。你需要为每个被派遣的忍者 支付一定的薪水，同时使得支付的薪水总额不超过你的预算。另外，为了发送指令，你需要选择一名忍者作为管理者，要求这个管理者可以向所有被派遣的忍者 发送指令，在发送指令时，任何忍者（不管是否被派遣）都可以作为消息的传递 人。管理者自己可以被派遣，也可以不被派遣。当然，如果管理者没有被排遣，</span><span style="color: black">就不需要支付管理者的薪水。</span><span style="color: black">你的目标是在预算内使顾客的满意度最大。这里定义顾客的满意度为派遣的</span><span style="color: black">忍者总数乘以管理者的领导力水平，其中每个忍者的领导力水平也是一定的。</span><span style="color: black">写一个程序，给定每一个忍者</span><i><span style="color: black"> i</span></i><span style="color: black">的上级</span><i><span style="color: black"> B</span></i><i><span style="color: black">i</span></i><i><span style="color: black">，薪水</span></i><i><span style="color: black">Ci</span></i><i><span style="color: black">，领导力</span></i><i><span style="color: black">L i</span></i><i><span style="color: black">，以及支付给</span></i><span style="color: black">忍者们的薪水总预算</span><i><span style="color: black"> M</span></i><span style="color: black">，输出在预算内满足上述要求时顾客满意度的最大值。</span></span></div>
</div>
<p><span style="font-size: medium"><br clear="all"/>
</span> </p>
<div>
<div style="margin: 0cm -1.5pt 0pt 42pt; line-height: 14.25pt" align="left"><span style="font-size: medium"><span style="color: black">1 </span><span style="color: black"> ≤<i>N</i> ≤ 100,000 <span style="font-size: medium"><span style="color: black">忍者的个数；</span></span></span></span></div>
<div style="margin: 0cm -1.5pt 0pt 42pt; line-height: 14.25pt" align="left"><span style="font-size: medium"><span style="color: black">1 </span><span style="color: black"> ≤<i>M</i> ≤ 1,000,000,000 <span style="font-size: medium"><span style="color: black">薪水总预算；</span></span> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 1pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.5pt 0pt 42pt; line-height: 14.25pt" align="left"><span style="font-size: medium"><span style="color: black">0 </span><span style="color: black"> ≤<i>B</i></span></span><span style="font-size: medium"><i><span style="color: black">i &lt; i  <span style="font-size: medium"><span style="color: black">忍者的上级的编号；</span></span></span></i></span></div>
</div>
<div>
<div style="margin: 0cm -1.5pt 0pt 42pt; line-height: 14.25pt; text-align: left" align="left"><span style="font-size: medium"><span style="color: black">1 </span><span style="color: black"> ≤<i>C</i></span><i><span style="color: black">i ≤ M </span></i><span style="color: black">                    </span><span style="color: black">忍者的薪水；</span></span></div>
<div style="margin: 0cm -1.5pt 0pt 42pt; line-height: 14.25pt; text-align: left" align="left"><span style="font-size: medium"><span style="color: black">1 </span><span style="color: black"> ≤<i>L</i></span><i><span style="color: black">i ≤ 1,000,000,000 </span></i><span style="color: black">            </span><span style="color: black">忍者的领导力水平。</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 5pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
</div>
<p></p></div>

# Input

<div class="content"><div style="margin: 11.75pt -3pt 0pt 42pt; line-height: 14.25pt" align="left"><span style="font-size: medium"><span style="color: black">从标准输入读入数据。</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 1pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -3pt 0pt 42pt; line-height: 13.75pt; text-align: left" align="left"><span style="font-size: medium"><span style="color: black">第一行包含两个整数</span><i><span style="color: black"> N</span></i><span style="color: black">和</span><i><span style="color: black"> M</span></i><span style="color: black">，其中</span><i><span style="color: black"> N</span></i><span style="color: black">表示忍者的个数，</span><i><span style="color: black">M</span></i><span style="color: black">表示薪水的总预</span></span><span style="font-size: medium"><span style="color: black">算。</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 1pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -3pt 0pt 42pt; line-height: 13.75pt; text-align: left" align="left"><span style="font-size: medium"><span style="color: black">接下来</span><i><span style="color: black"> N</span></i><span style="color: black">行描述忍者们的上级、薪水以及领导力。其中的第</span><i><span style="color: black"> i</span></i><span style="color: black"> </span><span style="color: black">行包含三个整</span></span> <span style="font-size: medium"><i><span style="color: black">B</span></i></span><span style="font-size: medium"><i><span style="color: black">i , C i , L i</span></i><i><span style="color: black">分别表示第</span></i><i><span style="color: black">i</span></i><i><span style="color: black">个忍者的上级，薪水以及领导力。</span></i><i><span style="color: black">Master</span></i><i><span style="color: black">满足</span></i><i><span style="color: black">B i = 0</span></i><i><span style="color: black">，</span></i></span><span style="font-size: medium"><span style="color: black">并且每一个忍者的老板的编号一定小于自己的编号</span><span style="color: black"> <i>B</i></span></span><span style="font-size: medium"><i><span style="color: black">i &lt; i</span></i><i><span style="color: black">。</span></i></span></div>
<p><span style="font-size: medium"><br clear="all"/>
</span> </p>
<div></div></div>

# Output

<div class="content"><div>
<div style="margin: 0cm -3pt 0pt 42pt; line-height: 14.25pt" align="left"><span style="font-size: medium"><span style="color: black">输出一个数，表示在预算内顾客的满意度的最大值。</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
5  4<br/>
0  3 3<br/>
1  3 5<br/>
2  2 2<br/>
1  2 4<br/>
2  3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
如果我们选择编号为 1的忍者作为管理者并且派遣第三个和第四个忍者，薪水总和为 4，没有超过总预算                         4。因为派遣了                              2   个忍者并且管理者的领导力为      3，<br/><br/>
用户的满意度为 2      ，是可以得到的用户满意度的最大值。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

