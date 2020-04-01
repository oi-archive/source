
# Description

<div class="content"><div>有n个人，编号分别为1,2,?n。这n个人中每个人不是诚实者就是说谎者，并且每个人都知道下一个人的身份（即第</div>
<div>k个人知道第k+1个人的身份，1&lt;=k&lt;n，且第n个人知道第1个人的身份）。现在已知每个人对他下一个人的身份的判</div>
<div>断，并且说谎者的人数不超过t，问哪些人一定是说谎者。注意，诚实者给出的判断一定是正确的，但说谎者给出</div>
<div>的判断是不确定的，可能正确也可能错误。</div></div>

# Input

<div class="content"><div>第一行一个整数T，表示数据个数。</div>
<div>下面接T组数据，每组数据两行。</div>
<div>第一行为两个正整数n和t，表示一共有n个人，且说谎者人数不超过t。</div>
<div>第二行为n个整数，每个数为0或1。第i个数若为0，则表示第i个人判断下一个人为诚实者；</div>
<div>若为1，则表示第i个人判断下一个人为说谎者。</div>
<div>n&lt;=100000</div></div>

# Output

<div class="content"><div>每组数据输出一行，每行两个整数。</div>
<div>第一个整数表示一定是说谎者的人的个数，第二个数表示一定是说谎者的人中，编号最小的人的编号。若第一个数是0，则第二个数也为0。</div>
<div>若定义集合S={k|第k个人一定是说谎者}，那么第一个数就是|S|，</div>
<div>第二个数就是S中最小的数。若S为空集则第二个数为0</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
5  2<br/>
0  1 1 0 0<br/>
7  2<br/>
0  0 1 0 0 1 1<br/>
9  8<br/>
1  0 0 0 0 1 0 0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1  3<br/>
2  4<br/>
0  0<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

