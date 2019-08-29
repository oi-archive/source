<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　组合子逻辑是Moses Schönfinkel和Haskell Curry发明的一种符号系统，用于消除数理逻辑中对于变量的需要。本题考察一种与真实世界的组合子演算略有差别的组合子系统。<br/>
　　一个组合子项是下列形式之一：<br/>
　　P<br/>
　　(E1 E2)<br/>
　　其中 P 表示一个基本函数，E1 以及 E2 表示一个组合子项(可以相同)。不满足以上形式的表达式均非组合子项。<br/>
　　我们将一个组合子项 E 的参数个数 np(E)  如下：<br/>
　　np(P)=基本函数P的参数个数；<br/>
　　np((E1 E2))=np(E1)-1。<br/>
　　本题中，我们用一个正整数同时表示一个基本函数，以及该基本函数的参数个数。<br/>
　　对于一个组合子项 E ，如果它和它包含的所有组合子项的参数个数np均为正整数，那么我们称这个 E 为范式。<br/>
　　我们经常将组合子项简化表示：如果一个组合子项E含有连续子序列 (...((E1 E2) E3) … En)  (其中n≥3 )，其中 Ek 表示组合子项（可以是简化表示的），那么将该部分替换为 (E1 E2 E3 … En)  ，其他部分不变，得到表达式E的一个简化表示。一个组合子项可以被简化表示多次。<br/>
　　给定一个基本函数序列，问至少需要添加多少对括号，才能使得该表达式成为一个范式的简化表示（即满足范式的性质）；如果无论怎样添加括号，均不能得到范式的简化表示，输出 -1 。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个正整数 T ，表示有 T 次询问。<br/>
　　接下来 2T 行。<br/>
　　第 2k 行有一个一个整数 n_k，表示第 k 次询问的序列中基本函数的个数。<br/>
　　第 2k+1 行有 n_k  个正整数，其中第 i 个整数表示序列中第 i 个基本函数。</div>
# 输出格式

<div class="pdcont">　　输出 T 行，每行一个整数，表示对应询问的输出结果。</div>
# 样例输入

<div class="pddata">2<br/>
5<br/>
3 2 1 3 2<br/>
5<br/>
1 1 1 1 1</div>
# 样例输出

<div class="pddata">3<br/>
-1</div>
# 样例说明

<div class="pdcont">　　第一次询问：一个最优方案是(3 (2 1) (3 2))。可以证明不存在添加括号对数更少的方案。<br/>
　　第二次询问：容易证明不存在合法方案。</div>
# 数据规模和约定

<div class="pdcont">　　令 TN 表示输入中所有 n_k  的和。<br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt">规模<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">T≤30,n_k≤3<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">T≤30,n_k≤15<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤100<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤500<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤2000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤5000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤5000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤100000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤200000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">TN≤200000<br/>
</td></tr></tbody></table></div>

</div>