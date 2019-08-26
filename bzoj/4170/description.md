
# Description

<div class="content"><div>&#34;若是万一琪露诺（俗称rhl）进行攻击，什么都好，冷静地回答她的问题来吸引她。对方表现出兴趣的话，那就慢</div>
<div>慢地反问。在她考虑答案的时候，趁机逃吧。就算是很简单的问题，她一定也答不上来。&#34;               </div>
<div> --《上古之魔书》</div>
<div></div>
<div>天空中出现了许多的北极光，这些北极光组成了一个长度为n的正整数数列a[i],远古之魔书上记载到：2个位置的g</div>
<div>raze值为两者位置差与数值差的和：</div>
<div>graze(x,y)=|x-y|+|a[x]-a[y]|。</div>
<div>要想破解天罚，就必须支持2种操作（k都是正整数）：</div>
<div>Modify x k：将第x个数的值修改为k。</div>
<div>Query x k：询问有几个i满足graze(x,i)&lt;=k。</div>
<div>由于从前的天罚被圣王lmc破解了，所以rhl改进了她的法术，询问不仅要考虑当前数列，还要考虑任意历史版本，</div>
<div>即统计任意位置上出现过的任意数值与当前的a[x]的graze值&lt;=k的对数。（某位置多次修改为同样的数值，按多次</div>
<div>统计）</div></div>

# Input

<div class="content"><div>第1行两个整数n,q。分别表示数列长度和操作数。</div>
<div>第2行n个正整数，代表初始数列。</div>
<div>第3~q+2行每行一个操作。</div>
<div>N&lt;=40000, <span style="color: rgb(255, 0, 0);">修改操作数&lt;=60000</span>, 询问操作数&lt;=10000, Max{a[i]}(含修改)&lt;=80000</div></div>

# Output

<div class="content"><p><span style="font-size:10.5pt;font-family:宋体;
mso-ascii-font-family:Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:
Consolas;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:
ZH-CN;mso-bidi-language:AR-SA">对于每次询问操作，输出一个非负整数表示答案</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
2 4 3<br/>
Query 2 2<br/>
Modify 1 3<br/>
Query 2 2<br/>
Modify 1 2<br/>
Query 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

