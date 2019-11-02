# 

 
 # 题目背景 
<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Codeforces&nbsp;上面翻译的题</p> 

 
 # 题目描述 
<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="line-height: 1.4em;">Limak&nbsp;is&nbsp;a&nbsp;little&nbsp;polar&nbsp;bear.&nbsp;He&nbsp;enjoyed&nbsp;this&nbsp;year&nbsp;a&nbsp;lot.&nbsp;Now,&nbsp;he&nbsp;is&nbsp;so&nbsp;eager&nbsp;to&nbsp;the&nbsp;coming&nbsp;year&nbsp;2016.</span></p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Limak是一个北极熊。他很享受它的这2015年。现在，他非常期待2016年的到来。</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Limak&nbsp;wants&nbsp;to&nbsp;prove&nbsp;how&nbsp;responsible&nbsp;a&nbsp;bear&nbsp;he&nbsp;is.&nbsp;He&nbsp;is&nbsp;going&nbsp;to&nbsp;regularly&nbsp;save&nbsp;candies&nbsp;for&nbsp;the&nbsp;entire&nbsp;year&nbsp;2016!&nbsp;He&nbsp;considers&nbsp;various&nbsp;saving&nbsp;plans.&nbsp;He&nbsp;can&nbsp;save&nbsp;one&nbsp;candy&nbsp;either&nbsp;on&nbsp;some&nbsp;fixed&nbsp;day&nbsp;of&nbsp;the&nbsp;week&nbsp;or&nbsp;on&nbsp;some&nbsp;fixed&nbsp;day&nbsp;of&nbsp;the&nbsp;month.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Limak想证明他是多么负责的一只北极熊，他打算在2016年全年来节省糖果，他考虑了很多不同的方法。他能在一周固定的某一天或者一个月固定的某一天来节省一颗糖果。</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Limak&nbsp;chose&nbsp;one&nbsp;particular&nbsp;plan.&nbsp;He&nbsp;isn&#39;t&nbsp;sure&nbsp;how&nbsp;many&nbsp;candies&nbsp;he&nbsp;will&nbsp;save&nbsp;in&nbsp;the&nbsp;2016&nbsp;with&nbsp;his&nbsp;plan.&nbsp;Please,&nbsp;calculate&nbsp;it&nbsp;and&nbsp;tell&nbsp;him.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Limak选择了了一个计划，但是他不确定一年里他会节省多少糖果。那么请计算出来告诉他。</p> 

 
 # 输入格式 
<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">唯一输入的一行是下面两个公式中的一个:</p>

<ul style="margin: 0.5em 0px 0px 1em; padding-right: 0px; padding-left: 0px; list-style-position: outside; font-size: 14px; line-height: 21px; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">
	<li style="margin: 0px 0px 0px 0.8em; padding: 0px; line-height: 1.5em; font-size: 1em;">&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;"><span class="tex-span" style="font-size: 19.25px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>x</i></span>&nbsp;of&nbsp;week</span>&quot;&nbsp;其中：<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>x</i></span>&nbsp;(<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;">1&thinsp;&le;&thinsp;<i>x</i>&thinsp;&le;&thinsp;7</span>)&nbsp;代表一个星期中的每一天.&nbsp;第一天是星期一，第七天是星期日。</li>
	<li style="margin: 0px 0px 0px 0.8em; padding: 0px; line-height: 1.5em; font-size: 1em;">&quot;<span class="tex-font-style-tt" style="font-size: 15.4px; font-family: 'courier new', monospace;"><span class="tex-span" style="font-size: 19.25px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>x</i></span>&nbsp;of&nbsp;month</span>&quot;&nbsp;其中：&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;"><i>x</i></span>&nbsp;(<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;">1&thinsp;&le;&thinsp;<i>x</i>&thinsp;&le;&thinsp;31</span>)&nbsp;代表一个月中的每一天</li>
</ul> 

 
 # 输出格式 
<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
4&nbsp;of&nbsp;week
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
52
</pre>
</div>

<div class="input" style="margin: 0px; padding: 0px; border: 1px solid rgb(136, 136, 136); color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">input</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
30&nbsp;of&nbsp;month
</pre>
</div>

<div class="output" style="margin: 0px 0px 1em; padding: 0px; border: 1px solid rgb(136, 136, 136); position: relative; top: -1px; color: rgb(34, 34, 34); font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; font-size: 12.6px; line-height: 21px;">
<div class="title" style="margin: 0px; padding: 0.25em; font-size: 1.3em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(136, 136, 136); text-transform: lowercase; font-weight: bold;">output</div>

<pre style="margin-top: 0px; margin-bottom: 0px; padding: 0.25em; font-size: 12.6px; font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier; line-height: 1.25em; color: rgb(136, 0, 0); background-color: rgb(239, 239, 239);">
11</pre>
</div> 

 
 # 提示 
<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Polar&nbsp;bears&nbsp;use&nbsp;the&nbsp;Gregorian&nbsp;calendar.&nbsp;It&nbsp;is&nbsp;the&nbsp;most&nbsp;common&nbsp;calendar&nbsp;and&nbsp;you&nbsp;likely&nbsp;use&nbsp;it&nbsp;too.&nbsp;You&nbsp;can&nbsp;read&nbsp;about&nbsp;it&nbsp;on&nbsp;Wikipedia&nbsp;if&nbsp;you&nbsp;want&nbsp;to&nbsp;&ndash;&nbsp;<a href="https://en.wikipedia.org/wiki/Gregorian_calendar" style="color: rgb(77, 135, 199); text-decoration: none; background: transparent;">https://en.wikipedia.org/wiki/Gregorian_calendar</a>.&nbsp;每个星期从星期一开始。</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">In&nbsp;the&nbsp;first&nbsp;sample&nbsp;Limak&nbsp;wants&nbsp;to&nbsp;save&nbsp;one&nbsp;candy&nbsp;on&nbsp;each&nbsp;Thursday&nbsp;(the&nbsp;4-th&nbsp;day&nbsp;of&nbsp;the&nbsp;week).&nbsp;There&nbsp;are&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;">52</span>&nbsp;Thursdays&nbsp;in&nbsp;the&nbsp;2016.&nbsp;Thus,&nbsp;he&nbsp;will&nbsp;save&nbsp;<span class="tex-span" style="font-size: 17.5px; font-family: 'times new roman', sans-serif; white-space: nowrap;">52</span>&nbsp;candies&nbsp;in&nbsp;total.</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">在第一个测试样例中，Limak想要在每周四节省一个糖果，那么在2016年有52个周四，所以他会节省54颗糖果。</p>

<p style="margin: 1.5em 0px 0px; padding: 0px; font-size: 14px; line-height: 1.4em; color: rgb(34, 34, 34); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第二个例子中，他想要在每月的第30天节省一颗糖果，那个2016年有11个月有第30天，所以他节省了11颗糖果。</p> 
