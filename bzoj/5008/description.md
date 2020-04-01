
# Description

<div class="content"><div>方师傅来到了一个二维平面。他站在原点上，觉得这里风景不错，就建了一个房子。这个房子是n个点的凸多边形</div>
<div>，原点一定严格在凸多边形内部。有m个人也到了这个二维平面。现在你得到了m个人的坐标，你要判断这m个人中</div>
<div>有多少人在房子内部。点在凸多边形边上或者内部都认为在房子里面。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数n，接下来n行，每行两个整数x，y。输入按照逆时针顺序输入一个凸包。  </div>
<div>接下来一个数m，最后有m行，第一行两个整数 x，y，表示第一个人的坐标。</div>
<div>对于第i个询问(i&gt;=2) ，输入两个数dx，dy。</div>
<div>如果上一个人在房子内部，x[i]=x[i-1]+dx,y[i]=y[i-1]+dy。否则x[i]=x[i-1]-dx,y[i]=y[i-1]-dy。</div>
<div>n &lt;= 100000， m &lt;= 200000，输入保证所有人的坐标，房屋的坐标都在[-1e9，1e9]之内。</div>
<p></p></div>

# Output

<div class="content"><div>输出一个数，在房子内部人的个数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
-2 -2<br/>
2 -2<br/>
2 2<br/>
-2 2<br/>
3<br/>
5 5<br/>
4 4<br/>
0 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1	</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

