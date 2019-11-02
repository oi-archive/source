<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>"找啊找啊找GF,找到一个好GF,吃顿饭啊拉拉手,你是我的好GF.再见."<br>"诶,别再见啊..."<br>七夕...七夕...七夕这个日子,对于sqybi这种单身的菜鸟来说是多么的痛苦...虽然他听着这首叫做"找啊找啊找GF"的歌,他还是很痛苦.为了避免这种痛苦,sqybi决定要给自己找点事情干.他去找到了七夕模拟赛的负责人zmc MM,让她给自己一个出题的任务.经过几天的死缠烂打,zmc MM终于同意了.<br>但是,拿到这个任务的sqybi发现,原来出题比单身更让人感到无聊-_-....所以,他决定了,要在出题的同时去办另一件能够使自己不无聊的事情--给自己找GF.<br>sqybi现在看中了n个MM,我们不妨把她们编号1到n.请MM吃饭是要花钱的,我们假设请i号MM吃饭要花rmb[i]块大洋.而希望骗MM当自己GF是要费人品的,我们假设请第i号MM吃饭试图让她当自己GF的行为(不妨称作泡该MM)要耗费rp[i]的人品.而对于每一个MM来说,sqybi都有一个对应的搞定她的时间,对于第i个MM来说叫做time[i]. sqybi保证自己有足够的魅力用time[i]的时间搞定第i个MM^_^.<br>sqybi希望搞到尽量多的MM当自己的GF,这点是毋庸置疑的.但他不希望为此花费太多的时间(毕竟七夕赛的题目还没出),所以他希望在保证搞到MM数量最多的情况下花费的总时间最少.<br>sqybi现在有m块大洋,他也通过一段时间的努力攒到了r的人品(这次为模拟赛出题也攒rp哦~~).他凭借这些大洋和人品可以泡到一些MM.他想知道,自己泡到最多的MM花费的最少时间是多少.<br>注意sqybi在一个时刻只能去泡一个MM--如果同时泡两个或以上的MM的话,她们会打起来的...</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是n,表示sqybi看中的MM数量.接下来有n行,依次表示编号为1, 2, 3, ..., n的一个MM的信息.每行表示一个MM的信息,有三个整数:rmb, rp和time.最后一行有两个整数,分别为m和r.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你只需要输出一行,其中有一个整数,表示sqybi在保证MM数量的情况下花费的最少总时间是多少.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>1 2 5<br>2 1 6<br>2 2 2<br>2 2 3<br>5 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据规模<br>对于20%数据,1&lt;=n&lt;=10;<br>对于100%数据,1&lt;=rmb&lt;=100,1&lt;=rp&lt;=100,1&lt;=time&lt;=1000;<br>对于100%数据,1&lt;=m&lt;=100,1&lt;=r&lt;=100,1&lt;=n&lt;=100.</p>
</div>
</div>