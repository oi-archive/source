
# Description

<div class="content"><p class="MsoNormal"><font color="#ff0000" size="3"><b><br/>
</b></font></p>
<p class="MsoNormal"><span style="font-size: medium"><span lang="EN-US">taorunz</span><span style="font-family: 宋体">平时最喜欢的东西就是可移动存储器了……只要看到别人的可移动存储器，他总是用尽一切办法把它里面的东西弄到手。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体">突然有一天，</span><span lang="EN-US">taorunz</span><span style="font-family: 宋体">来到了一个密室，里面放着一排可移动存储器，存储器里有非常珍贵的</span><span lang="EN-US">OI</span><span style="font-family: 宋体">资料……不过比较特殊的是，每个存储器上都写着一个非负整数。</span><span lang="EN-US">taorunz</span><span style="font-family: 宋体">很高兴，要把所有的存储器都拿走（</span><span lang="EN-US">taorunz</span><span style="font-family: 宋体">的智商高达</span><span lang="EN-US">500</span><span style="font-family: 宋体">，他一旦弄走了这里的所有存储器，在不久到来的</span><span lang="EN-US">AHOI</span><span style="font-family: 宋体">和</span><span lang="EN-US">NOI</span><span style="font-family: 宋体">中……你懂的）。不过这时有一个声音传来：“你只能拿走这里的一个存储器，而且还不能直接拿，你需要指定一段区间</span><span lang="EN-US">[l, r]</span><span style="font-family: 宋体">，满足</span><span lang="EN-US">l&lt;r</span><span style="font-family: 宋体">，然后在第</span><span lang="EN-US">l</span><span style="font-family: 宋体">个和第</span><span lang="EN-US">r</span><span style="font-family: 宋体">个存储器之间选一个拿走，你能获得的知识增加量等于区间</span><span lang="EN-US">[l, r]</span><span style="font-family: 宋体">中所有存储器上写的整数的次大值与你拿走的这个存储器上写的整数作按位异或运算的结果。”</span></span></p>
<p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体">问题是，这里的可移动存储器数量太多，而且，它们还在不断地发生变化，有时候天上会掉下来一个新的存储器，并插入到这一排存储器中，有时候某个存储器会不明原因消失，有时候某个存储器上写的整数变化了。</span><span lang="EN-US">taorunz</span><span style="font-family: 宋体">虽然智商很高，但也无法应对如此快的变化，他指定了许多段区间，让你帮他找出如果在这个区间中拿走存储器，他能获得的最多的知识是多少。</span></span></p>
<p class="MsoNormal"><font face="宋体" size="3"><br/>
</font></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal"><span style="font-size: medium; font-family: 宋体; ">第一行两个整数</span><span lang="EN-US" style="font-size: medium; ">N</span><span style="font-size: medium; font-family: 宋体; ">、</span><span lang="EN-US" style="font-size: medium; ">M</span><span style="font-size: medium; font-family: 宋体; ">，表示一开始的存储器数和后面发生的事件数。</span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">第二行</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">个非负整数，表示一开始从左到右每个存储器上写的数字。注意，存储器从</span><span lang="EN-US">0</span><span style="font-family: 宋体; ">开始编号，也就是最左边的存储器是第</span><span lang="EN-US">0</span><span style="font-family: 宋体; ">个。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">接下来</span><span lang="EN-US">M</span><span style="font-family: 宋体; ">行，每行描述一个事件，有</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">种可能的事件。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">（</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">）</span><span lang="EN-US">I x y</span><span style="font-family: 宋体; ">：表示天上掉下来一个写着数字</span><span lang="EN-US">y</span><span style="font-family: 宋体; ">的存储器，并插入到原来的第</span><span lang="EN-US">x</span><span style="font-family: 宋体; ">个存储器之前，如果</span><span lang="EN-US">x</span><span style="font-family: 宋体; ">等于原来存储器的个数，则插入到末尾；</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">（</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">）</span><span lang="EN-US">D x</span><span style="font-family: 宋体; ">：表示第</span><span lang="EN-US">x</span><span style="font-family: 宋体; ">个存储器消失；</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">（</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">）</span><span lang="EN-US">C x y</span><span style="font-family: 宋体; ">：表示第</span><span lang="EN-US">x</span><span style="font-family: 宋体; ">个存储器上写的数字变为</span><span lang="EN-US">y</span><span style="font-family: 宋体; ">；</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">（</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">）</span><span lang="EN-US">F l r</span><span style="font-family: 宋体; ">：表示</span><span lang="EN-US">taorunz</span><span style="font-family: 宋体; ">指定区间</span><span lang="EN-US">[l, r]</span><span style="font-family: 宋体; ">，让你告诉他最多能获得多少知识。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">注意，本题强制在线，也就是事件中出现的所有数字都进行了加密，数字</span><span lang="EN-US">s</span><span style="font-family: 宋体; ">表示的真实值是</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">对于</span><span lang="EN-US">I</span><span style="font-family: 宋体; ">、</span><span lang="EN-US">D</span><span style="font-family: 宋体; ">、</span><span lang="EN-US">C</span><span style="font-family: 宋体; ">事件中的</span><span lang="EN-US">x</span><span style="font-family: 宋体; ">及</span><span lang="EN-US">F</span><span style="font-family: 宋体; ">事件中的</span><span lang="EN-US">l</span><span style="font-family: 宋体; ">、</span><span lang="EN-US">r</span><span style="font-family: 宋体; ">：</span><span lang="EN-US">(s+last_ans) mod n0</span><span style="font-family: 宋体; ">；</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">对于</span><span lang="EN-US">I</span><span style="font-family: 宋体; ">、</span><span lang="EN-US">C</span><span style="font-family: 宋体; ">事件中的</span><span lang="EN-US">y</span><span style="font-family: 宋体; ">：</span><span lang="EN-US">(s+last_ans) mod 1048576</span><span style="font-family: 宋体; ">。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">其中</span><span lang="EN-US">n0</span><span style="font-family: 宋体; ">为目前存储器个数，</span><span lang="EN-US">last_ans</span><span style="font-family: 宋体; ">为上一个</span><span lang="EN-US">F</span><span style="font-family: 宋体; ">事件的结果，如果前面尚未发生</span><span lang="EN-US">F</span><span style="font-family: 宋体; ">事件，则</span><span lang="EN-US">last_ans=0</span><span style="font-family: 宋体; ">。</span></span></p>
<p class="MsoNormal"><font face="宋体" size="3"><br/>
</font></p>
<p class="MsoNormal"></p>
<p></p></div>

# Output

<div class="content"><p></p>
<div></div>
<div>
<p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体">对于每个</span><span lang="EN-US">F</span><span style="font-family: 宋体">事件，输出结果。</span></span></p>
<p class="MsoNormal"><font face="宋体" size="3"><br/>
</font></p>
<p class="MsoNormal"></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
<br/>
2 6 3 8 7<br/>
<br/>
F 1 4<br/>
<br/>
I 2 1048565<br/>
<br/>
I 0 1048566<br/>
<br/>
D 3<br/>
<br/>
F 3 0<br/>
<br/>
I 3 1048569<br/>
<br/>
D 5<br/>
<br/>
C 1 1048570<br/>
<br/>
F 1 2<br/>
<br/>
F 2 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
15<br/>
<br/>
7<br/>
<br/>
4<br/>
<br/>
7<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium; "><br/><br/>
</span></div><br/>
<div><span style="font-size: medium; "><br/><br/>
</span></div><br/>
<div><span style="font-size: medium; ">1&lt;=N, M&lt;=100000。所有F事件满足l&lt;r。</span></div><br/>
<div><span style="font-size: medium; "><br/><br/>
</span></div><br/>
<div><span style="font-size: medium; ">本题共有5组数据，除1组为随机数据外，其它数据均为人工构造。</span></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By mato_no1
">By mato_no1<br/>
</a></p></div>

