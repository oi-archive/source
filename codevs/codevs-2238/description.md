<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>目前，高等院校往往采用GPA(Grade Point Average)来评价学生的学术表现。传统的排名方式是求每一个学生的平均成绩，以平均成绩作为依据进行排名。</p>
<p>但是这样的排名方法已经引起了教育界以及社会各界人士的争议。因为它存在着许多弊端。对于不同的课程，选课学生的平均成绩会不同程度地受到课程的难易程度和老师的严厉程度的制约。因而这样的排名系统无形中就鼓励了学生选择一些比较容易的课程，因为这样可以事半功倍地获得较高的平均分。</p>
<p> </p>
<p>为了克服这些弊端，我们需要对排名系统做一定的改进。</p>
<p><span style="">一种改进的方案是对选第i门课的每一个学生的成绩加上一个特定的修正值d</span><sub>i</sub><span style="">，例如编号为j的学生该课的成绩G</span><sub>ij</sub><span style="">修改为G’</span><sub>ij</sub><span style="">=G</span><sub>ij</sub><span style="">+d</span><sub>i</sub><span style="">。最终使得经过调整后，该课的平均分等于选该课的所有学生的所有课的平均分。对每一门课都做这样的调整，使得上述条件对所有课程都满足。这种调整方案一定程度地避免了传统排名系统的不公正。而你的任务正是根据一个大学某一个年级学生某学年的成绩，给出他们的排名。假设每一个学生都至少选一门课。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是两个正整数m和n，分别表示学生人数和课程数目。</p>
<p>接下来m行是一个矩阵，矩阵中第i 行的第j个元素表示第i个学生第j门课的成绩G(i,j)。输入的成绩是一个0到100之间的整数，如果该学生没有选这门课，那么G(i,j)＝-1。由于该方案的施行只是为了获得更加科学的排名，因此调整后的成绩的数值大小本身没有什么意义，因此调整后的成绩可以不是0－100之间的数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出采用改进方案后这些学生的排名。以学生编号的形式输出，每行是一个学生的编号。</p>
<p>如果在上述调整后，有若干学生平均分相等(精确到小数点后的三位)，则他们的名次相同，按照任意顺序输出。</p>
<p>当然许多时候，上述调整无法顺利进行，即调整的目标无法达到。（因此，在实际问题中，我们往往在最小二乘意义下获得一种最接近目标的调整方案。）也有可能或者因调整不唯一而不能确定学生的名次。若以上两种情况发生，则输出&ldquo;fail&ldquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p>
<p>60 -1</p>
<p>70 -1</p>
<p>80 45</p>
<p><span style="">-1 65</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">4</p>
<p style="">3</p>
<p style="">2</p>
<p style="">1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">1&lt;=m&lt;=500</p>
<p style="">1&lt;=n&lt;=100</p>
<p>一种可行的调整方法是：</p>
<p>第一门课每一个学生的成绩加上10，第二门课每一个学生的成绩加上35。</p>
<p>调整后的情况是：</p>
<p>70 –1</p>
<p>80 –1</p>
<p>90 80</p>
<p>-1 100</p>
<p>调整后第一门课的平均分为：(70＋80+90)/3=80</p>
<p>选第一门课的所有学生的所有课的平均分为：(70+80+90+80)/4=80。</p>
<p>第二门课的平均分为：(80+100)/2=90</p>
<p>选第二门课的所有学生的所有课的平均分为：(90+80+100)/3=90</p>
<p>然后，计算每一个学生的平均分并且排名，即得到了输出的结果。</p>
</div>
</div>