
# Description

<div class="content"><div>新建的圆形动物园是亚太地区的骄傲。圆形动物园坐落于太平洋的一个小岛上，包含一大圈围栏，每个围栏里有一</div>
<div>种动物。如下图所示：</div>
<div><img src="/source/bzoj/1151/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xKDEpLnBuZw==.png" width="340" height="335" alt=""/></div>
<div>你是动物园的公共主管。你要做的是，让每个来动物园的人都尽可能高兴。今天有一群小朋友来动物园参观，你希</div>
<div>望能让他们在动物园度过一段美好的时光。但这并不是一件容易的事——有的动物有一些小朋友喜欢，有的动物有</div>
<div>一些小朋友害怕。如，Alex 喜欢可爱的猴子和考拉，而害怕拥牙齿锋利的狮子。而Polly 会因狮子有美丽的鬃毛</div>
<div>而喜欢它，但害怕有臭味的考拉。你可以选择将一些动物从围栏中移走以使得小朋友不会害怕。但你不能移走所有</div>
<div>的动物，否则小朋友们就没有动物可看了。每个小朋友站在大围栏圈的外面，可以看到连续的 5 个围栏。你得到</div>
<div>了所有小朋友喜欢和害怕的动物信息。当下面两处情况之一发生时，小朋友就会高兴：</div>
<div>至少有一个他害怕的动物被移走</div>
<div>至少有一个他喜欢的动物没被移走</div>
<div></div>
<div>例如，考虑下图中的小朋友和动物：</div>
<div><img src="/source/bzoj/1151/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8yLnBuZw==.png" width="602" height="484" alt=""/></div>
<div>假如你将围栏 4 和 12 的动物移走。Alex 和 Ka-Shu 将很高兴，因为至少有一个他们害怕的动物被移走了。这也</div>
<div>会使 Chaitanya 高兴，因为他喜欢的围栏 6 和8 中的动物都保留了。但是，Polly 和 Hwan 将不高兴，因为他们</div>
<div>看不到任何他们喜欢的动物，而他们害怕的动物都还在。这种安排方式使得三个小朋友高兴。现在，换一种方法，</div>
<div>如果你将围栏 4 和 6 中的动物移走，Alex 和 Polly 将很高兴，因为他们害怕的动物被移走了。Chaitanya 也会</div>
<div>高兴，虽然他喜欢的动物 6被移走了，他仍可以看到围栏 8 里面他喜欢的动物。同样的 Hwan 也会因可以看到自</div>
<div>己喜欢的动物 12 而高兴。唯一不高兴的只有 Ka-Shu。如果你只移走围栏 13 中的动物，Ka-Shu 将高兴，因为有</div>
<div>一个他害怕的动物被移走了，Alex, Polly, Chaitanya 和 Hwan 也会高兴，因为他们都可以看到至少一个他们喜</div>
<div>欢的动物。所以有 5 个小朋友会高兴。这种方法使得了最多的小朋友高兴。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>输入的第一行包含两个整数N, C，用空格分隔。</div>
<div>N是围栏数(10≤N≤10 000)，C是小朋友的个数(1≤C≤50 000)。</div>
<div>围栏按照顺时针的方向编号为1,2,3,…,N。</div>
<div>接下来的C行，每行描述一个小朋友的信息，</div>
<div>以下面的形式给出： E F L X1 X2 … XF Y1 Y2 … YL </div>
<div>其中： E表示这个小朋友可以看到的第一个围栏的编号(1≤E≤N)，</div>
<div>换句话说，该小朋友可以看到的围栏为E, E+1, E+2, E+3, E+4。</div>
<div>注意，如果编号超过N将继续从1开始算。</div>
<div>如：当N=14, E=13时，这个小朋友可以看到的围栏为13,14,1, 2和3。 </div>
<div>F表示该小朋友害怕的动物数。</div>
<div>L表示该小朋友喜欢的动物数。</div>
<div>围栏X1, X2, …, XF 中包含该小朋友害怕的动物。</div>
<div>围栏Y1, Y2, …, YL 中包含该小朋友喜欢的动物。 </div>
<div>X1, X2, …, XF, Y1, Y2, …, YL是两两不同的整数，</div>
<div>而且所表示的围栏都是该小朋友可以看到的。</div>
<div>小朋友已经按照他们可以看到的第一个围栏的编号从小到大的顺序排好了</div>
<div>(这样最小的E对应的小朋友排在第一个，最大的E对应的小朋友排在最后一个)。</div>
<div>注意可能有多于一个小朋友对应的E是相同的。</div></div>

# Output

<div class="content"><p>仅输出一个数，表示最多可以让多少个小朋友高兴</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10<br/>
1 1 1 3 2<br/>
2 1 0 4<br/>
3 1 1 5 6<br/>
4 1 1 7 6<br/>
5 1 0 6<br/>
6 1 2 9 8 10<br/>
7 1 0 10<br/>
8 1 0 8<br/>
9 1 1 1 2<br/>
10 1 0 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

