
# Description

<div class="content"><div>一台超级计算机共有N颗CPU。现在这台超级计算机有M个任务要做，但同时还要考虑到不能让CPU过热。所幸的是这</div>
<div>台超级计算机已经将任务安排好了，现在要做的只是请你根据安排好的指令来模拟它的工作过程。一开始，这N颗C</div>
<div>PU都没有被分配任何的任务。之后，会给你以下几类指令（CPU的编号为1到N的整数，任务的编号为1到M的整数）</div>
<div>指令格式     作用</div>
<div>ADD n k w    将 k 号任务（权值为 w）分配给 n 号 CPU</div>
<div>DEC n k w    将 k 号任务的权值减少 w（已知 k 号任务被分配给了 n 号 CPU）</div>
<div>TRANS n1 n2  将分配给 n1 号 CPU 的任务全部转移给 n2 号 CPU</div>
<div>MIN n        输出分配给 n 号 CPU 的任务中权值最小的任务的权值</div>
<div>WORK n w     将分配给 n 号 CPU 的任务中权值最小的任务的权值加上 w，</div>
<div>如果权值最小的任务不唯一，则不更改权值，并输出一行“ ERROR”</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>包含N+1行。</div>
<div>第1行包含三个正整数N、M、K，分别表示CPU的数目、任务数和指令数。</div>
<div>第2行到K+1行，每行包含一条指令。</div>
<div>N≤500， M≤300000， K≤300000。</div>
<div>保证任务的权值在 32 位有符号整型的范围内。</div>
<div>保证一个任务只会被分配一次（即至多被 ADD 一次）。</div>
<div>保证 ADD 指令、DEC 指令和 WORK 指令中的 w 是非负整数。</div>
<div>保证 TRANS 指令的两个参数不相同。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>若干行，其中包括MIN语句的输出和“ERROR”输出，每个输出占一行</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 13<br/>
ADD 1 2 100<br/>
ADD 1 1 90<br/>
MIN 1<br/>
WORK 1 20<br/>
TRANS 1 2<br/>
MIN 2<br/>
ADD 1 3 105<br/>
TRANS 2 1<br/>
MIN 1<br/>
DEC 1 3 200<br/>
MIN 1<br/>
DEC 1 1 205<br/>
WORK 1 15</span></div>

# Sample Output

<div class="content"><span class="sampledata">90<br/>
100<br/>
100<br/>
-95<br/>
ERROR</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

