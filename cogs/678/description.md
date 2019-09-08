# 题目描述


<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>Dual Palindromes</b> 双重回文数</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">描述 [USACO 1.2.5]</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">如果一个数从左往右读和从右往左读都是一样，那么这个数就叫做“回文数”。例如，12321就是一个回文数，而77778就不是。当然，回文数的首和尾都应是非零的，因此0220就不是回文数。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">事实上，有一些数（如21），在十进制时不是回文数，但在其它进制（如二进制时为10101）时就是回文数。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">编一个程序，从文件读入两个十进制数N (1 &lt;= N &lt;= 15)S (0 &lt; S &lt; 10000)然后找出前N个满足大于S且在两种或两种以上进制（二进制至十进制）上是回文数的十进制数，输出到文件上。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">本问题的解决方案不需要使用大于32位的整型</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>PROGRAM NAME</b>: dualpal</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(file dualpal.in)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">只有一行，用空格隔开的两个数N和S。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(file dualpal.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">N行, 每行一个满足上述要求的数，并按从小到大的顺序输出.</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">3 25
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">26
27
28</pre>
