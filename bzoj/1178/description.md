
# Description

<div class="content"><div>Siruseri政府建造了一座新的会议中心。许多公司对租借会议中心的会堂很感兴趣，他们希望能够在里面举行会议</div>
<div>。 对于一个客户而言，仅当在开会时能够独自占用整个会堂，他才会租借会堂。会议中心的销售主管认为：最好</div>
<div>的策略应该是将会堂租借给尽可能多的客户。显然，有可能存在不止一种满足要求的策略。 例如下面的例子。总</div>
<div>共有4个公司。他们对租借会堂发出了请求，并提出了他们所需占用会堂的起止日期（如下表所示）。 开始日期 </div>
<div>结束日期 公司1 4 9 公司2 9 11 公司3 13 19 公司4 10 17 上例中，最多将会堂租借给两家公司。租借策略分别</div>
<div>是租给公司1和公司3，或是公司2和公司3，也可以是公司1和公司4。注意会议中心一天最多租借给一个公司，所以</div>
<div>公司1和公司2不能同时租借会议中心，因为他们在第九天重合了。 销售主管为了公平起见，决定按照如下的程序</div>
<div>来确定选择何种租借策略：首先，将租借给客户数量最多的策略作为候选，将所有的公司按照他们发出请求的顺序</div>
<div>编号。对于候选策略，将策略中的每家公司的编号按升序排列。最后，选出其中字典序最小1的候选策略作为最终</div>
<div>的策略。 例中，会堂最终将被租借给公司1和公司3：3个候选策略是{(1,3),(2,3),(1,4)}。而在字典序中(1,3)&lt;(</div>
<div>1,4)&lt;(2,3)。 你的任务是帮助销售主管确定应该将会堂租借给哪些公司。</div></div>

# Input

<div class="content"><div>第一行有一个整数N，表示发出租借会堂申请的公司的个数。</div>
<div>第2到第N+1行每行有2个整数。第i+1行的整数表示第i家公司申请租借的起始和终止日期。</div>
<div>对于每个公司的申请，起始日期为不小于1的整数，终止日期为不大于10^9的整数。</div>
<div>N≤200000</div></div>

# Output

<div class="content"><div>输出的第一行应有一个整数M，表示最多可以租借给多少家公司。</div>
<div>第二行应列出M个数，表示最终将会堂租借给哪些公司。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
4 9<br/>
9 11<br/>
13 19<br/>
10 17</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
1 3</span></div>

# Hint

<div class="content"><p></p><p>修复数据bug,并新加数据一组By <span style="font-family: &#39;Microsoft Yahei&#39;; font-size: 14px; line-height: 22.3999996185303px;">NanoApe 2016.5.11</span></p><br/>
<p>修复后数据:<a href="/JudgeOnline/upload/201605/dd.rar">JudgeOnline/upload/201605/dd.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

