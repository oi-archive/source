# 题面



<pre class="pddata"><font face="DejaVu Sans, monospace">问题描述</font>
<font face="WenQuanYi Micro Hei">Byteland</font><font face="DejaVu Sans, monospace">生物研究中心（</font><font face="WenQuanYi Micro Hei">BIBR</font><font face="DejaVu Sans, monospace">）正在调查两种细菌的性质，这两种细菌分别被称为</font><font face="WenQuanYi Micro Hei">0</font><font face="DejaVu Sans, monospace">和</font><font face="WenQuanYi Micro Hei">1.</font><font face="DejaVu Sans, monospace">即便是在显微镜下，也很难分辨这两种细菌。实际上，科学家们能分辨它们的唯一途径是通过一种叫做</font><font face="WenQuanYi Micro Hei">Formurosa</font><font face="DejaVu Sans, monospace">的植物。</font>
<font face="DejaVu Sans, monospace">如果科学家们把细菌样本分别放在</font><font face="WenQuanYi Micro Hei">Formurosa</font><font face="DejaVu Sans, monospace">的每一片叶子上，那么这样就会激活一个复杂的反应。在这个反应中，</font><font face="WenQuanYi Micro Hei">Formurosa</font><font face="DejaVu Sans, monospace">的颜色会根据一个细菌种类的逻辑运算公式而变化，这个算式可能非常复杂。其中包含常数，以及</font><font face="WenQuanYi Micro Hei">|(or)</font><font face="DejaVu Sans, monospace">、</font><font face="WenQuanYi Micro Hei">&amp;(and)</font><font face="DejaVu Sans, monospace">、</font><font face="WenQuanYi Micro Hei">^(xor)</font><font face="DejaVu Sans, monospace">三种运算符。若运算结果是</font><font face="WenQuanYi Micro Hei">0</font><font face="DejaVu Sans, monospace">，则植株变红。否则，它将变蓝。</font>
<font face="DejaVu Sans, monospace">举例来说，如果</font><font face="WenQuanYi Micro Hei">Formurosa</font><font face="DejaVu Sans, monospace">的反应是以下算式决定的：</font><font face="WenQuanYi Micro Hei">(((?^?)|?)&amp;(1^?))</font><font face="DejaVu Sans, monospace">。（“</font><font face="WenQuanYi Micro Hei">?”</font><font face="DejaVu Sans, monospace">表示叶子，共四片叶子）当我们把</font><font face="WenQuanYi Micro Hei">0</font><font face="DejaVu Sans, monospace">，</font><font face="WenQuanYi Micro Hei">1</font><font face="DejaVu Sans, monospace">，</font><font face="WenQuanYi Micro Hei">0</font><font face="DejaVu Sans, monospace">，</font><font face="WenQuanYi Micro Hei">0</font><font face="DejaVu Sans, monospace">分别放在相应的叶子上，那么算式的结果是</font><font face="WenQuanYi Micro Hei">(((0^1)|0)&amp;(1^0)) = 1. </font><font face="DejaVu Sans, monospace">于是植株变蓝。</font>
<font face="DejaVu Sans, monospace">科学家们共有</font><font face="WenQuanYi Micro Hei">n</font><font face="DejaVu Sans, monospace">群细菌。他们不知道细菌的种类，只知道所有的细菌不可能种类全都相同。科学家们希望不断地用</font><font face="WenQuanYi Micro Hei">Formurosa</font><font face="DejaVu Sans, monospace">检验，从而确定细菌的种类。在每一次检验时，每一片叶子上只能放置恰好一个样品，不过可以把同一群细菌放在多个叶子上——甚至可以用同一群细菌放满整棵植株！</font>
<font face="DejaVu Sans, monospace">不论细菌的种类（假设所有细菌种类不全相同），科学家们是否总是能确定每一群细菌的种类呢？</font>
<font face="DejaVu Sans, monospace">输入</font>
<font face="DejaVu Sans, monospace">第一行有一个整数</font><font face="WenQuanYi Micro Hei">n</font><font face="DejaVu Sans, monospace">，代表细菌有</font><font face="WenQuanYi Micro Hei">n</font><font face="DejaVu Sans, monospace">群。</font>
<font face="DejaVu Sans, monospace">第二行是一个描述反应的算式。第二行只包含以下字符：“</font><font face="WenQuanYi Micro Hei">0”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">1”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">?”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">|”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">&amp;”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">^”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">(”</font><font face="DejaVu Sans, monospace">，“</font><font face="WenQuanYi Micro Hei">)”</font><font face="DejaVu Sans, monospace">。并且遵从以下语法：</font><font face="WenQuanYi Micro Hei">s → 0|1|?|(s|s)|(s&amp;s)|(s^s)</font>
<font face="DejaVu Sans, monospace">输出</font>
<font face="DejaVu Sans, monospace">如果科学家们总是能确定每一群细菌的种类，输出“</font><font face="WenQuanYi Micro Hei">YES”</font><font face="DejaVu Sans, monospace">（不包含引号）。</font>
<font face="DejaVu Sans, monospace">否则，输出“</font><font face="WenQuanYi Micro Hei">NO”</font><font face="DejaVu Sans, monospace">（不包含引号）。</font>
<font face="DejaVu Sans, monospace">数据规模与约定</font>
<font face="WenQuanYi Micro Hei">2 &lt;= n &lt;= 10^6</font><font face="DejaVu Sans, monospace">。</font>
<font face="DejaVu Sans, monospace">算式不超过</font><font face="WenQuanYi Micro Hei">10^6</font><font face="DejaVu Sans, monospace">个字符。</font>
<font face="DejaVu Sans, monospace">样例输入</font>
<font face="WenQuanYi Micro Hei">2</font>
<font face="WenQuanYi Micro Hei">(?^?)</font>
<font face="DejaVu Sans, monospace">样例输出</font>
<font face="WenQuanYi Micro Hei">NO</font>
<font face="DejaVu Sans, monospace">样例输入</font>
<font face="WenQuanYi Micro Hei">10</font>
<font face="WenQuanYi Micro Hei">?</font>
<font face="DejaVu Sans, monospace">样例输出</font>
<font face="WenQuanYi Micro Hei">YES</font>
<font face="DejaVu Sans, monospace">样例输入</font>
<font face="WenQuanYi Micro Hei">2</font>
<font face="WenQuanYi Micro Hei">((?^?)&amp;?)</font>
<font face="DejaVu Sans, monospace">样例输出</font>
<font face="WenQuanYi Micro Hei">YES</font>
</pre>




