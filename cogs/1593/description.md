# 题目描述


<h3>
【题目描述】
</h3>
<p>
“啦啦啦，啦啦啦，我是采姑娘的小蘑菇……”手提麻袋，一脸人贩子像的宇宇在这个神奇的八维空间中忽悠来忽悠去。<br/>
话说3分钟前，刚刚小宇宙爆发的他冲出了地面，雨后明媚的阳光滋润着小蘑菇宇宇的身体，看着四周和谐的环境，宇宇舒畅地伸了个懒腰。“噗——”好景不长，一只带着血腥味的大脚（玛丽大叔的香港脚），将宇宇送到了这个神奇的世界。<br/>
为什么这个空间是如此的神奇呢？因为其中的m个mm，她们的质量居然有着神秘的关系！任何两个mm，她们的质量总有一个是另一个的整数倍（可能相等）-_-|||。<br/>
为了抗议苍天对自己的不公（“士可杀不可辱！怎么能让蘑菇死在别人的脚下！”——宇宇如是说），宇宇开始对这个八维空间中mm的掠夺。可惜的是，满脸横肉的宇宇手中只有n个麻袋来装mm，甚至每个麻袋都有质量承受限制。<br/>
作为宇宇的基友，你需要帮助他算算他最多能掠夺多少mm。
</p>
<h3>
【输入格式】
</h3>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">输入文件的第一行包含两个数<span style="font-family:Calibri;">n</span><span style="font-family:宋体;">和</span><span style="font-family:Calibri;">m</span><span style="font-family:宋体;">，表示</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">麻袋</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">的数量以及</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">mm</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">的数量</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">（</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">n, m</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">100000</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">）</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">。第二行包含<span style="font-family:Calibri;">n</span><span style="font-family:宋体;">个整数</span><span style="font-family:Calibri;">w</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">i</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">，表示每个</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">麻袋</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">能够装的最大质量</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">（</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">w</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">i </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1000000000</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">）</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">。第三行包含<span style="font-family:Calibri;">m</span><span style="font-family:宋体;">个整数</span><span style="font-family:Calibri;">m</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">j</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">，表示每个<span style="font-family:Calibri;">mm</span><span style="font-family:宋体;">的质量</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">（</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">m</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">j </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">≤</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1000000000</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">）</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">。</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【输出格式】
</h3>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">输出文件要求仅包含一个数，为能够装进</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">麻袋</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">的最多的</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">mm</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">数量。</span> 
</p>
<!--EndFragment-->
<h3>
【样例输入】
</h3>
<h3>
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">2 4</span> 
</h3>
<h3>
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">13 9</span> 
</h3>
<h3>
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">4 12 2 4</span> 
</h3>
<h3>
【样例输出】
</h3>
<pre>3</pre>
<h3>
【提示】
</h3>
<p>
没有
</p>
<h3>
【来源】
</h3>
<p>
hzoi2014
</p>
