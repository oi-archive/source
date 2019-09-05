# 题目描述


<p>
<span style="font-family:Verdana;"><span style="font-family:&#34;font-size:12pt;">最近，阿Q</span><span style="font-family:&#34;font-size:12pt;">开了一间宠物收养所。收养所提供两种服务：收养被主人遗弃的宠物和让新的主人领养这些宠物。</span><span style="font-family:&#34;font-size:12pt;">每个领养者都希望领养到自己满意的宠物，阿</span><span style="font-family:&#34;font-size:12pt;">Q</span><span style="font-family:&#34;font-size:12pt;">根据领养者的要求通过他自己发明的一个特殊的公式，得出该领养者希望领养的宠物的特点值</span><span style="font-family:&#34;font-size:12pt;">a</span><span style="font-family:&#34;font-size:12pt;">（</span><span style="font-family:&#34;font-size:12pt;">a</span><span style="font-family:&#34;font-size:12pt;">是一个正整数，</span><span style="font-family:&#34;font-size:12pt;">a&lt;2^31），而他也给每个处在收养所的宠物一个特点值。这样他就能够很方便的处理整个领养宠物的过程了，宠物收养所总是会有两种情况发生：被遗弃的宠物过多或者是想要收养宠物的人太多，而宠物太少。</span></span> 
</p>
<div style="margin-left:18pt;">
<span style="font-family:Verdana;"><span style="font-family:&#34;font-size:12pt;">1．被遗弃的宠物过多时，假若到来一个领养者，这个领养者希望领养的宠物的特点值为</span><span style="font-family:&#34;font-size:12pt;">a</span><span style="font-family:&#34;font-size:12pt;">，那么它将会领养一只目前未被领养的宠物中特点值最接近</span><span style="font-family:&#34;font-size:12pt;">a</span><span style="font-family:&#34;font-size:12pt;">的一只宠物。（任何两只宠物的特点值都不可能是相同的，任何两个领养者的希望领养宠物的特点值也不可能是一样的）如果有两只满足要求的宠物，即存在两只宠物他们的特点值分别为</span><span style="font-family:&#34;font-size:12pt;">a-b</span><span style="font-family:&#34;font-size:12pt;">和</span><span style="font-family:&#34;font-size:12pt;">a+b</span><span style="font-family:&#34;font-size:12pt;">，那么领养者将会领养特点值为</span><span style="font-family:&#34;font-size:12pt;">a-b的那只宠物。</span></span> 
</div>
<div style="margin-left:18pt;">
<span style="font-family:Verdana;"><span style="font-family:&#34;font-size:12pt;">2．收养宠物的人过多，假若到来一只被收养的宠物，那么哪个领养者能够领养它呢？能够领养它的领养者，是那个希望被领养宠物的特点值最接近该宠物特点值的领养者，如果该宠物的特点值为</span><span style="font-family:&#34;font-size:12pt;">a</span><span style="font-family:&#34;font-size:12pt;">，存在两个领养者他们希望领养宠物的特点值分别为</span><span style="font-family:&#34;font-size:12pt;">a-b</span><span style="font-family:&#34;font-size:12pt;">和</span><span style="font-family:&#34;font-size:12pt;">a+b</span><span style="font-family:&#34;font-size:12pt;">，那么特点值为</span><span style="font-family:&#34;font-size:12pt;">a-b的那个领养者将成功领养该宠物。</span></span> 
</div>
<div>
<span style="font-family:Verdana;"> </span> 
</div>
<div>
<span style="font-family:Verdana;"><span style="font-family:&#34;font-size:12pt;">一个领养者领养了一个特点值为a</span><span style="font-family:&#34;font-size:12pt;">的宠物，而它本身希望领养的宠物的特点值为</span><span style="font-family:&#34;font-size:12pt;">b</span><span style="font-family:&#34;font-size:12pt;">，那么这个领养者的不满意程度为</span><span style="font-family:&#34;font-size:12pt;">abs(a-b)。</span></span> 
</div>
<div>
<span style="font-family:&#34;"><b><span style="font-family:&#34;font-size:large;">【任务描述】</span></b></span> 
</div>
<div>
<span style="font-family:&#34;"><span style="font-family:&#34;font-size:12pt;">你得到了一年当中，领养者和被收养宠物到来收养所的情况，希望你计算所有收养了宠物的领养者的不满意程度的总和。这一年初始时，收养所里面既没有宠物，也没有领养者。</span></span> 
</div>
<div>
<span style="font-family:&#34;"><b><span style="font-family:&#34;font-size:large;">【输入格式】</span></b></span> 
</div>
<div>
<span style="font-family:Verdana;"><span style="font-family:&#34;font-size:12pt;">你将从文件当中读入数据。文件的第一行为一个正整数</span><span style="font-family:&#34;font-size:12pt;">n</span><span style="font-family:&#34;font-size:12pt;">，</span><span style="font-family:&#34;font-size:12pt;">n&lt;=80000</span><span style="font-family:&#34;font-size:12pt;">，表示一年当中来到收养所的宠物和领养者的总数。接下来的</span><span style="font-family:&#34;font-size:12pt;">n</span><span style="font-family:&#34;font-size:12pt;">行，按到来时间的先后顺序描述了一年当中来到收养所的宠物和领养者的情况。每行有两个正整数</span><span style="font-family:&#34;font-size:12pt;">a, b</span><span style="font-family:&#34;font-size:12pt;">，其中</span><span style="font-family:&#34;font-size:12pt;">a=0</span><span style="font-family:&#34;font-size:12pt;">表示宠物，</span><span style="font-family:&#34;font-size:12pt;">a=1</span><span style="font-family:&#34;font-size:12pt;">表示领养者，</span><span style="font-family:&#34;font-size:12pt;">b</span><span style="font-family:&#34;font-size:12pt;">表示宠物的特点值或是领养者希望领养宠物的特点值。（同一时间呆在收养所中的，要么全是宠物，要么全是领养者，这些宠物和领养者的个数不会超过</span><span style="font-family:&#34;font-size:12pt;">10000个）</span></span> 
</div>
<div>
<span style="font-family:&#34;">【输入样例】</span> 
</div>
<p>
</p><table width="204" style="border:currentColor;width:153pt;border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="204" valign="top" style="border:1pt solid windowtext;">
<div>
<span style="font-family:&#34;">5</span> 
</div>
<div>
<span style="font-family:&#34;">0 2</span> 
</div>
<div>
<span style="font-family:&#34;">0 4</span> 
</div>
<div>
<span style="font-family:&#34;">1 3</span> 
</div>
<div>
<span style="font-family:&#34;">1 2</span> 
</div>
<div>
<span style="font-family:&#34;">1 5</span> 
</div>
</td>
</tr>
</tbody>
</table>
<p></p>
<div>
<span style="font-family:&#34;"><b><span style="font-family:&#34;font-size:large;">【输出格式】</span></b></span> 
</div>
<div>
<span style="font-family:&#34;">输出文件中仅有一个正整数，表示一年当中所有收养了宠物的领养者的不满意程度的总和mod 1000000以后的结果。</span> 
</div>
<div>
<span style="font-family:&#34;">【输出样例】</span> 
</div>
<p>
</p><table width="204" style="border:currentColor;width:153pt;border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="204" valign="top" style="border:1pt solid windowtext;">
<div>
<span style="font-family:&#34;">3</span> 
</div>
</td>
</tr>
</tbody>
</table>
<p></p>
<div>
<span style="font-family:&#34;">(abs(3-2) + abs(2-4)=3，最后一个领养者没有宠物可以领养)</span> 
</div>
<div>
<span style="font-family:&#34;"><b><span style="font-family:&#34;font-size:large;">【运行限制】</span></b></span> 
</div>
<div>
<span style="font-family:Verdana;"> <span style="font-family:&#34;font-size:12pt;">运行时限：</span><span style="font-family:&#34;font-size:12pt;">1秒钟</span></span> 
</div>
<div>
<span style="font-family:&#34;"><b><span style="font-family:&#34;font-size:large;">【评分方法】</span></b></span> 
</div>
<div>
<span style="font-family:&#34;">本题目一共有十个测试点，每个测试点的分数为总分数的10%。对于每个测试点来说，如果你给出的答案正确，那么你将得到该测试点全部的分数，否则得0分。</span> 
</div>
<div>
<span style="font-family:Verdana;"> </span> 
</div>
