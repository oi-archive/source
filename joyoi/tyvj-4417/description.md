# 

 
 # 题目背景 
<p>改编版，带翻译。</p>

<p>【原文】</p>

<p style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">The&nbsp;structure&nbsp;of&nbsp;some&nbsp;biological&nbsp;objects&nbsp;is&nbsp;represented&nbsp;by&nbsp;thesequence&nbsp;of&nbsp;their&nbsp;constituents,&nbsp;where&nbsp;each&nbsp;part&nbsp;is&nbsp;denote&nbsp;by&nbsp;anuppercase&nbsp;letter.&nbsp;Biologists&nbsp;are&nbsp;interested&nbsp;in&nbsp;decomposing&nbsp;a&nbsp;longsequence&nbsp;into&nbsp;shorter&nbsp;ones&nbsp;called&nbsp;<em>primitives</em>.</p>

<p style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">We&nbsp;say&nbsp;that&nbsp;a&nbsp;sequence&nbsp;S&nbsp;can&nbsp;be&nbsp;composed&nbsp;from&nbsp;a&nbsp;given&nbsp;set&nbsp;of&nbsp;primitivesP&nbsp;if&nbsp;there&nbsp;is&nbsp;a&nbsp;some&nbsp;sequence&nbsp;of&nbsp;(possibly&nbsp;repeated)&nbsp;primitives&nbsp;fromthe&nbsp;set&nbsp;whose&nbsp;concatenation&nbsp;equals&nbsp;S.&nbsp;Not&nbsp;necessarily&nbsp;all&nbsp;primitivesneed&nbsp;be&nbsp;present.&nbsp;For&nbsp;instance&nbsp;the&nbsp;sequence&nbsp;<tt><u>ABABACABAAB</u>&nbsp;</tt>can&nbsp;becomposed&nbsp;from&nbsp;the&nbsp;set&nbsp;of&nbsp;primitives</p>

<pre style="color: rgb(54, 46, 43); font-size: 14px; line-height: 26px;">
	&nbsp;&nbsp;&nbsp;{A,&nbsp;AB,&nbsp;BA,&nbsp;CA,&nbsp;BBC}
</pre>

<p style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">The&nbsp;first&nbsp;K&nbsp;characters&nbsp;of&nbsp;S&nbsp;are&nbsp;the&nbsp;<em>prefix&nbsp;of&nbsp;S&nbsp;with&nbsp;lengthK</em>.&nbsp;Write&nbsp;a&nbsp;program&nbsp;which&nbsp;accepts&nbsp;as&nbsp;input&nbsp;a&nbsp;set&nbsp;of&nbsp;primitives&nbsp;anda&nbsp;sequence&nbsp;of&nbsp;constituents&nbsp;and&nbsp;then&nbsp;computes&nbsp;the&nbsp;length&nbsp;of&nbsp;the&nbsp;longestprefix&nbsp;that&nbsp;can&nbsp;be&nbsp;composed&nbsp;from&nbsp;primitives.</p>

<h3 style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">INPUT&nbsp;FORMAT</h3>

<p style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;"><span style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">First,&nbsp;the&nbsp;input&nbsp;file&nbsp;contains&nbsp;the&nbsp;list&nbsp;(length&nbsp;1..200)&nbsp;of&nbsp;primitives(length&nbsp;1..10)&nbsp;expressed&nbsp;as&nbsp;a&nbsp;series&nbsp;of&nbsp;space-separated&nbsp;strings&nbsp;ofupper-case&nbsp;characters&nbsp;on&nbsp;one&nbsp;or&nbsp;more&nbsp;lines.&nbsp;The&nbsp;list&nbsp;of&nbsp;primitives&nbsp;isterminated&nbsp;by&nbsp;a&nbsp;line&nbsp;that&nbsp;contains&nbsp;nothing&nbsp;more&nbsp;than&nbsp;a&nbsp;period&nbsp;(`.&#39;).No&nbsp;primitive&nbsp;appears&nbsp;twice&nbsp;in&nbsp;the&nbsp;list.Then,&nbsp;the&nbsp;input&nbsp;file&nbsp;contains&nbsp;a&nbsp;sequence&nbsp;S&nbsp;(length&nbsp;1..200,000)expressed&nbsp;as&nbsp;one&nbsp;or&nbsp;more&nbsp;lines,&nbsp;none&nbsp;of&nbsp;which&nbsp;exceeds&nbsp;76&nbsp;lettersin&nbsp;length.&nbsp;The&nbsp;&quot;newlines&quot;&nbsp;(line&nbsp;terminators)&nbsp;are&nbsp;not&nbsp;part&nbsp;of&nbsp;thestring&nbsp;S.</span></p>

<h3 style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">OUTPUT&nbsp;FORMAT</h3>

<p><span style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">A&nbsp;single&nbsp;line&nbsp;containing&nbsp;an&nbsp;integer&nbsp;that&nbsp;is&nbsp;the&nbsp;length&nbsp;of&nbsp;the&nbsp;longestprefix&nbsp;that&nbsp;can&nbsp;be&nbsp;composed&nbsp;from&nbsp;the&nbsp;set&nbsp;P.</span></p>

<p style="color: rgb(54, 46, 43); font-family: Arial; font-size: 14px; line-height: 26px;">&nbsp;</p> 

 
 # 题目描述 
<p>&nbsp;一些生物体的复杂结构可以用其基元的序列表示，而一个基元用一个大写英文字符串表示。生物学家的一个问题就是将一个这样的长序列分解为基元（字符串）的序列，对于给定的基元的集合P，如果可源又醒〕鯪个基元P1，P2，&hellip;Pn，将它们各自对应的字符串依次联接后得到一个字符串S，称S可以由基元集合P构成。在从P中挑选基元时，一个基元可以使用多次，也可以不用，例如，序列ABABACABAB可以由基元集合{A,AB,BA,CA,BBC}构成。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;字符串的前K个字符称为该字符串的前缀，其长度为K.请写一个程序，对于输入的基元集合P和字符串T，求出一个可以由基元集合P构成的字符串T的前缀，要求该前缀的长度尽可能的长，输出其长度。</p> 

 
 # 输入格式 
<p><span style="line-height: 1.6em;">&nbsp;&nbsp;&nbsp;</span>第一行是基元集合P中基元的数目N（1&lt;=N&lt;=100），随后有2N行，每两行描述一个基元。第一行为该基元的长度L（1&lt;=L&lt;=20）。随后一行是一个长度为L的大写英文字符串，表示该基元。每个基元互不相同。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;接下来要处理的字符串T，每一行行首有一个大写英文字母，最后一行是一个字符&ldquo;.&rdquo;，表示字符串结束。T的长度最小为1，最大不超过500000。</p> 

 
 # 输出格式 
<p>只有一行，是一个数字，表示可以由P构成的T的最长前缀的长度。</p> 

 
 # 提示 
<h3>说明</h3>

<p>因此题输入数据较为特殊，故数据暂时未上传。请见谅！</p>

<h3 style="margin: 20px 0px; font-size: 18px; line-height: 22px; color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI';">版权</h3>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20px;">如有侵权请联系管理员，谢谢！</p> 
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
<tr><td>A AB BA CA BBC
.
ABABACABAABC</td><td>11</td></tr></table>
