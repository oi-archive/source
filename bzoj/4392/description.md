
# Description

<div class="content"><p>Farmer John is trying to hire contractors to help rearrange his farm, but so far all of them have quit when they saw the complicated sequence of instructions FJ wanted them to follow. Left to complete the project by himself, he realizes that indeed, he has made the project perhaps more complicated than necessary. Please help him follow his instructions to complete the farm upgrade.<br/>
<br/>
FJ&#39;s farm consists of NN fields in a row, conveniently numbered 1…N1…N. In each field there can be any number of haybales. Farmer John&#39;s instructions contain three types of entries:<br/>
<br/>
1) Given a contiguous interval of fields, add a new haybale to each field.<br/>
<br/>
2) Given a contiguous interval of fields, determine the minimum number of haybales in a field within that interval.<br/>
<br/>
3) Given a contiguous interval of fields, count the total number of haybales inside that interval.</p>
<p>农夫约翰打算重修他的农场。他有 N 块土地，连续排列成一行，标号为 1…N。在每块土地上有任意数量的草堆。他可以发出三种指令：<br/>
1) 对一个连续区间的土地，每块土地增加相同数量的草堆。<br/>
2) 对一个连续区间的土地，输出其中最少的草堆数量。<br/>
3) 对一个连续区间的土地，输出草堆数量总数。<br/>
<br/>
第一行两个正整数，N (1≤N≤200,000) 和 Q (1≤Q≤100,000)。<br/>
下一行是N个非负整数，最大100,000，表示每块土地上有多少个草堆。<br/>
以下Q行，每行一单个大写字母开头(M，P或S)，空格后跟随两个正整数 A 和 B (1≤A≤B≤N), 或者三个正整数 A, B, 和 C (1≤A≤B≤N; 1≤C≤100,000)。当且仅当第一个字母是 P 时，是三个正整数。<br/>
当该字母是M，输出区间A…B的最小草堆数。<br/>
当该字母是P，在区间A…B，每块土地增加C堆草。<br/>
当该字母是M，输出区间A…B的草堆数之和。<br/>
<br/>
每行一个数字，用于响应&#39;M&#39; 或 &#39;S&#39; 命令。</p>
<p></p></div>

# Input

<div class="content"><p>The first line contains two positive integers, N (1≤N≤200,000) and Q (1≤Q≤100,000).<br/>
<br/>
The next line contains N nonnegative integers, each at most 100,000, indicating how many haybales are initially in each field.<br/>
<br/>
Each  of the next Q lines contains a single uppercase letter, either M, P or  S, followed by either two positive integers AA and BB (1≤A≤B≤N), or  three positive integers AA, BB, and CC (1≤A≤B≤N; 1≤C≤100,000). There  will be three positive integers if and only if the uppercase letter is  P.<br/>
<br/>
If the letter is M, print the minimum number of haybales in the interval of fields from A…B.<br/>
<br/>
If the letter is P, put C new haybales in each field in the interval of fields from A…B.<br/>
<br/>
If the letter is S, print the total number of haybales found within interval of fields from A…B.</p></div>

# Output

<div class="content"><p>A line in the output should appear in response to every &#39;M&#39; or &#39;S&#39; entry in FJ&#39;s instructions.</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
3 1 2 4<br/>
M 3 4<br/>
S 1 3<br/>
P 2 3 1<br/>
M 3 4<br/>
S 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
6<br/>
3<br/>
8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum鸣谢Claris提供译文">Platinum鸣谢Claris提供译文</a></p></div>

