<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       楚楚每一次都在你的帮助下过了一关又一关(比如他开宴会)。这一次，你的才华让楚楚被劫住了！(好心办了坏事啊，下次不理他了=_=)</p>
<p>       歹徒： hehe~</p>
<p>       楚楚：(冷汗ing)干啥^_^！(PS：现在还笑得出来！！！)</p>
<p>       歹徒：抢劫的说~</p>
<p>       楚楚：你们想干啥！！(PS：不是告诉你了，是抢劫~)</p>
<p>       歹徒：这里是银行的陷阱,也就是一个迷宫……你要带我们离开这里……否则……</p>
<p>       楚楚：(想：那你是咋抓到我的，郁闷)好吧……</p>
<p>       楚楚认为生命还是最重要的……(大不了出去以后找警察……)</p>
<p>       于是，他认命了……</p>
<p>       他从歹徒口中得知这是一个方形的迷宫(歹徒老大：你还要啥形状的，跟我说一声！)，他们的位置是[1,1]，要走到[n,m],长是n，宽是m，这是一个很大的迷宫，里面有陷阱(小明：能不能踩进去的，说！楚楚：当然不能，不过可以用轻功，多花一秒蓄力~用轻功走过的陷阱会石化，变成路，而且刚好走过~ 歹徒想：虾米轻功~明明是杀人利器~还好没和他打起来~)，还有墙(PS：说一声，墙不能穿过，虽有轻功，但是还是过不去墙，这个墙也是银行的秘密~即使你是神犇也不行哦~ 楚楚：又坑我~)。(小明：路呢？ 楚楚：废话，当然有，只不过这是银行机密，不能说！)</p>
<p>       楚楚想在最短时间里走出迷宫(小明：否则歹徒会发怒的，对不对？ 楚楚：废话！)，若是超过了歹徒老大的忍耐时间time，那就……</p>
<p>       (楚楚：小明……SOS，别忘了帮我报警！！ 传呼机：嘀，嘀，嘀…… 楚楚：咋么可以这样！可恶！)于是，他顺便还要去找电话报个警(报警不需要时间，打通即可。且电话机可能有多个，但也没有可能没有~)。</p>
<p>楚楚：我的预感告诉我，这个迷宫只能向右或下走~郁闷了~</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       第1行是n,m, time，三个整数。</p>
<p>       第2到n+1行每行有m个字母(有大写也有小写的)(楚楚：歹徒真笨~，就不能翻译一下吗~)。</p>
<p>       字母解析：T(t)是陷阱，W(w)是墙，R(r)是路，A(a)是电话~ (遇到不认识的字符就~算之为路！)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;仅一行走出迷宫的最小时间t(走一步要一秒的说)，不能在规定时间走出迷宫，或者打不了电话，请输出&ldquo;Oh my god!&rdquo;(不包括引号)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 100</p>
<p>RRR</p>
<p>WWA</p>
<p>TRR</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>时间限制</strong><strong> Time Limitation</strong></p>
<p>各个测试点1s</p>
<p><strong>注释</strong><strong> Hint</strong><strong></strong></p>
<p>       10%的数据 n≤20,m≤20</p>
<p>100%的数据 n≤500,m≤500,time≤100000,不保证[1,1]或者[n,m]不是墙的说,且若[1,1]或者[n,m]不是路，那么就不能活着回去了……</p>
<p>数据解析：</p>
<p>由于楚楚一开始就站在1,1上，所以走这一块不用时间~</p>
</div>
</div>