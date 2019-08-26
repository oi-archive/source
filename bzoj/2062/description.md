
# Description

<div class="content"><p>引子：     if I can see you again,will I have the feeling?       All the truly happiness sadness have been buried in yesterday.       No mix of performing ,how wonderful that days.       I&#39;ve missed it, why you&#39;ve missed it ? Missing cant bring you back.      if I can see you again,will I have the feeling?       All the truly happiness sadness have been buried in yesterday.       No mix of performing ,how wonderful that days is.       I feel pity,why you feel that? The disappeared clean face.          (秀英语，请无视) 背景： WJMZBMR已经长大啦，不由得感到All the truly happiness sadness have been buried in yesterday. 又想起以前的一些往事，和小时候玩过的一个游戏。。 （怎么跟上次的那题背景一模一样囧） 题目描述： WJMZBMR以前跟一群小朋友一起玩游戏。 他们都有名字，为了方便就用一个字母代替，还可能有重名。 每个小朋友呢，都有一个最喜欢的同学（可以不是二分图，自己理解，他甚至可以自恋。）。 然后他们开始玩传球小游戏，每个人接到球之后，会喊出自己的名字，并把球传给自己最喜欢的同学。 然后从每个人开始做第一个接到球的人，他会记录下每次别人喊出的名字，这些名字按顺序组成的字符串就是他的结果字符串。 比如3个人名字分别是 a b c，传球关系是a传给b，b传给c，c传给b 那么a的结果字符串是abcbcbcbc。。。,b的结果字符串是bcbcbcbc。。。,c的结果字符串是 cbcbcbc 。由于环的存在，结果字符串都是无穷的。 他们想按结果字符串的字典序从小到大排序，如果某两人结果字符串一样大，编号小的在前。</p></div>

# Input

<div class="content"><p>第一行n表示小朋友的个数。 接下来一行n个字符第i个表示第i个小朋友的名字ai。 接下来一行n个数第i个表示第i个小朋友最喜欢的同学是第几个小朋友bi</p></div>

# Output

<div class="content"><p>n行每行第i行一个数表示第i个人的编号。。。 数据范围： 对于100%的数据,n&lt;=100000; 每个人的名字都是小写字母</p></div>

# Sample Input

<div class="content"><span class="sampledata">100<br/>
b a b b b b a a b b a b a b b a a a a a b a b b a a a b b b b a a a b b b a b a b b b b a b a a b a b a b a a b a a a b b b a b a b a b b b a b a b a b a a b a b a a a a a b b a b a a a a b a a a a b <br/>
17 60 91 65 83 39 36 74 90 30 4 27 13 2 16 94 53 28 56 98 11 20 23 95 49 46 96 26 100 3 48 19 59 68 8 76 89 67 87 12 73 24 54 63 61 25 57 78 85 21 1 99 79 42 70 93 75 7 51 37 72 81 82 34 97 18 71 35 40 58 77 52 33 10 88 6 62 84 41 69 22 43 38 86 55 92 47 15 64 50 31 9 66 29 32 14 5 80 45 44 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13<br/>
83<br/>
48<br/>
22<br/>
38<br/>
78<br/>
20<br/>
67<br/>
52<br/>
47<br/>
84<br/>
73<br/>
65<br/>
85<br/>
98<br/>
32<br/>
27<br/>
63<br/>
71<br/>
99<br/>
57<br/>
86<br/>
33<br/>
16<br/>
58<br/>
97<br/>
91<br/>
11<br/>
25<br/>
40<br/>
55<br/>
50<br/>
26<br/>
80<br/>
18<br/>
93<br/>
19<br/>
96<br/>
89<br/>
82<br/>
77<br/>
45<br/>
75<br/>
92<br/>
2<br/>
59<br/>
34<br/>
17<br/>
54<br/>
94<br/>
8<br/>
7<br/>
5<br/>
31<br/>
81<br/>
72<br/>
87<br/>
41<br/>
4<br/>
49<br/>
95<br/>
12<br/>
44<br/>
15<br/>
70<br/>
3<br/>
21<br/>
46<br/>
69<br/>
90<br/>
28<br/>
66<br/>
56<br/>
37<br/>
14<br/>
64<br/>
1<br/>
43<br/>
35<br/>
62<br/>
61<br/>
39<br/>
79<br/>
24<br/>
100<br/>
88<br/>
30<br/>
9<br/>
60<br/>
51<br/>
68<br/>
6<br/>
53<br/>
42<br/>
29<br/>
10<br/>
76<br/>
74<br/>
36<br/>
23<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=和谐社会模拟赛">和谐社会模拟赛</a></p></div>

