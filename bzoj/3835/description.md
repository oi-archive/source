
# Description

<div class="content"><div>Byteasar has designed a supercomputer of novel architecture. It may comprise of many (identical) processing units. Each processing unit can execute a single instruction per time unit.</div>
<div>The programs for this computer are not sequential but rather have a tree structure. Each instruction may have zero, one, or multiple subsequent instructions, for which it is the parent instruction.</div>
<div>The instructions of the program can be executed in parallel on all available processing units. Moreover, they can be executed in many orders: the only restriction is that an instruction cannot be executed unless its parent instruction has been executed before. For example, as many subsequent instructions of an instruction that has been executed already can be executed in parallel as there are processing units.</div>
<div>Byteasar has a certain program to run. Since he likes utilizing his resources optimally, he is wondering how the number of processing units would affect the running time. He asks you to determine, for a given program and number of processing units, the minimum execution time of the program on a supercomputer with this many processing units.</div>
<div></div>
<div>
<div>给定一棵N个节点的有根树，根节点为1。</div>
<div>Q次询问，每次给定一个K，用最少的操作次数遍历完整棵树，输出最少操作次数。</div>
<div>每次操作可以选择访问不超过K个未访问的点，且这些点的父亲必须在之前被访问过。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>In the first line of standard input, there are two integers, N and Q （1&lt;=N,Q&lt;=1 000 000）, separated by a single space, that specify the number of instructions in Byteasar&#39;s program and the number of running time queries (for different numbers of processing units).</div>
<div>In the second line of input, there is a sequence of Q integers, K1,k2,…Kq (1&lt;=Ki&lt;=1 000 000), separated by single spaces: Ki is the number of processing units in Byteasar&#39;s i-th query.</div>
<div>In the third and last input line, there is a sequence of N-1 integers, A2,A2…An (1&lt;=Ai&lt;i), separated by single spaces: Ai specifies the number of the parent instruction of the instruction number i. The instructions are numbered with successive integers from 1 to N, where the instruction no. 1 is the first instruction of the program.</div>
<p></p></div>

# Output

<div class="content"><div>
<div>Your program should print one line consisting of Q integers, separated by single spaces, to the standard output: the i-th of these numbers should specify the minimum execution time of the program on a supercomputer with Ki processing units.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">20 1<br/>
3<br/>
1 1 1 3 4 3 2 8 6 9 10 12 12 13 14 11 11 11 11<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p><div>1</div><br/>
<div>2</div><br/>
<div>3</div><br/>
<div>4</div><br/>
<div>5</div><br/>
<div>6</div><br/>
<div>7</div><br/>
<div>8</div><br/>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span> <span class="Apple-tab-span" style="white-space:pre">	</span> </div><br/>
<div>2<span class="Apple-tab-span" style="white-space:pre">	</span>3<span class="Apple-tab-span" style="white-space:pre">	</span>4</div><br/>
<div>5<span class="Apple-tab-span" style="white-space:pre">	</span>6<span class="Apple-tab-span" style="white-space:pre">	</span>7</div><br/>
<div>8<span class="Apple-tab-span" style="white-space:pre">	</span>10<span class="Apple-tab-span" style="white-space:pre">	</span> </div><br/>
<div>9<span class="Apple-tab-span" style="white-space:pre">	</span>12<span class="Apple-tab-span" style="white-space:pre">	</span> </div><br/>
<div>11<span class="Apple-tab-span" style="white-space:pre">	</span>13<span class="Apple-tab-span" style="white-space:pre">	</span>14</div><br/>
<div>15<span class="Apple-tab-span" style="white-space:pre">	</span>16<span class="Apple-tab-span" style="white-space:pre">	</span>17</div><br/>
<div>18<span class="Apple-tab-span" style="white-space:pre">	</span>19<span class="Apple-tab-span" style="white-space:pre">	</span>20</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Claris">鸣谢 Claris</a></p></div>

