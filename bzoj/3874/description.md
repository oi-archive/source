
# Description

<div class="content"><div> 【故事背景】</div>
<div>自从迷上了拼图，JYY就变成了个彻底的宅男。为了解决温饱问题，JYY</div>
<div>不得不依靠叫外卖来维持生计。</div>
<div>【问题描述】</div>
<div>外卖店一共有N种食物，分别有1到N编号。第i种食物有固定的价钱Pi和保质期Si。第i种食物会在Si天后过期。JYY是不会吃过期食物的。</div>
<div>比如JYY如果今天点了一份保质期为1天的食物，那么JYY必须在今天或</div>
<div>者明天把这个食物吃掉，否则这个食物就再也不能吃了。保质期可以为0天，这</div>
<div>样这份食物就必须在购买当天吃掉。</div>
<div>JYY现在有M块钱，每一次叫外卖需要额外付给送外卖小哥外送费F元。</div>
<div>送外卖的小哥身强力壮，可以瞬间给JYY带来任意多份食物。JYY想知道，在</div>
<div>满足每天都能吃到至少一顿没过期的外卖的情况下，他可以最多宅多少天呢？</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含三个整数M，F和N。</div>
<div>
<div>接下来N行，第i行包含两个整数Pi和Si。</div>
</div></div>

# Output

<div class="content"><p>输出仅包含一行一个整数表示JYY可以宅的最多的天数。</p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">32 5 2<br/>
5 0<br/>
10 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 【样例说明】</p><br/>
<div>JYY的最佳策略是：</div><br/>
<div>第一天买一份食物1和一份食物2并且吃一份食物1；</div><br/>
<div>第二天吃一份食物2；</div><br/>
<div>第三天买一份食物1并且吃掉。</div><br/>
<div></div><br/>
<div>【数据规模与约定】</div><br/>
<div>对于100%的数据满足0&lt;=Si&lt;=10^18,1&lt;=F,Pi,M&lt;=10^18,1&lt;=N&lt;=200</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round2 By 佚名上传">Round2 By 佚名上传</a></p></div>

