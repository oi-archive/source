# 题目描述


<h3>
【题目描述】
</h3>
<p>
    <img src="/upload/image/20131214/20131214110050_26832.png" alt=""/> 
</p>
<p>
    农夫约翰的N头奶牛(3 &lt;= N &lt;= 1000)站在一排，每一处有明显的位置线。他们正在练习投掷棒球，准备对邻近的农场奶牛一场重要的比赛。
</p>
<p>
    农民约翰，他观察一组三头奶牛（x，y，z）完成两个成功的投球。牛X向右投球给牛Y，然后牛Y把球向右抛给牛Z。农民约翰指出：第二投，是第一投的一到二倍远。请计算牛可能的三元组的数目。
</p>
<p>
<br/>
</p>
<p>
(Cow X throws the ball to cow Y on her right, and then cow Y throws the ball to
</p>
<p>
cow Z on her right.)
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第1行：牛的数量，N。
</p>
<p>
第2..1+N行：每行包含一个整数牛位置（范围在0..100000000的整数）。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
*行1：三元组的奶牛数量（X，Y，Z），其中Y在X右边，Z在Y右边，从Y到Z之间的距离为|XY|--2|XY|（含），|XY|是X到Y的距离。
</p>
<h3>
【样例输入】
</h3>
<pre>5
3
1
10
7
4</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
输入详细信息：
</p>
<p>
有5头奶牛，在位置3，1，10，7，和4。
</p>
<p>
输出的细节：
</p>
<p>
四个可能的三元组是奶牛的位置1-3-7，1-4-7，4-7-10，和1-4-10。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
<br/>
</p>
<p>
USACO Dec 13 Bronze
</p>
<p>
data from cstdio
</p>
<p>
<br/>
</p>
