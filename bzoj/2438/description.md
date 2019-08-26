
# Description

<div class="content"><div>一位冷血的杀手潜入 Na-wiat，并假装成平民。警察希望能在 N 个人里面，查出谁是杀手。警察能够对每一个人</div>
<div>进行查证，假如查证的对象是平民，他会告诉警察，他认识的人， 谁是杀手， 谁是平民。 假如查证的对象是杀</div>
<div>手， 杀手将会把警察干掉。现在警察掌握了每一个人认识谁。每一个人都有可能是杀手，可看作他们是杀手的概</div>
<div>率是相同的。问：根据最优的情况，保证警察自身安全并知道谁是杀手的概率最大是多少？</div></div>

# Input

<div class="content"><p>第一行有两个整数 N,M。 <br/>
接下来有 M 行，每行两个整数 x,y，表示 x 认识 y（y 不一定认识 x,例如胡锦涛同志） 。</p></div>

# Output

<div class="content"><p>仅包含一行一个实数，保留小数点后面 6 位，表示最大概率。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 <br/>
1 2 <br/>
1 3 <br/>
1 4 <br/>
1 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">0.800000 </span></div>

# Hint

<div class="content"><p></p><p>警察只需要查证 1。假如1是杀手，警察就会被杀。假如 1不是杀手，他会告诉警<br/><br/>
察 2,3,4,5 谁是杀手。而 1 是杀手的概率是 0.2,所以能知道谁是杀手但没被杀的概<br/><br/>
率是0.8。对于 100%的数据有 1≤N ≤  10 0000,0≤M ≤  30 0000</p><br/>
<p>数据已加强！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

