# 

 
 # 题目背景 
<p>蒟蒻中学校医YJZ遇到了一些小问题。</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>蒟蒻中学校医YJZ在治疗<strong>左旋咪挫致脱髓鞘脑病（</strong><strong>LIDE）</strong>时，发现一种感染细菌，此细菌的数量在达到一个值后会导致患者迅速发病，为及早进行治疗，YJZ希望计算出这种细菌的增长速度。已知这种细菌每一秒会产生一只新细菌，3秒后死亡。<b>在第i秒新生的细菌需要1秒钟准备时间，在第i+1秒才会产生新细菌。</b>现给出一个时间n，请你帮忙计算出此细菌在n秒时的增长速度，并保留t位小数输出。第一秒时YJZ只有一个细菌，没有新的细菌产生。</p>

<p><strong>增长速度的定义：设细菌在第</strong><strong>i</strong><strong>秒时出生的数量为</strong><strong>x</strong><strong>，在第</strong><strong>i-1</strong><strong>秒时数量出生为</strong><strong>y&nbsp;</strong><strong>则第</strong><strong>i</strong><strong>秒增长速度为</strong><strong>x/y</strong></p>

<p><strong>三秒后死亡的定义：细菌在第i秒出生，在第i+3秒死亡，并且在i+2秒至第i+3秒的过程中不会产生新细菌</strong></p>

<p><strong>详细请参考样例</strong></p> 

 
 # 输入格式 
<p>一行两个数，n和t&nbsp;分别表示第n秒时的增长速度和保留t位小数输出</p> 

 
 # 输出格式 
<p>一行一个数，为第n秒时的增长速度</p> 

 
 # 提示 
<p><strong>样例输入：</strong></p>

<p>4&nbsp;3</p>

<p>&nbsp;</p>

<p><strong>样例输出：</strong></p>

<p>1.500</p>

<p>&nbsp;</p>

<p><strong style="line-height: 20.7999992370605px;">样例解释：</strong></p>

<p>第一秒没有新的细菌产生，只有一只细菌A，它在进行准备。</p>

<p>第二秒第一只细菌产生了新细菌B。第二秒时产生了1只新细菌。</p>

<p>第三秒时两只细菌均会产生新细菌，产生了细菌C,D。第三秒时产生了2只新细菌。</p>

<p>第四秒时细菌A死亡。细菌B,C,D分别产生了细菌E,F,G。第四秒时产生了3只新细菌。</p>

<p>所以答案为3/2=1.5&nbsp;保留3位小数输出&nbsp;为1.500</p>

<p><strong>数据范围：</strong></p>

<p>对于30%的数据&nbsp;3&lt;=n&lt;=100</p>

<p>对于60%的数据&nbsp;3&lt;=n&lt;=10^9</p>

<p>对于100%的数据&nbsp;3&lt;=n&lt;=10^1000&nbsp;1&lt;=t&lt;=10</p> 
