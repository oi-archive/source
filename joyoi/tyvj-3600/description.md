# 

 
 # 题目描述 
<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">The&nbsp;pride&nbsp;of&nbsp;the&nbsp;Asia-Pacific&nbsp;region&nbsp;is&nbsp;the&nbsp;newly&nbsp;constructed&nbsp;Great&nbsp;Circular&nbsp;Zoo.&nbsp;Situated&nbsp;on&nbsp;a&nbsp;small&nbsp;Pacific&nbsp;island,&nbsp;it&nbsp;consists&nbsp;of&nbsp;a&nbsp;large&nbsp;circle&nbsp;of&nbsp;different&nbsp;enclosures,&nbsp;each&nbsp;containing&nbsp;its&nbsp;own&nbsp;exotic&nbsp;animal&nbsp;as&nbsp;illustrated&nbsp;below.</p>

<p><img src="/source/joyoi/tyvj-3600/img/aHR0cDovL3d3dy5zcG9qLmNvbS9jb250ZW50L2pvaG5fam9uZXM6em9vMS5qcGc=.jpg" style="color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; text-align: center; background-color: rgb(246, 249, 224);" /></p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">You&nbsp;are&nbsp;in&nbsp;charge&nbsp;of&nbsp;public&nbsp;relations&nbsp;for&nbsp;the&nbsp;zoo,&nbsp;which&nbsp;means&nbsp;it&nbsp;is&nbsp;your&nbsp;job&nbsp;to&nbsp;keep&nbsp;people&nbsp;as&nbsp;happy&nbsp;as&nbsp;possible.&nbsp;A&nbsp;busload&nbsp;of&nbsp;schoolchildren&nbsp;has&nbsp;just&nbsp;arrived,&nbsp;and&nbsp;you&nbsp;are&nbsp;eager&nbsp;to&nbsp;please&nbsp;them.&nbsp;However,&nbsp;this&nbsp;is&nbsp;no&nbsp;easy&nbsp;task|there&nbsp;are&nbsp;animals&nbsp;that&nbsp;some&nbsp;children&nbsp;love,&nbsp;and&nbsp;there&nbsp;are&nbsp;animals&nbsp;that&nbsp;some&nbsp;children&nbsp;fear.&nbsp;For&nbsp;example,&nbsp;little&nbsp;Alex&nbsp;loves&nbsp;monkeys&nbsp;and&nbsp;koalas&nbsp;because&nbsp;they&nbsp;are&nbsp;cute,&nbsp;but&nbsp;fears&nbsp;lions&nbsp;because&nbsp;of&nbsp;their&nbsp;sharp&nbsp;teeth.&nbsp;On&nbsp;the&nbsp;other&nbsp;hand,&nbsp;Polly&nbsp;loves&nbsp;lions&nbsp;because&nbsp;of&nbsp;their&nbsp;beautiful&nbsp;manes,&nbsp;but&nbsp;fears&nbsp;koalas&nbsp;because&nbsp;they&nbsp;are&nbsp;extremely&nbsp;smelly.</p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">You&nbsp;have&nbsp;the&nbsp;option&nbsp;of&nbsp;removing&nbsp;some&nbsp;animals&nbsp;from&nbsp;their&nbsp;enclosures,&nbsp;so&nbsp;that&nbsp;children&nbsp;are&nbsp;not&nbsp;afraid.&nbsp;However,&nbsp;you&nbsp;are&nbsp;worried&nbsp;that&nbsp;if&nbsp;you&nbsp;remove&nbsp;too&nbsp;many&nbsp;animals&nbsp;then&nbsp;this&nbsp;will&nbsp;leave&nbsp;the&nbsp;children&nbsp;with&nbsp;nothing&nbsp;to&nbsp;look&nbsp;at.&nbsp;Your&nbsp;task&nbsp;is&nbsp;to&nbsp;decide&nbsp;which&nbsp;animals&nbsp;to&nbsp;remove&nbsp;so&nbsp;that&nbsp;as&nbsp;many&nbsp;children&nbsp;can&nbsp;be&nbsp;made&nbsp;happy&nbsp;as&nbsp;possible.</p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">Each&nbsp;child&nbsp;is&nbsp;standing&nbsp;outside&nbsp;the&nbsp;circle,&nbsp;where&nbsp;they&nbsp;can&nbsp;see&nbsp;five&nbsp;consecutive&nbsp;enclosures.&nbsp;You&nbsp;have&nbsp;obtained&nbsp;a&nbsp;list&nbsp;of&nbsp;which&nbsp;animals&nbsp;each&nbsp;child&nbsp;fears,&nbsp;and&nbsp;which&nbsp;animals&nbsp;each&nbsp;child&nbsp;loves.&nbsp;A&nbsp;child&nbsp;will&nbsp;be&nbsp;made&nbsp;happy&nbsp;if&nbsp;either&nbsp;at&nbsp;least&nbsp;one&nbsp;animal&nbsp;they&nbsp;fear&nbsp;is&nbsp;removed&nbsp;from&nbsp;their&nbsp;field&nbsp;of&nbsp;vision,&nbsp;or&nbsp;at&nbsp;least&nbsp;one&nbsp;animal&nbsp;they&nbsp;love&nbsp;is&nbsp;not&nbsp;removed&nbsp;from&nbsp;their&nbsp;field&nbsp;of&nbsp;vision.</p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">For&nbsp;example,&nbsp;consider&nbsp;the&nbsp;list&nbsp;of&nbsp;children&nbsp;and&nbsp;animals&nbsp;illustrated&nbsp;below:</p>

<p><img src="/source/joyoi/tyvj-3600/img/aHR0cDovL3d3dy5zcG9qLmNvbS9jb250ZW50L2pvaG5fam9uZXM6em9vMi5qcGc=.jpg" style="color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; text-align: center; background-color: rgb(246, 249, 224);" /></p>

<pre style="color: rgb(0, 0, 32); line-height: normal; background-color: rgb(246, 249, 224);">
-----------------------------------------------------------------------
|Child&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosures&nbsp;Visible&nbsp;|Fears&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Loves&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|Alex&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|2,&nbsp;3,&nbsp;4,&nbsp;5,&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosures&nbsp;2,&nbsp;6|
|Polly&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|3,&nbsp;4,&nbsp;5,&nbsp;6,&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;|
|Chaitanya&nbsp;&nbsp;|6,&nbsp;7,&nbsp;8,&nbsp;9,&nbsp;10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosures&nbsp;6,&nbsp;8|
|Hwan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|8,&nbsp;9,&nbsp;10,&nbsp;11,&nbsp;12&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;9&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Enclosure&nbsp;12&nbsp;&nbsp;&nbsp;|
|Ka-Shu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|12,&nbsp;13,&nbsp;14,&nbsp;1,&nbsp;2&nbsp;&nbsp;&nbsp;|Enclosures&nbsp;12,&nbsp;13,&nbsp;2&nbsp;|-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
-----------------------------------------------------------------------
</pre>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">Suppose&nbsp;you&nbsp;remove&nbsp;the&nbsp;animals&nbsp;from&nbsp;enclosures&nbsp;4&nbsp;and&nbsp;12.&nbsp;This&nbsp;will&nbsp;make&nbsp;Alex&nbsp;and&nbsp;Ka-Shu&nbsp;happy,&nbsp;because&nbsp;at&nbsp;least&nbsp;one&nbsp;animal&nbsp;that&nbsp;they&nbsp;fear&nbsp;has&nbsp;gone.&nbsp;This&nbsp;will&nbsp;also&nbsp;keep&nbsp;Chaitanya&nbsp;happy,&nbsp;since&nbsp;both&nbsp;enclosures&nbsp;6&nbsp;and&nbsp;8&nbsp;still&nbsp;contain&nbsp;animals&nbsp;that&nbsp;he&nbsp;loves.&nbsp;However,&nbsp;both&nbsp;Polly&nbsp;and&nbsp;Hwan&nbsp;will&nbsp;be&nbsp;unhappy,&nbsp;since&nbsp;they&nbsp;cannot&nbsp;see&nbsp;any&nbsp;animals&nbsp;that&nbsp;they&nbsp;love&nbsp;but&nbsp;they&nbsp;can&nbsp;still&nbsp;see&nbsp;all&nbsp;the&nbsp;animals&nbsp;that&nbsp;they&nbsp;fear.&nbsp;This&nbsp;arrangement&nbsp;therefore&nbsp;gives&nbsp;a&nbsp;total&nbsp;of&nbsp;three&nbsp;happy&nbsp;children.</p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">Now&nbsp;suppose&nbsp;you&nbsp;put&nbsp;these&nbsp;animals&nbsp;back&nbsp;into&nbsp;their&nbsp;enclosures,&nbsp;and&nbsp;remove&nbsp;the&nbsp;animals&nbsp;from&nbsp;enclosures&nbsp;4&nbsp;and&nbsp;6&nbsp;instead.&nbsp;Alex&nbsp;and&nbsp;Polly&nbsp;will&nbsp;be&nbsp;happy&nbsp;because&nbsp;the&nbsp;animals&nbsp;that&nbsp;they&nbsp;fear&nbsp;in&nbsp;enclosures&nbsp;4&nbsp;and&nbsp;6&nbsp;have&nbsp;gone.&nbsp;Chaitanya&nbsp;will&nbsp;be&nbsp;happy&nbsp;because,&nbsp;even&nbsp;though&nbsp;animal&nbsp;6&nbsp;has&nbsp;gone,&nbsp;he&nbsp;can&nbsp;still&nbsp;see&nbsp;the&nbsp;animal&nbsp;in&nbsp;enclosure&nbsp;8&nbsp;which&nbsp;he&nbsp;loves.&nbsp;Likewise,&nbsp;Hwan&nbsp;will&nbsp;be&nbsp;happy&nbsp;because&nbsp;she&nbsp;can&nbsp;now&nbsp;see&nbsp;the&nbsp;animal&nbsp;in&nbsp;enclosure&nbsp;12,&nbsp;which&nbsp;she&nbsp;loves.&nbsp;The&nbsp;only&nbsp;person&nbsp;unhappy&nbsp;will&nbsp;be&nbsp;Ka-Shu.</p>

<p style="text-align: justify; color: rgb(0, 0, 32); font-family: Verdana, Arial, Helvetica, sans-serif; line-height: normal; background-color: rgb(246, 249, 224);">Finally,&nbsp;suppose&nbsp;you&nbsp;put&nbsp;the&nbsp;animals&nbsp;back&nbsp;once&nbsp;more&nbsp;and&nbsp;then&nbsp;remove&nbsp;only&nbsp;the&nbsp;animal&nbsp;from&nbsp;enclosure&nbsp;13.&nbsp;Ka-Shu&nbsp;will&nbsp;now&nbsp;be&nbsp;happy&nbsp;since&nbsp;one&nbsp;animal&nbsp;that&nbsp;he&nbsp;fears&nbsp;has&nbsp;been&nbsp;removed,&nbsp;and&nbsp;Alex,&nbsp;Polly,&nbsp;Chaitanya&nbsp;and&nbsp;Hwan&nbsp;will&nbsp;all&nbsp;be&nbsp;happy&nbsp;since&nbsp;they&nbsp;can&nbsp;all&nbsp;see&nbsp;at&nbsp;least&nbsp;one&nbsp;animal&nbsp;that&nbsp;they&nbsp;love.&nbsp;Thus&nbsp;this&nbsp;arrangement&nbsp;gives&nbsp;five&nbsp;happy&nbsp;children,&nbsp;the&nbsp;largest&nbsp;number&nbsp;possible.</p> 

 
 # 输入格式 
<p>输入的第一行包含两个整数N,&nbsp;C，用空格分隔。N是围栏数(10&le;N&le;10&nbsp;000)，C是小朋友的个数(1&le;C&le;50&nbsp;000)。围栏按照顺时针的方向编号为1,2,3,&hellip;,N。<br />
接下来的C行，每行描述一个小朋友的信息，以下面的形式给出：<br />
E&nbsp;F&nbsp;L&nbsp;X1&nbsp;X2&nbsp;&hellip;&nbsp;XF&nbsp;Y1&nbsp;Y2&nbsp;&hellip;&nbsp;YL<br />
其中：<br />
E表示这个小朋友可以看到的第一个围栏的编号(1&le;E&le;N)，换句话说，该小朋友可以看到的围栏为E,&nbsp;E+1,&nbsp;E+2,&nbsp;E+3,&nbsp;E+4。注意，如果编号超过N将继续从1开始算。如：当N=14,&nbsp;E=13时，这个小朋友可以看到的围栏为13,14,1,&nbsp;2和3。<br />
F表示该小朋友害怕的动物数。L表示该小朋友喜欢的动物数。<br />
围栏X1,&nbsp;X2,&nbsp;&hellip;,&nbsp;XF&nbsp;中包含该小朋友害怕的动物。<br />
围栏Y1,&nbsp;Y2,&nbsp;&hellip;,&nbsp;YL&nbsp;中包含该小朋友喜欢的动物。<br />
X1,&nbsp;X2,&nbsp;&hellip;,&nbsp;XF,&nbsp;Y1,&nbsp;Y2,&nbsp;&hellip;,&nbsp;YL是两两不同的整数，而且所表示的围栏都是该小朋友可以看到的。<br />
小朋友已经按照他们可以看到的第一个围栏的编号从小到大的顺序排好了(这样最小的E对应的小朋友排在第一个，最大的E对应的小朋友排在最后一个)。注意可能有多于一个小朋友对应的E是相同的。</p> 

 
 # 输出格式 
<p>仅输出一个数，表示最多可以让多少个小朋友高兴</p> 
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
<tr><td>样例输入1 
14 5 5
2 1 2 4 2 6
3 1 1 6 4
6 1 2 9 6 8
8 1 1 9 12
12 3 0 12 13 2

样例输入2 
12 7 6
1 1 1 1 5
5 1 1 5 7
5 0 3 5 7 9
7 1 1 7 9
9 1 1 9 11
9 3 0 9 11 1</td><td>
样例输出1
5

样例输出2
6

</td></tr></table>
