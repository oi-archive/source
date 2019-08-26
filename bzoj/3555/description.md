
# Description

<div class="content"><p>PenguinQQ是中国最大、最具影响力的SNS（Social Networking Services）网站，以实名制为基础，为用户提供日志、群、即时通讯、相册、集市等丰富强大的互联网功能体验，满足用户对社交、资讯、娱乐、交易等多方面的需求。<br/>
小Q是PenguinQQ网站的管理员，他最近在进行一项有趣的研究——哪些账户是同一个人注册的。经过长时间的分析，小Q发现同一个人注册的账户名称总是很相似的，例如Penguin1，Penguin2，Penguin3……于是小Q决定先对这种相似的情形进行统计。<br/>
小Q定义，若两个账户名称是相似的，当且仅当这两个字符串等长且恰好只有一位不同。例如“Penguin1”和“Penguin2”是相似的，但“Penguin1”和“2Penguin”不是相似的。而小Q想知道，在给定的 个账户名称中，有多少对是相似的。<br/>
为了简化你的工作，小Q给你的 个字符串长度均等于 ，且只包含大小写字母、数字、下划线以及<a href="mailto:‘@’">‘@’</a>共64种字符，而且不存在两个相同的账户名称。</p></div>

# Input

<div class="content"><p>第一行包含三个正整数 ， ， 。其中 表示账户名称数量， 表示账户名称长度， 用来表示字符集规模大小，它的值只可能为2或64。<br/>
若 等于2，账户名称中只包含字符‘0’和‘1’共2种字符；<br/>
若 等于64，账户名称中可能包含大小写字母、数字、下划线以及<a href="mailto:‘@’">‘@’</a>共64种字符。<br/>
随后 行，每行一个长度为 的字符串，用来描述一个账户名称。数据保证 个字符串是两两不同的。</p></div>

# Output

<div class="content"><p>仅一行一个正整数，表示共有多少对相似的账户名称。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 64<br/>
Fax<br/>
fax<br/>
max<br/>
mac</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>4对相似的字符串分别为：Fax与fax，Fax与max，fax与max，max与mac。N&lt;=30000,L&lt;=200,S&lt;=64<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

