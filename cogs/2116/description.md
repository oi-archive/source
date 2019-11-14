# 题目描述


<p>
题目描述：
</p>
<p>
<strong>Asm.def是人类协会情报组织的顶级特工，为了对叛变人类的人工智能的战争，他不得不进行一系列任务......</strong> 
</p>
<p>
<strong><img src="/upload/image/20160318/20160318153118_97254.jpg" alt="" height="419" width="745"/></strong> 
</p>
<p>
<embed src="http://player.youku.com/player.php/sid/XMzA3NjE3MDg0/v.swf" type="application/x-shockwave-flash" width="800" height="600" quality="high"/>
<strong></strong> 
</p>
<p>
<strong><img src="/upload/image/20160318/20160318154732_87072.jpg" alt=""/></strong> 
</p>
<p>
<img src="http://5577.com/zt/flappybird/flappybird.swf" alt=""/><img src="http://5577.com/zt/flappybird/flappybird.swf" alt="" height="600" width="600"/> 
</p>
<p>
<strong></strong>公元2333年，Asm.def发现，叛变的人工智能由一个神秘的大人物控制着，经过了一系列的调查，发现这个人就是<strong>唐老鸭·特朗普，</strong>原来，特朗普已经不满足凡人的世界，要成立一个<strong>人工智能控制的乌托邦</strong>，为此他准备了许多刺杀方案，其中一种方式就是使用沾有毒药的匕首刺杀，然而物理天才Asm.def对化学并不精通，因此他把配置毒药的任务交给了你，<strong>化学理论学家ZLX</strong>将辅佐你。
</p>
<p>
化学专家ZLX：下面是一些<strong><span style="color:#009900;">没有接触化学竞赛</span>的高二学生也应该<span style="color:#4C33E5;">早已</span><span style="color:#E53333;">熟练</span>掌握的化学知识</strong><span style="color:#009900;"><strong></strong><span style="color:#000000;">，鉴于ZLX对你的不信任，ZLX还是给出了以下的理论：</span></span> 
</p>
<p>
<span style="color:#009900;"><span style="color:#000000;"></span></span> 
</p>
<p>
化学反应的方向一直是化学学科研究的重要课题之一，化学反应进行程度可以用反应平衡常数K和<strong>吉布斯自由能G</strong>来描述。
</p>
<p>
<strong>H是化学反应的焓变，即1mol单位化学反应产生或吸收的热量，H&lt;0为放热反应，H&gt;0为吸热反应，一般认为，放热反应是趋向自发的</strong> 
</p>
<p>
<strong>S是化学反应的熵变，即1mol单位化学反应体系混乱度的变化，S&lt;0为混乱度减小，S&gt;0为混乱度增大，一般认为，混乱度增大是趋向自发的</strong> 
</p>
<p>
吉布斯--亥姆霍兹方程：
</p>
<p>
<img src="/upload/image/20160216/20160216071748_89330.gif" alt=""/> 
</p>
<p>
由于T对H,S的影响很小，于是我们可以得到简化后的方程
</p>
<p>
<img src="/upload/image/20160216/20160216072248_11845.gif" alt=""/> 
</p>
<p>
<strong>当G&lt;0是正向化学反应在理论上自发。</strong> 
</p>
<p>
你有一个巨大的反应炉里发生着许许多多的化学反应，由于许多化学反应都有两步，我们把这两个相关联的化学反应称为化学反应组。
</p>
<p>
<strong>化学反应组分为两种：“或”型化学反应和“与”型化学反应：</strong> 
</p>
<p>
<strong>“或”型化学反应只要一种化学反应发生，则该反应组会产生效果</strong> 
</p>
<p>
<strong>“与”型化学反应需要两种化学反应发生，该反应组会产生效果</strong> 
</p>
<p>
化学反应组产生效果<strong>会增加效益或产生杂质和有害气体</strong>，工厂的目标是<strong>使生成毒药的总收益最大</strong>，在此之下，<strong>为了降低成本，使温度尽量低</strong>，你需要计算<strong>最大总收益</strong>和<strong>对应的温度</strong>(<strong><span style="color:#E53333;">转换为摄氏度，设绝对零度为C(-273.15)，则S=T+C，如T=1，则S=-272.15</span></strong>)
</p>
<p>
<strong><br/>
</strong> 
</p>
<p>
【输入格式】：
</p>
<p>
第一行一个整数n,表示反应炉内有n个化学反应组
</p>
<p>
第二行-n+1行每行六个整数，H1,S1,H2,S2,w,type
</p>
<p>
分别表示两个化学反应的焓变和熵变，产生收益和种类（type为1为“或”，为0为“与&#34;）
</p>
<p>
【输出格式】：
</p>
<p>
只有一行，输出一个实数温度和最大收益.
</p>
<p>
<strong>温度保留两位小数。</strong> 
</p>
<p>
<strong>当最大收益小于等于0时，输出“Stupid!”(不加引号)</strong> 
</p>
<p>
<strong>T在任何条件下大于等于0</strong> 
</p>
<p>
<strong>注意G=0时反应并不会发生<br/>
</strong> 
</p>
<p>
【输入样例】：
</p>
<p>
3
</p>
<p>
0 5 0 -5 -5 1
</p>
<p>
-2 7 -2 7 999 0
</p>
<p>
4 2 -12 -3 3 0
</p>
<p>
【输出样例】注意第三行数据已经改了，之前有错误
</p>
<p>
-273.15 999
</p>
<p>
【样例解释】
</p>
<p>
第三个反应在(2,4)上会发生，产生3收益，第二个反应在任何条件下都能自发进行，第一个反应在(0,INF)上会发生，会产生负收益.
</p>
<p>
所以当T为0时收益最大为999，当(0,2]或者[4,INF)时收益为999-5=994，当(2,4)时收益为999-5+3=997
</p>
<p>
(x,y)表示T的开区间，即x&lt;T&lt;y
</p>
<p>
[x,y]表示T的闭区间，即x&lt;=T&lt;=y
</p>
<p>
(x,y]表示T的左开右闭区间,即x&lt;T&lt;=y
</p>
<p>
[x,y)表示T的左闭右开区间,即x&lt;=T&lt;y
</p>
<p>
INF表示一个特别特别大的数字
</p>
<p>
【数据范围】
</p>
<p>
对于40%的数据,n&lt;=20000
</p>
<p>
对于100%的数据,n&lt;=100000,w&lt;=40000,输入数据均为整数，<strong>不存在熵变S为0的情况</strong> 
</p>
<p>
【提示】
</p>
<p>
我们将方程变形后，会得到T关于S和H的不等式
</p>
<p>
【题目来源】
</p>
<p>
<strong><span style="color:#E53333;">高中选修课本《化学反应原理》第二章第一节</span></strong> 
</p>
