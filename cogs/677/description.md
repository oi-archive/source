# 题目描述


<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 1.2.4]</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">回文数是指从左向右念和从右向左念都一样的数。如12321就是一个典型的回文数。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">给定一个进制B(2&lt;=B&lt;=20,由十进制表示)，输出所有的大于等于1小于等于300（十进制下）且它的平方用B进制表示时是回文数的数。用’A’,’B’……表示10，11等等。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>PROGRAM NAME</b>: palsquare</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">file (palsquare.in)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">共一行，一个单独的整数B(B用十进制表示)。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">file (palsquare.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">每行两个B进制的符合要求的数字，第二个数是第一个数的平方，且第二个数是回文数。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">10
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">1 1
2 4
3 9
11 121
22 484
26 676
101 10201
111 12321
121 14641
202 40804
212 44944
264 69696</pre>
