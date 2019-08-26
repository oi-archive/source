
# Description

<div class="content"><div>X是T大的一名老师，每年他都要教授许多学生基础的C++知识。在T大，每个学生在每学期的开学前都需要选课，每</div>
<div>次选课一共分为三个阶段：预选，正选，补退选；其中&#34;补退选&#34;阶段最忙碌。在补退选阶段，学生即可以选课，也</div>
<div>可以退课。对于X老师来说，在补退选阶段可能发生以下两种事件：</div>
<div>1:一个姓名为S的学生选了他的课（姓名S将出现在X的已选课学生名单中）</div>
<div>2:一个姓名为S的学生退了他的课（姓名S将从X的已选课学生名单中移除）</div>
<div>同时，X老师对于有哪些学生选了他的课非常关心，所以他会不定时的查询已选课学生名单，每次查询的格式如下</div>
<div>：最早在哪个事件之后，姓名以S为前缀的学生数量超过了vX老师看你骨骼惊奇，所以想用这个问题考考你，你当</div>
<div>然不会畏惧，所以勇敢的接下了这个任务。</div>
<div>注意1：学生的姓名可能相同，如果有p个姓名相同的学生都选了X老师的课，则他们的姓名将出现在X老师的名单上p次。</div>
<div>注意2：只有已经选了课的学生才会退课，如果姓名为S的学生退课，则在他退课之前X老师的名单上一定有姓名S。</div>
<div>注意3：选课，退课和查询都被定义为&#34;事件&#34;，&#34;事件&#34;的编号从1开始</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个正整数n，表示一共发生了n个事件。</div>
<div>接下来n行，每行描述一个事件；每行第一个正整数k表示事件类型：</div>
<div>1.如果k=1，表示选课事件，接下来一个字符串S，表示一个姓名为S的学生选了X老师的课</div>
<div>2.如果k=2，表示退课事件，接下来一个字符串S，表示一个姓名为S的学生退了X老师的课</div>
<div>3.如果k=3，表示查询事件，接下来一个字符串S以及三个非负整数a,b,c，表示X老师想知道最早在第几个事件之后</div>
<div>，姓名以S为前缀的学生数量超过了(a*|ANS|+b)%c，|ANS|表示上次查询事件的答案的绝对值，如果当前是第一次</div>
<div>查询，则|ANS|=0；如果任何时刻都没有超过该值，则答案为-1。注：输入中的所有字符串均只包含小写字母。</div>
</div>
<div></div></div>

# Output

<div class="content"><div>
<div>对于每个查询事件，输出一行表示该查询答案。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 lcaq<br/>
3 lca 0 0 5<br/>
1 lcq<br/>
3 lc 0 1 5<br/>
2 lcaq<br/>
3 lc 0 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
3</span></div>

# Hint

<div class="content"><p></p><p>n&lt;=100000，字符串长度 &lt;= 60，输入中的所有字符串只会包含前 10 个小写字母</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Sengxian上传">鸣谢Sengxian上传</a></p></div>

