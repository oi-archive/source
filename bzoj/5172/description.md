
# Description

<div class="content"><div>
<div>进入大学以后，学生们将面临选课，有N个学生需要选课，学校里有三个老师JYY，YJY，YYJ。第一年里，每个学生</div>
<div>们都选择了其中一位老师。经过了一年的学习，学生之间相互都有一定的印象，每个同学会根据自己的印象给另外</div>
<div>N-1个学生从好到坏排序。第二年的选课开始了，每个学生需要选择老师，可能是因为被坑多了，每一位同学都想</div>
<div>换一个老师。这时需要你来调度同学们选课，使得上同一堂课的学生之间印象最坏的最好。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>文件第一行包含一个整数N。</div>
<div>第2到N+1行，每行有N个正整数。</div>
<div>其中第i+1行提供第i个同学的信息，其中第一个整数Ai，值为0,1,2中的一个，表示第一年第i个同学选的老师。</div>
<div>接下来N-1个数字，是1,2,…,i-1,i+1,…,N的一个排列，表示第i个同学对其他同学印象从好到坏的排序。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出文件包含一行一个整数，为最小的非负整数T，满足：</div>
<div>1、所有同学选择了和第一年不同的老师。</div>
<div>2、所有选择同一个老师的学生间彼此印象都是前T好的。</div>
<div>N≤1000</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
0 2 3 4 5 6<br/>
0 1 3 4 5 6<br/>
1 6 5 4 2 1<br/>
2 6 5 3 2 1<br/>
1 1 2 3 4 6<br/>
2 1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
六名同学分别选择老师1，2，0，0，2，0。<br/>
此时老师0的课中同学六对同学四的印象为第4好，所以答案T为4。并且找不到更小的T。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

