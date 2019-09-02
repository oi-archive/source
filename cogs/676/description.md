# 题目描述


<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述 [USACO 1.1.3]</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">13号又是一个星期五。13号在星期五比在其他日子少吗?为了回答这个问题,写一个程序，要求计算每个月的十三号落在周一到周日的次数。给出N年的一个周期，要求计算1900年1月1日至1900+N-1年12月31日中十三号落在周一到周日的次数，N为正整数且不大于400.</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">这里有一些你要知道的:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">1、1900年1月1日是星期一.<br/>
2、4,6,11和9月有30天.其他月份除了2月都有31天.闰年2月有29天,平年2月有28天.<br/>
3、年份可以被4整除的为闰年(1992=4*498 所以 1992年是闰年,但是1990年不是闰年).<br/>
4、以上规则不适合于世纪年。可以被400整除的世纪年为闰年,否则为平年。所以,1700,1800,1900和2100年是平年,而2000年是闰年.<br/>
 </p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">请不要调用现成的函数</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">请不要预先算好数据（就是叫不准打表）!</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>PROGRAM NAME</b>: friday</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(friday.in)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">一个正整数n.</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(friday.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">七个在一行且相分开的整数,它们代表13日是星期六,星期日,星期一...星期五的次数..</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E8.BE.93.E5.85.A5.E6.A0.BC.E5.BC.8F"><br/>
输入格式</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">20
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E8.BE.93.E5.87.BA.E6.A0.BC.E5.BC.8F"><br/>
输出格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">36 33 34 33 35 35 34</p>
