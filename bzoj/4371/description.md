
# Description

<div class="content"><p>Aizhan有一个由N个互不相同的整数组成的序列S[0],S[1],…,S[N-1]，其中S[i]取值范围是[0,N-1]。Aizhan试图通过交换某些元素对的方法将这个序列按照升序排序。Aizhan的朋友Ermek也想交换某些元素对，Ermek的交换未必有助于Aizhan的排序。<br/>
Ermek和Aizhan打算通过若干轮次来修改这个序列。在每一轮，Ermek首先做一次交换，然后Aizhan做另一次交换。更确切地说，做交换的人选择两个有效的下标并交换这两个下标的元素。请注意这两个下标可能相同。如果它们相等，则对这个元素自身做交换，并不改变这个序列。<br/>
Aizhan知道Ermek并不关心对序列S排序的事情。Aizhan还知道Ermek将会选择哪些下标。Ermek打算参加M轮交换，将这些轮次从0到M-1编号。对于0到M-1之间的每个i，Ermek在第i轮将选择下标X[i]和Y[i]的元素进行交换。<br/>
Aizhan要对序列S按升序进行排序。在每一轮之前，如果Aizhan看到当前的序列已经按升序排列，她将结束这个排序过程。给定初始序列S以及Ermek要选择的下标，请你找出一个交换的序列，使得Aizhan能完成对序列S的排序。此外，在有些子任务中，你还要找出尽可能短的交换序列来完成排序任务。题目保证通过M或更少的轮次能够将序列S排好序。<br/>
请注意如果Aizhan发现在Ermek的交换之后，序列S已经排好序，则Aizhan可以选择交换两个相同下标（例如0和0）的元素。这样，序列S在这一轮次之后也完成排序，于是也达到了Aizhan的目标。另外，如果初始序列S就已经排好序，那么所需的最少排序轮数就是0。</p></div>

# Input

<div class="content"><p>第 1 行: N<br/>
第 2 行: S[0] … S[N-1]<br/>
第 3 行: M<br/>
第 4 行, …, M+3行: X[i]　Y[i]<br/>
N: 序列S的长度.<br/>
S: 一个整数数组，表示初始序列S。<br/>
M: Ermek打算做交换的次数。<br/>
X, Y: 长度为M的整数数组。 对于0≤i≤M-1, 在第i轮Ermek打算交换下<br/>
标为X[i]和Y[i]的数组。</p></div>

# Output

<div class="content"><p>第 1 行: 交换的长度R<br/>
第 2+i（0≤i&lt; R）行：P[i] Q[i]<br/>
P, Q: 整数数组。利用这两个数组报告Aizhan完成对序列S排序的一种可能的交换序列，假设这个交换序列的长度为R，对于0到R-1之间的每个i, Aizhan在轮次i选择的下标将被存入P[i]和Q[i]。 你可以假设数组P和Q均已分别被分配了M个元素。</p></div>

# Sample Input

<div class="content"><span class="sampledata">输入样例1<br/>
5<br/>
4 3 2 1 0<br/>
6<br/>
0 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
0 1<br/>
1 2<br/>
输入样例2<br/>
5<br/>
3 0 4 2 1<br/>
5<br/>
1 1<br/>
4 0<br/>
2 3<br/>
1 4<br/>
0 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例1<br/>
3<br/>
0 4<br/>
1 3<br/>
3 4<br/>
输出样例2<br/>
3<br/>
1 4<br/>
4 2<br/>
2 2</span></div>

# Hint

<div class="content"><p></p><p><img width="589" height="482" src="/source/bzoj/4371/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMi8zMygxKS5naWY=.gif" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yts1999上传 鸣谢mcfx提供SPJ">鸣谢yts1999上传 鸣谢mcfx提供SPJ</a></p></div>

