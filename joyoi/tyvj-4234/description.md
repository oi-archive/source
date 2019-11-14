# 

 
 # 题目背景 
<p>随着第三次世界大战进入僵持阶段，轴心国正在酝酿一个绝密的大动作，为了彻底粉碎他们的计划并加速战争的结束，破获他们的情报就至关重要。作为S国安全局的局长xcl急切需要情报，故找来了学习信息学的你，希望你能早日破获敌方情报。</p> 

 
 # 题目描述 
<p>首先，我们会向你提供上次我们截获的敌方<strong>明文</strong>和已知敌方的行动，并对其行动转述为明文所对应的<strong>密文</strong>（逐字母对应且明文和密文均仅由大写英文字母组成），而敌人很狡猾，故意在密文所对应的<strong>明文</strong>前后会增添一些没用的字母（中间不添加，且对于每一组数据前后增添的字母数保持一致），以增加破获难度。但据我们安插的卧底报告，敌方上次的明文中最靠前的并完整的有与密文一一对应的一段为<strong>有效明文</strong>（换句话说，从&lsquo;A&rsquo;到&lsquo;Z&rsquo;均有一一对应，既没落空也不会一个字母对应几个字母），而对于同一组数据，本次有效明文中不一定有出现每一个字母，但在其前后所增添的字母数和上次明文中增添的字母数都保持一致，但不同组的增添数不一样，这就大大减小了我们的工作量。现给你上次我们截获的敌方明文和其中有效明文所对应的有效密文，再给你本次截获的明文，要求你把它转换为有效密文。</p> 

 
 # 输入格式 
<p>对于每组数据，输入分三行（每行控制在255字节内且行中无空格）：</p>

<p>&nbsp;&nbsp;&nbsp;上次截获的<strong>明文</strong></p>

<p>&nbsp;&nbsp;&nbsp;上次有效明文对应的<strong>有效密文</strong></p>

<p>&nbsp;&nbsp;&nbsp;本次截获的<strong>明文</strong></p> 

 
 # 输出格式 
<p>输出仅一行（行中无空格，行末有回车）：</p>

<p>&nbsp;&nbsp;&nbsp;本次有效明文所对应的<strong>有效密文</strong></p> 

 
 # 提示 
<p>样例解释：</p>

<p>输入样例第一行（上次明文)从第10位开始，连续35位（有效密文长度)，到倒数第15位（DTKIUGONHJAYPWAQRUFCLAEKJDTKBMZSXAV）为有效明文，其对应的有效密文为第二行，即D对应的密文字母为T&hellip;&hellip;以此类推，由此推出有效明文前插9位，后插14位没用的字母成明文，用这种方法处理本次明文（输入样例第三行），依然是从第10位开始，到倒数第15位(DTKVKJFMPDJAACLXKOGXKXDAHBAYXAYPDTKNKSJAMXYTGOTOAPPKODDTKULYGDTOMPMXMMDWGEKDTGJDSDAFAJJAY）为有效明文，转换为有效密文即为输出的那一行。</p>

<p>据此，我们把有效密文断一下句：THE&nbsp;GERMAN&nbsp;TROOPS&nbsp;DECIDED&nbsp;TO&nbsp;BLOW&nbsp;DOWN&nbsp;THE&nbsp;KEY&nbsp;ROAD&nbsp;WHICH&nbsp;CONNECT&nbsp;THE&nbsp;US&nbsp;WITH&nbsp;CANADA&nbsp;AT&nbsp;FIVE&nbsp;THIRTY&nbsp;TOMORROW&nbsp;（明天5：30德军要炸断通往美国和加拿大的关键公路！）我们就得立马做好当地的防空工作。</p> 
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
<tr><td>KPKNVKPQJDTKIUGONHJAYPWAQRUFCLAEKJDTKBMZSXAVKHWBYGJLTUNLOJ
THEQUICKBROWNFOXJUMPSOVERTHELAZYDOG
OICQAJUXTDTKVKJFMPDJAACLXKOGXKXDAHBAYXAYPDTKNKSJAMXYTGOTOAPPKODDTKULYGDTOMPMXMMDWGEKDTGJDSDAFAJJAYDVVYLTULNTQCSP</td><td>THEGERMANTROOPSDECIDEDTOBLOWDOWNTHEKEYROADWHICHCONNECTTHEUSWITHCANADAATFIVETHIRTYTOMORROW</td></tr></table>
