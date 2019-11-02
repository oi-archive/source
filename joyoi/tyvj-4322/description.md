# 

 
 # 题目背景 
<p>翻译自Codeforces原题</p> 

 
 # 题目描述 
<p><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 21px; line-height: 21px; text-align: center;">The&nbsp;Text&nbsp;Splitting</span></p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">&nbsp;&nbsp;&nbsp;&nbsp;You&nbsp;are&nbsp;given&nbsp;the&nbsp;string&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>s</i></span>&nbsp;of&nbsp;length&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>n</i></span>&nbsp;and&nbsp;the&nbsp;numbers&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>p</i>,&thinsp;<i>q</i></span>.&nbsp;Split&nbsp;the&nbsp;string&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>s</i></span>&nbsp;to&nbsp;pieces&nbsp;of&nbsp;length&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>p</i></span>&nbsp;and&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>q</i></span>.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">&nbsp;&nbsp;&nbsp;&nbsp;给出长度为n的字符串s，还有数字q和p。那么把字符串S分割为长度为长度为p和q的部分。</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">For&nbsp;example,&nbsp;the&nbsp;string&nbsp;&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;">Hello</span>&quot;&nbsp;for&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>p</i>&thinsp;=&thinsp;2</span>,&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>q</i>&thinsp;=&thinsp;3</span>&nbsp;can&nbsp;be&nbsp;split&nbsp;to&nbsp;the&nbsp;two&nbsp;strings&nbsp;&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;">Hel</span>&quot;&nbsp;and&nbsp;&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;">lo</span>&quot;&nbsp;or&nbsp;to&nbsp;the&nbsp;two&nbsp;strings&nbsp;&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;">He</span>&quot;&nbsp;and&nbsp;&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;">llo</span>&quot;.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">例如，对于字符串&ldquo;Hello&rdquo;，若<span class="tex-span" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>p</i>&thinsp;=&thinsp;2</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">,&nbsp;</span><span class="tex-span" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>q</i>&thinsp;=&thinsp;3，它就能被分割成</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&quot;</span><span class="tex-font-style-tt" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 15.4px; font-family: 'courier new', monospace;">Hel</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&quot;&nbsp;和&nbsp;&quot;</span><span class="tex-font-style-tt" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 15.4px; font-family: 'courier new', monospace;">lo</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&quot;或者&nbsp;&nbsp;&quot;</span><span class="tex-font-style-tt" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 15.4px; font-family: 'courier new', monospace;">He</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&quot;&nbsp;and&nbsp;&quot;</span><span class="tex-font-style-tt" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 15.4px; font-family: 'courier new', monospace;">llo</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&quot;两部分字符串。</span></p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">&nbsp;</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">&nbsp;</p> 

 
 # 输入格式 
<div class="input-specification" style="margin: 0px; padding: 0px; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 21px;">
<div class="section-title" style="margin: 0px; padding: 0px; font-size: 16.1px; font-weight: bold;">Input</div>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">第一行包含3个数n,p,q&nbsp;<span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">&nbsp;(</span><span class="tex-span" style="color: rgb(34, 34, 34); line-height: 19.6px; font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;">1&thinsp;&le;&thinsp;<i>p</i>,&thinsp;<i>q</i>&thinsp;&le;&thinsp;<i>n</i>&thinsp;&le;&thinsp;100</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">).</span></p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">第二行是包含大写小写字母和数字的字符串s</p>
</div>

<div class="output-specification" style="margin: 0px 0px 1em; padding: 0px; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 21px;">
<div class="section-title" style="margin: 0px; padding: 0px; font-size: 16.1px; font-weight: bold;">Output</div>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">如果不可能将字符串s分割为长度为p和q的子串则输出-1.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">否则在第一行打印出k（k代表的是将字符串分割为多少部分）</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;"><span style="font-size: 1em; line-height: 1.4em;">.</span><span style="font-size: 1em; line-height: 1.4em;">每一个字符串的长度应该为p或者q。分割完成的字符串里面字符顺序不变。</span></p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 1em; line-height: 1.4em;">如果有许多结果，那么打印出他们其中之一。</p>
</div> 

 
 # 输出格式 
<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
5&nbsp;2&nbsp;3
Hello
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
2
He
llo
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
10&nbsp;9&nbsp;5
Codeforces
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
2
Codef
orces
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
6&nbsp;4&nbsp;5
Privet
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
-1
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
8&nbsp;1&nbsp;1
abacabac
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
8
a
b
a
c
a
b
a
c</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
2
He
llo
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
10&nbsp;9&nbsp;5
Codeforces
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
2
Codef
orces
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
6&nbsp;4&nbsp;5
Privet
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
-1
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
8&nbsp;1&nbsp;1
abacabac
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
8
a
b
a
c
a
b
a
c</pre>
</div> 

 
 # 提示 
<p><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">把字符串S只</span><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">分割成p部分或者只分割成q部分是允许的。详见样例2.</span></p>

<p><span style="color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 19.6px;">（我的理解是如果字符串分割不成长度为p的子串和长度为q的子串部分，如果能分割成长度都是p的k个子串或者长度都是q的k个子串也是可以的。）</span></p> 
