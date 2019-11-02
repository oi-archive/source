# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;提高组&nbsp;题1 

 
 # 题目描述 
16&nbsp;世纪法国外交家&nbsp;Blaise&nbsp;de&nbsp;Vigenère&nbsp;设计了一种多表密码加密算法——Vigenère&nbsp;密码。Vigenère&nbsp;密码的加密解密算法简单易用,且破译难度比较高,曾在美国南北战争中为南军所广泛使用。<br>在密码学中,我们称需要加密的信息为明文,用&nbsp;M&nbsp;表示;称加密后的信息为密文,用C&nbsp;表示;<br>而密钥是一种参数,是将明文转换为密文或将密文转换为明文的算法中输入的数据,记为&nbsp;k。&nbsp;在&nbsp;Vigenère&nbsp;密码中,密钥&nbsp;k&nbsp;是一个字母串,&nbsp;k1k2...kn。<br>当明文&nbsp;M=m1m2...mn&nbsp;时,得到的密文&nbsp;C=c1c2...cn,其中&nbsp;ci=mi?ki,运算?的规则如下表所示:<br>[图片]<br>Vigenère&nbsp;加密在操作时需要注意:<br>1.&nbsp;?运算忽略参与运算的字母的大小写,并保持字母在明文&nbsp;M&nbsp;中的大小写形式;<br>2.&nbsp;当明文&nbsp;M&nbsp;的长度大于密钥&nbsp;k&nbsp;的长度时,将密钥&nbsp;k&nbsp;重复使用。<br>例如,明文&nbsp;M=Helloworld,密钥&nbsp;k=abc&nbsp;时,密文&nbsp;C=Hfnlpyosnd。<br>明文&nbsp;H&nbsp;e&nbsp;l&nbsp;l&nbsp;o&nbsp;w&nbsp;o&nbsp;r&nbsp;l&nbsp;d<br>密钥&nbsp;a&nbsp;b&nbsp;c&nbsp;a&nbsp;b&nbsp;c&nbsp;a&nbsp;b&nbsp;c&nbsp;a<br>密文&nbsp;H&nbsp;f&nbsp;n&nbsp;l&nbsp;p&nbsp;y&nbsp;o&nbsp;s&nbsp;n&nbsp;d 

 
 # 输入格式 
输入共&nbsp;2&nbsp;行。<br>第一行为一个字符串,表示密钥&nbsp;k,长度不超过&nbsp;100,其中仅包含大小写字母。第二行为一个字符串,表示经加密后的密文,长度不超过&nbsp;1000,其中仅包含大小写字母。 

 
 # 输出格式 
输出共&nbsp;1&nbsp;行,一个字符串,表示输入密钥和密文所对应的明文。 

 
 # 提示 
对于&nbsp;100%的数据,输入的密钥的长度不超过&nbsp;100,输入的密文的长度不超过&nbsp;1000,且都仅包含英文字母。NOIP&nbsp;2012 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>CompleteVictory
Yvqgpxaimmklongnzfwpvxmniytm</td><td>Wherethereisawillthereisaway</td></tr></table>
