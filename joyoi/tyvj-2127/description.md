# 

 
 # 题目描述 
<p><span style="line-height: 20.7999992370605px;">一场地震把约翰家园摧毁了，坚强的约翰决心重建家园。约翰已经修复了N&nbsp;个牧场，他需要再</span><span style="line-height: 20.7999992370605px;">修复一些道路把它们连接起来。碰巧的是，奶牛们最近也成立了一个工程队，专门从事道路修复。而</span><span style="line-height: 20.7999992370605px;">然，奶牛们很有经济头脑，如果无利可图，它们是不会干的。</span><br style="line-height: 20.7999992370605px;" />
<span style="line-height: 20.7999992370605px;">约翰和奶牛达成了协议，约翰向奶牛支付F&nbsp;元，奶牛负责修路，但不必修复所有道路，只要确保</span><span style="line-height: 20.7999992370605px;">所有牧场连通即可。可供奶牛选择修复的道路有M&nbsp;条，第i&nbsp;条道路连接第Ui&nbsp;个牧场和第Vi&nbsp;个牧场，</span><span style="line-height: 20.7999992370605px;">修复需要Ti&nbsp;分钟，支出成本为Ci。保证连通所有牧场的道路修复方案总是存在的。奶牛们关注的是</span><span style="line-height: 20.7999992370605px;">挣钱速度，即总利润和总施工时间的比值。请帮助奶牛们选择修复哪些道路，才能使它们在单位时间</span><span style="line-height: 20.7999992370605px;">里的利润最大？</span></p> 

 
 # 输入格式 
<p>&bull;&nbsp;第一行：三个整数N，M&nbsp;和F，1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;400;&nbsp;1&nbsp;&le;&nbsp;M&nbsp;&le;&nbsp;10000;&nbsp;1&nbsp;&le;&nbsp;F&nbsp;&le;&nbsp;2&nbsp;&times;&nbsp;10^9<br />
&bull;&nbsp;第二行到第M&nbsp;+&nbsp;1&nbsp;行：第i&nbsp;+&nbsp;1&nbsp;行有四个整数Ui，Vi，Ci&nbsp;和Ti，1&nbsp;&le;&nbsp;Ui;&nbsp;Vi&nbsp;&le;&nbsp;N,&nbsp;1&nbsp;&le;&nbsp;Ci;&nbsp;Ti&nbsp;&le;2&nbsp;&times;&nbsp;10^9</p> 

 
 # 输出格式 
<p>&bull;&nbsp;单个浮点数：表示施工队的最大挣钱速度，以四舍五入的方法保留四位小数，如果这个项目一定亏本，输出0.0000</p> 

 
 # 提示 
<p>样例输入&nbsp;&nbsp;</p>

<p>5&nbsp;5&nbsp;100<br />
1&nbsp;2&nbsp;20&nbsp;5<br />
1&nbsp;3&nbsp;20&nbsp;5<br />
1&nbsp;4&nbsp;20&nbsp;5<br />
1&nbsp;5&nbsp;20&nbsp;5<br />
2&nbsp;3&nbsp;23&nbsp;1</p>

<p>&nbsp;</p>

<p>样例输出</p>

<p>1.0625</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 
