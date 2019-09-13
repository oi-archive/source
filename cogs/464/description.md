# 题目描述


<div style="layout-grid-mode:char;">
你有一条由N个红色的，白色的，或蓝色的珠子组成的项链(3&lt;=N&lt;=350)，珠子是随意安排的。这里是 n=29 的二个例子:
</div>
<div style="layout-grid-mode:char;">
</div>
<div style="layout-grid-mode:char;">
              1 2                               1 2<br/>
            r b b r                           b r r b<br/>
          r         b                       b         b<br/>
         r           r                     b           r<br/>
        r             r                   w             r<br/>
       b               r                 w               w<br/>
      b                 b               r                 r<br/>
      b                 b               b                 b<br/>
      b                 b               r                 b<br/>
       r               r                 b               r<br/>
        b             r                   r             r<br/>
         b           r                     r           r<br/>
           r       r                         r       b<br/>
             r b r                             r r w<span style="font-size:x-small;"><br/>
</span><span style="font-size:10pt;"></span> 
</div>
<div style="layout-grid-mode:char;">
             图片 A<span>                       </span>图片 B
</div>
<div style="layout-grid-mode:char;">
<span></span> 
</div>
<div style="layout-grid-mode:char;">
<span>r </span>代表 红色的珠子<span> </span> 
</div>
<div style="layout-grid-mode:char;">
<span>b </span>代表 蓝色的珠子<span> </span> 
</div>
<div style="layout-grid-mode:char;">
<span></span>w 代表 白色的珠子
</div>
<div style="layout-grid-mode:char;">
第一和第二个珠子在图片中已经被作记号。
</div>
<div style="layout-grid-mode:char;">
图片 A 中的项链可以用下面的字符串表示：
</div>
<div style="layout-grid-mode:char;">
<span><span>brbrrrbbbrrrrrbrrbbrbbbbrrrrb</span></span><span> . </span> 
</div>
<div style="layout-grid-mode:char;">
假如你要在一些点打破项链,展开成一条直线，然后从一端开始收集同颜色的珠子直到你遇到一个不同的颜色珠子，在另一端做同样的事 <span>(</span>颜色可能与在这之前收集的不同) 。确定应该在哪里打破项链来收集到最大多数的数目的子。
</div>
<div style="layout-grid-mode:char;">
举例来说，在图片 A 中的项链，可以收集到8个珠子,在珠子 9 和珠子 10 或珠子 24 和珠子 25 之间打断项链。 在一些项链中，包括白色的珠子如图片 B 所示。 当收集珠子的时候，一个<span>被遇到的白色珠子可以被当做红色也可以被当做蓝色。</span> 表现项链的字符串将会包括三符号 r ， b 和 w 。 写一个程序来确定从一条被供应的项链最大可以被收集珠子数目。
</div>
<div>
</div>
<div>
【输入】
</div>
<div>
输入文件 <span style="font-size:13.5pt;"><span style="font-size:12px;">beads</span><span style="font-size:x-small;">.in</span></span>，共2 行。<strong></strong><span></span><span></span><span></span><span></span><span></span><strong></strong><span></span><span></span><strong></strong><span></span>第 1 行:  N, 珠子的数目
</div>
<div>
第 2 行:  一串度为N的字符串, 每个字符是 r ， b 或 w。
</div>
<div>
</div>
<div>
【输出】
</div>
<div>
输出文件 <span style="font-size:13.5pt;"><span style="font-size:12px;">beads</span><span style="font-size:x-small;">.out</span></span><strong>，</strong><span style="font-size:12px;">仅 1 行</span><span style="font-size:12px;">包含从被</span><span style="font-size:12px;">供应的项链可以被收集的珠子数目的最大值。</span> 
</div>
<div>
<strong><span style="font-size:12pt;"></span></strong> 
</div>
<div>
<strong><span style="font-size:12pt;"></span></strong>【样例】
</div>
<div>
<span style="font-size:13.5pt;"><span style="font-size:12px;">beads</span><span style="font-size:10pt;font-weight:normal;">.in</span></span> 
</div>
<div style="layout-grid-mode:char;">
29
</div>
<div style="layout-grid-mode:char;">
<span>wwwbbrwrbrbrrbrbrwrwwrbwrwrrb</span> 
</div>
<div>
<span style="font-size:12px;">beads</span>.out
</div>
<div>
<span style="font-size:12pt;">11 </span> 
</div>
<div>
</div>
