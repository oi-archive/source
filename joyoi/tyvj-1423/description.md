# 

 
 # 题目背景 
水题No.3 

 
 # 题目描述 
GF同学和猫咪得到了一个特别的玩具，这个玩具由n个金属环（编号为1---n），和m条绳索组成，每条绳索连接两个不同的金属环，并且长度相同。GF左手拿起金属环L，猫咪右手(或者说:爪)拿起金属环R（L不等于R），然后尽量的向两边拉，他希望选择合适的L和R，使得被拉紧的绳索尽量的多。&nbsp;<BR><BR>注：如果像样例那样1-2-4-3-5-6-1构成了一个环，我们认为拉1和3时只能拉紧一边(1-2-4-3或3-5-6-1)而不算全部拉紧。通俗地说，也就是当两个环之间有几个绳索数相等的连接方法时，只算其中一条连接方法拉紧，不算全部拉紧。<BR><BR> 

 
 # 输入格式 
第一行包含两个正整数n，m<BR>接下来的m行包含两个正整数a，b，表示有一条绳索连接了a和b的绳索。<BR>n&lt;=100 

 
 # 输出格式 
仅包含一个整数，表示最多能拉紧的绳索数。 

 
 # 提示 
By&nbsp;lydliyudong 
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
<tr><td>6 6
1 2
1 6
2 4
6 5
4 3
5 3</td><td>3</td></tr></table>
