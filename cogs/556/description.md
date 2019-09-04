

# 问题描述</b>



# 输入格式



# 输出格式



# 输入样例


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
