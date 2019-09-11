# 题目描述


<div>【问题描述】</div>
<div style="text-indent: 24pt">在一个装满财宝的屋子里，有2N个盒子排成一排。除了两个相邻的空盒外，其余的每个盒子里都装有一个金球或者一个银球，总共有N-1个金球和N-1个银球。用图6．3所示为一个N=5时的例子，G表示金球，S表示银球。</div>
<table cellspacing="0" cellpadding="0" border="1" style="border-collapse: collapse; margin-left: 50.15pt">
    <tbody>
        <tr style="height: 18.9pt">
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: windowtext 1pt solid; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">G</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">S</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">S</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">G</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph"> </div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph"> </div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">G</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">S</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">G</div>
            </td>
            <td width="36" valign="top" style="border-bottom: windowtext 1pt solid; border-left: medium none; padding-bottom: 0cm; padding-left: 5.4pt; width: 27.1pt; padding-right: 5.4pt; height: 18.9pt; border-top: windowtext 1pt solid; border-right: windowtext 1pt solid; padding-top: 0cm">
            <div style="text-justify: inter-ideograph">S</div>
            </td>
        </tr>
    </tbody>
</table>
<div style="text-indent: 21pt"> </div>
<div style="text-indent: 24pt">任意两个相邻的非空的盒子里的球可以移动到两个相邻的空盒中，移动不能改变这两个球的排列顺序。写一个程序，用最少的移动次数把所有的金球都移到所有的银球的左边。</div>
<div style="text-indent: 24pt"> </div>
<div>【输入格式】</div>
<div style="text-indent: 24pt">输入文件包含多组数据。第一行为K，表示数据的总数。</div>
<div style="text-indent: 24pt">每组数据的第一行是N(3≤N≤7)，</div>
<div style="text-indent: 24pt">第二行是2N个盒子的初始状态。金球用a表示， 银球用b表示，空盒用空格表示。每两组相邻数据用空行隔开。</div>
<div style="text-indent: 24pt"> </div>
<div>【输出格式】</div>
<div style="text-indent: 24pt">对于每一组数据，若无解则输出一行NO SOLUTION，若有解，输出一组状态来表示移动的序列，每个状态占一行。每行输出到此状态的移动的步数，紧接着是一个空格，然后是此时的状态。初始状态为第0步，每组数据都要先输出初始状态。如有多种最少移动次数的方案，输出“空格靠前靠左”的一种，如下两种方案，需输出第二种。</div>
<div style="text-indent: 24pt">0 bbbb  aaaa<br/>
         1 bbbbaa   aa<br/>
         2    bbaabbaa<br/>
         3 aabbaabb  <br/>
         4 aa  aabbbb</div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt">0 bbbb  aaaa<br/>
         1    bbbbaaaa<br/>
         2 aabbbb  aa<br/>
         3 aa  bbbbaa<br/>
         4 aaaabbbb  </div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt">相邻的两组数据用一个空行隔开。</div>
<div>【输入输出样例】</div>
<div style="text-indent: 24pt">样例输入（<span>balls.in</span>）:</div>
<pre>3
3
abab  

5
abba  abab

6
a  babbababa
</pre>
<div style="text-indent: 24pt"><span style="text-indent: 24pt">样例输出（</span><span style="text-indent: 24pt">balls.out）：</span></div>
<pre>NO SOLUTION

0 abba  abab
1 abbabaa  b
2 a  abaabbb
3 aaaab  bbb

0 a  babbababa
1 aabbabb  aba
2 aabbabbbaa
3 aa  abbbaabb
4 aaaaabbb  bb  
</pre>
