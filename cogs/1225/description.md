# 题目描述


<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Winy<span>是一家酒吧的老板，他的酒吧提供两种体积的啤酒，</span><span>a ml</span><span>和</span><span>b ml</span><span>，分别使用容积为</span><span>a ml</span><span>和</span><span>b ml</span><span>的酒杯来装载。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    酒吧的生意并不好。<span>Winy</span><span>发现酒鬼们都非常穷。有时，他们会因为负担不起</span><span>aml</span><span>或者</span><span>bml</span><span>啤酒的消费，而不得不离去。因此，</span><span>Winy</span><span>决定出售第三种体积的啤酒</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">较小体积的啤酒</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">  Winy<span>只有两种杯子，容积分别为</span><span>a ml</span><span>和</span><span>b ml</span><span>，而且啤酒杯是没有刻度的。他只能通过两种杯子和酒桶间的互相倾倒来得到新的体积的酒。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    为了简化倒酒的步骤，<span>Winy</span><span>规定：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>1</span><span>）</span><span>a</span><span>≥</span><span>b</span><span>；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>2</span><span>）酒桶容积无限大，酒桶中酒的体积也是无限大</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">但远小于桶的容积</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>3</span><span>）只包含三种可能的倒酒操作：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">①将酒桶中的酒倒入容积为<span>b ml</span><span>的酒杯中；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">②将容积为<span>a ml</span><span>的酒杯中的酒倒入酒桶；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">③将容积为<span>b ml</span><span>的酒杯中的酒倒入容积为</span><span>a ml</span><span>的酒杯中。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>4</span><span>）每次倒酒必须把杯子倒满或把被倾倒的杯子倒空。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Winy<span>希望通过若干次倾倒得到容积为</span><span>a ml</span><span>酒杯中剩下的酒的体积尽可能小，他请求你帮助他设计倾倒的方案</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">两个整数<span>a</span><span>和</span><span>b</span><span>（</span><span>0</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">b<span>≤</span><span>a</span><span>≤</span><span>10</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:super;">9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">）</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行一个整数<span>c</span><span>，表示可以得到的酒的最小体积。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二行两个整数<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（中间用一个空格分隔），分别表示从体积为<span>a ml</span><span>的酒杯中倒出酒的次数和将酒倒入体积为</span><span>b ml</span><span>的酒杯中的次数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">若有多种可能的<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">、<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">满足要求，那么请输出<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">最小的一个。若在<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">最小的情况下，有多个<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">满足要求，请输出<span>P</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">最小的一个。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">pour.in</span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 3</span> 
</p>
<p>
<span style="font-family:宋体;font-size:10.5pt;">pour.out</span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">倾倒的方案为：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>、桶</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">B<span>杯；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>、</span><span>B</span><span>杯</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A<span>杯；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3<span>、桶</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">B<span>杯；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4<span>、</span><span>B</span><span>杯</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A<span>杯；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5<span>、</span><span>A</span><span>杯</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">桶<span>;</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6<span>、</span><span>B</span><span>杯</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A<span>杯；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
