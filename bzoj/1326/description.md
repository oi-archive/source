
# Description

<div class="content">有一条蛇在它的洞里面，现在他要出来，问最少要多少步才可以移动到出口。出口的位置是(1,1)。蛇可以弯曲的，但是它的部分必须是连接的，比如：如果它有一个部位在一个坐标，连接它那个部位的坐标一定是它的上下左右。
</div>

# Input

<div class="content">  有多组数据。每组数据的第一行有3个数，N,M,L（N，M）表示洞的大小N*M，L表示蛇的长度。然后下面有L行，每行两个数，表示蛇所有部位的位置。第一组是蛇的头，第L组是蛇的尾巴，也就是说是按顺序给出蛇的头至尾的位置，移动时蛇的蛇的后面一个部位要移到之前那个部位的位置。当然蛇不能走到有石头的地方且它不能走在自己身上。
  然后给出一个K，表示洞里面有多少块石头。然后下面有K行，每行2个数，表示每块石头的坐标。
  每个数据之间有一空行，数据以3个0表示结束。
</div>

# Output

<div class="content"> 如果蛇可以走出洞的话，那么输出最小步数，如果蛇不能走出洞，那么输出-1；
</div>

# Sample Input

<div class="content"><span class="sampledata">5 6 4<br/>
4 1<br/>
4 2<br/>
3 2<br/>
3 1<br/>
3<br/>
2 3<br/>
3 3<br/>
3 4<br/>
<br/>
4 4 4<br/>
2 3<br/>
1 3<br/>
1 4<br/>
2 4<br/>
4<br/>
2 1<br/>
2 2<br/>
3 4<br/>
4 2<br/>
<br/>
0 0 0<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 9<br/>
Case 2: -1<br/>
</span></div>

# Hint

<div class="content"><p>注意：出口处是没有石头的。<br/>
<br/>
说明：第一组数据依次按以下坐标走是最短的。           <br/>
<br/>
(4,1)  &#39;(5,1)   (5,2)  &#39;(5,3)  &#39;(4,3)   &#39;(4,2)   &#39;(4,1)&#39;   (3,1)   &#39;(2,1)&#39;(1,1)<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

