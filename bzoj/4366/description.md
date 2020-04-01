
# Description

<div class="content"><p>我们建立了一个由编号为0, ... ,n-1的n个人组成的社交网络。网络中的有些对会成为朋友。如果X号人成为Y号人的朋友，则Y号人同时也会成为X号人的朋友。<br/>
这些人将通过n个阶段加入这个网络，阶段也编号为0至n-1。第i号人在第i个阶段加入。在阶段0，0号人加入网络并成为唯一的人。此后n-1个阶段的各个阶段，都有一个人会被主持人加入到网络中，而这个主持人可以是已在网络中的任何一个人。在阶段i中 (0&lt;i&lt;n)，该阶段的主持人可以用如下三种方式之一把第 号人加入到网络中：<br/>
1.IAmYourFriend 将第i号人仅变成主持人的朋友。<br/>
2.MyFriendsAreYourFriends 将第i号人变成主持人当前的每一个朋友的朋友。 注意，这个方式不会将第i号人变成主持人的朋友。<br/>
3.WeAreYourFriends 将第i号人变成主持人的朋友，同时也变成主持人当前的 每一个朋友的朋友。<br/>
在建立此网络之后，我们想挑选一个调查的样本，也就是说要从网络中选择一组人。由于朋友之间通常拥有相似的兴趣，因此样本不应包含任何一对互为朋友的人。每个人都会有一个调查的可信度，表示为一个正整数，而我们想要找出一个可信度总和最大的样本。</p></div>

# Input

<div class="content"><p>第 1 行: n<br/>
第 2 行: confidence[0], ..., confidence[n-1]<br/>
第 3 行: host[1], protocol[1], host[2], protocol[2], ..., host[n-1], protocol[n-1]<br/>
n: 人数.<br/>
confidence: 大小为n的数组；confidence[i]表示第i号人的可信度。<br/>
host: 大小为n的数组；host[i] 表示阶段i的主持人。<br/>
protocol:  大小为n的数组；protocol[i] 表示在阶段i(0&lt;i&lt;n)所采用的方式的代码: 0 代表 IAmYourFriend, 1  代表 MyFriendsAreYourFriends, 而 2 代表WeAreYourFiends。</p></div>

# Output

<div class="content"><p>输出一个整数表示样本可信度总和的最大值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
13 3 6 20 10 15<br/>
0 0 0 1 1 2 2 1 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">35</span></div>

# Hint

<div class="content"><p></p><p><img width="566" height="577" alt="" src="/source/bzoj/4366/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMi9iYi5naWY=.gif"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yts1999上传">鸣谢yts1999上传</a></p></div>

