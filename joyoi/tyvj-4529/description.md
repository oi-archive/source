# 

 
 # 题目描述 
<p>http://www.tyvj.cn/p/1006</p>

<p>你的任务就是<span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">在给你丢失了一个数字的</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">ISBN</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">码之后，确定那个丢失的数字。丢失数字的地方用</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">&ldquo;?&rdquo;</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">表示。</span></p>

<p><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">至于ISBN码的判定规则，请看上面的网址。</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">共</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">1</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">行，一个十个数字组成的</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">ISBN</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">码，其中包含用</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">&ldquo;?&rdquo;</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">表示的一个丢失的数字。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">共</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">1</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">行，就是那个丢失的数码（</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">0..9</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">或大写</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">X</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">）。如果标有的</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">&ldquo;?&rdquo;</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">的位置上没有数字可以使之成为一个合法的</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">ISBN</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">码的话，就输出</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 'Times New Roman';">-1</span><span style="box-sizing: border-box; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px; font-family: 宋体;">。如果多解，输出最小的。</span></p> 

 
 # 提示 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">注意X和不为0(⊙o⊙)哦。</span></p>

<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">样例输入：</span></p>

<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">15688?111X</span></p>

<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">样例输出：</span></p>

<p>1</p> 
