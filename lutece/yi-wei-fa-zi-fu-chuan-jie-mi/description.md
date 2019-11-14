
# Content

密码学是一门既古老又年轻的学科。说它古老，是因为早在几千年前，人类就已经有了通信保密的思想，并先后出现了易位法和置换法等加密方法。到了1949年，信息论的创始人香农(C.E.Shannon)论证了由传统的加密方法所获得的密文，几乎是都可攻破的，这使得密码学的研究面临着严重的危机。

直至进入20世纪60年代，由于电子技术和计算机技术的迅速发展，以及结构代数、可计算性理论学科研究成果的出现，才使密码学的研究走出困境而进入了一个新的发展时期；特别是美国的数据加密标准DES和公开密钥密码体制的推出，又为密码学的广泛应用奠定了坚实的基础。

虽然加密方法很多，但最基本的加密方法只有两种，即易位法和置换法，其它方法大多是基于这两种方法形成的。易位法是按照一定的规则，重新安排明文中的比特或字符的顺序来形成密文，而字符本身保持不变。按易位单位的不同又可分成比特易位和字符易位两种易位方式。前者的实现方法简单易行，并可用硬件实现，主要用于数字通信中；而后者即字符易位法则是利用密钥对明文进行易位后形成密文。

具体方法是：假定有一密钥`DCAB`，其长度为`4`，字符串为`I love China`，去掉空格，四位四位分组，不足四位时用`e`补齐。具体见下图所示。输出时转化为大写输出。注意分组时先去掉了空格，取列时按密钥的ASCII码从小到大取，输出时英文字母全转换为了大写。

![title](/source/lutece/yi-wei-fa-zi-fu-chuan-jie-mi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTY5LzIwMTQwOTE5MTgwMTA4OTEyNy5naWY=.gif)

你的任务是把加密后的密文还原为明文。

# Standard Input

本题有多组输入。第一行数字$T$表示输入的组数，每一组有两行，第一行是密钥字符串，长度不超过$20$个(保证字符不重复)；第二行是已加密的字符串，不多于$1000$个。

# Standard Output

对应每一组，输出有一行，为解密后的字符串。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
DCAB
OHEVIELCAIEN</td><td>ILOVECHINAEE</td></tr></table>


# Constraints



# Note



# Source


