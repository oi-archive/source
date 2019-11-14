<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　【问题描述】<i></i>　　再过几天就是Catherine的生日了！Catherine决定举办一个生日宴会，并想邀请她的好朋友们参加宴会。<br/>
　　......<br/>
　　Catherine是个很有魅力的人，她一共有<i>N</i>个好朋友。而她的这些好朋友互相之间可能认识，也可能不认识，还可能<b>有矛盾</b>。<br/>
　　这<i>N</i>个人之间是否认识是无所谓的，但是如果两个人之间存在矛盾就会产生一些问题。这里，<b>矛盾关系是双向的</b>。<br/>
　　Catherine知道，如果她邀请的<b>任意一个</b>好朋友小X在宴会上<b>只看到一个与小</b><b>X</b><b>有矛盾的人</b>小Y，就会不太高兴，不过可以假装没看见。但是，如果小X<b>又看到另一个与小</b><b>X</b><b>有矛盾的人</b>小Z，小X就会很生气并离开宴会。<br/>
　　......<br/>
　　为了防止这样的情形出现，Catherine决定只邀请她的一部分好朋友参加宴会，使得对于这些人中的<b>任意一个人</b>，<b>至多有一个</b>与他（或她）有矛盾的人同时受到邀请。这样，就不会有人中途离开宴会了。<br/>
　　......<br/>
　　经过调查，Catherine已经掌握了在她的<i>N</i>个好朋友中有哪些人之间存在矛盾。在保证上述原则的前提下，她希望邀请<b>尽量多</b>的好朋友参加宴会。<br/>
　　请你帮助Catherine计算出她<b>最多</b>邀请多少个好朋友参加这个宴会。<br/>
　　......<br/>
<b>注意，输入文件包含多组测试数据。</b></div>
# 输入格式

<div class="pdcont">　　第一行包含一个正整数<i>T</i>，表示有<i>T</i>组测试数据。接下来依次是<i>T</i>组测试数据。<br/>
　　每组测试数据的第一行包含一个正整数<i>N</i>，表示Catherine的好朋友数目。<br/>
　　接下来<i>N</i>行，每行一个长度为<i>N</i>的字符串。其中第<i>i</i>个字符串<i>Str[i]</i>的第<i>j</i>个字符<i>Str[i][j]</i>表示第<i>i</i>个人和第<i>j</i>个人是否有矛盾。若<i>Str[i][j] = ‘Y’</i><i>，</i>则表示<i>i</i>和<i>j</i>有矛盾；否则的话，<i>Str[i][j] = ‘N’</i><i>，</i>表示没有矛盾。<br/>
　　数据保证对于任意<i>1</i><i>≤</i><i>i</i>, <i>j</i><i>≤</i><i>N</i>，有<i>Str[i][j] = Str[j][i]</i>；对于任意<i>1</i><i>≤</i><i>i</i><i>≤</i><i>N</i>，有<i>Str[i][i] = ‘N’</i>。</div>
# 输出格式

<div class="pdcont">　　输出<i>T</i>行，每行一个整数，依次表示每组测试数据的答案。</div>
# 样例输入

<div class="pddata">4<br/>
3<br/>
NYY<br/>
YNY<br/>
YYN<br/>
6<br/>
NYYNNN<br/>
YNYNYN<br/>
YYNYYY<br/>
NNYNNN<br/>
NYYNNY<br/>
NNYNYN<br/>
4<br/>
NNYN<br/>
NNNY<br/>
YNNN<br/>
NYNN<br/>
7<br/>
NNNNNNN<br/>
NNNNYNY<br/>
NNNYYYY<br/>
NNYNNYY<br/>
NYYNNNN<br/>
NNYYNNN<br/>
NYYYNNN</div>
# 样例输出

<div class="pddata">2<br/>
4<br/>
4<br/>
5</div>
# 样例说明

<div class="pdcont">　　第<i>1</i>组数据：<i>3</i>个人两两之间都有矛盾，所以最多同时邀请两个人。<br/>
　　第<i>2</i>组数据：一个可行的最优方案是邀请编号为<i>1</i><i>、</i><i>4</i><i>、</i><i>5</i><i>、</i><i>6</i>的朋友。<br/>
　　第<i>3</i>组数据：每个人恰好和一个人有矛盾，因此可以邀请所有人。<br/>
　　第<i>4</i>组数据：最优方案是唯一的，即邀请编号为<i>1</i><i>、</i><i>2</i><i>、</i><i>4</i><i>、</i><i>5</i><i>、</i><i>6</i>的朋友。</div>
# 数据规模和约定

<div class="pdcont">　　设<i>M</i>表示<i>N</i>个人之间存在多少对矛盾关系。<br/>
　　对于<i>10%</i>的数据：<i>1 </i><i>≤</i><i> N </i><i>≤</i><i> 10</i><i>。</i><i></i><br/>
　　对于<i>30%</i>的数据：<i>1 </i><i>≤</i><i> N </i><i>≤</i><i> 20</i><i>。</i><i></i><br/>
　　对于<i>50%</i>的数据：<i>1 </i><i>≤</i><i> N </i><i>≤</i><i> 30</i><i>。</i><i></i><br/>
　　另有<i>10%</i>的数据：<i>N = 40</i><i>，</i><i>0 </i><i>≤</i><i> M </i><i>≤</i><i> 40</i><i>。</i><i></i><br/>
　　另有<i>10%</i>的数据：<i>N = 40</i><i>，</i><i>500 </i><i>≤</i><i> M </i><i>≤</i><i> 780</i><i>。</i><i></i><br/>
　　对于<i>100%</i>的数据：<i>1 ≤ N ≤ 40，0 ≤ M ≤ 780，1 ≤ T ≤ 50。</i></div>

</div>