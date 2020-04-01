
# Description

<div class="content"><div>在 Byteland一共开着 n家商店，编号依次为 1到 n，其中编号为1到 m的商店有日消费量上限，第 i家商店的日消</div>
<div>费量上限为wi。Byteasar每次购物的过程是这样的：依次经过每家商店，然后购买非负整数价格的商品，并在结账</div>
<div>的时候在账本上写上在这家商店消费了多少钱。当然，他在这家商店也可以什么都不买，然后在账本上写上一个0</div>
<div>。这一天， Byteasar日常完成了一次购物，但是他不慎遗失了他的账本。他只记得自己这一天一共消费了多少钱</div>
<div>，请写一个程序，帮助 Byteasar计算有多少种可能的账单。 </div>
<div></div></div>

# Input

<div class="content"><div>第一行包含三个正整数 </div>
<div>n, m, k，分别表示商店的个数、有限制的商店个数以及总消费量。</div>
<div>第二行包含 m个整数，依次表示 w1;w2...wm。 </div>
<div>1 ≤ m ≤ n，0≤ wi ≤ 300，1 ≤ n, k ≤ 5000000</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">m&lt;=300</span></div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即可能的账单数，由于答案可能很大，请对1000000007取模输出。 </div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 8<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
HINT<br/>
6 种方案分别为：{0; 0; 8}; {1; 0; 7}; {2; 0; 6}; {0; 1; 7}; <br/>
{1; 1; 6}; {2; 1; 5}。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Claris原创，本站版权所有">Claris原创，本站版权所有</a></p></div>

