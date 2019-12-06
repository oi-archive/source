# 

 
 # 题目背景 
本题原为TYVJ五月月赛提高组第一题……<BR>可Admin害怕把大家吓跑……<BR>其实本题已经很简单了……<BR>注意仔细读题即可……<BR> 

 
 # 题目描述 
现给出一个由c语言写出的N行程序，试分析其时间复杂度。<BR><BR>提示与说明：<BR>（1）循环被【严格】定义为以下形式：<BR>	for(int&nbsp;i=x;i&lt;=y;i++){<BR>		//循环体<BR>	}<BR>	其中，x和y可能为数字或n。<BR>（2）程序无递归，无调用，无跳转，时间复杂度只保留多项式的最高次项，并忽略系数，详见样例。<BR>（3）程序无分支，不存在并列循环，但可以嵌套。<BR>	for(int&nbsp;i=?;i&lt;=?;i++){<BR>		for(int&nbsp;j=?;j&lt;=?;j++){<BR>			//...<BR>		}<BR>		for(int&nbsp;k=?;k&lt;=?;k++){<BR>			//...<BR>		}<BR>	}<BR>	其中，内层两个循环相互并列，为并列循环。<BR>（4）常量与变量：<BR>	程序中只有1个常量，以【#define&nbsp;n&nbsp;100】的形式定义；<BR>	循环变量最多有五个，分别为【i,j,k,l,m】(不一定按顺序)；<BR>	除循环变量外，仅有一个变量sum，以【int&nbsp;sum=0;】形式定义。<BR>（5）代码中的注释为两个斜线，即【//】，一行中，【//】之后的全部内容被视为注释。<BR>（6）代码区分大小写。<BR> 

 
 # 输入格式 
第一行：N；<BR>接下来N行：一个由c语言写出的程序代码。<BR> 

 
 # 输出格式 
仅一行：程序的时间复杂度。<BR>格式：n^b&nbsp;（b为常数）<BR>注意：输出应符合大多数人的书写习惯。<BR> 

 
 # 提示 
对于100%数据，循环少于5层，每行不多于50字符(包含不可见字符)，0&lt;N&lt;30。 
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
<tr><td>9
#define n 100
int sum=0;
void main(){
	for(int i=0;i<=n;i++){
		for(int j=0;j<=n;j++){
			sum++;
		}
	}
}
</td><td>n^2
</td></tr></table>
