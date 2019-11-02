# 

 
 # 题目描述 
<p style="margin-left:10.5pt;">陈老师喜欢网购书籍,经常一次购它个百八十本,然后拿来倒卖,谋取暴利.前些天,高一的新同学来了,他便像往常一样,兜售他的书,经过一番口舌,同学们决定买他的书,但是CS桌上的书有三堆,每一堆都有厚厚的一叠,他要想个办法用最轻松的方式把书拿下来给同学们.但是你想逗一下CS于是,请你设计一个最累的方式给他.</p>

<p style="margin-left:10.5pt;">若告诉你这三堆分别有i,j,k本书,以及每堆从下到上书的重量.每次取书只能从任意一堆的最上面取,那么请你帮助他设计一个方案,让他花最大的力气取下所有书(CS别打我).</p>

<p style="margin-left:10.5pt;">显然,每次取书,陈老师的体力消耗都会加大,这里用体力系数代表,取下第一本书时,体力系数为1,第二本时为2,依次类推,而每次体力消耗值则为体力系数和书的重量之积</p>

<p style="margin-left:10.5pt;">举个例子:</p>

<p style="margin-left:10.5pt;">三堆书及重量如下</p>

<p style="margin-left:10.5pt;"><img align="left" height="108" hspace="12" src="/source/joyoi/tyvj-4168/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDE2OC9maWxlOi8vL0M6L0RPQ1VNRX4xL0FETUlOSX4xL0xPQ0FMU34xL1RlbXAvbXNvY2xpcDEvMDMvY2xpcF9pbWFnZTAwMS5qcGc=.jpg" width="288" /></p>

<p style="margin-left:10.5pt;">&nbsp;</p>

<p style="margin-left:10.5pt;">&nbsp;</p>

<p style="margin-left:10.5pt;">&nbsp;</p>

<p style="margin-left:10.5pt;">&nbsp;</p>

<p>不用证明,最累的取书方式为:&nbsp;右左左中,&nbsp;即:&nbsp;3*1+9*2+2*3+10*4=3+18+6+40=67</p> 

 
 # 输入格式 
<p>输入文件的第一行为3个数,分别为三堆数量I,j,k</p>

<p>&nbsp;第二行至第四行分别为每堆<strong>由下至上</strong>的书本重量</p> 

 
 # 输出格式 
<p>&nbsp;输出最累方式的体力消耗总值即可</p> 

 
 # 提示 
<p>【输入样例】&nbsp;&nbsp;&nbsp;</p>

<p>3&nbsp;2&nbsp;4</p>

<p>2&nbsp;3&nbsp;2</p>

<p>1&nbsp;5</p>

<p>9&nbsp;8&nbsp;7&nbsp;4</p>

<p>【输出样例】</p>

<p>257</p> 
