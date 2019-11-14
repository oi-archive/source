# 题目描述


<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    在幻想乡，帕秋莉·诺蕾姬</span><span style="font-size:9.0pt;">(</span><span style="font-size:9.0pt;font-family:宋体;">パチュリー·ノーレッジ</span><span style="font-size:9.0pt;">)</span><span style="font-size:9.0pt;font-family:宋体;">是以宅在图书馆闻名的魔法使。</span><span style="font-size:9.0pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    其语文，数学，英语，物理，化学，生物，政治，历史，地理，哲♂学，无所不通晓。</span><span style="font-size:9.0pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    <img src="/upload/image/20170330/20170330182542_30180.jpeg" alt=""/><br/>
</span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    这天魔理沙又来图书馆&lt;del&gt;偷&lt;/del&gt;窃算法导论，不由又被咲夜抓到了。</span><span style="font-size:9.0pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    这次帕</span><span style="font-size:9.0pt;">Q</span><span style="font-size:9.0pt;font-family:宋体;">要亲自用算多项式的方式惩罚摸你傻，如果摸你傻算出来了就放她走。</span><span style="font-size:9.0pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-size:9.0pt;font-family:宋体;">    问题就是</span><b><span style="font-family:微软雅黑, sans-serif;">求关于自变量<span>z</span>的函数<span>$F(z)=$</span></span></b><b><span style="font-family:微软雅黑, sans-serif;">    <img src="/upload/image/20170329/20170329114439_19653.png" alt=""/></span></b> 
</p>
<p class="MsoNormal">
<b><span style="font-family:微软雅黑, sans-serif;">泰勒展开后的 $[z^n] $项系数乘上$n!$之后  $\mod p$ 的值</span></b><b><span style="font-family:微软雅黑, sans-serif;">(</span></b><b><span style="font-family:微软雅黑, sans-serif;">其中·表示乘法运算，e为自然对数)</span></b> 
</p>
<p class="MsoNormal" align="left">
<span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-family:微软雅黑, sans-serif;">    你可能会用到的知识<span>:</span></span></b><span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-family:微软雅黑, sans-serif;">    泰勒展开的作用是将一个式子展开成与其等价的无限项多项式的形式</span></b><span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-family:微软雅黑, sans-serif;">    泰勒展开意义下<span> $ e^z=\frac{z^0}{0!}+\frac{z^1}{1!}+\frac{z^2}{2!}+\frac{z^3}{3!}+\dots\ $</span></span></b><span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-family:微软雅黑, sans-serif;">    若多项式<span> $F(z)$ </span>满足<span>$ F(z)=a_0+a_1 z^1+a_2 z^2+a_3 z^3...$ </span>那么<span>$ [z^n]F(z)=a_n $</span></span></b><span style="font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal">
【输入格式】
</p>
<p class="MsoNormal">
    第一行一个整数$T$
</p>
<p class="MsoNormal">
    接下来$T$行每行两个整数$n,p$
</p>
<p class="MsoNormal">
【输出格式】
</p>
<p class="MsoNormal">
    每行一个整数表示所需的值
</p>
<p class="MsoNormal">
【样例输入】
</p>
<p class="MsoNormal">
    1
</p>
<p class="MsoNormal">
    3 3
</p>
<p class="MsoNormal">
【样例输出】
</p>
<p class="MsoNormal">
    0
</p>
<p class="MsoNormal">
【解释】
</p>
<p class="MsoNormal">
    答案本应该是3，在mod 3意义下为0
</p>
<p class="MsoNormal">
【提示】
</p>
<p class="MsoNormal">
    由于出题人心情不好所以不存在梯度数据
</p>
<p class="MsoNormal">
    $1 \le T,n,p\le 5·10^4$
</p>
<p class="MsoNormal">
【来源】
</p>
<p class="MsoNormal">
    某次出题和唐教主撞车的驴蛋蛋...
</p>
