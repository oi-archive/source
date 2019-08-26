
# Description

<div class="content">背景：
gaoxin神犇在夺得了IOI2011金牌之后，根据惯例要进行获奖感言的发表。
gaoxin神犇深知社会主义的五大优越性和一切帝国主义都是纸老虎，下面
截取他的发言：
我是来自由伟大，光荣，正确的xx领导的走在伟大，光荣，正确的中国特色xx主义道路上的
新中国的gaoxin，感谢伟大，光荣，正确的xx给我这次机会参加IOI。。。。。
题目描述：
gaoxin神犇频繁的在发言中表现对伟大，光荣，正确的xx的热爱，我们可以做如下定义：
A=伟大，光荣，正确的
B=xx
C=引领我们向前
赞美祖国=ABC
拼命赞美祖国=赞美祖国*10
gaoxin的发言=拼命赞美祖国*100
显然这个定义必须是无环的。
WJMZBMR感到十分的有压力，
他好不容易数出了某个字串的出现次数。。。
某天他打开电视，发现某人的发言有同样的结构。。他很无语。。。想知道某些字串出现的次数。。
你能帮帮他吗？
//----分割----//
一些定义：
为了简化期间，在输入中用英文表示。。
字符串：由小写字母组成如a
字串名：一定是大写字母如A
那么上面的系统可以写成
A=greatglorycorrect
B=xx
C=leadusgo
D=ABC
E=DDDDdjh
F=EEEEEgoodbye
同时存在一个母字串名，他就是某人的发言
</div>

# Input

<div class="content">第一行一个数N表示字串名的数量。
第二行一个字符F表示某人的发言的字串名。
接下来N行，每行一个描述
一个描述的左端是一个大写字母表示字串名，
然后一个等号
右端由一系列大写或小写字母组成。。表示该字串的内容。
最后一行是一个字符串，表示WJMZBMR想知道出现了几次的字符串
</div>

# Output

<div class="content">一行，表示次数（跟10000取余）
</div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
F<br/>
A=greatglorycorrect<br/>
B=xx<br/>
C=leadusgo<br/>
D=ABC<br/>
E=DDDDdjh<br/>
F=EEEEEgoodbye<br/>
g<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">61<br/>
数据范围：<br/>
对于100%的数据<br/>
N&lt;=26 每条描述长度&lt;=100<br/>
最后一行的字符串长度&lt;=100<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=和谐社会模拟赛">和谐社会模拟赛</a></p></div>

