# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">描述 Description</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">今年的NOIp初赛还有差不多一个月就要开始了，为了激励大家取得好成绩，信息老师给他的得力助手小Q布置了一个任务：统计本校历年来的获奖情况。当然，这里统计的奖项不仅仅是NOIp一等这么简单，小Q的任务是把学校历年来NOIp普及组、NOIp提高组、NOI</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 、CTSC、APIO、IOI、UOI等等这些奖项的情况统计出来，这里对各个竞赛都解释一下。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp:这个不解释，我们在统计这个奖项的时候按照普及和提高划分，对于普及组按照参赛奖，三等奖，二等奖，一等奖来统计。提高同理。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOI:全称为全国青少年信息学奥林匹克竞赛，一年一度，今年NOI在吉林大学举办，共有340名选手参加角逐。我们在统计这个奖项的时候按照金牌，银牌，铜牌，胸牌来统计。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> CTSC:这个就是集训队一帮人去IOI必须拿下的比赛和各种即将去NOI虐人的神牛必须来打酱油的比赛。统计这个奖项的时候同NOI.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> APIO:亚太地区亲少年信息学奥铃匹克竞赛，统计奖项的时候我们增加一个国内评奖和国外评奖，对于国内评奖我们在统计这个奖项的时候按照金牌，银牌，铜牌来统计，对于国外评奖我们按照金牌，银牌，铜牌来统计。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> IOI:国际青少年信息学奥林匹克竞赛，统计的时候按照金牌，银牌，铜牌来统计。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> UOI:宇宙青少年信息学奥林匹克竞赛，统计的时候同NOI.</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 那么接下来给出n行获奖信息，请统计各个类别比赛的获奖选手。</span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式 Input Format</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 第一行是一个数n，表示接下来有n个获奖信息</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 之后是n行，每一行为一组输入，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里NOIp的获奖信息描述为 NOIp#TG#I#</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里NOIp描述为这个奖是NOIp，TG表示是提高组，PJ表示是普及组，最后一组为罗马数字I,II,III表示为一二三等，特殊的如果是J表示参赛奖.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里NOI的获奖描述为NOI#Au#</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里NOI描述这个奖是NOI，Au代表金牌，Ag代表银牌，Cu代表铜牌，Xp代表胸牌。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对CTSC和UOI的奖同上，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对于APIO的获奖信息描述为APIO#C#Cu#</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里APIO描述这个奖是APIO，C代表国内，A代表国际，Au代表金牌，Ag代表银牌，Cu代表铜牌。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对于IOI，描述为IOI#Au#</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里IOI描述这个奖是IOI，Au代表金牌，Ag代表银牌，Cu代表铜牌。</span><br/>
<br/>
<br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对于任何不符合上述所有形式的获奖描述我们都计入到other里面。</span><br/>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式 Output Format</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输出的内容如下</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#PJ#I#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#PJ#II#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#PJ#III#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#PJ#J#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#TG#I#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#TG#II#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#TG#III#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOIp#TG#J#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOI#Au#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOI#Ag#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOI#Cu#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> NOI#Xp#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> CTSC#Au#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> ……</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> CTSC#Xp#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> APIO#C#Au#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> ……</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> APIO#A#Cu#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> IOI#Au#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> ……</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> IOI#Cu#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> UOI#Au#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">……</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> UOI#Xp#:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> other:XX</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 这里XX代表数量.</span><br/>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">详见样例</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输入</span> 
</h3>
<span></span> 
<p>
	<br/>
</p>
<div>
	<span></span><br/>
</div>
<pre>7
NOIp#TG#I#
CTSC#Au#
APIO#C#Au#
NOI#Au#
IOI#Au#
UOI#Au#
Orz CLJ!
</pre>
<h3>
	样例输出
</h3>
<pre>NOIp#PJ#I#:0
NOIp#PJ#II#:0
NOIp#PJ#III#:0
NOIp#PJ#J#:0
NOIp#TG#I#:1
NOIp#TG#II#:0
NOIp#TG#III#:0
NOIp#TG#J#:0
NOI#Au#:1
NOI#Ag#:0 
</pre>
<span><br/>
<div style="color:#355F29;text-align:center;background-color:#509A47;">
	<div>
		<div>
			<div style="background-color:white;">
				<div style="color:orange;text-align:left;font-weight:bold;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;">时间限制 Time Limitation</span> 
				</div>
				<div style="font-family:&#39;Courier New&#39;;text-align:left;">
					<span style="font-family:Microsoft YaHei;">每个测试点1s;</span> 
				</div>
			</div>
		</div>
		<div>
		</div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
	</div>
</div>
<div style="color:#355F29;text-align:center;background-color:#509A47;">
	<div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
		<div>
		</div>
		<div>
			<div style="background-color:white;">
				<div style="color:orange;text-align:left;font-weight:bold;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;">注释 Hint</span> 
				</div>
				<div style="font-family:&#39;Courier New&#39;;text-align:left;">
					<span style="font-family:Microsoft YaHei;">100%的数据有1&lt;=n&lt;=100;</span><br/>
				</div>
			</div>
		</div>
		<div>
		</div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
	</div>
</div>
<div style="color:#355F29;text-align:center;background-color:#509A47;">
	<div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
		<div>
		</div>
		<div>
			<div style="background-color:white;">
				<div style="color:orange;text-align:left;font-weight:bold;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;">来源 Source</span> 
				</div>
				<div style="font-family:&#39;Courier New&#39;;text-align:left;">
					<span style="font-family:Microsoft YaHei;">来自西部314 七号苦情赛</span> 
				</div>
			</div>
		</div>
	</div>
</div>
</span>
