# 题目描述


<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id=".E6.8F.8F.E8.BF.B0">描述  [USACO 1.4.2]</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">考虑将如此安排在一个 3 x 3 行列中的九个时钟:</p>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; "> |-------|    |-------|    |-------|
 |       |    |       |    |   |   |
 |---O   |    |---O   |    |   O   |
 |       |    |       |    |       |
 |-------|    |-------|    |-------|
     A            B            C
</pre>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; "> |-------|    |-------|    |-------|
 |       |    |       |    |       |
 |   O   |    |   O   |    |   O   |
 |   |   |    |   |   |    |   |   |
 |-------|    |-------|    |-------|
     D            E            F
</pre>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; "> |-------|    |-------|    |-------|
 |       |    |       |    |       |
 |   O   |    |   O---|    |   O   |
 |   |   |    |       |    |   |   |
 |-------|    |-------|    |-------|
     G            H            I
</pre>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "> </p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">目标要找一个最小的移动顺序将所有的指针指向12点。下面原表格列出了9种不同的旋转指针的方法，每一种方法都叫一次移动。选择1到9号移动方法，将会使在表格中对应的时钟的指针顺时针旋转90度。</p>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">移动方法  受影响的时钟 
1        ABDE
2        ABC
3        BCEF
4        ADG
5        BDEFH
6        CFI
7        DEGH
8        GHI
9        EFHI

</pre>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>Example</b></p>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">9 9 12          9 12 12       9 12 12        12 12 12         12 12 12
6 6 6   5 -&gt;    9  9  9   8-&gt; 9  9  9   4 -&gt; 12  9  9   9 -&gt;  12 12 12
6 3 6           6  6  6       9  9  9        12  9  9         12 12 12

[但这可能不是正确的方法，请看下面]
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id=".E6.A0.BC.E5.BC.8F"><br/>
格式</span></h2>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>PROGRAM NAME</b>: clocks</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>INPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">(file clocks.in)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">第1-3行: 三个空格分开的数字，每个数字表示一个时钟的初始时间，3,6,9,12。数字的含意和上面第一个例子一样。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; "><b>OUTPUT FORMAT</b>:</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">(file clocks.out)</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">单独的一行包括一个用空格分开的将所有指针指向12:00的最短移动顺序的列表。</p>
<p style="margin-top: 0.4em; margin-right: 0px; margin-bottom: 0.5em; margin-left: 0px; line-height: 28px; font-family: sans-serif; font-size: 19px; ">如果有多种方案，输出那种使其连接起来数字最小的方案。(举例来说5 2 4 6 &lt; 9 3 1 1)。</p>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id="SAMPLE_INPUT"><br/>
SAMPLE INPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">9 9 12
6 6 6
6 3 6 
</pre>
<h2 style="background-image: none; background-attachment: initial; background-origin: initial; background-clip: initial; font-weight: normal; margin-top: 0px; margin-right: 0px; margin-bottom: 0.6em; margin-left: 0px; overflow-x: hidden; overflow-y: hidden; padding-top: 0.5em; padding-bottom: 0.17em; border-bottom-width: 1px; border-bottom-style: solid; border-bottom-color: rgb(170, 170, 170); font-size: 29px; font-family: sans-serif; line-height: 28px; "><span class="mw-headline" id="SAMPLE_OUTPUT"><br/>
SAMPLE OUTPUT</span></h2>
<pre style="padding-top: 1em; padding-right: 1em; padding-bottom: 1em; padding-left: 1em; border-top-width: 1px; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-top-style: dashed; border-right-style: dashed; border-bottom-style: dashed; border-left-style: dashed; border-top-color: rgb(47, 111, 171); border-right-color: rgb(47, 111, 171); border-bottom-color: rgb(47, 111, 171); border-left-color: rgb(47, 111, 171); border-image: initial; line-height: 1.1em; ">4 5 8 9</pre>
