
# Description

<div class="content"><div>一个被分为n*n个网格的盒子，每一格有可能包含一瓶牛奶或者什么都没有。史密斯先生对每行从左到右记下牛奶</div>
<div>的情况，对每列从上到下记下牛奶的情况。每一条记录包含n个数字，0表示没有牛奶，1表示有牛奶。不幸的是，2</div>
<div>n条记录的顺序被打乱了，有些数字也模糊不清。</div>
<div>Your Task </div>
<div>恢复原来盒子的牛奶情况以及原来记录的顺序。 </div>
<div></div></div>

# Input

<div class="content"><p> 第一行n表示网格大小 </p>
<div>接下来的2n行，每行一条记录，每条记录有n个数字，0表示一定没有牛奶，1表示一定有牛奶，2表示不能确定 </div>
<div>1≤n≤10</div>
<div></div></div>

# Output

<div class="content"><p> 第一行输出n个数，第i个数ai表示第ai条记录对应第i行的信息 </p>
<div>第一行输出n个数，第i个数bi表示第bi条记录对应第i列的信息 </div>
<div>接下来n行n列输出原来盒子的牛奶情况，0表示没有牛奶，1表示有牛奶 </div>
<div>保证有解，有多组解时输出任意一组即可 </div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
01210 <br/>
21120 <br/>
21001 <br/>
12110 <br/>
12101 <br/>
12101 <br/>
00011 <br/>
22222 <br/>
11001 <br/>
10010 </span></div>

# Sample Output

<div class="content"><span class="sampledata">10 9 8 6 2 <br/>
4 3 7 5 1 <br/>
10010 <br/>
11001 <br/>
10010 <br/>
10101 <br/>
01110 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

