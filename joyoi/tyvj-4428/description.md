# 

 
 # 题目背景 
<p>&nbsp;</p>

<div style="background:#eee;border:1px solid #ccc;padding:5px 10px;">&nbsp;</div>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>&nbsp;</p>

<div><span style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px; background-color: rgb(228, 240, 248);">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;乔普好不容易进入宝藏的入口，来到比较宽敞的地下室大厅，在大厅的中央，放着类似一张桌子，却是一个机关，这张桌子一只石青蛙，石青蛙会吐出的能量彩球，球造型美丽，并且有着神秘的色彩，环绕着石青蛙的是载骷髅的轨道，各种不同颜色的骷髅鬼会沿着轨道往前滑动，石青蛙必需遏止骷髅们滚进去轨道终点的洞里头，要靠石青蛙吐出的能量彩珠与轨道上的骷髅相结合，三个以上颜色相同即可以消失，消失后，前面和与后面的骷髅会发生碰撞，一旦三个以上颜色相同的骷髅的同样也会消失，直到轨道上的骷髅通通都被清干净为止，只有把这些骷髅全部清理干净，这个机关才会被解除，打开另一扇门。乔普被这个景象吸引，惊呼&ldquo;这不是祖玛游戏吗，难道几百年前就有这个游戏，是游戏的最原始版本&rdquo;。现在需要最小步骤将这些的骷髅全部清理干净，这个石青蛙吐出的能量彩球的颜色，可根据操作人意向而决定，一次只能吐出一个球；而原先在轨道的三个以上相同颜色的骷髅，在没有碰撞的情况下是不会消失的。</span><img alt="" height="140" src="/source/joyoi/tyvj-4428/img/aHR0cDovL29qLm5iZHAubmV0L3VwbG9hZC8yMDE2MDMvMTk2OC5qcGc=.jpg" style="height: auto; border: 0px; vertical-align: middle; font-family: 'Times New Roman'; font-size: 20px; line-height: 24px;" width="150" />​</div> 

 
 # 输入格式 
<pre class="content" style="padding: 8.5px; font-family: Menlo, Monaco, 'Courier New', monospace; font-size: 12.025px; border-radius: 4px; margin-top: 0px; margin-bottom: 9px; line-height: 18px; border: 1px solid rgba(0, 0, 0, 0.14902); word-break: break-all; background-color: rgb(245, 245, 245);">
<span style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px; background-color: rgb(228, 240, 248);">第一行，一个整数n，表示有轨道上有n骷髅；</span>
<span style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px; background-color: rgb(228, 240, 248);">第二行，有n个整数ai，表示n骷髅，不同颜色的骷髅由不同的数表示，数与数之间由空格隔开。</span></pre> 

 
 # 输出格式 
<pre class="content" style="padding: 8.5px; font-family: Menlo, Monaco, 'Courier New', monospace; font-size: 12.025px; border-radius: 4px; margin-top: 0px; margin-bottom: 9px; line-height: 18px; border: 1px solid rgba(0, 0, 0, 0.14902); word-break: break-all; background-color: rgb(245, 245, 245);">
<span style="font-family: 'Times New Roman'; font-size: 20px; line-height: 24px; background-color: rgb(228, 240, 248);">一个整数，表示需要最小步骤将这些的骷髅全部清理干净。</span></pre> 

 
 # 提示 
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">【数据范围约定】</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">50%&nbsp;的测试点输入数据保证&nbsp;1&le;n&le;50，|ai|&nbsp;&le;10；</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">90%&nbsp;的测试点输入数据保证&nbsp;1&le;n&le;500，|ai|&nbsp;&le;10000；</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">100%&nbsp;的测试点输入数据保证&nbsp;1&le;n&le;2000，|ai|&nbsp;&lt;32767；</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">【样例解释】</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">样例1，输入1&nbsp;2&nbsp;2&nbsp;3&nbsp;3&nbsp;1，红色球表示1骷髅，绿色球表示2骷髅，蓝色球表示3骷髅；如图1</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">第一步，操作者用一个绿色的能量彩球插入到2个绿色球中，这时相结合后三个绿色球消失；第二步，操作者用一个蓝色的能量彩球插入到2个蓝色球中，这时相结合后三个蓝色球消失；第三步，这时只剩下二个红色的球，只要一个红色的能量彩球插入到2个红色球中，这时相结合后三个蓝色球消失。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">因此，最少需要3步将这些骷髅全部清理干净。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<img alt="" height="240" src="/source/joyoi/tyvj-4428/img/aHR0cDovL29qLm5iZHAubmV0L3VwbG9hZC8yMDE2MDMvMTk2OC0xLmdpZg==.gif" style="height: auto; border: 0px; vertical-align: middle; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" width="264" /><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">图1</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">样例2，&nbsp;1&nbsp;2&nbsp;2&nbsp;2&nbsp;3&nbsp;3&nbsp;2&nbsp;1&nbsp;1&nbsp;按样例1的方式，如图2；</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">第一步，在操作者用一个蓝色的能量彩球插入到2个蓝色球中，这时相结合后三个蓝色球消失，消失后，前面和后面的绿色的球结合在一起共有4个，这时也消失，接着，前面和后面的红色的球结合在一起共3个，也消失了，所以这些骷髅只需一步操作就可以全部清理干净。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<img alt="" height="166" src="/source/joyoi/tyvj-4428/img/aHR0cDovL29qLm5iZHAubmV0L3VwbG9hZC8yMDE2MDMvMTk2OC0yLmdpZg==.gif" style="height: auto; border: 0px; vertical-align: middle; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" width="372" /><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">&nbsp;&gt;</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; line-height: 18px; background-color: rgb(228, 240, 248);">图2</span></p> 
