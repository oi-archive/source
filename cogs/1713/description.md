# 题目描述


<h3>
【题目描述】
</h3>
<p>
Little cat在Byterland的首都读物理专业。这些天他收到了一条悲伤地信息：他的母亲生病了。担心买火车票花钱太多（Byterland是一个巨大的国家，因此他坐火车回家需要16小时），他决定只给母亲发短信。
</p>
<p>
Little cat的家境并不富裕，因此他经常去营业厅查看自己发短信花了多少钱。昨天营业厅的电脑坏掉了，打印出两条很长的信息。机智的little cat很快发现：
</p>
<p>
1.信息中所有的字符都是小写英文字母，没有标点和空格。
</p>
<p>
2.所有的短信都被连在了一起——第i+1条短信直接接在第i条短信后面——这就是这两条信息如此长的原因。
</p>
<p>
3.虽然他发的短信都被连在了一起，但由于电脑坏掉了，它们的左边或右边都可能会有许多冗余字符。
</p>
<p>
例如：如果短信是&#34;motheriloveyou&#34;，电脑打印出的每条信息都可能是&#34;hahamotheriloveyou&#34;,&#34;motheriloveyoureally&#34;,&#34;motheriloveyouornot&#34;,&#34;bbbmotheriloveyouaaa&#34;，等等。
</p>
<p>
4.因为这些乱七八糟的问题，little cat打印了两遍（所以有两条非常长的信息）。尽管原始的短信文本在两条信息中都一样，但两条信息在文本两侧的冗余字符都可能不一样。
</p>
<p>
给出这两条很长的信息，输出little cat写下的原始短信文本的最长可能长度。
</p>
<p>
背景：
</p>
<p>
在Byterland，短信按照美元/字节的单位计价。这就是little cat想要知道原始文本最长可能长度的原因。
</p>
<p>
为什么让你写一个程序？有四个原因：
</p>
<p>
1.little cat这些天忙于他的物理课程。
</p>
<p>
2.little cat不想透露他对母亲说了什么。
</p>
<p>
3.POJ是个好网站。
</p>
<p>
4.little cat想要从POJ那里挣点钱，并尝试说服他的母亲去医院:(
</p>
<h3>
【输入格式】
</h3>
<p>
两行两个由小写英文字母组成的字符串。字符串长度都不会超过100000
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个整数，即little cat写下的原始文本的最长可能长度。
</p>
<h3>
【样例输入】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;line-height:20px;background-color:white;">yeshowmuchiloveyoumydearmotherreallyicannotbelieveit</span> 
</p>
<p>
yeaphowmuchiloveyoumydearmother
</p>
<h3>
【样例输出】
</h3>
<p>
27
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://poj.org/problem?id=2774" target="_blank">POJ 2774 Long Long Message</a> 
</p>
<p>
Problem by 朱泽园，“献给我深爱的母亲。”
</p>
