
# Description

<div class="content"><div>Farmer John is arranging his N cows in a line to take a photo (1≤N≤100,000). The height of the iit</div>
<div>h cow in sequence is hihi, and the heights of all cows are distinct.As with all photographs of his c</div>
<div>ows, FJ wants this one to come out looking as nice as possible. He decides that cow ii looks &#34;unbala</div>
<div>nced&#34; if Li and RRi differ by more than factor of 2, where LiLi and RiRi are the number of cows tall</div>
<div>er than i on her left and right, respectively. That is, ii is unbalanced if the larger of Li and Ri </div>
<div>is strictly more than twice the smaller of these two numbers. FJ is hoping that not too many of his </div>
<div>cows are unbalanced.Please help FJ compute the total number of unbalanced cows.</div>
<div>农夫约翰正在安排他的N头牛拍照片， 每头牛有一个身高，从1到N编号，排列成一行(h1,h2...hn)，每头牛i左边</div>
<div>比他高的牛的数量记为Li，右边比他高的牛的数量记为Ri，如果存在i满足max(Ri,Li)&gt;2*min(Li,Ri)则这个牛i是</div>
<div>不平衡的，现在FJ需要你告诉他有多少头牛不平衡。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N. The next NN lines contain h1…hN</div>
<div>each a nonnegative integer at most 1,000,000,000.</div>
<div>输入第一行为N(N&lt;=1e5)，接下来的一行有N个数，每个数表示第i头牛的身高，不超过1e9</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output a count of the number of cows that are unbalanced.</div>
<div>输出有多少头牛是不平衡的</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
34<br/>
6<br/>
23<br/>
0<br/>
5<br/>
99<br/>
2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
//在这个样例中，身高为34，5,2的牛是不平衡的</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

