# 

 
 # 题目描述 
<p align="left">　　为了加快存取速度，计算机中往往会在CPU和内存之间加入一个缓存。原理很简单。当CPU需要读取数据时，会先在缓存中找，如果缓存里有就直接使用缓存中的数据。如果缓存中没有，那么缓存就会从内存中读取所需的数据并提供给CPU，然后将数据保存在缓存中，以备后续使用。</p>

<p align="left">　　假设缓存中有M个存储单元，每个存储单元只能存放一个单位的数据。当数据从内存存入缓存时，如果此时缓存中已有的数据少于M个，就会将这个数据存入一个空的存储单元。如果此时缓存中已经有了M个数据，就会清空最早进入缓存的那个数据，空出存储单元来存放新的数据。</p>

<p align="left">　　假设CPU总共需要读取N次数据，然后给定一个需求的数据的序列，请你编写程序来计算缓存需要从内存中读取几次数据？假设一开始缓存中没有任何数据。</p> 

 
 # 输入格式 
<p align="left">用标准输入来输入数据。输入共2行，每行中两个数之间用一个空格隔开。</p>

<p align="left">第一行为2个正整数M和N，表示缓存容量和CPU读取数据的次数。</p>

<p align="left">第二行为N(N小于等于1000)个非负整数，按照CPU读取数据的顺序（每个数不超过1000），代表一个单位的数据。同样的非负整数代表同样的数据。</p> 

 
 # 输出格式 
<p>用标准输出来输出答案。输出共1行，包含1个整数，表示缓存需要从内存中读取数据的次数。</p> 

 
 # 提示 
<p align="left">整个读取数据过程如下：每行表示CPU读取一次数据，冒号前为本次读取数据后缓存的状况。缓存初始为空。</p>

<p align="left">&nbsp;</p>

<p align="left">1:&nbsp;读取1号数据并存入缓存。</p>

<p align="left">1&nbsp;2:&nbsp;读取2号数据并存入缓存。</p>

<p align="left">1&nbsp;2:&nbsp;读取1号数据，此时1号数据已经在缓存中。</p>

<p align="left">1&nbsp;2&nbsp;5:&nbsp;读取5号数据并存入缓存。</p>

<p align="left">2&nbsp;5&nbsp;4:&nbsp;读取4号数据并存入缓存，代替1号数据。</p>

<p align="left">2&nbsp;5&nbsp;4:&nbsp;读取4号数据，此时4号数据已经在缓存中。</p>

<p align="left">5&nbsp;4&nbsp;1:&nbsp;读取1号数据并存入缓存，代替2号数据。</p>

<p align="left">缓存共计从内存中存入了5次数据。</p>

<p align="left">&nbsp;</p> 
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
<tr><td>3 7
1 2 1 5 4 4 1
</td><td>5
</td></tr></table>
