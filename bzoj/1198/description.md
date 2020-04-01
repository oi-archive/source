
# Description

<div class="content"><div>凯萨拥有一支由n个人组成的雇佣军，他们靠在威尼斯商行接任务过活。这支军队的成份比较复杂，不同的人往往</div>
<div>具有不同的技能，有的人还拥有多项技能。威尼斯商行的任务也参差不齐，有的需要几个人合作完成，有的只需要</div>
<div>一个人独立完成：有的很简单，不需要耗多少时间，因此报酬也较低，有的很有难度，需要多个人长期合作完成，</div>
<div>因此报酬就高。完成这些任务的时间不会超过一个月。并且，一个人不能同时执行两项任务，也不能中途加入或者</div>
<div>退出任务。但可以不执行任何任务。一项只需要n个人来完成的任务，如果执行该任务的人数p大于n,那么反而会得</div>
<div>到更少的报酬，即原报酬的1/(p-n+1)。凯萨是一位英明的领袖，他往往在每个月的月底召开军事会议，总结上个</div>
<div>月的成果，发给大家报酬，并指派下个月的任务。请问，凯萨应该怎样指派任务，才能使总报酬最高？总报酬为多</div>
<div>少？</div></div>

# Input

<div class="content"><div>
<div>
<div>一行包含两个正整数n,m。彼此用空格隔开，</div>
<div>其中n〈10表示雇佣军的人数，m〈15表示下个月可选的任务数。</div>
<div>接下来的n行中第i行（对应文件的第i+1行）的第一个整数小于等于表示编号为i的雇佣军可执行的任务数</div>
<div>后面的整数是编号为i的雇佣军可以执行的所有任务的编号，这些整数之间用空格隔开。</div>
<div>最后的m行中，每行有四个整数b、e、p和r，彼此之间用空格隔开，</div>
<div>其中第j行（对应整个文件的第n+j+1行）是编号为j的任务的描述：</div>
<div>0&lt;b&lt;32表示该任务的开始日（这一天会被计入任务所需的时间中），</div>
<div>0&lt;e&lt;32表示该任务的结束日（这一天也会被计入任务所需的时间中），</div>
<div>p&lt;10表示该任务所需人数，0&lt;r&lt;100000表示该任务的报酬。</div>
</div>
</div></div>

# Output

<div class="content"><p>第一行只有一个整数t,表示最多可获得的总报酬</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
2 1 4<br/>
2 2 4<br/>
3 3 4 5<br/>
2 20 1 100 <br/>
1 18 1 200 <br/>
3 28 1 800 <br/>
21 30 3 1500 <br/>
19 21 1 400 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1800</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

