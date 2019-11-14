
# Description

<div class="content"><p>　　小春现在很清闲,面对书桌上的N张牌,他决定给每张染色,目前小春只有3种颜色:红色,蓝色,绿色.他询问Sun有<br/>
多少种染色方案,Sun很快就给出了答案.进一步,小春要求染出Sr张红色,Sb张蓝色,Sg张绝色.他又询问有多少种方<br/>
案,Sun想了一下,又给出了正确答案. 最后小春发明了M种不同的洗牌法,这里他又问Sun有多少种不同的染色方案.<br/>
两种染色方法相同当且仅当其中一种可以通过任意的洗牌法(即可以使用多种洗牌法,而每种方法可以使用多次)洗<br/>
成另一种.Sun发现这个问题有点难度,决定交给你,答案可能很大,只要求出答案除以P的余数(P为质数).</p></div>

# Input

<div class="content"><p>　　第一行输入 5 个整数：Sr,Sb,Sg,m,p(m&lt;=60,m+1&lt;p&lt;100)。n=Sr+Sb+Sg。<br/>
接下来 m 行，每行描述一种洗牌法，每行有 n 个用空格隔开的整数 X1X2...Xn，恰为 1 到 n 的一个排列，<br/>
表示使用这种洗牌法，第 i位变为原来的 Xi位的牌。输入数据保证任意多次洗牌都可用这 m种洗牌法中的一种代<br/>
替，且对每种洗牌法，都存在一种洗牌法使得能回到原状态。<br/>
<br/>
</p></div>

# Output

<div class="content"><p>　　不同染法除以P的余数</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 1 2 7<br/>
2 3 1<br/>
3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>　　有2 种本质上不同的染色法RGB 和RBG，使用洗牌法231 一次可得GBR 和BGR，使用洗牌法312 一次 可得BRG <br/><br/>
和GRB。<br/><br/>
100%数据满足 Max{Sr,Sb,Sg}&lt;=20。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

