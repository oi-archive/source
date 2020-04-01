
# Description

<div class="content"><div>给定N个仅有a~z组成的字符串ai,每个字符串都有一个权值vi,有M次操作，操作分三种：</div>
<div>Cv x v&#39;:把第x个字符串的权值修改为v&#39;</div>
<div>Cs x a&#39;:把第x个字符串修改成a&#39;</div>
<div>Q:求出当前的最大权字符串集合，使得这个集合中的字符串经过重新排列后满足除最后一个字符串外，前一个字符</div>
<div>串是后一个的前缀(两个字符串相同也是前缀关系，也可以一个字符串都不选)</div>
<div>前50%的数据可以接受离线算法，后50%的数据要求在线算法。</div></div>

# Input

<div class="content"><div>
<div>输入的第一行包含一个正整数Test表示当前的数据类型。</div>
<div>输入的第二行包含两个正整数N,M表示字符串数和操作数。</div>
<div>以下N行，每行一个字符串ai</div>
<div>第N+3行包含N个整数vi</div>
<div>以下M行，为M次操作，操作有三种Cv x v&#39;,Cs x a&#39;,Q,第三种操作如题目描述一样，对于Test=1的修改操作，不用</div>
<div>做 任何变化，对于Test=2的修改操作，假设当前最后一次询问操作的答案是ans(如果还没有询问操作，ans=0),那</div>
<div>么对于第 一种操作中的v&#39;=min(1000,v&#39;+(ans mod 1000)),对于第二种操作的字符串a&#39;,它的每一位都要加上ans m</div>
<div>od 26(a~z循环)</div>
<div>数据分两种，A类数据可以用离线的方法来完成，B类数据必须使用在线算法。</div>
<div>令len=输入数据中所有出现的字符串总长度</div>
<div>数据分两种，A类数据可以用离线的方法来完成，B类数据必须使用在线算法。</div>
<div>N&lt;=50000,M&lt;=10^5,Len&lt;=10^6</div>
<div></div>
</div>
<div>
<div></div>
</div></div>

# Output

<div class="content"><p>对于每一次询问输出合法的最大权字符串集合的权值和</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 5<br/>
aba<br/>
ab<br/>
babb<br/>
abaa<br/>
abab<br/>
-2 1 4 2 3<br/>
Q<br/>
Cv 1 2<br/>
Q<br/>
Cs 3 abaab<br/>
Q</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
6<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

