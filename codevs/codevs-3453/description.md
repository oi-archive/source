<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    <span style="">镇海中学开设了很多校本选修课程，有体育类、音乐类、美术类、无线电测向、航空航海航天模型制作等，力争使每位学生高中毕业后，能学到一门拿得出手的兴趣爱好，为将来的终身发展打下基础。在体育类的校本选修课程中，有一门课程是斯诺克台球。</span></p><p style=""><span style="">斯诺克台球比赛中有</span><span style="font-family: Verdana, sans-serif;">21</span><span style="">个球，其中有</span><span style="font-family: Verdana, sans-serif;">15</span><span style="">个红球，</span><span style="font-family: Verdana, sans-serif;">6</span><span style="">个彩球（黄、绿、棕、蓝、粉、黑）。甲乙二人轮流打球。打一个红球得</span><span style="font-family: Verdana, sans-serif;">1</span><span style="">分，打一个彩球的得分如下：</span></p><p style=""><span style="">黄球：</span><span style="font-family: Verdana, sans-serif;">2</span><span style="">分；</span><span style="font-family: Verdana, sans-serif;">        </span><span style="">绿球：</span><span style="font-family: Verdana, sans-serif;">3</span><span style="">分；</span><span style="font-family: Verdana, sans-serif;">         </span><span style="">棕球：</span><span style="font-family: Verdana, sans-serif;">4</span><span style="">分；</span></p><p style=""><span style="">蓝球：</span><span style="font-family: Verdana, sans-serif;">5</span><span style="">分；</span><span style="font-family: Verdana, sans-serif;">        </span><span style="">粉球：</span><span style="font-family: Verdana, sans-serif;">6</span><span style="">分；</span><span style="font-family: Verdana, sans-serif;">         </span><span style="">黑球：</span><span style="font-family: Verdana, sans-serif;">7</span><span style="">分；</span></p><p style=""><span style="">最后以得分高者为胜。</span></p><p style=""><span style="">简化后的打球规则如下：</span></p><p style=""><span style="font-family: Verdana, sans-serif;">1</span><span style="">．如果有红球，第</span><strong><span style="">奇数次</span></strong><span style="">必须打红球，打过的红球从桌面上拿走；</span></p><p style=""><span style="font-family: Verdana, sans-serif;">2</span><span style="">．每打一个红球后，可以任意选一个彩球打，打红球后接着打的彩球不从桌面上拿走；</span></p><p style=""><span style="font-family: Verdana, sans-serif;">3. </span><span style="">如果桌面上已经没有红球可打了，那么按照分值从小到大的次序打彩球，这时候每打一个彩球都从桌面上拿走。</span></p><p style=""><span style="">打球时犯规的判罚如下：</span></p><p style=""><span style="font-family: Verdana, sans-serif;">  1. </span><span style="">没有打中球，给对方加</span><span style="font-family: Verdana, sans-serif;">4</span><span style="">分；</span></p><p style=""><span style="font-family: Verdana, sans-serif;">  2</span><span style="">．没有按照打球规则打该打的球，即打中了错误的球时：</span></p><p style=""><span style="">（</span><span style="font-family: Verdana, sans-serif;">1</span><span style="">）如果这个错误的球的分值大于</span><span style="font-family: Verdana, sans-serif;">4</span><span style="">，那么给对方加等于这个球的分值；</span></p><p style=""><span style="">（</span><span style="font-family: Verdana, sans-serif;">2</span><span style="">）如果这个错误的球的分值不大于</span><span style="font-family: Verdana, sans-serif;">4</span><span style="">，那么给对方加</span><span style="font-family: Verdana, sans-serif;">4</span><span style="">分；</span></p><p style=""><span style="">打中的错误球不从桌面上拿走。</span></p><p style=""><span style="">请统计某局比赛进行到现在为止的比分。</span><span style="font-family: Verdana, sans-serif;">    </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入有两行，</span><span style="">第一行有二个整数</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">和</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">，表示甲打了</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">个球，乙打了</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">个球。</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">和</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">之间以一个空格分隔。</span></p><p style=""><span style="">第二行，有</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">个以空格分隔的整数，表示甲的</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">次连续打球情况。</span></p><p style=""><span style="">第三行，有</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">个以空格分隔的整数，表示乙的</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">次连续打球情况。</span></p><p style=""><span style="">第二行和第三行中：</span></p><p style=""><span style="">（</span><span style="font-family: Verdana, sans-serif;">1</span><span style="">）</span><span style="font-family: Verdana, sans-serif;">1</span><span style="">至</span><span style="font-family: Verdana, sans-serif;">7</span><span style="">的整数表示打了相应分值的球；</span></p><p style=""><span style="">（</span><span style="font-family: Verdana, sans-serif;">2</span><span style="">）最后一个数字是</span><span style="font-family: Verdana, sans-serif;">0,</span><span style="">表示没有打中球犯规，</span><span style="font-family: Verdana, sans-serif;">0</span><span style="">只会出现在这二行的最后一个数字处；</span></p><p style=""><span style="">（</span><span style="font-family: Verdana, sans-serif;">3</span><span style="">）打了错误球的犯规也只会出现在这二行最后一个数字处；</span></p><p style=""><span style="">输入数据保证是正确，不会出现打到桌面上不存在的球的情况，数据不必检验。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp;<span style="line-height: 150%; text-indent: 32px; font-family: 宋体;">输出仅</span><span style="line-height: 150%; text-indent: 32px; font-family: 宋体;">有一行，该行有二个整数</span><span style="line-height: 150%; text-indent: 32px; font-family: Verdana, sans-serif;">(</span><span style="line-height: 150%; text-indent: 32px; font-family: 宋体;">互相之间以一个空格分隔</span><span style="line-height: 150%; text-indent: 32px; font-family: Verdana, sans-serif;">)</span><span style="line-height: 150%; text-indent: 32px; font-family: 宋体;">，表示比赛进行到现在为止甲乙二人的得分（先打的甲在前）。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Verdana','sans-serif';">4 3</span></p><p style=""><span style="font-family: 'Verdana','sans-serif';">1 7 1 6 </span></p><p style=""><span style="font-family: 'Verdana','sans-serif';">1 7 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Verdana','sans-serif';">15 9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>    甲依次打了红球、黑球、红球、粉球，甲得15分（1+7+1+6）。</p><p>    乙依次打了红球、黑球、红球，乙得9分（1+7+1）。</p><p>【数据范围】</p><p>   <span style=""> <strong>8</strong><strong style="">0</strong><strong style=""><span style="">%</span></strong><strong style=""><span style="">的数据，每次</span></strong><strong style=""><span style="">总是打中球</span></strong><strong style=""><span style="">的，并且每次打中的球</span></strong><strong style=""><span style="">总是正确的</span></strong><strong style=""><span style="">，没有犯规情况。100%的数据，会有未打中或犯规情况。</span></strong></span></p><p><span style=""><strong style=""><span style="">    保证输出不超过2^64-1.</span></strong></span></p><p>    </p>
</div>
</div>