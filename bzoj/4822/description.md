
# Description

<div class="content"><div>老 C 是个程序员。    </div>
<div>最近老 C 从老板那里接到了一个任务——给城市中的手机基站写个管理系统。作为经验丰富的程序员,老 C 轻松</div>
<div>地完成了系统的大部分功能,并把其中一个功能交给你来实现。由于一个基站的面积相对于整个城市面积来说非常</div>
<div>的小,因此每个的基站都可以看作坐标系中的一个点,其位置可以用坐标(x, y)来表示。此外,每个基站还有很多属</div>
<div>性,例如高度、功率等。运营商经常会划定一个区域,并查询区域中所有基站的信息。现在你需要实现的功能就是,</div>
<div>对于一个给定的矩形区域,回答该区域中(包括区域边界上的)所有基站的功率总和。如果区域中没有任何基站,则回</div>
<div>答 0。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数 n, m,表示一共有n个基站和m次查询。    </div>
<div>接下来一共有 n 行,每行由x_i , y_i , p_i 三个空格隔开的整数构成,表示一个基站的坐标(x_i , y_i )和功率p</div>
<div>_i 。不会有两个基站位于同一坐标。    </div>
<div>接下来一共有m行,每行由x1_j , y1_j , x2_j , y2_j 四个空格隔开的整数构成,表示一次查询的矩形区域。该矩</div>
<div>形对角坐标为(x1_j , y1_j )和(x2_j , y2_j ),且 4 边与坐标轴平行。 </div>
<div>2^31 ≤ x_i , y_i , p_i , x1_j , y1_j , x2_j , y2_j &lt; 2^31, x1_j ≤ x2_j, y1_j ≤ y2_j。   </div>
<div></div></div>

# Output

<div class="content"><div>输出 m 行,每行一个整数,对应每次查询的结果。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
0 0 1<br/>
0 1 2<br/>
2 2 4<br/>
1 0 8<br/>
0 0 1 1<br/>
1 1 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

