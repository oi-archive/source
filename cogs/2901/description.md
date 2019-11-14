# 题目描述


<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【题目描述】</span></span><span style="font-family:Cambria;font-size:10.5pt;"> </span><span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>打扑克牌更重要的是技术，而不是运气。但</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔就不信这点，他觉得自己人品就是特别好，他认为自己总是能抽到炸弹（某种相同的牌有四张，如</span></span><span style="font-family:Cambria;font-size:10.5pt;">QQQQ</span><span style="font-family:Cambria;font-size:10.5pt;"><span>）。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>这副牌有</span></span><span style="font-family:Cambria;font-size:10.5pt;">52</span><span style="font-family:Cambria;font-size:10.5pt;"><span>张，没有大小王，且有</span></span><span style="font-family:Cambria;font-size:10.5pt;">13</span><span style="font-family:Cambria;font-size:10.5pt;"><span>种牌，每种牌有且只有</span></span><span style="font-family:Cambria;font-size:10.5pt;">4</span><span style="font-family:Cambria;font-size:10.5pt;"><span>张，不考虑花色，各种牌按牌面大小的的顺序排列如右，</span></span><span style="font-family:Cambria;font-size:10.5pt;">A,2,K,Q,J,10,9,8,7,6,5,4,3</span><span style="font-family:Cambria;font-size:10.5pt;"><span>。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>那么如果</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔手头上某种牌的牌数超过</span></span><span style="font-family:Cambria;font-size:10.5pt;">4</span><span style="font-family:Cambria;font-size:10.5pt;"><span>张，如</span></span><span style="font-family:Cambria;font-size:10.5pt;">AAAAA</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，那么就算</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔出千。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>至于</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔的人品出牌规则，用一句话就能概括了，那就是尽量出牌面小的炸弹。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>现在你的问题来了，对于</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔现在手头上的牌，请你按照</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔的出牌规则找出最小的且能出的炸弹。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【输入数据】</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>第一行一个正整数</span></span><span style="font-family:Cambria;font-size:10.5pt;">M</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，表示数据组数</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>对于每个数据组</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:Cambria;font-size:10.5pt;"><span>第一行一个正整数</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，表示</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>大叔手头上的牌数；</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>第二行</span></span><span style="font-family:Cambria;font-size:10.5pt;">N</span><span style="font-family:Cambria;font-size:10.5pt;"><span>个整数描述牌（</span></span><span style="font-family:Cambria;font-size:10.5pt;">13</span><span style="font-family:Cambria;font-size:10.5pt;"><span>表示</span></span><span style="font-family:Cambria;font-size:10.5pt;">K</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5pt;">12</span><span style="font-family:Cambria;font-size:10.5pt;"><span>表示</span></span><span style="font-family:Cambria;font-size:10.5pt;">Q</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5pt;">11</span><span style="font-family:Cambria;font-size:10.5pt;"><span>表示</span></span><span style="font-family:Cambria;font-size:10.5pt;">J</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5pt;">1</span><span style="font-family:Cambria;font-size:10.5pt;"><span>表示</span></span><span style="font-family:Cambria;font-size:10.5pt;">A</span><span style="font-family:Cambria;font-size:10.5pt;"><span>）；</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>数据保证输入的牌一定在给定的范围内。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【输出数据】</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>对于每组数据输出占一行</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span><span style="font-family:Cambria;font-size:10.5pt;"><span>如果输入的某张牌超过</span></span><span style="font-family:Cambria;font-size:10.5pt;">4</span><span style="font-family:Cambria;font-size:10.5pt;"><span>张，那么直接输出</span></span><span style="font-family:Cambria;font-size:10.5pt;">‘cheat’</span><span style="font-family:Cambria;font-size:10.5pt;"><span>。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:Cambria;font-size:10.5pt;"><span>否则如果有可以出的炸弹，则输出一个数表示该炸弹，该数按照输入的数来表示，且该数表示的牌面要尽量的小。</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:Cambria;font-size:10.5pt;"><span>如果没有能出的炸弹，则输出</span></span><span style="font-family:Cambria;font-size:10.5pt;">‘no bomb’</span><span style="font-family:Cambria;font-size:10.5pt;"><span>。（引号都不用输出）</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【输入样例】</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">3</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">8</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">1 1 1 1 2 2 2 2</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">5</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">1 2 3 4 5</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">5</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">2 2 2 2 2</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【输出样例】</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">2</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">no bomb</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">cheat</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;"><span>【数据约定】</span></span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5pt;">100%</span><span style="font-family:Cambria;font-size:10.5pt;"><span>数据满足</span></span><span style="font-family:Cambria;font-size:10.5pt;">N&lt;=20</span><span style="font-family:Cambria;font-size:10.5pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5pt;">M&lt;=100</span><span style="font-family:Cambria;font-size:10.5pt;"></span> 
</p>
<br/>
