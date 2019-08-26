
# Description

<div class="content"><div>小M的实验室有很多电源插排。这些插排的编号从1到N，由左向右排成一排。每天早晨，这些插排都是没有被使用</div>
<div>的。每当一个学生来到实验室，他就将自己的笔记本电源插到某一个未被使用的插排上。实验室的同学们都很奇怪</div>
<div>，他们完成这个过程是这样的：首先，他们找到还没有被使用的插排的最长区间。如果有多个区间长度相同，他们</div>
<div>就选择最靠右的那个。然后将自己的电源插到该区间的中间。如果区间长度是偶数，他们同样选择靠右的那个。当</div>
<div>一个同学离开实验室时，他会将自己的电源拔出来。数据保证每一个同学来到实验室时，至少有一个空的插排。现</div>
<div>在给你实验室同学的来到和离开事件，和一些询问。对于每一个询问，你需要计算在区间[L,R]已经有多少个插排</div>
<div>被使用了。</div>
<p></p></div>

# Input

<div class="content"><div>第一行是两个整数N和Q，表示插排数量和询问数量。</div>
<div>接下来Q行，每一行以一个整数K开头，如果K为0，</div>
<div>接下来就是两个整数L和R(1≤L≤R≤N)，表示一个询问。否则表示编号为K的学生到来或离开(K≤109)。</div>
<div>K的奇数次出现表示到来，偶数次出现表示离开。每个学生的编号都是唯一的。</div>
<div>N ≤ 10^9, Q ≤ 10^5</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一个询问，输出一个整数，表示询问区间内有多少个插排已经被使用了。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 10<br/>
1 2 3<br/>
0 1 2<br/>
0 4 7<br/>
0 2 5<br/>
20<br/>
0 6 6<br/>
99<br/>
0 4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
2 <br/>
2 <br/>
1 <br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

