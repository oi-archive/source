# 题目描述


<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">问题描述：</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">一位信使来到一个村落送信，他的送信方式是从某户</span><span style="font-family:Microsoft YaHei;font-size:18px;">X1</span><span style="font-family:Microsoft YaHei;font-size:18px;">出发，经过</span><span style="font-family:Microsoft YaHei;font-size:18px;">X2, X3, </span></span><span style="font-family:Microsoft YaHei;font-size:18px;">…</span><span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">, Xn-1</span><span style="font-family:Microsoft YaHei;font-size:18px;">最后到达</span><span style="font-family:Microsoft YaHei;font-size:18px;">Xn</span><span style="font-family:Microsoft YaHei;font-size:18px;">，</span><span style="font-family:Microsoft YaHei;font-size:18px;">X1</span></span><span style="font-family:Microsoft YaHei;font-size:18px;">…</span><span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">Xn</span><span style="font-family:Microsoft YaHei;font-size:18px;">为</span><span style="font-family:Microsoft YaHei;font-size:18px;">1..n</span><span style="font-family:Microsoft YaHei;font-size:18px;">的一种排列。即信使所走的路径为一条链，每户村民都恰好经过一次。这个村落中共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">户村民，第</span><span style="font-family:Microsoft YaHei;font-size:18px;">i(1</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">i</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">n)</span><span style="font-family:Microsoft YaHei;font-size:18px;">户村民可以用一个二元坐标</span><span style="font-family:Microsoft YaHei;font-size:18px;">(xi,yi)</span><span style="font-family:Microsoft YaHei;font-size:18px;">来表示其位置。信使刚刚拿到了村落的地图，但还不知道具体的任务细节，因此他想请你帮他算一下他每次送信可能走的最长路径，同时为了安慰信使，请你把最短路径也告诉他。</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">这是一道提交答案题目，你可以下载输入文件</span><span style="font-family:Microsoft YaHei;font-size:18px;">postman1.in</span></span><span style="font-family:Microsoft YaHei;font-size:18px;">…</span><span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">postman10.in</span><span style="font-family:Microsoft YaHei;font-size:18px;">，提交时只需提交相对应的输出文件</span><span style="font-family:Microsoft YaHei;font-size:18px;">postman1.out</span></span><span style="font-family:Microsoft YaHei;font-size:18px;">…</span><span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">postman10.out</span><span><span style="font-family:Microsoft YaHei;font-size:18px;">。</span><br/>
<br/>
</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输入格式：</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">输入文件共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">n+1</span><span style="font-family:Microsoft YaHei;font-size:18px;">行：</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">第一行是一个整数</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">，表示村落中共有</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">户村民。</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">第</span><span style="font-family:Microsoft YaHei;font-size:18px;">2</span><span style="font-family:Microsoft YaHei;font-size:18px;">到第</span><span style="font-family:Microsoft YaHei;font-size:18px;">n+1</span><span style="font-family:Microsoft YaHei;font-size:18px;">行每行两个整数</span><span style="font-family:Microsoft YaHei;font-size:18px;">xi</span><span style="font-family:Microsoft YaHei;font-size:18px;">和</span><span style="font-family:Microsoft YaHei;font-size:18px;">yi</span><span style="font-family:Microsoft YaHei;font-size:18px;">，表示第</span><span style="font-family:Microsoft YaHei;font-size:18px;">i</span><span><span style="font-family:Microsoft YaHei;font-size:18px;">户村民的坐标。</span><br/>
<br/>
</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">输出格式：</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">输出文件共两行，每行</span><span style="font-family:Microsoft YaHei;font-size:18px;">n</span><span style="font-family:Microsoft YaHei;font-size:18px;">个整数，为</span><span style="font-family:Microsoft YaHei;font-size:18px;">1..n</span><span><span style="font-family:Microsoft YaHei;font-size:18px;">的一种排列，分别表示信使可能走的最长路径和最短路径。</span><br/>
<br/>
</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">输入样例</span><span style="font-family:Microsoft YaHei;font-size:18px;">(</span></span><span style="font-family:Microsoft YaHei;font-size:18px;">postman</span><span style="font-family:Microsoft YaHei;font-size:18px;">c.in)</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">4</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">0 0</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">0 4</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">3 0</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">3 4</span><br/>
<br/>
</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">输出样例</span><span style="font-family:Microsoft YaHei;font-size:18px;">(</span></span><span style="font-family:Microsoft YaHei;font-size:18px;">postman</span><span style="font-family:Microsoft YaHei;font-size:18px;">c.out)</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">1 4 3 2</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">1 3 4 2</span><br/>
<br/>
</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:18px;">评分标准：</span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">评测插件会首先检验你的输出是否合法，若不合法该测试点得</span><span style="font-family:Microsoft YaHei;font-size:18px;">0</span><span style="font-family:Microsoft YaHei;font-size:18px;">分。若输出路径合法，记标准输出的最长和最短路径长度分别为</span><span style="font-family:Microsoft YaHei;font-size:18px;">A</span><span style="font-family:Microsoft YaHei;font-size:18px;">、</span><span style="font-family:Microsoft YaHei;font-size:18px;">B</span><span style="font-family:Microsoft YaHei;font-size:18px;">，选手输出的最长和最短路径长度分别为</span><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">、</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">，则评分标准如下：</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">B </span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">10</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.90A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.10B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">9</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.81A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.21B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">8</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.73A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.33B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">7</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.66A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.46B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">6</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.59A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.61B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">5</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.53A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.77B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">4</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.48A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">1.95B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">3</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C</span><span style="font-family:Microsoft YaHei;font-size:18px;">≥</span><span style="font-family:Microsoft YaHei;font-size:18px;">0.43A</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D</span><span style="font-family:Microsoft YaHei;font-size:18px;">≤</span><span style="font-family:Microsoft YaHei;font-size:18px;">2.14B</span><span style="font-family:Microsoft YaHei;font-size:18px;">得</span><span style="font-family:Microsoft YaHei;font-size:18px;">2</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" 宋体";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:18px;">C&gt;0</span><span style="font-family:Microsoft YaHei;font-size:18px;">且</span><span style="font-family:Microsoft YaHei;font-size:18px;">D&lt;</span><span style="font-family:Microsoft YaHei;font-size:18px;">∞得</span><span style="font-family:Microsoft YaHei;font-size:18px;">1</span><span style="font-family:Microsoft YaHei;font-size:18px;">分</span></span><span style="font-family:" 宋体";font-size:10.5pt;"=""></span> 
</p>
<p>
<br/>
<span style="font-family:Microsoft YaHei;font-size:18px;"> 数据规模：</span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;"> 见数据。</span> 
</p>
