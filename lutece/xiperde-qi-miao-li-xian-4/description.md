
# Content

在岳老师的教导之下， $Xiper$ 进步神速，很快就成为了一名熟练的白膜法师。

同时，潘警官与上司交易，拿到了 $Xiper$ 祖传豪宅的保险，凑齐了去咸鱼镇拯救世界的路费。

由于经费不足，$Xiper$ 只身和带路的潘警官前往咸鱼镇，与日天决一死战。

临走前，$Xiper$与卿学姐依依惜别，并发誓打败周日天后，就和学姐回喵哈哈村结婚。

很快， $Xiper$ 就到达了咸鱼镇。得知这一消息的日天开始慌了，他深知自己的身体还没恢复，不是 $Xiper$ 的对手。日天连忙让自己的咸鱼部队出动，妄图阻止 $Xiper$ 。

日天的咸鱼战士由 $N$ 个人组成，其中其中有 $M$ 对战士通过的神奇的咸鱼电波联系在一起。每次 $Xiper$ 可以对一个咸鱼战士使用膜法，让这个咸鱼战士与和他相关的战士断开连接，失去战斗力。

$Xiper$ 和咸鱼部队陷入了苦战。但是在一旁吃瓜的潘警官发现，对于已经断开的链接，如果对断开的一方再次释放膜法，那么链接就会重新生效！也就是说，如果 $A$ 和 $B$ 存在联系，但 $Xiper$ 对 $A$ 和 $B$ 都释放了一次膜法的话，那两个人仍旧会保持链接！而只有把所有咸鱼战士之间的联系切断，才能彻底打败日天的咸鱼部队。

潘警官赶忙把这个消息告诉了$Xiper$。$Xiper$ 仔细一想，很快就看出来如何最快地打败日天的咸鱼部队。日天看到咸鱼部队被击败，只好掏出光剑，亲自出马。

然而成为大膜法师 $Xiper$，竟然幻化出来两把光剑！

![title](/source/lutece/xiperde-qi-miao-li-xian-4/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM4Mi8yMDE2MDUwOTE3MjYyMDk2MzM3LmpwZw==.jpg)

很快，$Xiper$打败了日天。$Xiper$抱住已经断气的日天，流下了泪水，因为他的青春，是和日天在一起的青春啊！

回到了喵哈哈村的$Xiper$，与卿学姐举办了盛大的婚礼。从此，两人过上了幸福而平静的生活。而咸鱼王的传说，也暂时告一段落...

（潘警官：道理我都懂，但是为什么我没有女朋友呢？）

多年之后，潘警官对路过的你讲述了这段故事，但是他忘了$Xiper$当时是怎么打败咸鱼部队的。现在他告诉你咸鱼部队的人数$N$和$M$对关系，和哪些关系已经被$Xiper$断开，问你$Xiper$当时用了多少次膜法？

# Standard Input

第一行两个数$N，M(2 <= N <= 50000， 1 <= M <= 200000)$，代表人数和关系数量。
接下来M行，每行三个数$ai，bi，si$，表示ai和bi之间存在连接，$s = 0$表示链接已被断开，$s = 1$表示没有被断开。
保证没有重复的关系，且对于每个人，都存在另外一个人与之相连。

# Standard Output

输出一个数$Cnt$，表示最小的次数。如果无解，输出"Pan must forget something."

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2 1
1 2 1</td><td>1</td></tr><tr><td>4 6
1 2 1
1 3 1
1 4 1
2 3 1
2 4 1
3 4 1
</td><td>Pan must forget something.</td></tr><tr><td>4 3
1 2 1
2 3 1
3 4 0</td><td>1</td></tr></table>


# Constraints



# Note



# Source


