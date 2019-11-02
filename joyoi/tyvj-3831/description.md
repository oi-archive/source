# 

 
 # 题目背景 
<p>&nbsp;</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dC上一次秒了BZOJ上所有的数论题，今天他又把其他所有题都秒了，然后感觉萌萌哒，于是决定去颓。</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dC颓的游戏非常高端，dC有一个黑箱，黑箱内有N个元素，用0,1,2&hellip;N-1表示，dC会从中摸出若干元素，记下摸出的元素后，放回，然后再摸出若干元素，设两次都被摸出的元素集合为M&nbsp;，每个M都对应着一个收益（<strong>并不具备单调性等任何性质</strong>）。现在，已知dC摸出若干元素的所有情况（一共2^N种情况，可以什么也不摸）的概率p和M的所有情况（一共2^N种情况）的收益q。请帮dC求期望收益。<strong>为了避免精度问题，本题中的</strong><strong>p</strong><strong>、q</strong><strong>都是在mod&nbsp;10^9+7</strong><strong>的意义下的（其实就是随便一个数辣，请不要吐槽），因此本题中的所有运算都请在mod&nbsp;10^9&nbsp;+&nbsp;7</strong><strong>下完成（您要是不想打高精度分数类就不要吐槽为什么用整数，QwQ~~</strong><strong>）。</strong></p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一行一个整数P，意义请参考备注</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二行有16个正整数，意义请参考备注</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一行一个正整数N，表示黑箱中元素的个数。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一个整数，表示dC的期望收益（mod&nbsp;10^9&nbsp;+&nbsp;7）</p> 

 
 # 提示 
<p>数据范围：</p>

<p>30&nbsp;%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;&lt;=&nbsp;14</p>

<p>60%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;&lt;=&nbsp;16</p>

<p>100%&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N&nbsp;&lt;=&nbsp;20;&nbsp;&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;P&nbsp;&lt;=&nbsp;1000000009;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&lt;=&nbsp;X[i]&nbsp;&lt;&nbsp;1000000009</p>

<p>&nbsp;</p>

<p><strong>样例的&ldquo;</strong><strong>实际输入&rdquo;</strong><strong>：（看不懂的请把下面那一坨看完）</strong></p>

<p>2</p>

<p>131&nbsp;131</p>

<p>105&nbsp;137</p>

<p>139&nbsp;175</p>

<p>134&nbsp;113</p>

<p>&nbsp;</p>

<p>&ldquo;实际输入&ldquo;中左边的数代表概率，右边的数代表收益<strong>（具体意义请看下面的代码实现）</strong>。</p>

<p>&nbsp;</p>

<p>样例解释：</p>

<p>一共有2个元素，（接下来的说明以概率为例，收益类似）在一次摸取中，一个也没摸出的概率为131，只摸出0号元素的概率为105，只摸出1号元素的概率为139，摸出0号和1号元素的概率为134。</p>

<p>&nbsp;</p>

<p>关于P和那奇怪的16个整数的解释：</p>

<p>由于数据比较大，tyvj无法上传，因此概率p和收益q需要您自己生成。生成规则如下：</p>

<p>&nbsp;</p>

<p>（下面的代码中，P就是读入的第一个整数（Pascal代码中PP为读入的第一个整数），mod是个常数（Pascal中此常量为M），等于10^9&nbsp;+&nbsp;7）</p>

<p>生成规则窝就不详细解释辣，相信学过C/C++/pascal的同学一定能看懂！！！</p>

<ol>
	<li>C/C++版（伪代码）</li>
</ol>

<p>这是一个随机函数：</p>

<p align="left">int&nbsp;ran<strong>()</strong></p>

<p align="left"><strong>{</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;static&nbsp;int&nbsp;x&nbsp;<strong>=</strong>&nbsp;2<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;<strong>+=</strong>&nbsp;<strong>(</strong>x&nbsp;<strong>&lt;&lt;</strong>&nbsp;2<strong>)</strong>&nbsp;<strong>+</strong>&nbsp;123<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;<strong>&amp;=</strong>&nbsp;0x7fffffff<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;<strong>%=</strong>&nbsp;1000777<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>return</strong>&nbsp;x&nbsp;<strong>&amp;</strong>&nbsp;15<strong>;</strong></p>

<p align="left"><strong>}</strong></p>

<p>这也是一个随机函数：</p>

<p align="left">inline&nbsp;int&nbsp;getNext<strong>()</strong></p>

<p align="left"><strong>{</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;int&nbsp;ans&nbsp;<strong>=</strong>&nbsp;0<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong><strong>(</strong>int&nbsp;i&nbsp;<strong>=</strong>&nbsp;0<strong>;</strong>i&nbsp;<strong>&lt;</strong>&nbsp;16<strong>;</strong>i&nbsp;<strong>++)</strong>&nbsp;&nbsp;&nbsp;ans&nbsp;<strong>=</strong>&nbsp;<strong>(</strong>LL<strong>(</strong>ans<strong>)</strong>&nbsp;<strong>+</strong>&nbsp;X<strong>[</strong>ran<strong>()])</strong>&nbsp;<strong>%</strong>&nbsp;P<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>return</strong>&nbsp;ans&nbsp;<strong>%</strong>&nbsp;mod<strong>;</strong></p>

<p align="left"><strong>}</strong></p>

<p>&nbsp;</p>

<p>这是一个&ldquo;读入&rdquo;函数：</p>

<p align="left">inline&nbsp;void&nbsp;RD<strong>(</strong>int&nbsp;<strong>&amp;</strong>p<strong>,</strong>int&nbsp;<strong>&amp;</strong>q<strong>)</strong>&nbsp;&nbsp;&nbsp;<strong>{</strong>&nbsp;p&nbsp;<strong>=</strong>&nbsp;getNext<strong>(),</strong>q&nbsp;<strong>=</strong>&nbsp;getNext<strong>();</strong>&nbsp;<strong>}</strong></p>

<p>&nbsp;</p>

<p>这是一段&ldquo;AC&rdquo;代码：</p>

<p align="left">int&nbsp;main<strong>()</strong></p>

<p align="left"><strong>{</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;input<strong>(</strong>P<strong>);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong><strong>(</strong>int&nbsp;i&nbsp;<strong>=</strong>&nbsp;0<strong>;</strong>i&nbsp;<strong>&lt;</strong>&nbsp;16<strong>;</strong>i&nbsp;<strong>++)</strong>&nbsp;&nbsp;input<strong>(</strong>X<strong>[</strong>i<strong>]);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>这里的</strong><strong>X[]</strong><strong>就存储那</strong><strong>16</strong><strong>个奇怪的整数</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;input<strong>(</strong>n<strong>);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong><strong>(</strong>int&nbsp;i&nbsp;<strong>=</strong>&nbsp;0<strong>;</strong>i&nbsp;<strong>&lt;</strong>&nbsp;<strong>(</strong>1&nbsp;<strong>&lt;&lt;</strong>&nbsp;n<strong>);</strong>i&nbsp;<strong>++)</strong>&nbsp;&nbsp;&nbsp;&nbsp;RD<strong>(</strong>p<strong>[</strong>i<strong>],</strong>q<strong>[</strong>i<strong>]);&nbsp;//&nbsp;</strong><strong>这里的</strong><strong>RD()</strong><strong>函数就是上面的那个</strong><strong>&ldquo;</strong><strong>读入</strong><strong>&rdquo;</strong><strong>函数，一共需要&ldquo;读入&rdquo;</strong><strong>2^n</strong><strong>个，</strong><strong>i</strong><strong>表示一个集合，</strong><strong>i</strong><strong>的二进制位的第</strong><strong>k</strong><strong>位表示有没有编号为</strong><strong>k</strong><strong>的元素，例如：</strong><strong>p[3]</strong><strong>表示选择编号为</strong><strong>0</strong><strong>和</strong><strong>1</strong><strong>的元素的概率，</strong><strong>q[2]</strong><strong>表示两次选择的交集只有</strong><strong>1</strong><strong>号元素时</strong>&nbsp;<strong>的收益。</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;///&nbsp;...</p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;///&nbsp;...</p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;///&nbsp;...</p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;output<strong>(</strong>ans&nbsp;<strong>%</strong>&nbsp;mod<strong>);&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>输出的答案需要</strong><strong>mod&nbsp;(10^9&nbsp;+&nbsp;7)</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>return</strong>&nbsp;0<strong>;</strong></p>

<p align="left"><strong>}</strong></p>

<p>&nbsp;</p>

<ol>
	<li value="2">Pascal版（<strong>伪代码</strong>，窝实在不会写Pascal，如果写错了，勿喷）</li>
</ol>

<p>这是几个全局变量：</p>

<p align="left"><strong>var</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;PP<strong>:</strong>&nbsp;longint<strong>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>读入的第一个整数</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;X<strong>:</strong><strong>array</strong><strong>[</strong>0<strong>..</strong>16<strong>]</strong>&nbsp;<strong>of</strong>&nbsp;longint<strong>;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>那</strong><strong>16</strong><strong>个奇怪的整数</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;xx&nbsp;<strong>:</strong>&nbsp;longint<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;M&nbsp;<strong>:</strong>&nbsp;longint<strong>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>恒等于</strong><strong>10^9&nbsp;+&nbsp;7</strong><strong>（不要吐槽我为什么不用</strong><strong>const</strong><strong>）</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;n&nbsp;<strong>:</strong>&nbsp;longint<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;p<strong>:</strong><strong>array</strong>&nbsp;<strong>[</strong>0<strong>..</strong>1048678<strong>]</strong>&nbsp;<strong>of</strong>&nbsp;longint<strong>;&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>概率</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;q<strong>:</strong><strong>array</strong>&nbsp;<strong>[</strong>0<strong>..</strong>1048678<strong>]</strong>&nbsp;<strong>of</strong>&nbsp;longint<strong>;&nbsp;&nbsp;&nbsp;&nbsp;//&nbsp;</strong><strong>收益</strong></p>

<p>&nbsp;</p>

<p>这是一个随机函数：</p>

<p align="left"><strong>function</strong>&nbsp;ran<strong>()</strong>&nbsp;<strong>:</strong>&nbsp;longint<strong>;</strong></p>

<p align="left"><strong>begin</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;xx<strong>:=</strong>&nbsp;xx&nbsp;<strong>+</strong>&nbsp;<strong>(</strong>xx&nbsp;<strong>shl</strong>&nbsp;2<strong>)</strong>&nbsp;<strong>+</strong>&nbsp;123<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;xx<strong>:=</strong>&nbsp;xx&nbsp;<strong>and</strong>&nbsp;2147483647<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;xx<strong>:=</strong>&nbsp;xx&nbsp;<strong>mod</strong>&nbsp;PP<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;ran<strong>:=</strong>&nbsp;xx&nbsp;<strong>and</strong>&nbsp;15<strong>;</strong></p>

<p align="left"><strong>end</strong><strong>;</strong></p>

<p align="left">&nbsp;</p>

<p>这也是一个随机函数：</p>

<p align="left"><strong>function</strong>&nbsp;getNext<strong>()</strong>&nbsp;<strong>:</strong>longint<strong>;</strong></p>

<p align="left"><strong>var</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;ans&nbsp;<strong>:</strong>&nbsp;longint<strong>;</strong></p>

<p align="left"><strong>begin</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;ans<strong>:=</strong>&nbsp;0<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong>&nbsp;i<strong>:=</strong>&nbsp;0&nbsp;<strong>to</strong>&nbsp;15&nbsp;<strong>do</strong>&nbsp;ans&nbsp;<strong>:=</strong>&nbsp;<strong>(</strong>ans&nbsp;<strong>+</strong>&nbsp;X<strong>[</strong>ran<strong>()])</strong>&nbsp;<strong>mod</strong>&nbsp;PP<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;getNext&nbsp;<strong>:=</strong>&nbsp;ans&nbsp;<strong>mod</strong>&nbsp;M<strong>;</strong></p>

<p align="left"><strong>end</strong><strong>;</strong></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>这是一段&ldquo;AC&rdquo;代码：</p>

<p align="left"><strong>begin</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;xx<strong>:=</strong>&nbsp;2<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M<strong>:=</strong>&nbsp;1000000007<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ans<strong>:=</strong>&nbsp;0<strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;readln<strong>(</strong>PP<strong>);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong>&nbsp;i<strong>:=</strong>&nbsp;0&nbsp;<strong>to</strong>&nbsp;15&nbsp;<strong>do</strong>&nbsp;read<strong>(</strong>X<strong>[</strong>i<strong>]);&nbsp;//&nbsp;</strong><strong>这里的</strong><strong>X[]</strong><strong>就存储那</strong><strong>16</strong><strong>个奇怪的整数</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;readln<strong>(</strong>n<strong>);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tot&nbsp;<strong>:=</strong>&nbsp;<strong>(</strong>1&nbsp;<strong>shl</strong>&nbsp;n<strong>);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>for</strong>&nbsp;i&nbsp;<strong>:=</strong>&nbsp;0&nbsp;<strong>to</strong>&nbsp;<strong>(</strong>tot&nbsp;<strong>-</strong>&nbsp;1<strong>)</strong>&nbsp;<strong>do</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>begin</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>一共需要&ldquo;读入&rdquo;</strong><strong>2^n</strong><strong>个，</strong><strong>i</strong><strong>表示一个集合，</strong><strong>i</strong><strong>的二进制位的第</strong><strong>k</strong><strong>位表示有没有编号为</strong><strong>k</strong><strong>的元素，例如：</strong><strong>p[3]</strong><strong>表示选择编号为</strong><strong>0</strong><strong>和</strong><strong>1</strong><strong>的元素的概率，</strong><strong>q[2]</strong><strong>表示两次选择的交集只有</strong><strong>1</strong><strong>号元素时</strong>&nbsp;<strong>的收益。</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p<strong>[</strong>i<strong>]:=</strong>&nbsp;getNext<strong>();</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q<strong>[</strong>i<strong>]:=</strong>&nbsp;getNext<strong>();</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;writeln<strong>(</strong>p<strong>[</strong>i<strong>],</strong>q<strong>[</strong>i<strong>]);</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>end</strong><strong>;</strong></p>

<p align="left">&nbsp;&nbsp;&nbsp;</p>

<p align="left">&nbsp;&nbsp;&nbsp;</p>

<p align="left">&nbsp;&nbsp;&nbsp;</p>

<p align="left">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;writeln<strong>(</strong>ans&nbsp;<strong>mod</strong>&nbsp;M<strong>);</strong></p>

<p align="left"><strong>end</strong><strong>.</strong></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1000000009
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16
2</td><td>36340605</td></tr></table>
