# 题目描述


<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【题目描述】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>博士家的保险柜最近被小偷光顾了。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>但是值得庆幸的是，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>博士一项最重要的研究成果</span></span><span style="font-family:Cambria;font-size:10.5000pt;">——O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>式密码的相关论文，因为随身携带，而幸免于难。但紧张的</span></span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>博士害怕小偷再次光顾，所以将</span></span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>式密码设置在他家新买的保险柜上，关于</span></span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>式密码的相关描述如下。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>式密码的原文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">A</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>是由</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>个数字组成，而密文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">B</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>是一个长度为</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>的</span></span><span style="font-family:Cambria;font-size:10.5000pt;">01</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>数串，原文和密文的关联在于</span></span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>博士自己掌握的一个钥匙码</span></span><span style="font-family:Cambria;font-size:10.5000pt;">KEY</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>。若</span></span><span style="font-family:Cambria;font-size:10.5000pt;">KEY=<img src="/upload/image/20180211/20180211191915_96454.png" alt=""/></span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，则密文就是原文的一组合法密码。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;">O</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>博士拥有原文和钥匙码，也拥有一组密文，但是他不知道是否还有其他的密文也满足条件，所以他请你编一个程序来帮助他统计到底有多少个符合条件的密文。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输入数据】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>第一行两个数</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">KEY</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，意义同题目描述；</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>第二行</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>个数表示原文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">A</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，意义同题目描述。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输出数据】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>一个数</span></span><span style="font-family:Cambria;font-size:10.5000pt;">ANS</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，表示对于原文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">A</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>和</span></span><span style="font-family:Cambria;font-size:10.5000pt;">KEY</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，有多少组可行的密文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">B</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输入样例】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">3 2</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1 1 2</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输出样例】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">2</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【样例说明】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>密文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">110</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">1*1+1*1+0*2=2</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>密文</span></span><span style="font-family:Cambria;font-size:10.5000pt;">001</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">0*1+0*1+1*2=2</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>一共两组可行的密文。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【数据约定】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">60%</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>数据满足</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N&lt;=25</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">100%</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>数据满足</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N&lt;=40</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">-maxlongint&lt;=<img src="/upload/image/20180211/20180211192057_35580.png" alt=""/></span><span style="font-family:Cambria;font-size:10.5000pt;">&lt;=maxlongint</span><span style="font-family:Cambria;font-size:10.5000pt;"><br/>
</span> 
</p>
<br/>
