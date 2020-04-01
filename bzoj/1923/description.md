
# Description

<div class="content"><img border="0" src="/source/bzoj/1923/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MjMuanBn.jpg"/> </div>

# Input

<div class="content">第一行是两个正整数 N, M。 
接下来 M行，按顺序给出 Charles 这M次使用“点足机”的统计结果。每行
包含一个“01”串和一个数字，用一个空格隔开。“01”串按位依次表示每只虫
子是否被放入机器：如果第 i 个字符是“0”则代表编号为 i 的虫子未被放入，“1”
则代表已被放入。后面跟的数字是统计的昆虫足数 mod 2 的结果。 
由于 NASA的实验机器精确无误，保证前后数据不会自相矛盾。即给定数据
一定有解。 
 </div>

# Output

<div class="content">在给定数据存在唯一解时有 N＋1行，第一行输出一个不
超过M的正整数K，表明在第K 次统计结束后就可以确定唯一解；接下来 N 行
依次回答每只千足虫的身份，若是奇数条足则输出“?y7M#”（火星文），偶数
条足输出“Earth”。如果输入数据存在多解，输出“Cannot Determine”。 
所有输出均不含引号，输出时请注意大小写。 
 </div>

# Sample Input

<div class="content"><span class="sampledata">3 5 <br/>
011 1 <br/>
110 1 <br/>
101 0 <br/>
111 1 <br/>
010 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
Earth <br/>
?y7M# <br/>
Earth </span></div>

# Hint

<div class="content"><p>对于 20%的数据，满足 N＝M≤20； <br/>
对于 40%的数据，满足 N＝M≤500； <br/>
对于 70%的数据，满足 N≤500，M≤1,000； <br/>
对于 100%的数据，满足 N≤1,000，M≤2,000。 <br/>
<br/>
==========================================================<br/>
请不要提交!</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮Day1">第一轮Day1</a></p></div>

