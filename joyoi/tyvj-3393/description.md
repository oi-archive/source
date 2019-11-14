# 

 
 # 题目描述 
<p>
Panda的烦恼（panda.pas\c\cpp）<br><br>【题目描述】<br>　　Panda是个数学怪人，他非常喜欢研究跟别人相反的事情。最近他正在研究筛法，众所周知，对一个范围内的整数，经过筛法处理后，剩下的全部都是质数，不过panda对这些不感兴趣，他只对被筛掉的数感兴趣，他觉得在这些被筛掉的数中一定隐藏着重要的宇宙秘密，只是人们没有发现罢了。<br>　　Panda还觉得如果只是单纯地从小到大筛的话，还不足够发现其中的奥秘，于是他决定对至多只包含某些质因数的数进行研究（比如说至多只包含质因数２2,3的数有2,3,4,6,8,9……），他需要得到这些数中第k小的数（k是panda认为的宇宙系数），请你编个程序，帮助他找到这个数。<br></p> 

 
 # 输入格式 
<p>
　　输入文件：panda.in<br>　　第一行有2个数n，k。n代表质因数的个数，k代表那个宇宙系数（1<=n<=10,1<=k<=10000）。<br>　　第二行有n个数，代表这n个质因数。（每个均小于1000，且不相同）<br></p> 

 
 # 输出格式 
<p>
　　输出文件：panda.out<br>　　仅一行，即至多只包含这n个质因数的数中第k小的数。（这个数不会超过2000000000）<br><br></p> 

 
 # 提示 
<p>
【注】前6个数是3,5,9,15,25,27。</p> 
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
<tr><td>2  7
3  5
</td><td>45</td></tr></table>
