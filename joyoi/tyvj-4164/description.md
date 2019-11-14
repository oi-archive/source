# 

 
 # 题目描述 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">小涵很喜欢电脑游戏，这些天他正在玩一个叫做《三国》的游戏。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">　　在游戏中，小涵和计算机各执一方，组建各自的军队进行对战。游戏中共有&nbsp;N&nbsp;位武将（N为偶数且不小于&nbsp;4），任意两个武将之间有一个&ldquo;默契值&rdquo;，表示若此两位武将作为一对组合作战时，该组合的威力有多大。游戏开始前，所有武将都是自由的（称为自由武将，一旦某个自由武将被选中作为某方军队的一员，那么他就不再是自由武将了），换句话说，所谓的自由武将不属于任何一方。</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">　　游戏开始，小涵和计算机要从自由武将中挑选武将组成自己的军队，规则如下：小涵先从自由武将中选出一个加入自己的军队，然后计算机也从自由武将中选出一个加入计算机方的军队。接下来一直按照&ldquo;小涵&rarr;计算机&rarr;小涵&rarr;&hellip;&hellip;&rdquo;的顺序选择武将，直到所有的武将被双方均分完。然后，程序自动从双方军队中各挑出一对默契值最高</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">的武将组合代表自己的军队进行二对二比武，拥有更高默契值的一对武将组合获胜，表示两军交战，拥有获胜武将组合的一方获胜。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">　　已知计算机一方选择武将的原则是尽量破坏对手下一步将形成的最强组合，它采取的具体策略如下：任何时刻，轮到计算机挑选时，它会尝试将对手军队中的每个武将与当前每个自由武将进行一一配对，找出所有配对中默契值最高的那对武将组合，并将该组合中的自由武将选入自己的军队。&nbsp;下面举例说明计算机的选将策略，例如，游戏中一共有&nbsp;6&nbsp;个武将，他们相互之间的默契值如下表所示：</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<img src="/source/joyoi/tyvj-4164/img/aHR0cDovL3d3dy5sdW9ndS5vcmcvZG93bmxvYWQvZ2V0cGljP3VwbG9hZGlkPTU0" style="box-sizing: border-box; max-width: 100%; height: auto; display: inline-block; vertical-align: middle; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;" /><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">双方选将过程如下所示：&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<img src="/source/joyoi/tyvj-4164/img/aHR0cDovL3d3dy5sdW9ndS5vcmcvZG93bmxvYWQvZ2V0cGljP3VwbG9hZGlkPTU1" style="box-sizing: border-box; max-width: 100%; height: auto; display: inline-block; vertical-align: middle; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;" /><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">小涵想知道，如果计算机在一局游戏中始终坚持上面这个策略，那么自己有没有可能必</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">胜？如果有，在所有可能的胜利结局中，自己那对用于比武的武将组合的默契值最大是多</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">少？&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">　　假设整个游戏过程中，对战双方任何时候均能看到自由武将队中的武将和对方军队的武将。为了简化问题，保证对于不同的武将组合，其默契值均不相同。</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">输入文件名为&nbsp;sanguo.in，共&nbsp;N&nbsp;行。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">第一行为一个偶数&nbsp;N，表示武将的个数。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">第&nbsp;2&nbsp;行到第&nbsp;N&nbsp;行里，第（i+1）行有（Ni）个非负整数，每两个数之间用一个空格隔</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">开，表示&nbsp;i&nbsp;号武将和&nbsp;i+1，i+2，&hellip;&hellip;，N&nbsp;号武将之间的默契值（0&le;默契值&le;1,000,000,000）。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">输出文件&nbsp;sanguo.out&nbsp;共&nbsp;1&nbsp;或&nbsp;2&nbsp;行。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">若对于给定的游戏输入，存在可以让小涵获胜的选将顺序，则输出&nbsp;1，并另起一行输出</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">所有获胜的情况中，小涵最终选出的武将组合的最大默契值。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">如果不存在可以让小涵获胜的选将顺序，则输出&nbsp;0。</span></p> 

 
 # 提示 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">【数据范围】&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">对于&nbsp;40%的数据有&nbsp;N&le;10。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">对于&nbsp;70%的数据有&nbsp;N&le;18。&nbsp;</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">对于&nbsp;100%的数据有&nbsp;N&le;500。</span></p> 
