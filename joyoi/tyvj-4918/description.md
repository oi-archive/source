# 

 
 # 题目背景 
<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">（本题纯属作者原创，难度约为NOIP联赛普及组第四题，适合即将参加NOIP的选手们练练手）</p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">（P.S.因作者水平有限，题目可能会有小bug，请多多谅解）</p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">话说又到了一个阳光明媚的周末，clz本想约上他的好朋友zql和wlf出去放风筝的，可此时此刻他却还在为一大堆没有完成的作业发愁。clz那惨无人道的语文老师给他布置了好多好多抄写的作业，总共有n项（n不超过10000），每项作业都要抄写a[i]个字<span style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">（1</span><span style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">&le;a[i]</span><span style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">&le;10^6</span><span style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">）。clz想：这么多作业，要什么时候才能写完啊？？！！完了完了，写不完作业，要被老师骂的&hellip;&hellip;呜呜呜&hellip;&hellip;clz正伤心的时候，他的好朋友zql找到了他，告诉他：&ldquo;不要担心，我有妙招！&rdquo;&ldquo;真的？什么妙招？&rdquo;clz好奇地问。</span></p>

<p style="color: rgb(0, 0, 0); font-family: &quot;Microsoft YaHei UI&quot;, &quot;Microsoft YaHei&quot;, &quot;Segou UI&quot;; font-size: 14px;">&nbsp;</p> 

 
 # 题目描述 
<p>原来zql从神仙爷爷那里借来了一根魔法棒，这根魔法棒可以帮clz完成任意m项作业，只不过有一个奇怪的要求：clz必须先将所有n项作业依次排在一条直线上，魔法棒可以帮clz任意完成其中m项作业，但这m项作业中的任意两项不能隔得太近，如果太近了，魔法棒就会失效。clz当然希望魔法棒能帮他完成字数尽量多的作业，那样他就可以只做很少一部分作业了，嘿嘿&hellip;&hellip;于是clz找到了你，想请你帮忙算算clz最少总共要写多少字的作业。</p> 

 
 # 输入格式 
<p>输入共两行：第一行，包括三个整数n,m,k，表示从n项作业中取出m项作业由魔法棒代clz完成，其中任意两项间的距离要大于等于k，当然余下的(n-m)项作业就得clz自己完成了喽；</p>

<p>第二行，有n个正整数，分别表示每项作业的字数。</p> 

 
 # 输出格式 
<p>输出只有一个整数x，表示clz最少只需写x个字的作业。</p> 

 
 # 提示 
<p>【输入样例】</p>

<pre class="content" style="box-sizing: inherit; overflow: auto; font-family: monospace, monospace; font-size: 14px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; word-break: break-all; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">
<span class="sampledata" style="box-sizing: inherit;">4&nbsp;2&nbsp;2
3&nbsp;4&nbsp;5&nbsp;1</span></pre>

<p><span class="sampledata" style="box-sizing: inherit;">【输出样例】</span></p>

<pre class="content" style="box-sizing: inherit; overflow: auto; font-family: monospace, monospace; font-size: 14px; padding: 9.5px; margin-top: 0px; margin-bottom: 10px; line-height: 1.42857; word-break: break-all; background-color: rgb(245, 245, 245); border: 1px solid rgb(204, 204, 204); border-radius: 4px;">
<span class="sampledata" style="box-sizing: inherit;">5</span></pre>

<p>&nbsp;</p>

<p><span class="sampledata" style="box-sizing: inherit;">【数据范围】</span></p>

<p><span class="sampledata" style="box-sizing: inherit;">100%的数据，1</span>&le;m,k&le;n&le;10000,<span class="sampledata" style="box-sizing: inherit;">1</span>&le;a[i]&le;10^6</p> 
