# 

 
 # 题目背景 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">小明正在玩一个挂机游戏，他想节省时间，尽快玩通关，请编个程序来帮他。</span></p> 

 
 # 题目描述 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">有n个怪物，每个怪物都有一个hp值和打败它所能获得的金钱值（初始为0）。每个怪物可以打无数次(每秒最多打一次,且同时只能打一个怪)，但只有打赢过上一个怪物才能打下一个怪物。打完所有怪物就算通关。</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">小明每秒可以通过点击鼠标对怪物造成1点伤害，此外，他还可以购买一些兵来帮他打怪（购买不需要时间）。有若干种兵，每种兵都有一个价格，且价格随着购买数量而上升（每购买一个该种兵，该种兵的价格就上升一个定值a）。</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">现在，你需要求出通关的最小时间。</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">第一行，一个数n，表示怪物数量；</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">2&nbsp;到&nbsp;n+1&nbsp;行，每行两个数，表示每个怪的hp和打败后获得的金钱；</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">n+2&nbsp;行，一个数m，表示兵的种类数；</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">n+3&nbsp;到&nbsp;n+m+2&nbsp;行，每行三个数，分别表示每个该种兵每秒的伤害值，每个该种兵的初始价格，以及每购买一个该种兵价格的增加量a。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">一个数，表示通关的最小时间（秒）。</span></p> 

 
 # 提示 
<p><span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">数据范围很小。</span><br class="contentbr" style="box-sizing: border-box; display: inline; line-height: 30px; color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px;" />
<span style="color: rgb(34, 34, 34); font-family: 微软雅黑; font-size: 14px; line-height: 25px;">样例说明：第一秒，第三秒，第六秒，第十秒后分别买一个兵，然后四个兵加鼠标用二十秒打完第二个怪。</span></p> 
