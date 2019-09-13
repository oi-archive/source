# 题目描述


<p> </p>
<p><span style="font-family: 宋体"><b>【问题描述</b>】 </span></p>
<div>    CSV（逗号分隔值）这种文件格式可以在不同的应用程序间做数据交换用，因为曾被用于微软的电子表格（Excel），并逐渐成为一种行业伪标准，甚至也被应用于其它非微软平台上。<br/>
   本题中的CSV文件格式是这样定义的：<br/>
   1、一个CSV文件包含0行或多行记录，每一个记录包含0个或多个字段（域）。<br/>
   2、每一个记录都以一个换行符结尾（ASCII/LF=0X0A）。<br/>
   当然，一个字段中可能包含自带的换行符（参见下面），所以一个记录也可能跨越多行。<br/>
   3、字段之间以逗号（英文半角）分隔。<br/>
   例：Jonh,Doe,120 any st.,&#34;Anytown, WW&#34;,08123<br/>
   4、如果一个字段未用双引号引起来，那么该字段开头或结尾的空格将被忽略。<br/>
   比如，John, Doe,…就可以变成&#34;John&#34;和&#34;Doe&#34;，等等……空格可以是空格键或者Tab键。<br/>
   5、字段中若有自带的逗号，则必须用双引号引起来。<br/>
   在上例中，&#34;Anytown, WW&#34;必须加双引号，因为它中间有一个自带的逗号。<br/>
   6、字段中若有自带双引号，则该字段必须整体被双引号括起来，同时对于原来自带的双引号，每一个双引号都要被替换成两个连续的双引号。<br/>
   比如，John &#34;Da Man&#34; Doe将被转换成&#34;John &#34;&#34;Da Man&#34;&#34; Doe&#34;,120 any st.,… <br/>
   7、如果一个字段中包含自带的换行，则该字段必须完整地用双引号括起来。<br/>
   比如，<br/>
   字段1：Conference room 1<br/>
   字段2：John,<br/>
   Please bring the M.Mathers file for review<br/>
   -J.L.<br/>
<br/>
   字段3：10/18/2002<br/>
   …<br/>
   该记录可以转换为：<br/>
   Conference room 1,&#34;John,<br/>
   Please bring the M.Mathers file for review<br/>
   -J.L.<br/>
   &#34;,10/18/2002,…<br/>
   注意这是符合CSV格式的单个记录，尽管它跨越了多行，因为字段中有自带的换行。<br/>
   8、字段中若开头或结尾要用空格，则该字段需加双引号。<br/>
   如：为了保持开头与结尾的空格，John, Doe ,…要被写为John,&#34; Doe &#34;,…<br/>
   9、字段可以总是用双引号括起来，而双引号也总是可以被去掉。<br/>
   你的任务是写一个程序做为CSV文件解析程序，对输入的CSV格式的文件做解析。<br/>
 </div>
<div>【输入格式】</div>
<div><span>   你的程序需要读入输入文件，并参考CSV文件格式对输入内容加以解析，输入以EOF结束。<br/>
   每一个字段的字符数均不超过50，输入文件中最多有500个字段。</span></div>
<div>【输出格式】</div>
<p>   如果输入文件不是一个符合CSV格式的文件，输出“Wrong Format”，否则你需要输出所有的字段，每一个字段输出完毕请加上一个换行（‘ ’），例如，假定输入文件如下:<br/>
   field11,field12,...,field1n<br/>
   field21,field22,...,field2n<br/>
   …<br/>
   fieldm1,fieldm2,...,fieldmn<br/>
   则输出必须为：<br/>
   field11<br/>
   field12<br/>
   ...<br/>
   field1n<br/>
   field21<br/>
   field22<br/>
   ...<br/>
   field2n<br/>
   …<br/>
   fieldm1<br/>
   fieldm2<br/>
   ...<br/>
   fieldmn<br/>
   注意字段中可能会有自带的换行符，所以在输出文件中一个字段可能会占若干行（具体细节你可以参考下面的样例3）。</p>
<div>【输入样例】</div>
<div>输入文件名：<span>parser1.in</span></div>
<div>field11,field12<br/>
field21,field22</div>
<div>输出文件名：<span>parser1.out</span></div>
<div><span>field11<br/>
field12<br/>
field21<br/>
field22</span></div>
<div>输入文件名：<span>parser2.in</span></div>
<div>John, Doe , &#34;Anytown, WW&#34; , &#34;John &#34;&#34;Da Mon&#34;&#34; Von&#34;</div>
<div>输出文件名：<span>parser2.out</span></div>
<div><span>John<br/>
Doe<br/>
Anytown, WW<br/>
John &#34;Da Mon&#34; Von</span></div>
<div>输入文件名：<span>parser3.in</span></div>
<div>Conference room 1,&#34;John,<br/>
Please bring the M.Mathers file for review<br/>
-J.L.<br/>
&#34;,3/20/2006</div>
<div>输出文件名：<span>parser3.out</span></div>
<div><span>Conference room 1<br/>
John,<br/>
Please bring the M.Mathers file for review<br/>
-J.L.</span></div>
<div>3/20/2006<br/>
注意：<br/>
在这个样例中，输入文件中的第二个字段被双引号括起来了，于是在中间可以有换行符，也因此该字段在输出文件中看起来跟在输入文件中一样，不要忘了在该字段输出完毕、第三个字段输出之前加一个换行。</div>
<div>输入文件名：<span>parser4.in</span></div>
<div>John, &#34;Wrong field&#34; sample&#34;, Bob</div>
<div>输出文件名：<span>parser4.out</span></div>
<div><span>Wrong Format</span></div>
