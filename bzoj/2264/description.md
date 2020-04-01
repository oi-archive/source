
# Description

<div class="content"><p></p>
<p>Petra and Jan have just received a box full of free goodies, and want to divide the goodies between them. However, it is not easy to do this fairly, since they both value different goodies differently.</p>
<p>To divide the goodies, they have decided upon the following procedure: they choose goodies one by one, in turn, until all the goodies are chosen. A coin is tossed to decide who gets to choose the first goodie.</p>
<p>Petra and Jan have different strategies in deciding what to choose. When faced with a choice, Petra always selects the goodie that is most valuable to her. In case of a tie, she is very considerate and picks the one that is least valuable to Jan. (Since Petra and Jan are good friends, they know exactly how much value the other places on each goodie.)</p>
<p>Jan&#39;s strategy, however, consists of maximizing his own final value. He is also very considerate, so if multiple choices lead to the same optimal result, he prefers Petra to have as much final value as possible.</p>
<div class="p"><!----></div>
<p>You are given the result of the initial coin toss. After Jan and Petra have finished dividing all the goodies between themselves, what is the total value of the goodies each of them ends up with?</p>
<p></p>
<p></p>
<p>有两个人，分N个物品，每个物品分别对两个人有不同的价值。两个人每次轮流从未被拿走的物品中拿走一个物品。规则是第一个人每次是拿剩下物品中对他而言价值最高的那个，如果有相同的就会拿那个对另外一个人价值最低的物品。另一个人是每次拿那个能保证他最后能拿到价值最大的物品，当然如果有多种选项的话也会优先选择那个对另外一个人价值最低的物品。现在告诉你物品和谁先拿，问最后两人分别能拿到多少？</p></div>

# Input

<div class="content"><p align="left"><font face="Times New Roman" size="3">On the first line a positive integer: the number of test cases, at most 100. After that per test case: </font></p>
<p>One line with an integer n (1 ≤ n ≤ 1 000): the number of goodies.</p>
<p>One line with a string, either &#34;<tt><font face="NSimsun">Petra</font></tt>&#34; or &#34;<tt><font face="NSimsun">Jan</font></tt>&#34;: the person that chooses first.</p>
<p>n lines with two integers p<sub>i</sub> and j<sub>i</sub> (0 ≤ p<sub>i</sub>,j<sub>i</sub> ≤ 1 000) each: the values that Petra and Jan assign to the i-th goodie, respectively</p></div>

# Output

<div class="content"><p align="left"><font face="Times New Roman" size="3">Per test case: </font></p>
<p>One line with two integers: the value Petra gets and the value Jan gets. Both values must be according to their own valuations</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4<br/>
Petra<br/>
100 80<br/>
70 80<br/>
50 80<br/>
30 50<br/>
4<br/>
Petra<br/>
10 1<br/>
1 10<br/>
6 6<br/>
4 4<br/>
7<br/>
Jan<br/>
4 1<br/>
3 1<br/>
2 1<br/>
1 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">170 130<br/>
14 16<br/>
9 10<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

