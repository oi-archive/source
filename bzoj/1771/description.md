
# Description

<div class="content"><p><span style="font-size: medium">農夫約翰的N（1 &lt;= N &lt;= 1000）只奶牛（編號為1到N）決定成立M個學習小組（1 &lt;= M &lt;= 100）。在學習小組G_i中有S_i只牛，分別為牛G_i1、G_i2⋯⋯一頭牛可能會參加多個小組。 對於每個學習小組，有一只牛必須在每次聚會的時候帶餅乾飲料請大家吃（衰～）。因為買這些零食會消耗牛們那為數不多的零花錢，還會花費牛們寶貴的時間（這些金錢和時間本來是可以用來泡MM的），所以牛們希望盡可能公平地分攤帶零食的責任。 牛們決定。如果一只牛參加了K個學習小組，K個學習小組的大小分別為c_1、c_2、⋯、c_K，那麼她最多負責為ceil(1/c_1 + 1/c_2 + ⋯ + 1/c_K)個學習小組的聚會帶零食。其中ceil為上取整函數。 請计算出一个方案，决定每个学习小组的聚会由哪一头牛负责带零食。如果没有一种方案可行，输出&#34;-1&#34;。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">＊第一行：兩個由空格隔開的整數：N和M。 </span></p>
<p><span style="font-size: medium">＊第二到第M+1行：第i+1行包含若干由空格隔開的整數：S_i，G_i1，G_i2⋯⋯ </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">＊第1至第M行：如果有符合要求的方案，第i行有一個整數，表示為第i個學習小組的聚會帶 零食的奶牛的編號。如果沒有符合要求的方案，那麼第一行只包含一個整數-1。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
3 2 4 5<br/>
2 1 3<br/>
3 1 2 3<br/>
1 1<br/>
2 2 5<br/>
3 2 3 4<br/>
<br/>
輸入細節：<br/>
<br/>
第一、第二和第三只牛願意為兩個學習小組的聚會帶零食，第四和第五只牛只願意為一個學習<br/>
小組帶零食。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
3<br/>
1<br/>
2<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>请不要提交本题.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

