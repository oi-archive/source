# 题目描述


<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:18.3750pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">Peter</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">最近在</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">R</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">市开了一家快餐店，为了招揽顾客，该快餐店准备推出一种套餐，该套餐由</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个汉堡，</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个薯条和</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">C</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个饮料组成。价格便宜。为了提高产量，</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">Peter</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">从著名的麦当劳公司引进了</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">N</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">条生产线。所有的生产线都可以生产汉堡，薯条和饮料，由于每条生产线每天所能提供的生产时间是有限的、不同的，而汉堡，薯条和饮料的单位生产时间又不同。这使得</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">Peter</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">很为难，不知道如何安排生产才能使一天中生产的套餐产量最大。请你编一程序，计算一天中套餐的最大生产量。为简单起见，假设汉堡、薯条和饮料的日产量不超过</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">100</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输人格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">第一行为三个不超过</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">100</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">的正整数</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">、</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">、</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">C</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">中间以一个空格分开。</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">第二行为</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">3</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个不超过</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">100</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">的正整数</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">p1,p2,p3</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">分别为汉堡，薯条和饮料的单位生产耗时。中间以一个空格分开。</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">第三行为为一个整数</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">N (0&lt;=0&lt;=10)</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">，表示有</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">N</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">条流水线</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">第四行为</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">N</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">个不超过</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">10000</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">的正整数，其中</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">Ti</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">表示第</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">i</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">条生产流水线每天提供的生产时间，中间以一个空格分开。</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">仅一行，即每天套餐的最大产量。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输入样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">2 2 2</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">1 2 2</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">2</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;">6 6</span><span style="font-size:12.0000pt;font-family:&#39;Arial&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">出</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:10.5000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
