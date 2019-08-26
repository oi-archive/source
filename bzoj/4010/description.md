
# Description

<div class="content"><p>知名美食家小 A被邀请至ATM 大酒店，为其品评菜肴。 </p>
<div>ATM 酒店为小 A 准备了 N 道菜肴，酒店按照为菜肴预估的质量从高到低给予</div>
<div>1到N的顺序编号，预估质量最高的菜肴编号为1。由于菜肴之间口味搭配的问题，</div>
<div>某些菜肴必须在另一些菜肴之前制作，具体的，一共有 M 条形如“i 号菜肴‘必须’</div>
<div>先于 j 号菜肴制作”的限制，我们将这样的限制简写为&lt;i,j&gt;。现在，酒店希望能求</div>
<div>出一个最优的菜肴的制作顺序，使得小 A能尽量先吃到质量高的菜肴：也就是说，</div>
<div>(1)在满足所有限制的前提下，1 号菜肴“尽量”优先制作；(2)在满足所有限制，1</div>
<div>号菜肴“尽量”优先制作的前提下，2号菜肴“尽量”优先制作；(3)在满足所有限</div>
<div>制，1号和2号菜肴“尽量”优先的前提下，3号菜肴“尽量”优先制作；(4)在满</div>
<div>足所有限制，1 号和 2 号和 3 号菜肴“尽量”优先的前提下，4 号菜肴“尽量”优</div>
<div>先制作；(5)以此类推。 </div>
<div>例1：共4 道菜肴，两条限制&lt;3,1&gt;、&lt;4,1&gt;，那么制作顺序是 3,4,1,2。例2：共</div>
<div>5道菜肴，两条限制&lt;5,2&gt;、 &lt;4,3&gt;，那么制作顺序是 1,5,2,4,3。例1里，首先考虑 1，</div>
<div>因为有限制&lt;3,1&gt;和&lt;4,1&gt;，所以只有制作完 3 和 4 后才能制作 1，而根据(3)，3 号</div>
<div>又应“尽量”比 4 号优先，所以当前可确定前三道菜的制作顺序是 3,4,1；接下来</div>
<div>考虑2，确定最终的制作顺序是 3,4,1,2。例 2里，首先制作 1是不违背限制的；接</div>
<div>下来考虑 2 时有&lt;5,2&gt;的限制，所以接下来先制作 5 再制作 2；接下来考虑 3 时有</div>
<div>&lt;4,3&gt;的限制，所以接下来先制作 4再制作 3，从而最终的顺序是 1,5,2,4,3。 </div>
<div>现在你需要求出这个最优的菜肴制作顺序。无解输出“Impossible!” （不含引号，</div>
<div>首字母大写，其余字母小写） </div></div>

# Input

<div class="content"><p> 第一行是一个正整数D，表示数据组数。 </p>
<div>接下来是D组数据。 </div>
<div>对于每组数据： </div>
<div>第一行两个用空格分开的正整数N和M，分别表示菜肴数目和制作顺序限</div>
<div>制的条目数。 </div>
<div>接下来M行，每行两个正整数x,y，表示“x号菜肴必须先于y号菜肴制作”</div>
<div>的限制。（注意：M条限制中可能存在完全相同的限制） </div></div>

# Output

<div class="content"><p> 输出文件仅包含 D 行，每行 N 个整数，表示最优的菜肴制作顺序，或</p>
<div>者”Impossible!”表示无解（不含引号）。 </div></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
5 4 <br/>
5 4 <br/>
5 3 <br/>
4 2 <br/>
3 2 <br/>
3 3 <br/>
1 2 <br/>
2 3 <br/>
3 1 <br/>
5 2 <br/>
5 2 <br/>
4 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 5 3 4 2 <br/>
Impossible! <br/>
1 5 2 4 3 </span></div>

# Hint

<div class="content"><p></p><p> 【样例解释】 </p><br/>
<div>第二组数据同时要求菜肴1先于菜肴2制作，菜肴2先于菜肴3制作，菜肴3先于</div><br/>
<div>菜肴1制作，而这是无论如何也不可能满足的，从而导致无解。 </div><br/>
<div>100%的数据满足N,M&lt;=100000,D&lt;=3。 </div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

