# 

 
 # 题目背景 
小胖是一个lrc歌词编辑者，他每天的工作是制作歌曲相应的lrc歌词文件。<BR>（lrc歌词文件的格式由一个时间轴与相对应的歌词组成，例如：<BR>[00:38.02]兄弟你&nbsp;在哪里<BR>[00:42.52]天空又飘起了雨<BR>[00:46.90]我要你像黎明一样<BR>[00:51.19]出现在我眼里<BR>[00:55.85]兄弟你&nbsp;在哪里<BR>[01:00.07]听不见你的呼吸<BR>[01:04.70]只感觉我在哭泣）<BR>小胖是一个粗心的人，经常把歌曲前奏的时间计算错，导致接下来所有时间轴的数据都出错，不是快了就是慢了。因此，小胖总是把编辑下一首歌词文件的时间用来修改编辑错误的歌词文件，不仅浪费时间，还很麻烦，需要在所有时间轴上一个一个修改。最重要的是——老总要扣MONEY！！（晕了~~）<BR>昨天小胖又因没有完成上个月的任务被老总训了（扣了很多工资。。。），小胖心里很不是滋味，打算聘请一名专门为他修改歌词的歌词修改人。（看来小胖完全不了解编程的伟大……）<BR>要求：提供需要修改的歌词，歌词是快了或是慢了，以及需要更改的秒数<BR>工资：每天正确修改9个以下（含9个）歌词文件250元（无语），正确修改10个或以上每天可拿300元（我只修改10个^__^）。<BR> 

 
 # 题目描述 
看了招聘广告后，你立刻来应聘。通过面试后，你工作的第一天来了。小胖今天正好有10个歌词文件需要你修改（为了逃离那个倒霉的数字只能……）。下面就是你最关键的一步了（只需要编一个程序，你就可以每天不工作都拿高额工资了）。<BR>（我给你推荐的工作哦~~拿了工资别忘了分点给我^__^）<BR> 

 
 # 输入格式 
输入文件中，第一行有m1，m2两个数据（中间用空格隔开）。m1是‘+’，‘-’（加减符号）中的一个，如果m1是‘+’，则表示小胖给你的歌词数据比实际慢了，‘-’则是小胖歌词数据快了。接下来的n行中（n是一个未知整数），是lrc歌词文件，第n+2行（也就是所有歌词输入完后的一行）以‘#’结束。<BR>（数据保证0&lt;m2&lt;10，1≤n≤50，每行歌词包括时间轴不超过100个字节）<BR><BR> 

 
 # 输出格式 
输出文件也有n行，是修改后的歌词文件。只需修改时间轴，歌词原样输出。<BR>（输出文件的最长时间不到10分钟，最短不会出现负数）<BR> 

 
 # 提示 
1000毫秒合一秒，60秒合1分 
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
<tr><td>- 1.07
[ti:Only Love]
[ar:Selena]
[by:http://www.superlyrics.net]
[00:08.26]Selena
[00:13.19]
[00:14.87]I see the distant lights ahead
[00:21.84]Another hour or so, and I’ll be back in bed
[00:29.67]I guess I really thought
[00:32.90]that I was gone for good
[00:37.93]But you know I never could
#
</td><td>[ti:Only Love]
[ar:Selena]
[by:http://www.superlyrics.net]
[00:07.19]Selena
[00:12.12]
[00:13.80]I see the distant lights ahead
[00:20.77]Another hour or so, and I’ll be back in bed
[00:28.60]I guess I really thought
[00:31.83]that I was gone for good
[00:36.86]But you know I never could
</td></tr></table>
