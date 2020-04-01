
# Description

<div class="content"><div>
<div>最近实验室正在为其管理的超级计算机编制一套任务管理系统，而你被安排完成其中的查询部分。超级计算机中的</div>
<div>任务用三元组(Si,Ei,Pi)描述，(Si,Ei,Pi)表示任务从第Si秒开始，在第Ei秒后结束（第Si秒和Ei秒任务也在运行</div>
<div>），其优先级为Pi。同一时间可能有多个任务同时执行，它们的优先级可能相同，也可能不同。调度系统会经常向</div>
<div>查询系统询问，第Xi秒正在运行的任务中，优先级最小的Ki个任务（即将任务按照优先级从小到大排序后取前Ki个</div>
<div>）的优先级之和是多少。特别的，如果Ki大于第Xi秒正在运行的任务总数，则直接回答第Xi秒正在运行的任务优先</div>
<div>级之和。上述所有参数均为整数，时间的范围在1到n之间（包含1和n）。</div>
</div>
<div></div></div>

# Input

<div class="content"><div>
<div>输入文件第一行包含两个空格分开的正整数m和n，分别表示任务总数和时间范围。接下来m行，每行包含三个空格</div>
<div>分开的正整数Si、Ei和Pi(Si≤Ei)，描述一个任务。接下来n行，每行包含四个空格分开的整数Xi、Ai、Bi和Ci，</div>
<div>描述一次查询。查询的参数Ki需要由公式 Ki=1+(Ai*Pre+Bi) mod Ci计算得到。其中Pre表示上一次查询的结果，</div>
<div>对于第一次查询，Pre=1。</div>
</div>
<div></div>
<div></div></div>

# Output

<div class="content"><div>
<div>输出共n行，每行一个整数，表示查询结果。</div>
</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2 6<br/>
2 3 3<br/>
1 3 2<br/>
3 3 4<br/>
3 1 3 2<br/>
1 1 3 4<br/>
2 2 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
8<br/>
11</span></div>

# Hint

<div class="content"><p></p><div>样例解释</div><br/>
<div>K1 = (1*1+3)%2+1 = 1</div><br/>
<div>K2 = (1*2+3)%4+1 = 2</div><br/>
<div>K3 = (2*8+4)%3+1 = 3</div><br/>
<div>对于100%的数据，1≤m,n,Si,Ei,Ci≤100000，0≤Ai,Bi≤100000，1≤Pi≤10000000，Xi为1到n的一个排列</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

