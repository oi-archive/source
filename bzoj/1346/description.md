
# Description

<div class="content">有一个国家，流通着N种面值的硬币，其中包括了1分硬币。另外，有一种面值为K分的纸币，它超过了所有硬币的面值。 
有一位硬币收藏家，他想收集每一种面值的硬币样本。他家里已经有一些硬币，但是现在他只带着一张K分纸币去商店。 
商店里总共有K-1种商品，价格分别为1分、2分……K-1分。这家商店使用以下算法找零： 
1、 假设总共需要找A分； 
2、 寻找最高的不超过A的硬币面值，设它为B分硬币； 
3、 给顾客一枚B分硬币，然后令A为A-B； 
4、 如果A=0，算法结束；否则转2。 
收藏家想用他的K分纸币买一件商品。请你编写程序，计算： 
 收藏家能够得到多少种他还没有过的硬币？ 
 在满足上一问的前提下，他能够买的最贵的商品是什么？ 
</div>

# Input

<div class="content">第一行为两个整数N(1≤N≤500000)和K(2≤K≤1000000000)。 
以下N行描述流通的硬币。第i+1行包含两个整数ci(1≤ci

</div>

# Output

<div class="content">第一行为一个整数，表示收藏家最多能获得多少种之前还没有的硬币。 
第二行为一个整数，表示在前一问的前提下，收藏家能购买的最贵的商品价格。 

</div>

# Sample Input

<div class="content"><span class="sampledata">7 25<br/>
1 0<br/>
2 0<br/>
3 1<br/>
5 0<br/>
10 0<br/>
13 0<br/>
20 0<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
3<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

