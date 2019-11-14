
# Description

<div class="content"><p>写一个程序来模拟操作系统的进程调度。假设该系统只有一个CPU，每一个进程的到达时间，执行时间和运行优先级都是已知的。其中运行优先级用自然数表示，数字越大，则优先级越高。如果一个进程到达的时候CPU是空闲的，则它会一直占用CPU直到该进程结束。除非在这个过程中，有一个比它优先级高的进程要运行。在这种情况下，这个新的（优先级更高的）进程会占用CPU，而老的只有等待。如果一个进程到达时，CPU正在处理一个比它优先级高或优先级相同的进程，则这个（新到达的）进程必须等待。一旦CPU空闲，如果此时有进程在等待，则选择优先级最高的先运行。如果有多个优先级最高的进程，则选择到达时间最早的。</p></div>

# Input

<div class="content"><p>输入文件包含若干行，每一行有四个自然数（均不超过108），分别是进程号，到达时间，执行时间和优先级。不同进程有不同的编号，不会有两个相同优先级的进程同时到达。输入数据已经按到达时间从小到大排序。输入数据保证在任何时候，等待队列中的进程不超过15000个。</p></div>

# Output

<div class="content"><p>按照进程结束的时间输出每个进程的进程号和结束时间</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 5 3<br/>
2 10 5 1<br/>
3 12 7 2<br/>
4 20 2 3<br/>
5 21 9 4<br/>
6 22 2 4<br/>
7 23 5 2<br/>
8 24 2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 6<br/>
3 19<br/>
5 30<br/>
6 32<br/>
8 34<br/>
4 35<br/>
7 40<br/>
2 42</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

