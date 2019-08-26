
# Description

<div class="content"><div>牛牛是一个热爱算法设计的高中生。在他设计的算法中，常常会使用带小数的数进行计算。牛牛认为，如果在 k </div>
<div>进制下，一个数的小数部分是纯循环的，那么它就是美的。现在，牛牛想知道：对于已知的十进制数 n 和 m，在 </div>
<div>kk 进制下，有多少个数值上互不相等的纯循环小数，可以用分数 xy 表示,其中 1≤x≤n,1≤y≤m，且 x,y是整数</div>
<div>。一个数是纯循环的，当且仅当其可以写成以下形式：a.c1˙c2c3…cp-1cp˙其中，a 是一个整数，p≥1；对于 1</div>
<div>≤i≤p，ci是 kk 进制下的一位数字。例如，在十进制下，0.45454545……=0.4˙5˙是纯循环的，它可以用 5/11</div>
<div>、10/22 等分数表示；在十进制下，0.1666666……=0.16˙则不是纯循环的，它可以用 1/6 等分数表示。需要特</div>
<div>别注意的是，我们认为一个整数是纯循环的，因为它的小数部分可以表示成 0 的循环或是 k?1 的循环；而一个小</div>
<div>数部分非 0 的有限小数不是纯循环的。</div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">
<div>只有一行，包含三个十进制数N,M,K意义如题所述,保证 1≤n≤10^9,1≤m≤10^9,2≤k≤2000</div>
</div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">一行一个整数，表示满足条件的美的数的个数。</div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 6 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
explanation<br/>
满足条件的数分别是：<br/>
1/1=1.0000……<br/>
1/3=0.3333……<br/>
2/1=2.0000……<br/>
2/3=0.6666……<br/>
1/1 和 2/2 虽然都是纯循环小数，但因为它们相等，因此只计数一次；同样，1/3 和 2/6 也只计数一次。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

