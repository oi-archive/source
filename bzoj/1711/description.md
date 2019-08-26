
# Description

<div class="content"><p><span style="font-size: medium">农夫JOHN为牛们做了很好的食品,但是牛吃饭很挑食. 每一头牛只喜欢吃一些食品和饮料而别的一概不吃.虽然他不一定能把所有牛喂饱,他还是想让尽可能多的牛吃到他们喜欢的食品和饮料. 农夫JOHN做了F (1 &lt;= F &lt;= 100) 种食品并准备了D (1 &lt;= D &lt;= 100) 种饮料. 他的N (1 &lt;= N &lt;= 100)头牛都以决定了是否愿意吃某种食物和喝某种饮料. 农夫JOHN想给每一头牛一种食品和一种饮料,使得尽可能多的牛得到喜欢的食物和饮料. 每一件食物和饮料只能由一头牛来用. 例如如果食物2被一头牛吃掉了,没有别的牛能吃食物2. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第一行: 三个数: N, F, 和 D </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 每一行由两个数开始F_i 和 D_i, 分别是第i 头牛可以吃的食品数和可以喝的饮料数.下F_i个整数是第i头牛可以吃的食品号,再下面的D_i个整数是第i头牛可以喝的饮料号码.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: 一个整数,最多可以喂饱的牛数. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 3<br/>
2 2 1 2 3 1<br/>
2 2 2 3 1 2<br/>
2 2 1 3 1 2<br/>
2 1 1 3 3<br/>
<br/>
输入解释:<br/>
<br/>
牛 1:  食品从 {1,2}, 饮料从 {1,2} 中选<br/>
牛 2:  食品从 {2,3}, 饮料从 {1,2} 中选<br/>
牛 3:  食品从 {1,3}, 饮料从 {1,2} 中选<br/>
牛 4:  食品从 {1,3}, 饮料从 {3} 中选<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
输出解释:<br/>
<br/>
一个方案是:<br/>
Cow 1: 不吃<br/>
Cow 2: 食品 #2, 饮料 #2<br/>
Cow 3: 食品 #1, 饮料 #1<br/>
Cow 4: 食品 #3, 饮料 #3<br/>
用鸽笼定理可以推出没有更好的解 (一共只有3总食品和饮料).当然,别的数据会更难.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

