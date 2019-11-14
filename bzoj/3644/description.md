
# Description

<div class="content"><p><span style="font-size: medium">  A国有N座城市，它们用正整数1…N进行编号。这些城市之间通过N-1条双向道路连接，使得任意两座城市间都有且仅有一条路径相连。定义两个城市间的距离为连接这两个城市路径上的边数。<br/>
  陶陶要在A国进行若干趟旅行，每次他会选择一个起点城市s和终点城市t，他从城市s开始，沿着s到亡的路径旅行，当他到达第i个城市时，可以选择坐火车到达与城市i距离不超过Ai的另一座城市，但这座城市必须要在S到t的路径上，你的任务是求出陶陶每趟旅<br/>
行最少需要坐多少次火车。<br/>
    除此之外，某些城市的火车车次中途会有改变，也就是说陶陶的每趟旅行之间可能夹杂了一些城市Ai值的改变。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">共N+M+2行。<br/>
第一行包含一个正整数Ⅳ，表示A国城市的数目。<br/>
第二行包含N个正整数，第i个正整数表示Ai (Ai≤20)。<br/>
 接下来有N-1行，每行包含两个正整数U，V(U,V≤N），表示城市u和V之间有一条双向道路相连。<br/>
  第N+2行包含一个正整数M，表示操作次数。<br/>
  下面M行，每行先给出一个字符，Q表示询问操作、C表禾修改操作。假如是询问操作，后面会有两个正整数s，t(s，t≤N，s≠t)，分别表示起点城市和终点城市。假如是修改操作，后面会有两个正整数i，x(i≤N，x≤20)，表示将Ai修改为x。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">包含若干行，对于每次询问输出对应的答案。<br/>
</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
8                        <br/>
2 1 1 2 2 1 1 1                 <br/>
1 2                       <br/>
1 3                       <br/>
2 8                        <br/>
3 4                        <br/>
3 5                        <br/>
4 6                        <br/>
4 7                        <br/>
5                         <br/>
Q 5 8                       <br/>
Q 6 7                       <br/>
C 6 2                       <br/>
Q 6 7                       <br/>
Q 8 5                       <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
1<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
  第一次询问的路线为5--&gt;1--&gt;8；<br/><br/>
  第二次询问的路线为6--&gt;4--&gt;7；<br/><br/>
  第三次询问的路线为6 --&gt;7；<br/><br/>
  第四次询问的路线为8--&gt;2--&gt;1--&gt;5。</p><br/>
<p>  对于100%的数据满足N≤100，000，M≤100，000。对于包含修改操作的数据，修改操作约占操作总数的三分之一。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

