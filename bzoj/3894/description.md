
# Description

<div class="content"><div> 文理分科是一件很纠结的事情！（虽然看到这个题目的人肯定都没有纠</div>
<div>结过）</div>
<div> 小P所在的班级要进行文理分科。他的班级可以用一个n*m的矩阵进行</div>
<div>描述，每个格子代表一个同学的座位。每位同学必须从文科和理科中选择</div>
<div>一科。同学们在选择科目的时候会获得一个满意值。满意值按如下的方式</div>
<div>得到：</div>
<div>1．如果第i行第秒J的同学选择了文科，则他将获得art[i][j]的满意值，如</div>
<div>  果选择理科，将得到science[i][j]的满意值。</div>
<div>2．如果第i行第J列的同学选择了文科，并且他相邻（两个格子相邻当且</div>
<div>  仅当它们拥有一条相同的边）的同学全部选择了文科，则他会更开</div>
<div>  心，所以会增加same_art[i][j]的满意值。</div>
<div>3．如果第i行第j列的同学选择了理科，并且他相邻的同学全部选择了理</div>
<div>  科，则增加same_science[i]j[]的满意值。</div>
<div>  小P想知道，大家应该如何选择，才能使所有人的满意值之和最大。请</div>
<div>告诉他这个最大值。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div></div>
<div>第一行为两个正整数：n，m</div>
<div>接下来n术m个整数，表示art[i][j]；</div>
<div>接下来n术m个整数．表示science[i][j]；</div>
<div>接下来n术m个整数，表示same_art[i][j]；</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div></div>
<div>输出为一个整数，表示最大的满意值之和</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
13 2 4 13<br/>
7 13 8 12<br/>
18 17 0 5<br/>
<br/>
8 13 15 4<br/>
11 3 8 11<br/>
11 18 6 5<br/>
<br/>
1  2 3 4 <br/>
4  2 3 2<br/>
3  1 0 4<br/>
<br/>
3  2 3 2<br/>
0  2 2 1<br/>
0  2 4 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">152</span></div>

# Hint

<div class="content"><p></p><div>样例说明</div><br/>
<div>1表示选择文科，0表示选择理科，方案如下：</div><br/>
<div>1  0  0  1</div><br/>
<div>0  1  0  0</div><br/>
<div>1  0  0  0</div><br/>
<div></div><br/>
<div>N,M&lt;=100,读入数据均&lt;=500</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

