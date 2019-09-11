# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
我国的离婚率连续7年上升，今年的头两季，平均每天有近5000对夫妇离婚，大城市的离婚率上升最快，有研究婚姻问题的专家认为，是与简化离婚手续有关。<br/>
25岁的姗姗和男友谈恋爱半年就结婚，结婚不到两个月就离婚，是典型的“闪婚闪离”例子，而离婚的导火线是两个人争玩电脑游戏，丈夫一气之下，把电脑炸烂。<br/>
有社会工作者就表示，80后求助个案越来越多，有些是与父母过多干预有关。而根据民政部的统计，中国离婚五大城市首位是北京，其次是上海、深圳，广州和厦门，那么到底是什么原因导致我国成为离婚大国呢?有专家分析说，中国经济急速发展，加上女性越来越来越独立，另外，近年来简化离婚手续是其中一大原因。<br/>
——以上内容摘自第一视频门户<br/>
<br/>
现代生活给人们施加的压力越来越大，离婚率的不断升高已成为现代社会的一大问题。而其中有许许多多的个案是由婚姻中的“不安定因素”引起的。妻子与丈夫吵架后，心如绞痛，于是寻求前男友的安慰，进而夫妻矛盾激化，最终以离婚收场，类似上述的案例数不胜数。<br/>
我们已知n对夫妻的婚姻状况，称第i对夫妻的男方为B<sub>i</sub>，女方为G<sub>i</sub>。若某男B<sub>i</sub>与某女G<sub>j</sub>曾经交往过（无论是大学，高中，亦或是幼儿园阶段，i≠j），则当某方与其配偶（即B<sub>i</sub>与G<sub>i</sub>或B<sub>j</sub>与G<sub>j</sub>）感情出现问题时，他们有私奔的可能性。不妨设B<sub>i</sub>和其配偶G<sub>i</sub>感情不和，于是B<sub>i</sub>和G<sub>j</sub>旧情复燃，进而B<sub>j</sub>因被戴绿帽而感到不爽，联系上了他的初恋情人G<sub>k</sub>……一串串的离婚事件像多米诺骨牌一般接踵而至。若在B<sub>i</sub>和G<sub>i</sub>离婚的前提下，这2n个人最终依然能够结合成n对情侣，那么我们称婚姻i为不安全的，否则婚姻i就是安全的。<br/>
给定所需信息，你的任务是判断每对婚姻是否安全。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行为一个正整数n，表示夫妻的对数；<br/>
以下n行，每行包含两个字符串，表示这n对夫妻的姓名（先女后男），由一个空格隔开；<br/>
第n+2行包含一个正整数m，表示曾经相互喜欢过的情侣对数；<br/>
以下m行，每行包含两个字符串，表示这m对相互喜欢过的情侣姓名（先女后男），由一个空格隔开。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出文件共包含n行，第i行为“Safe”（如果婚姻i是安全的）或“Unsafe”（如果婚姻i是不安全的）。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2<br/>
Melanie Ashley<br/>
Scarlett Charles<br/>
1<br/>
Scarlett Ashley
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
Safe<br/>
Safe
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2<br/>
Melanie Ashley<br/>
Scarlett Charles<br/>
2<br/>
Scarlett Ashley<br/>
Melanie Charles
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
Unsafe<br/>
Unsafe
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于20%的数据，n≤20；<br/>
对于40%的数据，n≤100，m≤400；<br/>
对于100%的数据，所有姓名字符串中只包含英文大小写字母，大小写敏感，长度不大于8，保证每对关系只在输入文件中出现一次，输入文件的最后m行不会出现未在之前出现过的姓名，这2n个人的姓名各不相同，1≤n≤4000，0≤m≤20000。
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p class="NOI0">
<span style="font-family:黑体;">【问题描述】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">我国的离婚率连续</span><span lang="EN-US">7</span><span style="font-family:宋体;">年上升，今年的头两季，平均每天有近</span><span lang="EN-US">5000</span><span style="font-family:宋体;">对夫妇离婚，大城市的离婚率上升最快，有研究婚姻问题的专家认为，是与简化离婚手续有关。</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span lang="EN-US">25</span><span style="font-family:宋体;">岁的姗姗和男友谈恋爱半年就结婚，结婚不到两个月就离婚，是典型的“闪婚闪离”例子，而离婚的导火线是两个人争玩电脑游戏，丈夫一气之下，把电脑炸烂。</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">有社会工作者就表示，</span><span lang="EN-US">80</span><span style="font-family:宋体;">后求助个案越来越多，有些是与父母过多干预有关。而根据民政部的统计，中国离婚五大城市首位是北京，其次是上海、深圳，广州和厦门，那么到底是什么原因导致我国成为离婚大国呢</span><span lang="EN-US">?</span><span style="font-family:宋体;">有专家分析说，中国经济急速发展，加上女性越来越来越独立，另外，近年来简化离婚手续是其中一大原因。</span><span lang="EN-US"></span> 
</p>
<p class="NOI1" style="text-align:right;" align="right">
<span style="font-family:宋体;">——以上内容摘自第一视频门户</span><span lang="EN-US"></span> 
</p>
<p class="NOI1" style="text-align:left;" align="left">
<span lang="EN-US"> </span> 
</p>
<p class="NOI1" style="text-align:left;" align="left">
<span style="font-family:宋体;">现代生活给人们施加的压力越来越大，离婚率的不断升高已成为现代社会的一大问题。而其中有许许多多的个案是由婚姻中的“不安定因素”引起的。妻子与丈夫吵架后，心如绞痛，于是寻求前男友的安慰，进而夫妻矛盾激化，最终以离婚收场，类似上述的案例数不胜数。</span><span lang="EN-US"></span> 
</p>
<p class="NOI1" style="text-align:left;" align="left">
<span style="font-family:宋体;">我们已知</span><span lang="EN-US">n</span><span style="font-family:宋体;">对夫妻的婚姻状况，称第</span><span lang="EN-US">i</span><span style="font-family:宋体;">对夫妻的男方为</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">，女方为</span><span lang="EN-US">G<sub>i</sub></span><span style="font-family:宋体;">。若某男</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">与某女</span><span lang="EN-US">G<sub>j</sub></span><span style="font-family:宋体;">曾经交往过（无论是大学，高中，亦或是幼儿园阶段，</span><span lang="EN-US">i</span><span style="font-family:宋体;">≠</span><span lang="EN-US">j</span><span style="font-family:宋体;">），则当某方与其配偶（即</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">与</span><span lang="EN-US">G<sub>i</sub></span><span style="font-family:宋体;">或</span><span lang="EN-US">B<sub>j</sub></span><span style="font-family:宋体;">与</span><span lang="EN-US">G<sub>j</sub></span><span style="font-family:宋体;">）感情出现问题时，他们有私奔的可能性。不妨设</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">和其配偶</span><span lang="EN-US">G<sub>i</sub></span><span style="font-family:宋体;">感情不和，于是</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">和</span><span lang="EN-US">G<sub>j</sub></span><span style="font-family:宋体;">旧情复燃，进而</span><span lang="EN-US">B<sub>j</sub></span><span style="font-family:宋体;">因被戴绿帽而感到不爽，联系上了他的初恋情人</span><span lang="EN-US">G<sub>k</sub></span><span style="font-family:宋体;">……一串串的离婚事件像多米诺骨牌一般接踵而至。若在</span><span lang="EN-US">B<sub>i</sub></span><span style="font-family:宋体;">和</span><span lang="EN-US">G<sub>i</sub></span><span style="font-family:宋体;">离婚的前提下，这</span><span lang="EN-US">2n</span><span style="font-family:宋体;">个人最终依然能够结合成</span><span lang="EN-US">n</span><span style="font-family:宋体;">对情侣，那么我们称婚姻</span><span lang="EN-US">i</span><span style="font-family:宋体;">为不安全的，否则婚姻</span><span lang="EN-US">i</span><span style="font-family:宋体;">就是安全的。</span><span lang="EN-US"></span> 
</p>
<p class="NOI1" style="text-align:left;" align="left">
<span style="font-family:宋体;">给定所需信息，你的任务是判断每对婚姻是否安全。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【输入格式】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">第一行为一个正整数</span><span lang="EN-US">n</span><span style="font-family:宋体;">，表示夫妻的对数；</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">以下</span><span lang="EN-US">n</span><span style="font-family:宋体;">行，每行包含两个字符串，表示这</span><span lang="EN-US">n</span><span style="font-family:宋体;">对夫妻的姓名（先女后男），由一个空格隔开；</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">第</span><span lang="EN-US">n+2</span><span style="font-family:宋体;">行包含一个正整数</span><span lang="EN-US">m</span><span style="font-family:宋体;">，表示曾经相互喜欢过的情侣对数；</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">以下</span><span lang="EN-US">m</span><span style="font-family:宋体;">行，每行包含两个字符串，表示这</span><span lang="EN-US">m</span><span style="font-family:宋体;">对相互喜欢过的情侣姓名（先女后男），由一个空格隔开。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【输出格式】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">输出文件共包含</span><span lang="EN-US">n</span><span style="font-family:宋体;">行，第</span><span lang="EN-US">i</span><span style="font-family:宋体;">行为“</span><span lang="EN-US">Safe</span><span style="font-family:宋体;">”（如果婚姻</span><span lang="EN-US">i</span><span style="font-family:宋体;">是安全的）或“</span><span lang="EN-US">Unsafe</span><span style="font-family:宋体;">”（如果婚姻</span><span lang="EN-US">i</span><span style="font-family:宋体;">是不安全的）。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输入</span><span lang="EN-US">1</span><span style="font-family:黑体;">】</span><span lang="EN-US"></span> 
</p>
<p class="NOI2">
<span lang="EN-US">2</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Melanie Ashley</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Scarlett Charles</span> 
</p>
<p class="NOI2">
<span lang="EN-US">1</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Scarlett Ashley</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输出</span><span lang="EN-US">1</span><span style="font-family:黑体;">】</span><span lang="EN-US"></span> 
</p>
<p class="NOI2">
<span lang="EN-US">Safe</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Safe</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输入</span><span lang="EN-US">2</span><span style="font-family:黑体;">】</span><span lang="EN-US"></span> 
</p>
<p class="NOI2">
<span lang="EN-US">2</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Melanie Ashley</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Scarlett Charles</span> 
</p>
<p class="NOI2">
<span lang="EN-US">2</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Scarlett Ashley</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Melanie Charles</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输出</span><span lang="EN-US">2</span><span style="font-family:黑体;">】</span><span lang="EN-US"></span> 
</p>
<p class="NOI2">
<span lang="EN-US">Unsafe</span> 
</p>
<p class="NOI2">
<span lang="EN-US">Unsafe</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【数据规模和约定】</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">对于</span><span lang="EN-US">20%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">20</span><span style="font-family:宋体;">；</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">对于</span><span lang="EN-US">40%</span><span style="font-family:宋体;">的数据，</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">100</span><span style="font-family:宋体;">，</span><span lang="EN-US">m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">400</span><span style="font-family:宋体;">；</span><span lang="EN-US"></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">对于</span><span lang="EN-US">100%</span><span style="font-family:宋体;">的数据，所有姓名字符串中只包含英文大小写字母，大小写敏感，长度不大于</span><span lang="EN-US">8</span><span style="font-family:宋体;">，保证每对关系只在输入文件中出现一次，输入文件的最后</span><span lang="EN-US">m</span><span style="font-family:宋体;">行不会出现未在之前出现过的姓名，这</span><span lang="EN-US">2n</span><span style="font-family:宋体;">个人的姓名各不相同，</span><span lang="EN-US">1</span><span style="font-family:宋体;">≤</span><span lang="EN-US">n</span><span style="font-family:宋体;">≤</span><span lang="EN-US">4000</span><span style="font-family:宋体;">，</span><span lang="EN-US">0</span><span style="font-family:宋体;">≤</span><span lang="EN-US">m</span><span style="font-family:宋体;">≤</span><span lang="EN-US">20000</span><span style="font-family:宋体;">。</span><span lang="EN-US"></span> 
</p>
</div>
</div>
