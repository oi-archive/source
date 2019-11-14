
# Description

<div class="content"><p><span style="font-size: medium">Consider integer numbers from 1 to n. Let us call the sum of digits of an integer number its weight. Denote the weight of the number x as w(x). Now let us order the numbers using so called graduated lexicographical ordering, or shorter grlex ordering. Consider two integer numbers a and b. If w(a) &lt; w(b) then a goes before b in grlex ordering. If w(a) = w(b) then a goes before b in grlex ordering if and only if the decimal representation of a is lexicographically smaller than the decimal representation of b. Let us consider some examples. 120 &lt; grlex4 since w(120) = 1 + 2 + 0 = 3 &lt; 4 = w(4). 555 &lt; grlex78 since w(555) = 15 = w(78) and &#34;555&#34; is lexicographicaly smaller than &#34;78&#34;. 20 &lt; grlex200 since w(20) = 2 = w(200) and &#34;20&#34; is lexicographicaly smaller than &#34;200&#34;. Given n and some integer number k, find the position of the number k in grlex ordering of integer numbers from 1 to n, and the k-th number in this ordering. </span></p>
<p></p>
<p><span style="font-size: medium">考虑所有从1到n的整数。我们设一个整数 x 的十进制各位数字之和为 w(x)。 <br/>
让我们重新将整数排序：对于整数a 和整数b，如果w(a)&lt;w(b)，则a 在 b之前。如果<br/>
w(a)=w(b)，那么a 在b之前当且仅当a 的十进制表示在字典序中小于 b 的十进制表示。例<br/>
如： <br/>
120 &lt; grlex4 因为  w(120) = 1 + 2 + 0 = 3 &lt; 4 = w(4)。 <br/>
555 &lt; grlex78 因为  w(555) = 15 = w(78) 并且  &#34;555&#34;  的字典序小于  &#34;78&#34;。 <br/>
20 &lt; grlex200 因为  w(20) = 2 = w(200) 并且  &#34;20&#34;  的字典序小于  &#34;200&#34;。 <br/>
给定整数n和k，你需要求出1-n中的数按照上述方法排序后，k是第几个数，以及第 k<br/>
个数是多少。 <br/>
输入：包含多组数据，每组数据包含两个整数 n和 k。输入的最后一行是 n=k=0。 <br/>
输出：对于每组数据，输出一行两个整数，分别表示k在 1-n中的编号，以及第 k个数<br/>
是多少。 <br/>
数据规模：1 ≤ k ≤ n ≤ 10^18<br/>
。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">There are several lines in the input file, and each line stands two integers n and k (1 &lt;= k &lt;= n &lt;= 10^18). </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each line in the input, output one line in the output file. First print the position of the number k in grlex ordering of integer numbers from 1 to n, and then the integer that occupies the k-th position in this ordering. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">20 10<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 14<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

