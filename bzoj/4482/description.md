
# Description

<div class="content"><div>【故事背景】</div>
<div>刚从俄罗斯旅游回来的JYY买了很多很多好看的套娃作为纪念品！比如右</div>
<div>图就是一套他最喜欢的套娃J。JYY由于太过激动，把所有的套娃全</div>
<div>部都打开了。而由于很多套娃长得过于相像，JYY现在不知道该如何把它们装</div>
<div>回去了（他实在搞不清，应该把哪个套娃装到哪个里面去了）。</div>
<div>JYY一共有N个拆开的套娃，每个套娃从1到N编号。编号为i的套娃有一个外径Outi和一个内径Ini（Ini&lt;Outi）。</div>
<div>对于套娃i和套娃j，如果满足Outi&lt;INj，那么套娃i就可以装到套娃j里面去。</div>
<div>注意，一个套娃内部，不允许并排的放入多个套娃。</div>
<div>也就是说，如果我们将i装到j的内部之后，还存在另一个套娃k，也满足Outk&lt;Inj，我们此时是不允许再将k放</div>
<div>到j内部的（因为j的内部已经放入了i）。但是，如果k还满足Outk&lt;Ini，那么我们允许先将k放到i的内部，</div>
<div>然后再把k和i作为一个整体放入j的内部。</div>
<div>JYY认为一套好的套娃，内部的空隙一定是尽量少的。如果套娃j内部装入了套娃i，那么我们认为，套娃j内部</div>
<div>产生的空隙为Inj-Outi；如果套娃j的内部什么也没有装，那么套娃j的空隙则就是Inj。</div>
<div>JYY也希望，那些长得更加好看的套娃，里面可以填的尽量满一些；而相对</div>
<div>那些不那么好看的套娃，JYY也就相对不那么介意一些。为此JYY对于编号为</div>
<div>i的套娃设置了一个好看度Bi，如果这个套娃内部还存在K的空隙，那么JYY对</div>
<div>于这个套娃就会产生K*Bi的不满意度。</div>
<div>JYY对于一个套娃安装方案的不满意度，就是每个套娃产生的不满意度的总</div>
<div>和。JYY希望找出一个，不满意度最小的套娃安装方案。</div></div>

# Input

<div class="content"><p>第一行包含一个正整数N。接下来N行，每行包含三个正整数Outi,Ini,Bi，表示i号套娃的外径，内径，以及好看度。N&lt;=2∗10^5,1&lt;=Ini&lt;Outi&lt;=10^4,1&lt;=Bi&lt;=10^9</p></div>

# Output

<div class="content"><p>输出文件包含一行一个整数，表示不满意度的最小值</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
5 4 1<br/>
4 2 2<br/>
3 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

