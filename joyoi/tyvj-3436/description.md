# 

 
 # 题目描述 
<p>
字符串还原（restore.pas\c\cpp）<br><br>【问题背景】<br>　　小K是一位蔚蓝教主的崇拜者(Orz教主er)，有一天，他收到了一封匿名信，信告诉了小K由于他表现出色，得到了一次当面Orz教主的机会，但是要当面Orz教主可不那么容易，不是每个人都有资格Orz教主的……所以要破解下面一段密文才可以得到相关的信息，信中有提供加密的规则，但是小K觉得这个问题看似复杂，所以想请你帮忙……<br>【问题描述】<br>　　一个长度为n的由小写字母组成的字符串s1s2…sn按如下方式加密成3种形式：<br>　　1、将字符串翻转，即si与sn-i+1对换。<br>　　2、将字符串中每个字母变为其之后第k个字母，定义z之后的字母为a，0≤k≤6且未知。<br>　　3、将字符串中每个字母变为其之前第k个字母，定义a之前的字母为z，k同2。<br>　　例如字符串abcd按上面3种方式加密后，在k=1的情况下为：1、dcba；2、bcde；3、zabc。<br>　　现给出信中按以上3种形式分别加密后的3个字符串（不一定按以上顺序），要求还原原来的字符串，并输出告诉小K。<br></p> 

 
 # 输入格式 
<p>
　　输入文件restore.in的第1行为一个整数n，表示这个字符串的长度。<br>　　下面3行每行3个长度为n的字符串，且保证符合题目要求。<br></p> 

 
 # 输出格式 
<p>
　　输出文件restore.out仅包括1行，为还原后的字符串。</p> 

 
 # 提示 
<p>
【数据规模】<br>　　对于10%的数据，输入给出加密字符串的顺序同题目中1、2、3的顺序。<br>　　对于20%的数据，n≤5； 对于40%的数据，n≤10； <br>　　对于60%的数据，n≤255；对于100%的数据，n≤10000。<br></p> 
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
<tr><td>4
zabc
dcba 
bcde
</td><td>abcd</td></tr></table>
