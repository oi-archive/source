
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin-bottom: 10.75pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "></p>
<div>  Bytie is playing the computer game Tower Defense. His aim is to construct guard towers, so that they protect all of his domain. There are multiple towns in Bytie&#39;s domain, some of which are linked by bidirectional roads. If Bytie erects a guard tower in a city, then the tower protects its city and all the cities directly linked with it by roads.</div>
<div>  Just as Bytie was pondering over the placement of guard towers in his domain, his elder sister Bytea entered the room. She glanced at the map displayed on the screen, and after a moment exclaimed: &#34;Oi, what is there to think about, clearly K  towers suffice!&#34;.</div>
<div>  Angered by his sister spoiling the fun, Bytie showed his sister the door, and began wondering what to do next. Pride will not let him construct more than K  towers. He has an up his sleeve though: he can research a technology that will allow him to constructimproved guard towers. An improved guard tower protects not only the town it was erected in and its immediate neighbors but also the towns that are further away. Formally, an improved guard tower built in the town U protects the town V  if either of the following holds:</div>
<div>U=V;</div>
<div>there is a direct road from U to V ;</div>
<div>or there is such a town W that there are direct roads from U to W and from W to V.</div>
<div>Of course, Bytie still strives to erect at most K towers, but he has no qualms about making these the improved guard towers.</div>
<div>有一天XYW在4399上玩一个塔防游戏：</div>
<div>请你给他一种用k座以内加强过的塔保护所有城市的方案</div>
<div>有n座城市由m条双向道路连接。XYW可以在城市中建防御塔，每一座防御塔可以保护它所在的城市以及和这座城市有道路直接连接的城市。</div>
<div>由于XYW比较蠢萌，他建了n座塔保卫了所有城市。</div>
<div>突然XYW的男人看到了他的电脑屏幕：我只要用k座塔就可以了。（保证存在仅用k座塔就可以保卫所有城市的情况）</div>
<div>XYW不想被他的男人嘲笑，于是他就开始想如何用k座塔保护所有城市。</div>
<div>由于XYW比较蠢萌，他想不出来。</div>
<div>于是他更改了游戏规则：每一座塔可以保护和它所在城市最短距离在两条道路以内的所有城市。</div>
<div></div>
<p class="MsoNormal" align="left" style="margin-bottom: 10.75pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "></p>
<p></p></div>

# Input

<div class="content"><div></div>
<div>
<p class="MsoNormal" align="left" style="background-color: white; margin-bottom: 10.75pt; "></p>
<p class="MsoNormal" align="left" style="margin-bottom: 10.75pt;">  The towns in Bytie&#39;s domain are numbered from 1 to N. Next, M lines describing the roads follow. Each of those lines holds two integers, Ai and Bi (1&lt;=Ai,Bi&lt;=N,Ai&lt;&gt;Bi) , indicating that the towns no. Ai and Bi are directly linked by a bidirectional road. Each pair of towns is linked by at most a single road.</p>
<p class="MsoNormal" align="left" style="background-color: white; margin-bottom: 10.75pt; "></p>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div></div>
<div>
<p class="MsoNormal" align="left" style="background-color: white; margin-bottom: 10.75pt; "></p>
<p class="MsoNormal" align="left" style="margin-bottom: 10.75pt;">  If more than one solution exists, any solution can be printed. Let us remind that any placement of no more than K improved towers will do - you need not minimize their number. You may assume that Bytea was correct, i.e., that the whole domain of Bytie can indeed be protected by K plain (not improved) guard towers. Thus a solution always exists.</p>
<p class="MsoNormal" align="left" style="background-color: white; margin-bottom: 10.75pt; "></p>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 8 3<br/>
1 2<br/>
2 3<br/>
3 4<br/>
1 4<br/>
3 5<br/>
4 6<br/>
7 8<br/>
8 9<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1 5 7 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><a id="fck_paste_padding">﻿</a><span style="font-family: arial, verdana, helvetica, sans-serif;">2&lt;=n&lt;=500000,0&lt;=m&lt;=1000000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jiry_2">鸣谢Jiry_2</a></p></div>

