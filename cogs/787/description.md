# 题目描述


<p>
	【问题描述】
</p>
<p>
	定义1：如果字符串S=(S0 S1 S2...Sn)，Ror(S)=(SnS0 S1...Sn-1)
</p>
<p>
	定义2：Ror0(S)=S，Rorn(S)=Ror(Rorn-1(S) <br/>
定义3：Pow(S)={Ror0(S)，Ror1(S)，…，Rorlen(S)-1(S)} <br/>
现在你的工作是找到一个字符串T有最小的字典序在POW（S）里<br/>
举个例子：S=BOB，Ror0(S)=BOB，Ror1(S)=BBO，Ror2(S)=OBB<br/>
Pow(S)={ BOB，BBO，OBB}．<br/>
显然，T=BBO是正确的结果。
</p>
<p>
	【输入格式】
</p>
<p>
	输入第一行有一个整数，表示后面测试数据的个数。每组数据包括一个字符串S。都由大写字母组成。S的长度不会超过10000。
</p>
<p>
	【输出格式】
</p>
<p>
	程序的输出应该每个数据包括一行。每个输出只包括一个字符串T。不需要多余的空格。
</p>
<p>
	【输入样例】
</p>
<p>
	输入文件名：bob.in
</p>
<p>
	1<br/>
BOB
</p>
<p>
	输出文件名：bob.out
</p>
<p>
	BBO
</p>
