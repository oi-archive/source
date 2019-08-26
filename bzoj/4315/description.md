
# Description

<div class="content"><div>自从小C接过宇宙大总统的职位后，为了巩固自己的统治，他决定给全宇宙的精英排个队，这样，下次聚集精英们的时候，不至于乱成一锅粥。</div>
<div>当然，精英们可是非常挑剔的，它们对于排队可有很苛刻的要求。</div>
<div>为了方便描述，n个精英，被编号1~n。排完队之后，每个精英要求，自己的后面（不必是严格后面）都必须有一个人的编号和自己的编号相差为1（+1或-1）；</div>
<div>而且，有很多特别霸气的精英，比如Mars之类的人，他们认为自己只能站在队伍的某个位置，小C必须满足他们的需求。</div>
<div>小C想知道，存在多少方案满足精英们如此苛刻的条件。</div>
<p></p></div>

# Input

<div class="content"><div>第一行： 两个正整数n， k，表示有n个精英，k个人强制要求自己的位置。</div>
<div>第2~k+1行，两个整数a，b，表示编号为a的精英要求自己站在队伍的第b个位置；</div>
<p></p></div>

# Output

<div class="content"><div> 一个整数，输出方案， 答案对10^9+7 取模</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
1 1<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例解释】</div><br/>
<div>两种方案为：</div><br/>
<div>1 5 2 3 4</div><br/>
<div>1 5 2 4 3 </div><br/>
<div>最后一个人由于后面没有人，所以不要求后面有人和他编号相差为1</div><br/>
<div>强行要求位置的人，他的后面也必须有人和他编号相差为1（除非他是最后一个）</div><br/>
<div>【数据约定】</div><br/>
<div> 100% n &lt;= 100000， k&lt;=n;</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

