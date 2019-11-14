# 

 
 # 题目背景 
<p>转自&nbsp;Openjudge&nbsp;！</p> 

 
 # 题目描述 
<p><span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">通配符是一类键盘字符，当我们不知道真正字符或者不想键入完整名字时，常常使用通配符代替一个或多个真正字符。通配符有问号(?)和星号(*)等，其中，&ldquo;?&rdquo;可以代替一个字符，而&ldquo;*&rdquo;可以代替零个或多个字符。&nbsp;</span><br style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;" />
<br style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;" />
<span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">你的任务是，给出一个带有通配符的字符串和一个不带通配符的字符串，判断他们是否能够匹配。&nbsp;</span><br style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;" />
<br style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;" />
<span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">例如，1?456&nbsp;可以匹配&nbsp;12456、13456、1a456，但是却不能够匹配23456、1aa456；&nbsp;</span><br style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;" />
<span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">2*77?8可以匹配&nbsp;24457798、237708、27798。</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">输入有两行，每行为一个不超过20个字符的字符串，第一行带通配符，第二行不带通配符</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(35, 31, 23); font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif; font-size: 14px; line-height: 21px;">如果两者可以匹配，就输出&ldquo;matched&rdquo;，否则输出&ldquo;not&nbsp;matched&rdquo;</span></p> 
