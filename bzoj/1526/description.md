
# Description

<div class="content">BBB ( Byteotian Bit Bank的简称) 拥有一个非常巨大的现金分配系统. 他们的客户端使用现金卡和一个4位的PIN code来提取现金. 最近为了提升客户端的安全性, BBB为每台客户端都配置了一台摄象机. 不幸的是一个计算机盗窃团伙拦截了摄象机信号,团伙试图猜出4位的PIN codes.意识到这个问题以后, BBB 的客户端在用户输入PIN时加入了一些多余动作. 摄象机不能拍下用户按了什么键,它只能记录用户手指的移动. 因此通常不可能很清楚的知道用户到底按了哪些键. 举个例子,假如用户的手指移动到&#34;1&#34; 后又移动到了&#34;5&#34; ,那么他可能输入以下 codes: 1111, 1115, 1155, 1555, 5555. 绝望的盗贼收集了所有的摄象机录象,他们想知道一共有多少种可能的输入方案. 
</div>

# Input

<div class="content">第一行一个数n 表示录象的个数, 1 &lt;=n &lt;= 1000. 接下来n 行每行描述一个录象. 每一行第一个数t, 表示移动序列的元素个数, 1 &lt;= t &lt;= 10,000. 然后接下来t位的序列表示录象记录的移动.所有t的和不超过 1,000,000. 
</div>

# Output

<div class="content">输出一个数,表示所有可能的方案. 
</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 123<br/>
3 234<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

