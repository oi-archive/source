# 题目描述


<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">字串变换</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【问题描述】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">这一天，FK、ZYN和LHC又聚到了一起，在街上闲逛。突然，FK发现周围存</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">在不少字符串，比如：KFC、KTV、WC、MALL。。。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">于是，FK便又想了一个无厘头的问题，去刁难另外两个人。由于前些日子，</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">ZYN和LHC刚学习了集合，这个问题当然要和集合有关拉。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">定义一个（大写字母）字符串集合{S}，初始时只包含一个给定的字符串S1。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">每次从中任意取出一个字符串，将它们变换后再放入集合中。要求变换后的字</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">符串，在集合中没有出现过。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">变换的规则如下：在变换前、后，字符串都必须由大写字母组成，每次只准</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">改动一个位置，使它的ASCLL加1。例如:&#39;A&#39;-&gt;&#39;B&#39;、&#39;B&#39;-&gt;&#39;C&#39;、&#39;C&#39;-&gt;&#39;D&#39;、。。。、</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">&#39;Y&#39;-&gt;&#39;Z&#39;。而如果该位置为&#39;Z&#39;，则无法改动。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">那么，若干次操作后，该集合的元素个数一定会达到最大。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">而对于现在的{S}集合中的每个字符串Si（S1除外），都是由另外一个字符</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">串Sj=F(Si)转换得到的，把所有的F(Si)罗列下来，把它称作一种方案。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">例如：S1-&gt;S2、S1-&gt;S4、S4-&gt;S3</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">方案：(NO)、S1、S4、S1</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">而求的就是该集合的最大元素个数，以及构成有多少种不同的方案。ZYN和</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">LHC这个时候已经被绕晕，只好再次把这个任务交给你了。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">从文件change.in中读入数据。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第1行有1个由大写字母组成字符串</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出到文件change.out中。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出2行，每行包含1个数，第1行表示最大元素个数，第2行表示方案数，</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">答案都取模10007。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输入】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">XYZ</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输出】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">6</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例解释】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">最终集合为：</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">{&#39;XYZ&#39;,&#39;XZZ&#39;,&#39;YYZ&#39;,&#39;YZZ&#39;,&#39;ZYZ&#39;,&#39;ZZZ&#39;}</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">令XY S1=&#39;XYZ&#39;,S2=&#39;XZZ&#39;,S3=&#39;YYZ&#39;,S4=&#39;YZZ&#39;,S5=&#39;ZYZ&#39;,S6=&#39;ZZZ&#39;</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">构成的方案有：</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1.(NO),S1,S1,S2,S3,S4</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2.(NO),S1,S1,S3,S3,S4</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3.(NO),S1,S1,S2,S3,S5</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4.(NO),S1,S1,S3,S3,S5</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【数据范围】</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于30%数据，字符串长度≤5</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于60%数据，字符串长度≤25</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于100%数据，字符串长度≤400</span><br/>
