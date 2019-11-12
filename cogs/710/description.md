# 题目描述


<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">题目描述</span>
</h3>
<p>
在威斯康辛州牛大农场经营者之中，都习惯于请会计部门用连续数字给母牛打上烙印。
</p>
<p>
但是,母牛用手机时并没感到这个系统的便利,它们更喜欢用它们喜欢的名字来呼叫它们的同伴，而不是用像这个的语句&#34;C&#39;mon, #4734, get along.&#34;。
</p>
<p>
请写一个程序来帮助可怜的牧牛工将一只母牛的烙印编号翻译成一个可能的名字。
</p>
<p>
因为母牛们现在都有手机了，使用那标准的按键的排布来把收到从数目翻译到文字,除了&#34;Q&#34; 和 &#34;Z&#34;(没出现过）
</p>
<p>
2: A,B,C     5: J,K,L 8: T,U,V
</p>
<p>
3: D,E,F     6: M,N,O 9: W,X,Y
</p>
<p>
4: G,H,I     7: P,R,S
</p>
<p>
<img src="/upload/image/20140318/20140318100937_45981.jpg" alt=""/>
</p>
<p>
可接受的名字都被放在测试数据的前若干行，它包含一连串的少于 5,000个可接受的牛名字。 (所有的名字都是大写的)
</p>
<p>
收到母牛的编号返回那些能从编号翻译出来并且在字典中的名字。
</p>
<p>
举例来说,编号 4734 能产生的下列各项名字:
</p>
<p>
GPDG GPDH GPDI GPEG GPEH GPEI GPFG GPFH GPFI GRDG GRDH GRDI
</p>
<p>
GREG GREH GREI GRFG GRFH GRFI GSDG GSDH GSDI GSEG GSEH GSEI
</p>
<p>
GSFG GSFH GSFI HPDG HPDH HPDI HPEG HPEH HPEI HPFG HPFH HPFI
</p>
<p>
HRDG HRDH HRDI HREG HREH HREI HRFG HRFH HRFI HSDG HSDH HSDI
</p>
<p>
HSEG HSEH HSEI HSFG HSFH HSFI IPDG IPDH IPDI IPEG IPEH IPEI
</p>
<p>
IPFG IPFH IPFI IRDG IRDH IRDI IREG IREH IREI IRFG IRFH IRFI
</p>
<p>
ISDG ISDH ISDI ISEG ISEH ISEI ISFG ISFH ISFI
</p>
<p>
碰巧，81个中只有一个&#34;GREG&#34;是有效的(在字典中)。
</p>
<p>
Challenge One
</p>
<p>
写一个程序来对给出的编号打印出所有的有效名字，如果没有则输出&#34;NONE&#39;&#39; 。
</p>
<p>
编号可能有12位数字。
</p>
<h3>
输入格式
</h3>
<p>
<span style="color:#333333;font-size:14px;line-height:normal;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4618行，前4617行为可接受的名字（即字典），最后单独的一行</span></span><span style="color:#333333;line-height:normal;font-family:&#34;">包含一个编号(长度可能从1到12)。</span> 
</p>
<h3>
输出格式
</h3>
<p>
以字典顺序输出一个有效名字的不负列表，一行一个名字。
</p>
<h3>
样例输入
</h3>
<pre>/*前若干行的字典省略了*/
4734
</pre>
<h3>
样例输出
</h3>
<pre>GREG
</pre>
<h3>
来源
</h3>
<p>
USACO 1.2.3 Name That Number
译 by timgreen
</p>
