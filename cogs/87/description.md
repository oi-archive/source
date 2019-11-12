# 题目描述


<p>
  问题描述<span lang="EN-US" roman";"="" new="" times="">  </span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
今年是国际数学联盟确定的“<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">2000——世界数学年”，又恰逢我国著名数学家华罗庚先生诞辰<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">90周年。在华罗庚先生的家乡江苏金坛，组织了一场别开生面的数学智力竞赛的活动，你的一个好朋友<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">XZ也有幸得以参加。活动中，主持人给所有参加活动的选手出了这样一道题目：<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
设有一个长度为<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">N的数字串，要求选手使用<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K个乘号将它分成<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K+1个部分，找出一种分法，使得这<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K+1个部分的乘积能够为最大。<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
同时，为了帮助选手能够正确理解题意，主持人还举了如下的一个例子：<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
有一个数字串：<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">312，<span style="font-family:;" roman";"="" new="" times="">当<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">N=3，<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K=1时会有以下两种分法：<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
<!--[if !supportLists]--><span lang="EN-US" style="font-family:;" roman";"="" new="" times="">1）<span style="font-family:;" new="" times="" normal;"="" none;="" normal;="" 7pt;="" roman";="">   <!--[endif]--><span lang="EN-US" style="font-family:;" roman";"="" new="" times="">3*12=36</span></span></span> 
</p>
<p>
<!--[if !supportLists]--><span lang="EN-US" style="font-family:;" roman";"="" new="" times="">2）<span style="font-family:;" new="" times="" normal;"="" none;="" normal;="" 7pt;="" roman";="">  <!--[endif]--><span lang="EN-US" style="font-family:;" roman";"="" new="" times="">31*2=62</span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  </span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  这时，符合题目要求的结果是：<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">31*2=62</span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  现在，请你帮助你的好朋友<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">XZ设计一个程序，求得正确的答案。<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  输<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  入<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  </span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  程序的输入共有两行：<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  第一行共有<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">2个自然数<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">N，<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K(6≤<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">N≤<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">40，<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">1≤<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">K≤<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">6)</span></span></span></span></span></span></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  第二行是一个长度为<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">N的数字串。<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
<br/>
</p>
<p>
  输  出  
</p>
<p>
<br/>
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">  结果显示在屏幕上，相对于输入，应输出所求得的最大乘积<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">(一个自然数<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">)。<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""></span></span></span></span> 
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times=""> </span> 
</p>
<p>
  样  例  
</p>
<p>
<br/>
</p>
<p>
输入
</p>
<p>
<br/>
</p>
<p>
4 2
</p>
<p>
1231
</p>
<p>
<br/>
</p>
<p>
输出
</p>
<p>
<span lang="EN-US" style="font-family:;" roman";"="" new="" times="">62</span>
</p>
