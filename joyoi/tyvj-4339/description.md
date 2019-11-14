# 

 
 # 题目背景 
<p>POJ1087</p> 

 
 # 题目描述 
<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">原文</span></strong></h3>

<p><span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">You&nbsp;are&nbsp;in&nbsp;charge&nbsp;of&nbsp;setting&nbsp;up&nbsp;the&nbsp;press&nbsp;room&nbsp;for&nbsp;the&nbsp;inaugural&nbsp;meeting&nbsp;of&nbsp;the&nbsp;United&nbsp;Nations&nbsp;Internet&nbsp;eXecutive&nbsp;(UNIX),&nbsp;which&nbsp;has&nbsp;an&nbsp;international&nbsp;mandate&nbsp;to&nbsp;make&nbsp;the&nbsp;free&nbsp;flow&nbsp;of&nbsp;information&nbsp;and&nbsp;ideas&nbsp;on&nbsp;the&nbsp;Internet&nbsp;as&nbsp;cumbersome&nbsp;and&nbsp;bureaucratic&nbsp;as&nbsp;possible.&nbsp;</span></p>

<p><span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">Since&nbsp;the&nbsp;room&nbsp;was&nbsp;designed&nbsp;to&nbsp;accommodate&nbsp;reporters&nbsp;and&nbsp;journalists&nbsp;from&nbsp;around&nbsp;the&nbsp;world,&nbsp;it&nbsp;is&nbsp;equipped&nbsp;with&nbsp;electrical&nbsp;receptacles&nbsp;to&nbsp;suit&nbsp;the&nbsp;different&nbsp;shapes&nbsp;of&nbsp;plugs&nbsp;and&nbsp;voltages&nbsp;used&nbsp;by&nbsp;appliances&nbsp;in&nbsp;all&nbsp;of&nbsp;the&nbsp;countries&nbsp;that&nbsp;existed&nbsp;when&nbsp;the&nbsp;room&nbsp;was&nbsp;built.&nbsp;Unfortunately,&nbsp;the&nbsp;room&nbsp;was&nbsp;built&nbsp;many&nbsp;years&nbsp;ago&nbsp;when&nbsp;reporters&nbsp;used&nbsp;very&nbsp;few&nbsp;electric&nbsp;and&nbsp;electronic&nbsp;devices&nbsp;and&nbsp;is&nbsp;equipped&nbsp;with&nbsp;only&nbsp;one&nbsp;receptacle&nbsp;of&nbsp;each&nbsp;type.&nbsp;These&nbsp;days,&nbsp;like&nbsp;everyone&nbsp;else,&nbsp;reporters&nbsp;require&nbsp;many&nbsp;such&nbsp;devices&nbsp;to&nbsp;do&nbsp;their&nbsp;jobs:&nbsp;laptops,&nbsp;cell&nbsp;phones,&nbsp;tape&nbsp;recorders,&nbsp;pagers,&nbsp;coffee&nbsp;pots,&nbsp;microwave&nbsp;ovens,&nbsp;blow&nbsp;dryers,&nbsp;curling&nbsp;</span><br style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;" />
<span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">irons,&nbsp;tooth&nbsp;brushes,&nbsp;etc.&nbsp;Naturally,&nbsp;many&nbsp;of&nbsp;these&nbsp;devices&nbsp;can&nbsp;operate&nbsp;on&nbsp;batteries,&nbsp;but&nbsp;since&nbsp;the&nbsp;meeting&nbsp;is&nbsp;likely&nbsp;to&nbsp;be&nbsp;long&nbsp;and&nbsp;tedious,&nbsp;you&nbsp;want&nbsp;to&nbsp;be&nbsp;able&nbsp;to&nbsp;plug&nbsp;in&nbsp;as&nbsp;many&nbsp;as&nbsp;you&nbsp;can.&nbsp;</span><br style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;" />
<span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">Before&nbsp;the&nbsp;meeting&nbsp;begins,&nbsp;you&nbsp;gather&nbsp;up&nbsp;all&nbsp;the&nbsp;devices&nbsp;that&nbsp;the&nbsp;reporters&nbsp;would&nbsp;like&nbsp;to&nbsp;use,&nbsp;and&nbsp;attempt&nbsp;to&nbsp;set&nbsp;them&nbsp;up.&nbsp;You&nbsp;notice&nbsp;that&nbsp;some&nbsp;of&nbsp;the&nbsp;devices&nbsp;use&nbsp;plugs&nbsp;for&nbsp;which&nbsp;there&nbsp;is&nbsp;no&nbsp;receptacle.&nbsp;You&nbsp;wonder&nbsp;if&nbsp;these&nbsp;devices&nbsp;are&nbsp;from&nbsp;countries&nbsp;that&nbsp;didn&#39;t&nbsp;exist&nbsp;when&nbsp;the&nbsp;room&nbsp;was&nbsp;built.&nbsp;For&nbsp;some&nbsp;receptacles,&nbsp;there&nbsp;are&nbsp;several&nbsp;devices&nbsp;that&nbsp;use&nbsp;the&nbsp;corresponding&nbsp;plug.&nbsp;For&nbsp;other&nbsp;receptacles,&nbsp;there&nbsp;are&nbsp;no&nbsp;devices&nbsp;that&nbsp;use&nbsp;the&nbsp;corresponding&nbsp;plug.&nbsp;</span><br style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;" />
<span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">In&nbsp;order&nbsp;to&nbsp;try&nbsp;to&nbsp;solve&nbsp;the&nbsp;problem&nbsp;you&nbsp;visit&nbsp;a&nbsp;nearby&nbsp;parts&nbsp;supply&nbsp;store.&nbsp;The&nbsp;store&nbsp;sells&nbsp;adapters&nbsp;that&nbsp;allow&nbsp;one&nbsp;type&nbsp;of&nbsp;plug&nbsp;to&nbsp;be&nbsp;used&nbsp;in&nbsp;a&nbsp;different&nbsp;type&nbsp;of&nbsp;outlet.&nbsp;Moreover,&nbsp;adapters&nbsp;are&nbsp;allowed&nbsp;to&nbsp;be&nbsp;plugged&nbsp;into&nbsp;other&nbsp;adapters.&nbsp;The&nbsp;store&nbsp;does&nbsp;not&nbsp;have&nbsp;adapters&nbsp;for&nbsp;all&nbsp;possible&nbsp;combinations&nbsp;of&nbsp;plugs&nbsp;and&nbsp;receptacles,&nbsp;but&nbsp;there&nbsp;is&nbsp;essentially&nbsp;an&nbsp;unlimited&nbsp;supply&nbsp;of&nbsp;the&nbsp;ones&nbsp;they&nbsp;do&nbsp;have.</span></p>

<p>&nbsp;</p>

<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">翻译</span></strong></h3>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">您为联合国互联网行政处（the&nbsp;United&nbsp;Nations&nbsp;Internet&nbsp;eXecutive（UNIX））的成立大会负责建立新闻室，其中有一项国际性的任务，就是使得海量的和官方的信息尽可能在互联网上自由流动。</span><br style="box-sizing: border-box; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">新闻室的房间设计要满足来自世界各地的记者，所以在房屋建造的时候，就要在房间里配置多种插座，以符合各个国家使用的电器的不同的插头形状和电压。然而不幸的是，房间是许多年前建造的，那时的记者使用的电力和电子设备很少，所以每种类型的插座只有一个。而现在，记者也象其他人一样，要做工作，就需要许多这样的设备：笔记本电脑，手机，录音机，传呼机，咖啡壶，微波炉，吹塑机，卷边熨斗，牙刷，等等。这些设备可以用电池，但由于会议很可能是漫长而乏味的，所以您希望插座尽可能多。</span><br style="box-sizing: border-box; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">在会议开始之前，您收集了记者想要用的所有的设备，并尝试对它们进行接电处理。您发现一些使用插头的设备没有相应的插座，你知道在房间修建的时候，没有考虑这些设备来自的国家。而对于插座，有些插座，有使用相应的插头的设备；而另一些插座，则没有使用相应插头的设备。</span><br style="box-sizing: border-box; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">为了解决这个问题，你去了附近的一家部件供应商店。这家商店出售允许一类插头在不同类型的插座上使用的转换连接器。此外，转换连接器也可以被插入到其它转换连接器上。这家商店没有对所有可能的插头和插座组合适用的转换连接器，但部件的数量是无限的。</span></p> 

 
 # 输入格式 
<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">原文</span></strong></h3>

<p><span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">The&nbsp;input&nbsp;will&nbsp;consist&nbsp;of&nbsp;one&nbsp;case.&nbsp;The&nbsp;first&nbsp;line&nbsp;contains&nbsp;a&nbsp;single&nbsp;positive&nbsp;integer&nbsp;n&nbsp;(1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;100)&nbsp;indicating&nbsp;the&nbsp;number&nbsp;of&nbsp;receptacles&nbsp;in&nbsp;the&nbsp;room.&nbsp;The&nbsp;next&nbsp;n&nbsp;lines&nbsp;list&nbsp;the&nbsp;receptacle&nbsp;types&nbsp;found&nbsp;in&nbsp;the&nbsp;room.&nbsp;Each&nbsp;receptacle&nbsp;type&nbsp;consists&nbsp;of&nbsp;a&nbsp;string&nbsp;of&nbsp;at&nbsp;most&nbsp;24&nbsp;alphanumeric&nbsp;characters.&nbsp;The&nbsp;next&nbsp;line&nbsp;contains&nbsp;a&nbsp;single&nbsp;positive&nbsp;integer&nbsp;m&nbsp;(1&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;100)&nbsp;indicating&nbsp;the&nbsp;number&nbsp;of&nbsp;devices&nbsp;you&nbsp;would&nbsp;like&nbsp;to&nbsp;plug&nbsp;in.&nbsp;Each&nbsp;of&nbsp;the&nbsp;next&nbsp;m&nbsp;lines&nbsp;lists&nbsp;the&nbsp;name&nbsp;of&nbsp;a&nbsp;device&nbsp;followed&nbsp;by&nbsp;the&nbsp;type&nbsp;of&nbsp;plug&nbsp;it&nbsp;uses&nbsp;(which&nbsp;is&nbsp;identical&nbsp;to&nbsp;the&nbsp;type&nbsp;of&nbsp;receptacle&nbsp;it&nbsp;requires).&nbsp;A&nbsp;device&nbsp;name&nbsp;is&nbsp;a&nbsp;string&nbsp;of&nbsp;at&nbsp;most&nbsp;24&nbsp;alphanumeric&nbsp;</span><br style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;" />
<span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">characters.&nbsp;No&nbsp;two&nbsp;devices&nbsp;will&nbsp;have&nbsp;exactly&nbsp;the&nbsp;same&nbsp;name.&nbsp;The&nbsp;plug&nbsp;type&nbsp;is&nbsp;separated&nbsp;from&nbsp;the&nbsp;device&nbsp;name&nbsp;by&nbsp;a&nbsp;space.&nbsp;The&nbsp;next&nbsp;line&nbsp;contains&nbsp;a&nbsp;single&nbsp;positive&nbsp;integer&nbsp;k&nbsp;(1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;100)&nbsp;indicating&nbsp;the&nbsp;number&nbsp;of&nbsp;different&nbsp;varieties&nbsp;of&nbsp;adapters&nbsp;that&nbsp;are&nbsp;available.&nbsp;Each&nbsp;of&nbsp;the&nbsp;next&nbsp;k&nbsp;lines&nbsp;describes&nbsp;a&nbsp;variety&nbsp;of&nbsp;adapter,&nbsp;giving&nbsp;the&nbsp;type&nbsp;of&nbsp;receptacle&nbsp;provided&nbsp;by&nbsp;the&nbsp;adapter,&nbsp;followed&nbsp;by&nbsp;a&nbsp;space,&nbsp;followed&nbsp;by&nbsp;the&nbsp;type&nbsp;of&nbsp;plug.</span></p>

<p>&nbsp;</p>

<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">翻译</span></strong></h3>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">输入由一个测试用例组成。</span></p>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">第一行给出一个正整数n&nbsp;(1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;100)&nbsp;，表示房间里的插座数量。</span></p>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">后面的n行给出房间里插座的类型，每个插座类型由最多24个字母字符组成的字符串。</span></p>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">下一行给出一个正整数m&nbsp;(1&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;100)&nbsp;，表示要接电的设备数。</span></p>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">后面的m行每行给出一个设备名，然后给出使用的插头类型（与它所要使用的插座类型相同）。设备名是一个最多24个字母字符组成的字符串。任何两个设备的名字不会相同。插头类型和设备名之间用一个空格分开。</span></p>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">下一行给出一个正整数k（1&lt;=k&lt;=100）表述可供使用不同类型的转换连接器数量。后面的k行每行描述一类转换连接器，表示转换连接器提供的插座的类型，在一个空格后，是插头的类型。</span></p> 

 
 # 输出格式 
<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">原文</span></strong></h3>

<p><span style="color: rgb(0, 0, 0); font-family: 'Times New Roman', Times, serif; font-size: 16px; line-height: normal;">A&nbsp;line&nbsp;containing&nbsp;a&nbsp;single&nbsp;non-negative&nbsp;&nbsp;integer&nbsp;&nbsp;indicating&nbsp;&nbsp;the&nbsp;&nbsp;smallest&nbsp;&nbsp;number&nbsp;&nbsp;of&nbsp;&nbsp;devices&nbsp;&nbsp;that&nbsp;&nbsp;cannot&nbsp;&nbsp;be&nbsp;&nbsp;plugged&nbsp;&nbsp;in.</span></p>

<p>&nbsp;</p>

<h3><strong><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">翻译</span></strong></h3>

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px;">一行给出一个非负的整数，表示不能接电的设备的最小数量。</span></p> 

 
 # 提示 
<h3><strong>测试数据</strong></h3>

<p>测试数据尚未完善！(测试数据5-9未录入)故只有5组测试数据。之后会更新。</p>

<h3><strong>版权</strong></h3>

<p style="line-height: 20.8px;">本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</p> 
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
<tr><td>4 
A 
B 
C 
D 
5 
laptop B 
phone C 
pager B 
clock B 
comb X 
3 
B X 
X A 
X D</td><td>1</td></tr></table>
