# 题目描述


USACO/rockers(译 by Maigo Akisame)
<div>
<div>
<p>
Raucous Rockers“破锣摇滚”乐队
</p>
<hr/>
</div>
</div>
<p>
描述
</p>
<p>
你刚刚继承了流行的“破锣摇滚”乐队录制的尚未发表的N(1 &lt;= N &lt;= 20)首歌的版权。你打算从中精选一些歌曲，发行M(1 &lt;= M &lt;= 20)张CD。每一张CD最多可以容纳T(1 &lt;= T &lt;= 20)分钟的音乐，一首歌不能分装在两张CD中。
</p>
<p>
不巧你是一位古典音乐迷，不懂如何判定这些歌的艺术价值。于是你决定根据以下标准进行选择：
</p>
1.歌曲必须按照创作的时间顺序在CD盘上出现。 2.选中的歌曲数目尽可能地多。 3.不仅同光盘上的歌曲写入时间要按顺序，前一张光盘上的歌曲不能比后一张歌曲写入时间要晚。格式
<p>
PROGRAM NAME: rockers
</p>
<p>
INPUT FORMAT:
</p>
<p>
(file rockers.in)
</p>
<p>
第一行： 三个整数：N, T, M.
</p>
<p>
第二行： N个整数，分别表示每首歌的长度，按创作时间顺序排列。
</p>
<p>
OUTPUT FORMAT:
</p>
<p>
(file rockers.out)
</p>
<p>
一个整数，表示可以装进M张CD盘的乐曲的最大数目。
</p>
<p>
SAMPLE INPUT
</p>
<p>
4 5 2
</p>
<p>
4 3 4 2
</p>
<p>
SAMPLE OUTPUT
</p>
<p>
3<!-- NewPP limit report Preprocessor node count: 15/1000000 Post-expand include size: 0/2097152 bytes Template argument size: 0/2097152 bytes Expensive parser function count: 0/100 --><!-- Saved in parser cache with key newnocow:pcache:idhash:859-0!*!*!!zh-cn!*!* and timestamp 20120711023618 -->
</p>
