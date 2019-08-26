
# Description

<div class="content"><p>澳洲猴举办了一场宴会，他想要邀请A个男生和B个女生参加，这A个男生从1到A编号，女生也从1到B编号。<br/>
现在澳洲猴知道n组朋友关系，这n组朋友关系是这样描述的：男生中编号为Pi到Qi的和女生中编号为Si到Ei的是好朋友，这也就是说(Qi-Pi+1)个男生之间互相是好朋♂友，(Si-Ei+1)个女生之间互相是好朋♂友，(Qi-Pi+1)个男生和(Si-Ei+1)个女生之间互相也是好朋友，总之他们互相是好友关系，并且互相的友好指数为Ti。<br/>
现在，澳洲猴只认识一个非常要好的男生C，接着他要进行一系列邀请，使得所有的人都参加这次宴会，邀请的过程是这样的：<br/>
选出现有集合中的一个人u（初始时只有C），然后利用这个人u的某个朋友关系i，邀请另一个不在现有集合中的人v进入现有集合，整个集合的幸福值增加Ti。重复直到所有人都进入现有集合，如果不存在将所有人全部邀请的方案，输出-1。<br/>
</p></div>

# Input

<div class="content"><p>输入的第一行为A,B,C三个正整数。<br/>
接下来是n。<br/>
然后n行，每行5个正整数，Pi,Qi,Si,Ei,Ti，描述一组朋♂友关系。</p></div>

# Output

<div class="content"><p>输出一行，最大的幸福指数。如果不存在全部邀请的方案，输出-1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 3 <br/>
4 <br/>
2 4 1 3 20 <br/>
1 2 2 4 40 <br/>
4 5 2 3 30 <br/>
4 4 4 6 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">280<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例1解释：<br/><br/>
男3-&gt;男2 +20；<br/><br/>
男2-&gt;男1 +40；<br/><br/>
男2-&gt;女1 +20；<br/><br/>
男2-&gt;女2 +40；<br/><br/>
男2-&gt;女3 +40；<br/><br/>
女2-&gt;女4 +40；<br/><br/>
女3-&gt;男4 +30；<br/><br/>
女3-&gt;男5 +30；<br/><br/>
男4-&gt;女5 +10；<br/><br/>
男4-&gt;女6 +10；<br/><br/>
对于100%的数据 n&lt;=100000,1&lt;=A,B,Ti&lt;=1e9,Pi&lt;=Qi&lt;=A,Si&lt;=Ei&lt;=B,C&lt;=A。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

