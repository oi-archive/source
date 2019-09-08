# 题目描述


<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述  [USACO 1.3.2]</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">在一个夜黑风高,下着暴风雨的夜晚,farmer John的牛棚的屋顶、门被吹飞了。 好在许多牛正在度假，所以牛棚没有住满。 牛棚一个紧挨着另一个被排成一行，牛就住在里面过夜。 有些牛棚里有牛，有些没有。 所有的牛棚有相同的宽度。 自门遗失以后,farmer John必须尽快在牛棚之前竖立起新的木板。 他的新木材供应商将会供应他任何他想要的长度,但是吝啬的供应商只能提供有限数目的木板。 farmer John想将他购买的木板总长度减到最少。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">给出:可能买到的木板最大的数目M(1&lt;= M&lt;=50);牛棚的总数S(1&lt;= S&lt;=200); 牛棚里牛的总数C(1 &lt;= C &lt;=S);和牛所在的牛棚的编号stall_number(1 &lt;= stall_number &lt;= S),计算拦住所有有牛的牛棚所需木板的最小总长度。 输出所需木板的最小总长度作为答案。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>PROGRAM NAME</b>: barn1</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(file barn1.in)</p>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">1 行: 木板最大的数目M ,牛棚的总数S 和 牛的总数C(用空格分开)  
2 到 C+1行:  每行包含一个整数，表示牛所占的牛棚的编号。
</pre>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">(file barn1.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">单独的一行包含一个整数表示所需木板的最小总长度。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">4 50 18
3 
4 
6 
8 
14
15 
16 
17 
21
25 
26 
27 
30 
31 
40 
41 
42 
43
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 19px; font-family: sans-serif; line-height: 22px; "><span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; background-color: rgb(249, 249, 249); line-height: 1.1em; font-size: 15px; ">25
</pre>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 22px; font-family: sans-serif; font-size: 15px; ">[ 一种最优的安排是用板拦牛棚3-8,14-21,25-31,40-43.]</p>
