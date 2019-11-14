# 

 
 # 题目描述 
<p><span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">羊年到了，村长开始教小羊学习Pascal语言，刚开始学习四则运算。村长在白板上写下两个整数16和3，问小羊们，有16只羊，平均分到3个羊村，每个羊村分到的数量必须相同，这个分配的数量最大是多少？小羊们很快就得到了答案，每个羊村分到5只，有1只羊就只能落单了。村长在白板上写下5。没错，这个就是Div(整除)的用法！</span><br style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">为了检验小羊们是否掌握了整除运算，村长要求小羊们轮流从白板上任意选取两个不同的数，由大数整除小数，若所得结果没有出现在白板上，就将该值写在白板上。直到小羊们再也找不到没出现过的整数。</span><br style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">虽然这样上课很锻炼小羊们的运算能力，但是课堂时间有限。为了控制课堂时间，村长想要知道，根据当前白板上的数字，最终白板上会出现几个数字？现在请你帮他编写一个程序快速计算一下吧！</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">第一行一个整数N，表示当前白板上出现的整数个数。</span><br style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);" />
<span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">第二行N个整数，中间用空格分隔，表示当前在白板上的数字，保证每个数字都不相同。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(51, 51, 51); font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">输出一个整数，表示最终白板上数字的个数。</span></p> 

 
 # 提示 
<p style="margin: 0px 0px 9px; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; color: rgb(51, 51, 51);">【样例1解释】<br />
<br />
选择16和3，写下5；选择5和3，写下1；共16，3，5，1，四个整数。<br />
<br />
【样例2解释】<br />
<br />
选择17和2，写下8；再选择8和2，写下4；共17，2，8，4，1，五个整数。</p>

<p>&nbsp;</p>

<p style="margin: 0px 0px 9px; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; color: rgb(51, 51, 51);">【数据范围】<br />
<br />
50%的数据，N&lt;=50；<br />
<br />
100%的数据，N&lt;=100，1&lt;=ai&lt;=100。</p> 
