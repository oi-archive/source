
# Description

<div class="content"><div>留意着农场之外的长期职业生涯的可能性，奶牛Bessie开始在不同的在线编程网站上学习算法。她最喜欢的两个算</div>
<div>法是“冒泡排序”和“快速排序”，但是不幸的是Bessie轻易地把它们搞混了，最后实现了一个奇怪的混合算法！</div>
<div></div>
<div>如果数组A中A[...i]的最大值不大于A[i+1…]的最小值，我们就称元素i和i+1之间的位置为一个“分隔点”。Bess</div>
<div>ie还记得快速排序包含对数组的重排，产生了一个分隔点，然后要递归对两侧的A[...i]和A[i+1…]排序。然而，</div>
<div>尽管她正确地记下了数组中所有的分隔点都可以在线性时间内被求出，她却忘记快速排序应该怎么重排来快速构造</div>
<div>一个分隔点了！在这个可能会被证明是排序算法的历史中最糟糕的算法性失误之下，她做出了一个不幸的决定，使</div>
<div>用冒泡排序来完成这个任务。</div>
<div></div>
<div>以下是Bessie最初的对数组A</div>
<div></div>
<div>进行排序的实现的概要。她首先写了一个简单的函数，执行冒泡排序的一轮：</div>
<div></div>
<div>bubble_sort_pass (A) {</div>
<div>   for i = 0 to length(A)-2</div>
<div>      if A[i] &gt; A[i+1], swap A[i] and A[i+1]</div>
<div>}</div>
<div></div>
<div>她的快速排序（相当快）函数的递归代码是按下面的样子构成的：</div>
<div></div>
<div>quickish_sort (A) {</div>
<div>   if length(A) = 1, return</div>
<div>   do { // Main loop</div>
<div>      work_counter = work_counter + length(A)</div>
<div>      bubble_sort_pass(A)</div>
<div>   } while (no partition points exist in A) </div>
<div>   divide A at all partition points; recursively quickish_sort each piece</div>
<div>}</div>
<div></div>
<div>Bessie好奇于她的代码能够运行得多快。简单起见，她计算出她得主循环的每一轮都消耗线性时间，</div>
<div>所以她相应增加一个全局变量work_counter的值，以此来跟踪整个算法总共完成的工作量。</div>
<div></div>
<div>给定一个输入数组，请预测quickish_sort函数接收这个数组之后，变量work_counter的最终值。</div>
<div></div></div>

# Input

<div class="content"><div>输入的第一行包含N,接下来N行描述了A[0]…A[N-1]，每个数都是一个范围为0…10^9的整数。</div>
<div>输入数据不保证各不相同。</div>
<div>（1≤N≤100,000）</div>
<div></div></div>

# Output

<div class="content"><div>输出work_counter的最终值</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
20<br/>
2<br/>
3<br/>
4<br/>
9<br/>
8<br/>
7</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
在这个例子中，数组开始时为20 2 3 4 9 8 7。在一轮冒泡排序之后（增加7的工作量），我们得到2 | 3 | 4 | 9<br/>
 8 7 | 20，其中|表示一个分隔点。于是我们的问题被分成了递归的子问题，包括对2、3、4、20排序（每个消耗0<br/>
单元的工作量）和对9 8 7排序。对于9 8 7这个子问题，主循环的一轮（3单元工作量）得到8 7 | 9，在此之后最<br/>
后一轮处理8 7（2单元工作量） 就有效地完成了排序</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

