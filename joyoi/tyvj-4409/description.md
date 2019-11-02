# 

 
 # 题目描述 
<p style="margin-left:19.55pt;">有n个灯(1&le;n&le;1000000000)，编号为1，2，&hellip;&hellip;n，同时有n个人，依次对灯进行操作。</p>

<p style="margin-left:19.55pt;">开始时，所有灯是关闭状态。</p>

<p style="margin-left:19.55pt;">第1人操作：将所有灯打开</p>

<p style="margin-left:19.55pt;">第2人操作：将2及2的倍数的灯，状态取反，即开状态变为关状态，其状态变为开状态。</p>

<p style="margin-left:19.55pt;">第3人操作：将3及3倍数的灯状态取后。</p>

<p style="margin-left:19.55pt;">&hellip;&hellip;</p>

<p style="margin-left:19.55pt;">第i人操作：将i及i的倍数的灯状态取反(1&le;i&le;n)，当所有操作完成之后，计算出所有开状态的灯的编号之和。</p>

<p style="margin-left:19.55pt;">例如：n=6,&nbsp;&nbsp;0&mdash;状态，1&mdash;开状态</p>

<p style="margin-left:19.55pt;">开始&nbsp;&nbsp;0&nbsp;0&nbsp;0&nbsp;0&nbsp;0&nbsp;0</p>

<p style="margin-left:19.55pt;">第1人操作之后：变为1&nbsp;1&nbsp;1&nbsp;1&nbsp;1&nbsp;1</p>

<p style="margin-left:19.55pt;">第2人操作之后：变为1&nbsp;0&nbsp;1&nbsp;0&nbsp;1&nbsp;0</p>

<p style="margin-left:19.55pt;">第3人操作之后：变为1&nbsp;0&nbsp;0&nbsp;0&nbsp;1&nbsp;1</p>

<p style="margin-left:19.55pt;">第4人操作之后：变为1&nbsp;0&nbsp;0&nbsp;1&nbsp;1&nbsp;1</p>

<p style="margin-left:19.55pt;">第5人操作之后：变为1&nbsp;0&nbsp;0&nbsp;1&nbsp;0&nbsp;1</p>

<p style="margin-left:19.55pt;">第6人操作之后：变为1&nbsp;0&nbsp;0&nbsp;1&nbsp;0&nbsp;0</p>

<p style="margin-left:19.55pt;">所有开状态灯编号之和为1+4=5</p> 

 
 # 输入格式 
<p>6</p> 

 
 # 输出格式 
<p>5</p> 
