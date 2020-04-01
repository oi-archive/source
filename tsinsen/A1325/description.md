<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont"><b><br/>
</b><br/>
<b> </b></div>
# 问题描述

<div class="pdcont">　　给定N个仅有a~z组成的字符串a<sub>i</sub>,每个字符串都有一个权值v<sub>i</sub>,有M次操作，操作分三种：<br/>
　　Cv x v&#39;:把第x个字符串的权值修改为v&#39;<br/>
　　Cs x a&#39;:把第x个字符串修改成a&#39;<br/>
　　Q:求出当前的最大权字符串集合，使得这个集合中的字符串经过重新排列后满足除最后一个字符串外，前一个字符串是后一个的前缀(两个字符串相同也是前缀关系，也可以一个字符串都不选)<br/>
　　前50%的数据可以接受离线算法，后50%的数据要求在线算法。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个正整数Test表示当前的数据类型。<br/>
　　输入的第二行包含两个正整数N,M表示字符串数和操作数。<br/>
　　以下N行，每行一个字符串a<sub>i</sub><br/>
　　第N+3行包含N个整数v<sub>i</sub><br/>
　　以下M行，为M次操作，操作有三种Cv x v&#39;,Cs x a&#39;,Q,第三种操作如题目描述一样，对于Test=1的修改操作，不用做   任何变化，对于Test=2的修改操作，假设当前最后一次询问操作的答案是ans(如果还没有询问操作，ans=0),那么对于第   一种操作中的v&#39;=min(1000,v&#39;+(ans mod 1000)),对于第二种操作的字符串a&#39;,它的每一位都要加上ans  mod 26(a~z循环)</div>
# 输出格式

<div class="pdcont">　　对于每一次询问输出合法的最大权字符串集合的权值和。</div>
# 样例输入

<div class="pddata">1<br/>
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
Q</div>
# 样例输出

<div class="pddata">4<br/>
6<br/>
9</div>
# 数据规模和约定

<div class="pdcont">　　数据分两种，A类数据可以用<b>离线</b>的方法来完成，B类数据必须使用<b>在线</b>算法。<br/>
　　令len=输入数据中所有出现的字符串总长度<br/>
　　|v|&lt;1001<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">数据类别<br/>
</td><td valign="top" style="border:solid 1.0pt">范围<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td rowspan="10" valign="top" style="border:solid 1.0pt"><br/>
<br/>
<br/>
A<br/>
</td><td valign="top" style="border:solid 1.0pt">N,M≤30,len≤500<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td rowspan="3" valign="top" style="border:solid 1.0pt"><br/>
N,M≤1000,len≤10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td rowspan="6" valign="top" style="border:solid 1.0pt"><br/>
<br/>
N≤50000,M≤10<sup>5</sup>,len≤10<sup>6</sup><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td rowspan="10" valign="top" style="border:solid 1.0pt"><br/>
<br/>
<br/>
B<br/>
</td><td rowspan="10" valign="top" style="border:solid 1.0pt"><br/>
<br/>
<br/>
<br/>
N≤50000,M≤10<sup>5</sup>,len≤10<sup>6</sup><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">13<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">14<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">15<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">16<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">17<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">18<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">19<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">20<br/>
</td></tr></tbody></table></div>

</div>