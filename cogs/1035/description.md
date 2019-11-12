# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目背景】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">『Citric杯』NOIP模拟赛 I 第一题</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">某天Lemon去超市买柠檬，他发现货架上有N个柠檬，每个柠檬都有一个重量Wi和价格Ci.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon身上只带了S元钱，因此他想要买一个价格不超过S的柠檬回家，另外，他希望他买的那个柠檬的性价比尽量高。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">性价比的定义是重量除以价格，即第i个柠檬的性价比是Wi/Ci. 你的任务是告诉Lemon，他应该买第几个柠檬。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件第一行包含两个正整数N，S</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件第2～N+1行，每行包含两个正整数Wi，Ci，第i+1行的数表示第i个柠檬的重量和价格。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件第一行仅包含一个数K，表示购买第K只柠檬能使Lemon在可以接受的价格内获得最高的性价比。题目保证答案唯一。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 15</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 8</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">10000 20</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第1只柠檬重量为4，价格为8，性价比为4/8=0.5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第2只柠檬重量为4，价格为10，性价比为4/10=0.4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第3只柠檬重量为8，价格为10，性加比为8/10=0.8</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第4只柠檬重量为10000，价格为20，性价比为10000/20=500，但Lemon只带了15元，无法购买这只柠檬</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">因此Lemon的最佳选择是第3只柠檬。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模约定】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制为1s</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，满足0<n<=100000；0<s<=10^9；0<wi,ci<=10^9；n，s，w，c均为整数。< span=""><br/>
<br/>
</n<=100000；0<s<=10^9；0<wi,ci<=10^9；n，s，w，c均为整数。<></span>
