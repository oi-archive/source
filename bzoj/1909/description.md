
# Description

<div class="content">一个港口被分成了 M个区域(1&lt;=M&lt;=10)，每个区域最多允许同时停靠10000 艘船，只要这些船来去的时间不互相冲突.每艘船都只能停靠在特定的一个区域。有n 艘船(1&lt;=N&lt;=100000)，已知每条船的到达时刻、离开时刻和它应该进入的区域。求一个调度方案使得能有最多的船得以停靠。</div>

# Input

<div class="content">Input contains many test sets. A test data set is defined as follow:
The first line of test data set is two integers: m and n, separated by one or more spaces(1≤m≤10, 1≤n≤100000). m is the number of sections in the port, and n is the number of ships.
The next m lines, one positive integer r (that means the length of the section is r hundred meters long) per line. The length of each section does not exceed 10000 hundred meters.
The next n lines gives one ship information on each line, with three non-negative integers s, e, sec (0≤s≤e,1≤sec≤m) per line, s is the arrival time of the ship, e is the departure time of the ship, and sec is the section which the ship should be berthed in.
Input is ended by EOF. You can assume that all the input data are legal.
</div>

# Output

<div class="content">For each test data set you should output one integer, the maximal number of the berthed ships, per line.
</div>

# Sample Input

<div class="content"><span class="sampledata">2 6  //二个区域,六只船<br/>
3   //区域的大小<br/>
3  //区域的大小<br/>
1 2 1  //每只船来去的时间及它应该要停泊的区域号<br/>
1 2 1<br/>
1 2 1<br/>
1 2 1<br/>
1 2 2<br/>
1 2 2<br/>
<br/>
1 3<br/>
2<br/>
1 3 1<br/>
2 6 1<br/>
2 8 1<br/>
<br/>
1 4<br/>
2<br/>
1 3 1<br/>
5 6 1<br/>
2 8 1<br/>
4 10 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p>2004年广东省大学生程序竞赛试题 Problem B</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

