
# Description

<div class="content"><div>Farmer John needs your help deciding where to build a fence in the shape of a straight line to help </div>
<div>restrict the movement of his cows. He has considered several possible fence locations and needs your </div>
<div>help to determine which of these are usable, where a fence is considered usable if all of the cows </div>
<div>are on the same side of the fence. A fence is not usable if there is a cow that lies directly on it. </div>
<div>FJ will be asking you a number of queries regarding possible fence locations; a query should be </div>
<div>answered &#34;YES&#34; if it corresponds to a usable fence location, &#34;NO&#34; otherwise.</div>
<div>Additionally, FJ may occasionally bring new cows into the herd. When a new cow joins the herd, all </div>
<div>fence queries from that point onward will require her to be on the same side of a fence as the rest </div>
<div>of the herd for the fence to be usable.FJ需要你帮助他决定在哪里建造形状是一条无限长的直线的栅栏来限制</div>
<div>他的牛的活动。他选出了几个可能的建造栅栏的位置，你需要帮助他判断哪些栅栏是有用的。一个栅栏是有用的当且</div>
<div>仅当所有奶牛都在栅栏的同一侧(如果有牛群在栅栏所在的直线上，那么栅栏是没用的)，FJ将会问你一些问题，如果</div>
<div>这个栅栏是有用的，需要输出“YES”，反之输出“NO”。 另外，FJ也可能会带来一些新的奶牛加入这个牛群。一头牛</div>
<div>加入之后，以后的所有询问中，这头牛也需要与其它的牛在栅栏的同一侧。 </div>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
<p></p></div>

# Input

<div class="content"><div>
<div>The first line of input contains N (1 &lt;= N &lt;= 100,000) and Q (1 &lt;= Q &lt;= 100,000) separated by a space. </div>
<div>These give the number of cows initially in the herd and the number of queries, respectively.</div>
<div>The following N lines describe the initial state of the herd. Each line will contain two space separated </div>
<div>integers x and y giving the position of a cow.</div>
<div>The remaining Q lines contain queries either adding a new cow to the herd or testing a fence for usability. </div>
<div>A line of the form &#34;1 x y&#34; means that a new cow has been added to the herd at position (x, y). A line of </div>
<div>the form &#34;2 A B C&#34; indicates that FJ would like to test a fence described by the line Ax + By = C.</div>
<div>All cow positions will be unique over the whole data set and will satisfy (-10^9 &lt;= x, y &lt;= 10^9). </div>
<div>Additionally the fence queries will satisfy -10^9 &lt;= A, B &lt;= 10^9 and -10^18 &lt;= C &lt;= 10^18. No fence </div>
<div>query will have A = B = 0.</div>
<div>第一行包含两个用空格隔开的整数N和Q代表最开始奶牛的数目和FJ的提问的个数。 </div>
<div>接下来的N行每行包含两个整数x和y，代表每只奶牛的坐标 </div>
<div>最后的Q行，每行代表一个提问，形如“1 x y”的提问代表FJ在坐标为(x,y)的位置放置了一头新的奶牛。形如&#34;2 A B C&#34;的</div>
<div>提问代表FJ向你询问位于直线Ax+By+C上的栅栏是否是有用的。</div>
<div>
<div>输入数据保证所有奶牛的坐标都是互不相同的，而且不会出现A=B=0的询问</div>
<div>1&lt;=N&lt;=100000 </div>
<div>1&lt;=Q&lt;=100000 </div>
<div>-10^9&lt;=x,y&lt;=10^9 </div>
<div>-10^9&lt;=A,B&lt;=10^9 </div>
<div>-10^18&lt;=C&lt;=10^18 </div>
</div>
</div>
<div>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
</div>
<p></p></div>

# Output

<div class="content"><h4>
<div>
<div>
<div style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">
<div></div>
</div>
<div><span style="font-size: 14px; font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif;">For each fence query, output &#34;YES&#34; if the fence is usable. </span></div>
<div><span style="font-size: 14px; font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif;">Otherwise output &#34;NO&#34;.</span></div>
<div><font face="Raleway, Helvetica Neue, Helvetica, Arial, sans-serif"><span style="font-size: 14px;">对于每个形如“2 A B C”的提问，输出一行。 </span></font></div>
<div><font face="Raleway, Helvetica Neue, Helvetica, Arial, sans-serif"><span style="font-size: 14px;">如果栅栏是有用的，输出&#34;YES&#34;，否则输出&#34;NO&#34;(不包含引号)。</span></font></div>
<div style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">
<div></div>
</div>
<div style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></div>
</div>
<div style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></div>
</div>
<div style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></div>
</h4>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;"></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
0 0<br/>
0 1<br/>
1 0<br/>
2 2 2 3<br/>
1 1 1<br/>
2 2 2 3<br/>
2 0 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO<br/>
NO<br/>
//最开始的三头牛都在2x+2y=3这条直线同侧，但是奶牛(1,1)加入后，与其它三头牛不在同一侧，所有第二个栅栏是没用的。因为奶牛(0,1)和奶牛(1,1)在直线y=1上，所以第三个栅栏是没用的 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

