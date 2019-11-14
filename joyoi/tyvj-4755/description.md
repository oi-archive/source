# 

 
 # 题目描述 
<p>P老师需要去商店买n支铅笔作为小朋友们参加NOIP的礼物。她发现商店一共有&nbsp;3种包装的铅笔，不同包装内的铅笔数量有可能不同，价格也有可能不同。为了公平起&nbsp;见，P老师决定只买同一种包装的铅笔。</p>

<p>商店不允许将铅笔的包装拆开，因此P老师可能需要购买超过n支铅笔才够给小朋&nbsp;友们发礼物。</p>

<p>现在P老师想知道，在商店每种包装的数量都足够的情况下，要买够至少n支铅笔*最少*需要花费多少钱。</p> 

 
 # 输入格式 
<p>输入的第一行包含一个正整数n，表示需要的铅笔数量。</p>

<p>接下来三行，每行用两个正整数描述一种包装的铅笔：其中第一个整数表示这种&nbsp;包装内铅笔的数量，第二个整数表示这种包装的价格。</p>

<p>保证所有的7个数都是不超过10000的正整数。</p>

<p>[输入1]</p>

<pre>
57
2&nbsp;2
50&nbsp;30
30&nbsp;27</pre>

<p>[输入2]</p>

<p>57<br />
2&nbsp;2<br />
50&nbsp;30<br />
30&nbsp;27</p>

<p>[输入3]</p>

<pre>
9999
101&nbsp;1111
1&nbsp;9999
1111&nbsp;9999</pre> 

 
 # 输出格式 
<p>输出一行一个整数，表示P老师最少需要花费的钱。</p>

<p>[输出1]</p>

<p>54</p>

<p>[输出2]</p>

<p>18407</p>

<p>[输出3]</p>

<p>89991</p> 

 
 # 提示 
<p>铅笔的三种包装分别是：</p>

<p>&bull;2支装，价格为2;</p>

<p>&bull;50支装，价格为30;</p>

<p>&bull;30支装，价格为27。</p>

<p>P老师需要购买至少57支铅笔。</p>

<p>如果她选择购买第一种包装，那么她需要购买29份，共计2x29&nbsp;=&nbsp;58支，需要花&nbsp;费的钱为2x29&nbsp;=&nbsp;58。</p>

<p>实际上，P老师会选择购买第三种包装，这样需要买2份。虽然最后买到的铅笔数&nbsp;量更多了，为30x2&nbsp;=&nbsp;60支，但花费却减少为27&nbsp;x2&nbsp;=&nbsp;54，比第一种少。</p>

<p>对于第二种包装，虽然每支铅笔的价格是最低的，但要够发必须买2份，实际的&nbsp;花费达到了&nbsp;30&nbsp;x&nbsp;2&nbsp;=&nbsp;60，因此P老师也不会选择。</p>

<p>所以最后输出的答案是54。</p>

<p>【子任务】</p>

<p>子任务会给出部分测试数据的特点。如果你在解决题目中遇到了困难，可以尝试&nbsp;只解决一部分测试数据。</p>

<p>每个测试点的数据规模及特点如下表：</p>

<p>测试点&nbsp;整倍数&nbsp;其它特点</p>

<p>1,2,3,4&nbsp;&nbsp;&nbsp;&nbsp;&radic;&nbsp;&nbsp;&nbsp;&nbsp;三种包装内的铅笔数量都是相同的</p>

<p>5,6,7,8&nbsp;&nbsp;&nbsp;&nbsp;&times;&nbsp;&nbsp;&nbsp;&nbsp;三种包装内的铅笔数量都是相同的</p>

<p>9,10,11,12&nbsp;&nbsp;&nbsp;&nbsp;&radic;&nbsp;&nbsp;&nbsp;&nbsp;后两种包装的铅笔数量都是相同的</p>

<p>13,14,15,16&nbsp;&nbsp;&nbsp;&nbsp;&times;&nbsp;&nbsp;&nbsp;&nbsp;后两种包装的铅笔数量都是相同的</p>

<p>17,18&nbsp;&nbsp;&nbsp;&nbsp;&radic;&nbsp;&nbsp;&nbsp;&nbsp;没有特殊性质</p>

<p>19,20&nbsp;&nbsp;&nbsp;&nbsp;&times;&nbsp;&nbsp;&nbsp;&nbsp;没有特殊性质</p>

<p>&nbsp;</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>57
2 2
50 30
30 27
</td><td>54
</td></tr></table>
