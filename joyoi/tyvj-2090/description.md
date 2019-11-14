# 

 
 # 题目背景 
<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;">zy,wzy,gxy,dxc四个好基友，啦啦啦~~~</p> 

 
 # 题目描述 
<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">zy很喜欢吃菠萝包，她的经济人wzy每半个月就要为她安排接下来的菠萝包计划。今天是7月初，wzy有要去商场进货买菠萝包了。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">这次wzy总共买了N种菠萝包，每种一个。每个菠萝包都有一个初始美味值Ti，每过一天就会减少Di，即第2天的美味值为Ti-Di，第3天为Ti-2*Di，以此类推。一旦美味值减为负数，那个包就坏掉了，不能吃了。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">wzy每天都要为zy安排当天吃菠萝包的组合，这些组合不是随意的，而是只能从zy喜欢的M种搭配中挑选一种。每种搭配是由Ki个菠萝包组成的，一种搭配的总美味值是这Ki个菠萝包当天的美味值之和再加上一个额外的搭配的美味值Ei。不过要注意，一旦某种搭配的其中一个菠萝包坏掉了，这个搭配就不能选用了。而且，有可能存在两个搭配，里面的组合是一样的，但额外的搭配美味值却不同。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">wzy想让可爱的小zy尽可能地吃的美味，因此希望能找出一种最优的方案，让小zy吃上若干天的菠萝包，这些天的美味值之和最大。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">但wzy面临着两个邪恶的敌人，一个叫dxc，一个叫gxy，他们也想抢夺这个经纪人之位，因此要是他们提出更优的方案，wzy就可能会失去他的小zy了。那么，你们能帮帮这个可怜的wzy吗？</span></p> 

 
 # 输入格式 
<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">本题中包含多组测试数据。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">每组测试数据中的第一行为一个正整数N，表示菠萝包的种数，按1～N编号。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">接下来的N行，每行有两个正整数Ti，Di（Ti&lt;100，Di&lt;100)，表示第i种菠萝包的初始美味值和每天递减值。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">第N+2行中为一个正整数M，表示搭配的种数。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">接下来的M行，每行先是一个正整数Ki，表示组成这个搭配的菠萝包数目。然后是一个非负整数Ei（Ei&lt;100），表示这种搭配额外的美味值。最后是Ki个整数，每个整数为菠萝包的编号。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">当N=0时，表示输入结束。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p><!--EndFragment--></p> 

 
 # 输出格式 
<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于每组测试数据，输出一行为一个整数，表示最大的美味值之和。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p><!--EndFragment--></p> 

 
 # 提示 
<p>【输入输出样例】</p>

<p>输入：</p>

<p>2</p>

<p>3&nbsp;1</p>

<p>4&nbsp;2</p>

<p>2</p>

<p>1&nbsp;1&nbsp;1</p>

<p>1&nbsp;1&nbsp;2</p>

<p>2</p>

<p>3&nbsp;1</p>

<p>4&nbsp;2</p>

<p>3</p>

<p>1&nbsp;1&nbsp;1</p>

<p>1&nbsp;1&nbsp;2</p>

<p>2&nbsp;2&nbsp;1&nbsp;2</p>

<p>0</p>

<p>&nbsp;</p>

<p>输出：</p>

<p>8</p>

<p>9</p>

<p>&nbsp;</p>

<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="color: rgb(0, 0, 0); font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">【</span><span style="color: rgb(0, 0, 0); font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">样例说明</span><span style="color: rgb(0, 0, 0); font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">】</span><span style="color: rgb(0, 0, 0); font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于第一个样例，只有两个方案：</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">1．第一天选择搭配1，即吃编号1的菠萝包，美味值为3+1=4；第二天选择搭配2，即吃编号2的菠萝包，美味值为2+1=3。此时已把菠萝包都吃完了，总和为4+3=7。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">2．第一天选择搭配2，即吃编号2的菠萝包，美味值为4+1=5；第二天选择搭配1，即吃编号1的菠萝包，美味值为2+1=3，此时已把菠萝包都吃完了，总和为5+3=8。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">因此，第2个方案为最优方案，最大美味值总和为8。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于第二例，除了上述两个方案，还有第三个：</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">3．第一天选择搭配3，即编号为1和2的菠萝包一起吃，美味值为3+4+2=9。此时已把菠萝包都吃完了，总和即为9。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">虽然第3个方案只能吃1天，但因为其总和最大，所以选择第3个方案，答案为9。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p>&nbsp;</o:p></span></p>

<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">【</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">数据范围</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">】</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于30%的数据，满足：n&lt;=8，m&lt;=10；</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于60%的数据，满足：n&lt;=11，m&lt;=15；</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p class="p0" style="text-indent: 21pt; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;">对于100%的数据，满足：n&lt;=14，m&lt;=20。</span><span style="font-family: &quot;宋体&quot;; font-size: 10.5pt; mso-spacerun: &quot;yes&quot;;"><o:p></o:p></span></p>

<p><!--EndFragment--></p> 
