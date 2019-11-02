# 

 
 # 题目背景 
<p>SDOI2015&nbsp;Round1&nbsp;Day1&nbsp;T1</p> 

 
 # 题目描述 
<p style="font-family: arial, verdana, helvetica, sans-serif; color: rgb(0, 0, 0); font-size: 18px; line-height: normal;"><span style="font-family: Helvetica, 'Microsoft Yahei', verdana; font-size: 14px; line-height: 15.3333330154419px;">小A有一个1-2^N的排列A[1..2^N],他希望将A数组从小到大排序,小A可以执行的操作有N种,每种操作最多可以执行一次,对于所有的i(1&lt;=i&lt;=N),第i中操作为将序列从左到右划分为2^{N-i+1}段,每段恰好包括2^{i-1}个数,然后整体交换其中两段.小A想知道可以将数组A从小到大排序的不同的操作序列有多少个,小A认为两个操作序列不同,当且仅当操作个数不同,或者至少一个操作不同(种类不同或者操作位置不同).</span></p>

<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; color: rgb(0, 0, 0); font-size: 14px; line-height: 15.3333330154419px;">&nbsp;&nbsp;下面是一个操作事例:</div>

<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; color: rgb(0, 0, 0); font-size: 14px; line-height: 15.3333330154419px;">&nbsp;&nbsp;N=3,A[1..8]=[3,6,1,2,7,8,5,4].</div>

<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; color: rgb(0, 0, 0); font-size: 14px; line-height: 15.3333330154419px;">&nbsp;&nbsp;第一次操作,执行第3种操作,交换A[1..4]和A[5..8],交换后的A[1..8]为[7,8,5,4,3,6,1,2].</div>

<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; color: rgb(0, 0, 0); font-size: 14px; line-height: 15.3333330154419px;">&nbsp;&nbsp;第二次操作,执行第1种操作,交换A[3]和A[5],交换后的A[1..8]为[7,8,3,4,5,6,1,2].</div>

<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; color: rgb(0, 0, 0); font-size: 14px; line-height: 15.3333330154419px;">&nbsp;&nbsp;第三次操作,执行第2中操作,交换A[1..2]和A[7..8],交换后的A[1..8]为[1,2,3,4,5,6,7,8].</div> 

 
 # 输入格式 
<p style="font-family: arial, verdana, helvetica, sans-serif; color: rgb(0, 0, 0); font-size: 18px; line-height: normal;"><span style="font-family: Helvetica, 'Microsoft Yahei', verdana; font-size: 14px; line-height: 15.3333330154419px;">第一行,一个整数N</span></p>

<div style="font-family: arial, verdana, helvetica, sans-serif; color: rgb(0, 0, 0); font-size: 18px; line-height: normal;">
<div style="font-family: Helvetica, 'Microsoft Yahei', verdana; font-size: 14px; line-height: 15.3333330154419px;">第二行,2^N个整数,A[1..2^N]</div>
</div> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: Helvetica, 'Microsoft Yahei', verdana; font-size: 14px; line-height: 15.3333330154419px; background-color: rgb(228, 240, 248);">一个整数表示答案</span></p> 

 
 # 提示 
<p><span style="color: rgb(0, 0, 0); font-family: arial, verdana, helvetica, sans-serif; font-size: 18px; line-height: normal; background-color: rgb(228, 240, 248);">100%的数据,&nbsp;1&lt;=N&lt;=12.</span></p> 
