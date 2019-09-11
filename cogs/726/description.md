# 题目描述


<p>
	<span style="color:#FFE500;background-color:#006600;font-size:16px;">Source: SDOI2007 第二轮</span><br/>
<span style="font-size:large;"><span style="line-height:36px;">单词接龙游戏  wordgame<br/>
</span></span> <span style="font-size:14px;">[试题描述]</span><br/>
<span style="font-size:14px;"> 小木木和小凳子是两个聪明的孩子，他们五岁的时候就开始学习英语了。</span><br/>
<span style="font-size:14px;"> 英语老师教他们玩一个很简单的游戏。老师给他们一张全小写并无特殊符号的英语单词表，单词表如下：</span><br/>
<span style="font-size:14px;"> ab</span><br/>
<span style="font-size:14px;"> arc</span><br/>
<span style="font-size:14px;"> arco</span><br/>
<span style="font-size:14px;"> bar</span><br/>
<span style="font-size:14px;"> bran</span><br/>
<span style="font-size:14px;"> carbon</span><br/>
<span style="font-size:14px;"> carbons</span><br/>
<span style="font-size:14px;"> cobra</span><br/>
<span style="font-size:14px;"> crab</span><br/>
<span style="font-size:14px;"> crayon</span><br/>
<span style="font-size:14px;"> narc</span><br/>
<span style="font-size:14px;"> 然后让他们从单词表里找词语接龙。接龙的规则如下:</span><br/>
<span style="font-size:14px;"> 1 前一个单词拥有的所有字母，在后一个单词里必须出现，而且字母出现次数不少于前一单词。</span><br/>
<span style="font-size:14px;"> 2 后一个单词的长度比前一个单词的长度恰好多1</span><br/>
<span style="font-size:14px;"> 对于以上例子，一合法的接龙为:</span><br/>
<span style="font-size:14px;"> ab</span><br/>
<span style="font-size:14px;"> bar</span><br/>
<span style="font-size:14px;"> crab</span><br/>
<span style="font-size:14px;"> cobra</span><br/>
<span style="font-size:14px;"> carbon</span><br/>
<span style="font-size:14px;"> carbons</span><br/>
<span style="font-size:14px;"> 他们之中，谁接龙的长度长，谁就赢了。小木木肯定不想输，所以找到你，放肆撒娇，导致你因为不想再被打扰而帮他了。至于小凳子呢？？说不定找郭大牛去了。嘿嘿，你和郭大牛的编程比赛？？加油吧！！！</span><br/>
<span style="font-size:14px;"> [输入]</span><br/>
<span style="font-size:14px;"> n(1&lt;=n&lt;=10000)行，每行一个长度不超过100的单词。</span><br/>
<span style="font-size:14px;"> [输出]</span><br/>
<span style="font-size:14px;"> 第一行，输出最大长度ans</span><span style="font-size:14px;line-height:21px;"><br/>
</span> <span style="font-size:14px;"> Special Judge</span><br/>
<span style="font-size:14px;"> [样例]</span><br/>
<span style="font-size:14px;"> wordgame.in</span><br/>
<span style="font-size:14px;"> ab</span><br/>
<span style="font-size:14px;"> arc</span><br/>
<span style="font-size:14px;"> arco</span><br/>
<span style="font-size:14px;"> bar</span><br/>
<span style="font-size:14px;"> bran</span><br/>
<span style="font-size:14px;"> carbon</span><br/>
<span style="font-size:14px;"> carbons</span><br/>
<span style="font-size:14px;"> cobra</span><br/>
<span style="font-size:14px;"> crab</span><br/>
<span style="font-size:14px;"> crayon</span><br/>
<span style="font-size:14px;"> narc</span> 
</p>
<p>
	<span style="font-size:14px;">wordgame.out</span><br/>
<span style="font-size:14px;"> 6</span><br/>
<span style="font-size:14px;line-height:21px;"><br/>
</span> 
</p>
