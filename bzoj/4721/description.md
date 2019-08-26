
# Description

<div class="content"><div>本题中，我们将用符号[c]表示对c向下取整，例如：[3.0」= [3.1」=[3.9」=3。蛐蛐国最近蚯蚓成灾了！隔壁跳</div>
<div>蚤国的跳蚤也拿蚯蚓们没办法，蛐蛐国王只好去请神刀手来帮他们消灭蚯蚓。蛐蛐国里现在共有n只蚯蚓（n为正整</div>
<div>数)。每只蚯蚓拥有长度，我们设第i只蚯蚓的长度为a_i(i=1,2,...,n)，并保证所有的长度都是非负整数（即:可</div>
<div>能存在长度为0的蚯蚓）。每一秒，神刀手会在所有的蚯蚓中，准确地找到最长的那一只（如有多个则任选一个）</div>
<div>将其切成两半。神刀手切开蚯蚓的位置由常数p(是满足0&lt;p&lt;1的有理数)决定，设这只蚯蚓长度为x，神刀手会将其</div>
<div>切成两只长度分别为[px]和x-[px]的蚯蚓。特殊地，如果这两个数的其中一个等于0，则这个长度为0的蚯蚓也会被</div>
<div>保留。此外，除了刚刚产生的两只新蚯蚓，其余蚯蚓的长度都会增加q(是一个非负整常数)。蛐蛐国王知道这样不</div>
<div>是长久之计，因为蚯蚓不仅会越来越多，还会越来越长。蛐蛐国王决定求助于一位有着洪荒之力的神秘人物，但是</div>
<div>救兵还需要m秒才能到来......(m为非负整数）蛐蛐国王希望知道这m秒内的战况。具体来说，他希望知道：?m秒内</div>
<div>，每一秒被切断的蚯蚓被切断前的长度（有m个数）?m秒后，所有蚯蚓的长度（有n+m个数)。蛐蛐国王当然知道怎</div>
<div>么做啦！但是他想考考你......</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含六个整数n,m,q,u,v,t，其中：n,m,q的意义见问题描述；</div>
<div>u,v,t均为正整数；你需要自己计算p=u/v(保证0&lt;u&lt;v)t是输出参数，其含义将会在输出格式中解释。</div>
<div>第二行包含n个非负整数，为ai,a2,...,an，即初始时n只蚯蚓的长度。</div>
<div>同一行中相邻的两个数之间，恰好用一个空格隔开。</div>
<div>保证1&lt;=n&lt;=10^5，0&lt;m&lt;7*10^6，0&lt;u&lt;v&lt;10^9，0&lt;=q&lt;=200，1&lt;t&lt;71，0&lt;ai&lt;10^8。</div>
<div></div></div>

# Output

<div class="content"><div>第一行输出[m/t]个整数，按时间顺序，依次输出第t秒，第2t秒，第3t秒……被切断蚯蚓（在被切断前）的长度。</div>
<div>第二行输出[(n+m)/t]个整数，输出m秒后蚯蚓的长度；需要按从大到小的顺序</div>
<div>依次输出排名第t，第2t，第3t……的长度。</div>
<div>同一行中相邻的两个数之间，恰好用一个空格隔开。即使某一行没有任何数需要 输出，你也应输出一个空行。</div>
<div>请阅读样例来更好地理解这个格式。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 7 1 1 3 1<br/>
3 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 4 4 4 5 5 6<br/>
6 6 6 5 5 4 4 3 2 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

