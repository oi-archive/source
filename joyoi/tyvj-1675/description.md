# 

 
 # 题目描述 
今年的NOIp初赛还有差不多一个月就要开始了，为了激励大家取得好成绩，信息老师给他的得力助手小Q布置了一个任务：统计本校历年来的获奖情况。当然，这里统计的奖项不仅仅是NOIp一等这么简单，小Q的任务是把学校历年来NOIp普及组、NOIp提高组、NOI<BR>、CTSC、APIO、IOI、UOI等等这些奖项的情况统计出来，这里对各个竞赛都解释一下。<BR><BR>NOIp:这个不解释，我们在统计这个奖项的时候按照普及和提高划分，对于普及组按照参赛奖，三等奖，二等奖，一等奖来统计。提高同理。<BR>NOI:全称为全国青少年信息学奥林匹克竞赛，一年一度，今年NOI在吉林大学举办，共有340名选手参加角逐。我们在统计这个奖项的时候按照金牌，银牌，铜牌，胸牌来统计。<BR>CTSC:这个就是集训队一帮人去IOI必须拿下的比赛和各种即将去NOI虐人的神牛必须来打酱油的比赛。统计这个奖项的时候同NOI.<BR>APIO:亚太地区亲少年信息学奥铃匹克竞赛，统计奖项的时候我们增加一个国内评奖和国外评奖，对于国内评奖我们在统计这个奖项的时候按照金牌，银牌，铜牌来统计，对于国外评奖我们按照金牌，银牌，铜牌来统计。<BR>IOI:国际青少年信息学奥林匹克竞赛，统计的时候按照金牌，银牌，铜牌来统计。<BR>UOI:宇宙青少年信息学奥林匹克竞赛，统计的时候同NOI.<BR><BR>那么接下来给出n行获奖信息，请统计各个类别比赛的获奖选手。<BR> 

 
 # 输入格式 
第一行是一个数n，表示接下来有n个获奖信息<BR>之后是n行，每一行为一组输入，<BR>这里NOIp的获奖信息描述为&nbsp;NOIp#TG#I#<BR>这里NOIp描述为这个奖是NOIp，TG表示是提高组，PJ表示是普及组，最后一组为罗马数字I,II,III表示为一二三等，特殊的如果是J表示参赛奖.<BR>这里NOI的获奖描述为NOI#Au#<BR>这里NOI描述这个奖是NOI，Au代表金牌，Ag代表银牌，Cu代表铜牌，Xp代表胸牌。<BR>对CTSC和UOI的奖同上，<BR>对于APIO的获奖信息描述为APIO#C#Cu#<BR>这里APIO描述这个奖是APIO，C代表国内，A代表国际，Au代表金牌，Ag代表银牌，Cu代表铜牌。<BR>对于IOI，描述为IOI#Au#<BR>这里IOI描述这个奖是IOI，Au代表金牌，Ag代表银牌，Cu代表铜牌。<BR><BR><BR>对于任何不符合上述所有形式的获奖描述我们都计入到other里面。<BR> 

 
 # 输出格式 
输出的内容如下<BR>NOIp#PJ#I#:XX<BR>NOIp#PJ#II#:XX<BR>NOIp#PJ#III#:XX<BR>NOIp#PJ#J#:XX<BR>NOIp#TG#I#:XX<BR>NOIp#TG#II#:XX<BR>NOIp#TG#III#:XX<BR>NOIp#TG#J#:XX<BR>NOI#Au#:XX<BR>NOI#Ag#:XX<BR>NOI#Cu#:XX<BR>NOI#Xp#:XX<BR>CTSC#Au#:XX<BR>……<BR>CTSC#Xp#:XX<BR>APIO#C#Au#:XX<BR>……<BR>APIO#A#Cu#:XX<BR>IOI#Au#:XX<BR>……<BR>IOI#Cu#:XX<BR>UOI#Au#:XX<BR>……<BR>UOI#Xp#:XX<BR>other:XX<BR>这里XX代表数量.<BR>详见样例<BR> 

 
 # 提示 
100%的数据有1&lt;=n&lt;=100;<BR>来自西部314&nbsp;七号苦情赛 
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
<tr><td>7
NOIp#TG#I#
CTSC#Au#
APIO#C#Au#
NOI#Au#
IOI#Au#
UOI#Au#
Orz CLJ!
</td><td>NOIp#PJ#I#:0
NOIp#PJ#II#:0
NOIp#PJ#III#:0
NOIp#PJ#J#:0
NOIp#TG#I#:1
NOIp#TG#II#:0
NOIp#TG#III#:0
NOIp#TG#J#:0
NOI#Au#:1
NOI#Ag#:0
NOI#Cu#:0
NOI#Xp#:0 
CTSC#Au#:1
CTSC#Ag#:0
CTSC#Cu#:0
CTSC#Xp#:0
APIO#C#Au#:1
APIO#C#Ag#:0
APIO#C#Cu#:0
APIO#A#Au#:0 
APIO#A#Ag#:0 
APIO#A#Cu#:0
IOI#Au#:1
IOI#Ag#:0
IOI#Cu#:0
UOI#Au#:1
UOI#Ag#:0
UOI#Cu#:0
UOI#Xp#:0
other:1
</td></tr></table>
