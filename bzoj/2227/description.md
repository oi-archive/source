
# Description

<div class="content"><p>到了难得的假期，小白班上组织大家去看电影。但由于假期里看电影的人太多，很难做到让全班看上同一场电影，最后大家在一个偏僻的小胡同里找到了一家电影院。但这家电影院分配座位的方式很特殊，具体方式如下： 1. 电影院的座位共有K个，并被标号为1…K，每个人买完票后会被随机指定一个座位，具体来说是从1…K中等可能的随机选取一个正整数，设其为L。 2. 如果编号L的座位是空位，则这个座位就分配给此人，否则将L加一，继续前面的步骤。 3. 如果在第二步中不存在编号L的座位，则该人只能站着看电影，即所谓的站票。小白班上共有N人（包括小白自己），作为数学爱好者，小白想知道全班都能够有座位的概率是多少。</p></div>

# Input

<div class="content"><p>输入文件第一行有且只有一个正整数T，表示测试数据的组数。 第2～T+1行，每行两个正整数N,K，用单个空格隔开，其含义同题目描述。</p></div>

# Output

<div class="content"><p>输出文件共包含T行。第i行应包含两个用空格隔开的整数A,B，表示输入文件中的第i组数据的答案为A/B。（注意，这里要求将答案化为既约分数）</p></div>

# Sample Input

<div class="content"><span class="sampledata">      3<br/>
     1 1<br/>
     2 1<br/>
     2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1<br/>
     0 1<br/>
     3 4<br/>
<br/>
【数据范围】<br/>
对于100%的数据  T&lt;=50,N,K&lt;=200<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1&amp;IPSC2009第G题">Day1&amp;IPSC2009第G题</a></p></div>

