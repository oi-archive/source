# 

 
 # 题目描述 
<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">在这一学期一共有n次文科考试，考试科目有4种，分别为政治、历史、地理和综合。</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">每次考哪一科是不定的，因此在考试前Matrix67不知道应该去复习哪一科的功课。他希望能预测出下一次可能考的科目。于是，他收集到了以往的文科考试的资料。从以往的考试中，他发现了这样几个规律：</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">1.如果这次考的是政治，那么下一次一定会考历史；</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">2.如果这次考的是综合，那么下一次一定会考地理；</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">3.如果这次考的是历史，那么下一次要么考政治，要么考地理；</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">4.如果这次考的是地理，那么下一次要么考历史，要么考综合。</p>

<p style="margin: 7px 0px; padding: 0px; border: 0px; outline: 0px; font-size: 14px; vertical-align: baseline; text-indent: 2em; color: rgb(0, 0, 0); font-family: sans-serif; line-height: 23px; background: transparent;">Matrix67已经知道，本学期的第一次考试科目为政治。他打算拟定一个可以应对所有可能情况的应考复习计划。因此，他想知道，整个学期有多少种可能的考试科目安排满足以上规律。</p> 

 
 # 输入格式 
<p><span style="color: rgb(0, 0, 0); font-family: sans-serif; font-size: 14px; line-height: 23px; text-indent: 28px;">一个正整数n，代表本学期总的考试次数。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: sans-serif; font-size: 14px; line-height: 23px; text-indent: 28px;">一个正整数，表示符合规律的科目安排方案的总数。&nbsp;考虑到这个结果可能会很大，因此你只需要输出它mod&nbsp;7654321的值即可。</span></p> 

 
 # 提示 
<p><span style="line-height: 1.6em;">n&nbsp;&lt;=&nbsp;10000</span></p> 
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
<tr><td>1
</td><td>1
</td></tr></table>
