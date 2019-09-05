# 题目描述


<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 1.2.2]</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">一块N x N（1&lt;=N&lt;=10）正方形的黑白瓦片的图案要被转换成新的正方形图案。写一个程序来找出将原始图案按照以下列转换方法转换成新图案的最小方式：</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">1：转90度：图案按顺时针转90度。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">2：转180度：图案按顺时针转180度。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">3：转270度：图案按顺时针转270度。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">4：反射：图案在水平方向翻转（以中央铅垂线为中心形成原图案的镜像）。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">5：组合：图案在水平方向翻转，然后再按照1到3之间的一种再次转换。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">6：不改变：原图案不改变。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">7：无效转换：无法用以上方法得到新图案。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">如果有多种可用的转换方法，请选择序号最小的那个。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">一个步骤就要搞定</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>PROGRAM NAME</b>: transform</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">file (transformations.in)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">第一行： 单独的一个整数N。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">第二行到第N+1行： N行每行N个字符（不是“@”就是“-”）；这是转换前的正方形。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">第N+2行到第2*N+1行： N行每行N个字符（不是“@”就是“-”）；这是转换后的正方形。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">file (transformations.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">单独的一行包括1到7之间的一个数字（在上文已描述）表明需要将转换前的正方形变为转换后的正方形的转换方法。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">3
@-@
---
@@-
@-@
@--
--@
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">1</pre>
<p> </p>
