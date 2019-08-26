
# Description

<div class="content"><div>环环很喜欢种树，隔壁的健健发现最近环环不知道从哪里搞来了一棵奇怪的树。这棵树刚种下时每个点都有自己独</div>
<div>特的颜色。与一般的树一样，任何时刻它都只有一个根（初始根节点为 1 号点）。 “但是环环这么强，她种的树</div>
<div>怎么可能只会用五颜六色的外表来卖萌呢？”一直在暗中观察的健健想。于是健健又偷偷观察了几天，终于看到了</div>
<div>一些神奇的事情：这棵树的某个点有时会和根进行“交流”，它到根的路径上所有节点的颜色都会渐渐统一为一种</div>
<div>从未出现过的颜色。更神奇的是，这棵树有时会翻个身，它会拔起根，然后把另外的一个点插到泥土里使它变成新</div>
<div>的根，然后新的根会和原来的根进行一次“ 交流”。正当健健以为发现环环之所以强的秘密时，不幸的事发生了</div>
<div>。环环碰到了正在偷偷观察的健健，环环便说：“你来的正好，我正想考你一个问题，现在这个点的子树中所有点</div>
<div>到根的路径上平均有多少种颜色呢？昨天那个点的子树中所有点到根的路径上平均又有多少种颜色呢......”环环</div>
<div>一连串的问题把健健问晕了，为了不让健健再被环环鄙视，健健请你帮他回答这些问题。如果你不能帮健健正确回</div>
<div>答完这些问题，环环就会(*哔哔*)健健了。为了健健的人生大事，请你写一个程序帮助他。</div>
<div></div></div>

# Input

<div class="content"><div>第一行有两个正整数 n 和 m，分别代表这棵树的节点数和健健遇到的事件数。接下来 n-1 行，每行有两个正整数</div>
<div> a， b，表示节点 a 和 b 之间有树枝连接。接下来 m 行，表示健健遇到的事件：</div>
<div>(1) Make_Root x 表示这棵树翻了个身，新的根为节点 x，同时原来的根会与现在</div>
<div>的根进行一次交流，字符串与整数之间有一个空格；</div>
<div>(2) Paint x 表示节点 x 与根进行了一次交流；</div>
<div>(3) Query x 表示环环向健健问了一个问题，询问 x 的子树中所有节点到根的路径上平均有多少种颜色。</div>
<div>1 &lt;= n &lt;= 100000, 1 &lt;= m &lt;= 100000。</div>
<div></div></div>

# Output

<div class="content"><div>对于每个询问，输出一个实数（实数保留 7 位小数），表示以 x 为根的子树中所有节点到根的路径上的平均颜色</div>
<div>数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 6<br/>
1 2<br/>
1 3<br/>
2 8<br/>
3 4<br/>
3 5<br/>
3 6<br/>
4 7<br/>
Query 7<br/>
Paint 3<br/>
Query 3<br/>
Make_Root 5<br/>
Paint 2<br/>
Query 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.0000000<br/>
2.0000000<br/>
1.3333333</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

