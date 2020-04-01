
# Description

<div class="content"><div>　　排名系统通常要应付三种请求：上传一条新的得分记录、查询某个玩家的当前排名以及返回某个区段内的排名</div>
<div>记录。当某个玩家上传自己最新的得分记录时，他原有的得分记录会被删除。为了减轻服务器负担，在返回某个区</div>
<div>段内的排名记录时，最多返回10条记录。</div></div>

# Input

<div class="content"><p></p>
<div>　　第一行是一个整数n（n&gt;=10）表示请求总数目。接下来n行,每行包含了一个请求。请求的具体格式如下： +Na</div>
<div>me Score 上传最新得分记录。Name表示玩家名字，由大写英文字母组成，不超过10个字符。Score为最多8位的正</div>
<div>整数。 ?Name 查询玩家排名。该玩家的得分记录必定已经在前面上传。 ?Index 返回自第Index名开始的最多10名</div>
<div>玩家名字。Index必定合法，即不小于1，也不大于当前有记录的玩家总数。</div></div>

# Output

<div class="content"><div>　　对于?Name格式的请求，应输出一个整数表示该玩家当前的排名。对于?Index格式的请求，应在一行中依次输</div>
<div>出从第Index名开始的最多10名玩家姓名，用一个空格分隔。</div></div>

# Sample Input

<div class="content"><span class="sampledata">20<br/>
+ADAM 1000000     加入ADAM的得分记录<br/>
+BOB 1000000      加入BOB的得分记录<br/>
+TOM 2000000      加入TOM的得分记录<br/>
+CATHY 10000000   加入CATHY的得分记录<br/>
?TOM              输出TOM目前排名<br/>
?1                目前有记录的玩家总数为4，因此应输出第1名到第4名。<br/>
+DAM 100000       加入DAM的得分记录<br/>
+BOB 1200000      更新BOB的得分记录<br/>
+ADAM 900000      更新ADAM的得分记录（即使比原来的差）<br/>
+FRANK 12340000   加入FRANK的得分记录<br/>
+LEO 9000000      加入LEO的得分记录<br/>
+KAINE 9000000    加入KAINE的得分记录<br/>
+GRACE 8000000    加入GRACE的得分记录<br/>
+WALT 9000000     加入WALT的得分记录<br/>
+SANDY 8000000    加入SANDY的得分记录<br/>
+MICK 9000000     加入MICK的得分记录<br/>
+JACK 7320000     加入JACK的得分记录<br/>
?2                目前有记录的玩家总数为12，因此应输出第2名到第11名。<br/>
?5                输出第5名到第13名。<br/>
?KAINE            输出KAINE的排名</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
CATHY TOM ADAM BOB<br/>
CATHY LEO KAINE WALT MICK GRACE SANDY JACK TOM BOB<br/>
WALT MICK GRACE SANDY JACK TOM BOB ADAM DAM<br/>
4<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N&lt;=250000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

