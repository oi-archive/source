# 

 
 # 题目描述 
<p>
送给MM的生日礼物（gift.pas\c\cpp）<br><br>【题目描述】<br>　　10月11日是MM的生日，Matrix67打算自己DIY一些抱枕送给MM。Matrix67手中有一块矩形花布，花布分成了M x N个小格子，有些格子的花色相同，有些格子的花色不同。为了使最终成品更美观，Matrix67希望用于DIY的布匹都是正方形的，并且满足布匹花色上下对称且左右对称。为此，他希望能计算出这块花布里一共包含有多少个上下对称且左右对称的小正方形。<br>    举例来说，Matrix67手中的花布大小为6 x 4，上面共有5种花色：<br><br>　　　ABACDA<br>　　　DCDEAA<br>　　　ABABAA<br>　　　DDCBBA<br><br>　　则这块布里一共有26个上下对称且左右对称的正方形，其中包括最左上角的3x3正方形、右边4个A组成的2x2正方形，当然还有24个1x1的小正方形。<br></p> 

 
 # 输入格式 
<p>
　　输入文件gift.in第一行输入两个用空格隔开的正整数M,N，表示Matrix67手中的格子布分为M行N列。<br>    以下M行每行N个字符，描述布匹的花色。我们用26个大写字母来区别不同的花色，相同的字母代表相同的花色，不同的字母代表不同的花色。<br></p> 

 
 # 输出格式 
<p>
　　输出文件gift.out中输出在Matrix67的格子布中切出一块花色左右对称且上下对称的正方形共有多少种方案。</p> 

 
 # 提示 
<p>
【数据规模】<br>　　对于30%的数据，M,N<=10；<br>　　对于100%的数据，M,N<=200。<br><br>【FAQ】<br>　　Q: 第二题<br>　　　ABCAB<br>　　　ABCAB<br>　　　ABCAB<br>　　　这样算不算对称???<br>　　A: 这个图形满足上下对称，但不满足左右对称，而且它不是正方形。<br><br>　　Q: 上下左右对称是中心对称吗?<br>　　A: 这两者并不完全等价。题目的意思是上下轴对称且左右轴对称<br><br></p> 
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
<tr><td>4 6
ABACDA
DCDEAA
ABABAA
DDCBBA
</td><td>26</td></tr></table>
