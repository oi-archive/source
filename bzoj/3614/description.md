
# Description

<div class="content"><div>在人类的神经系统中，每个信号都可以用?1或+1来表示。这些信号组合起来最后形成 了喜怒哀乐，酸甜苦辣，红黄绿蓝等各种各样的复杂信息。纳米探测科技的突破让生物学家 可以测量大脑中特定区域的完整逻辑功能。然而超大数据的处理一直是令 H 教授头疼的问 题。</div>
<div> 假设一个逻辑单元接受N个信号输入，并产生一个代表某种意义的实数值r。那么总共 可能的情况有2^N种。</div>
<div>通过长时间的累积测量， H 教授可以准确地获得输入信号与r的关系表：</div>
<div> f:{-1,1}N →R  然而进一步研究发现，神经元的运算方式可以被建模为人们熟知的多项式。由于一个输 入</div>
<div>信号值的平方一定为1，所以我们可以用不含幂的2^N项的多项式来唯一表示任何一个逻辑f。 </div>
<div> 例如</div>
<div> x1 = +1; x2 = +1   x1 = +1; x2 = -1  x1 = -1; x2 = +1 x1 = -1; x2 = -1</div>
<div>        0                   1                2                3  </div>
<div>可以写成 f(x1,x2) = 1.5 - 0.5x2 - x1 研究一个逻辑单元的多项式形式对了解大脑工作十分有意义，于是</div>
<div>小 M 决定帮 H 教授 把测量出的逻辑关系表全部转换成多项式的形式。这么简单的工作一定难不倒编程能手</div>
<div>小M 的吧？ </div></div>

# Input

<div class="content"><p>第一行是n (1 ≤ n ≤ 20)，接下来共2^n行，每一行是一组逻辑输入和一个对应值，代表 x1 …xn的符号</p>
<div>
<div>以及对应的r。详见样例。数据保证所有逻辑值的绝对值不超过100，且不包 含超过 2 位小数。保证所有逻</div>
<div>辑的输入串都互不相同。 </div>
</div></div>

# Output

<div class="content"><p>最多2^N行，代表多项式每一项的系数，如果答案为整数，输出整数形式。</p>
<div>
<div>否则输出最简 分数形式。如果系数恰好为 0，则省略整行。</div>
<div>变量和系数用空格隔开，常数项不用加空格。 </div>
<div>顺序按多项式的字典序：</div>
<div>常数项优先；</div>
<div>没有常数项时，最小x下标更小的项优先</div>
<div>当两项含有相同最小下标时，按除掉最小下标x以后，</div>
<div>以同样规则递归比较。</div>
<div> 例： 1,x1,x1x2,x1x2x3,x1x3,x2,x2x3,x3 详见样例。 </div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">#1<br/>
<br/>
2 <br/>
++ 0 <br/>
+- 1 <br/>
-+ 2 <br/>
-- 3  <br/>
<br/>
<br/>
#2<br/>
<br/>
3 <br/>
--- -1.0 <br/>
-++ -1.0 <br/>
+-+ -1.0 <br/>
++- -1.0 <br/>
--+ 1.0 <br/>
-+- 1.0 <br/>
+-- 1.0 <br/>
+++ 1.0  </span></div>

# Sample Output

<div class="content"><span class="sampledata">#1<br/>
<br/>
3/2<br/>
-1 x1 <br/>
-1/2 x2<br/>
<br/>
#2<br/>
<br/>
1 x1x2x3</span></div>

# Hint

<div class="content"><p></p><p> 对于 100%的数据， 1 ≤N≤ 20, |r| ≤ 100, 100r∈ Z. </p><br/>
<div>请注意输入输出的效率。 </div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

