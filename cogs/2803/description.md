# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
    crb下象棋下得很好，整天在qm面前装b，qm很生气，于是qm让叁帮忙整crb，叁表示出几道题让他做好了，于是qm出了三道题。但是qm表示要难一点，于是把三道题合成一道，但是qm说太难了不好，于是时限加了0.1s。
</p>
<p>
   鉴于crb象棋中玩马玩得好，为了好好打他脸，现在给出一个棋盘，左上(0，0)，右下角(n,m)给出以下询问：
</p>
<p>
   1.使每个马都不能攻击其他马，最多放多少马；
</p>
<p>
   2.每行放一个马，使马互不攻击，有几种情况；
</p>
<p>
   3.每行放k个马，使马互不攻击，能否成立，能输出1，不能输出0。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
    有多组数据，每组数据格式如下：
</p>
<p>
    第一行，n，m，q；
</p>
<p>
    后q行，每行一个询问：a
</p>
<p>
    a==1时输出使每个马都不能攻击其他马，最多放多少马;
</p>
<p>
    a==2时输出每行放一个马，使马互不攻击，有几种情况;
</p>
<p>
    a==3时有一个k,输出每行放k个马，使马互不攻击，能否成立，能输出1，不能输出0；
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
    见输入（每次询问答案占一行,行后有回车）
</p>
<h3>
【样例输入】
</h3>
<pre><p>
1 1 1
</p>

<p>
3 1
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>1</pre>
<h3>
【提示】
</h3>
<p>
马行动遵循中国象棋规则
</p>
<p>
最后5%的数据n=10，m=10；
</p>
<p>
对于100%的数据 0&lt;=n,m&lt;=5000;0&lt;p&lt;=5;
</p>
<h3>
【来源】
</h3>
<p>
机房一
</p>
