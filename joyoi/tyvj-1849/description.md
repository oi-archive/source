# 

 
 # 题目描述 
新的技术正冲击着手机通讯市场，对于各大运营商来说，这既是机遇，更是挑战。THU&nbsp;集团旗下的CS&T&nbsp;通讯公司在新一代通讯技术血战的前夜，需要做太多的准备工作，仅就站址选择一项，就需要完成前期市场研究、站址勘测、最优化等项目。<BR>在前期市场调查和站址勘测之后，公司得到了一共N&nbsp;个可以作为通讯信号中转站的地址，而由于这些地址的地理位置差异，在不同的地方建造通讯中转站需要投入的成本也是不一样的，所幸在前期调查之后这些都是已知数据：建立第i个通讯中转站需要的成本为Pi（1≤i≤N）。<BR>另外公司调查得出了所有期望中的用户群，一共M&nbsp;个。关于第i&nbsp;个用户群的信息概括为Ai,&nbsp;Bi&nbsp;和Ci：这些用户会使用中转站Ai&nbsp;和中转站Bi&nbsp;进行通讯，公司可以获益Ci。（1≤i≤M,&nbsp;1≤Ai,&nbsp;Bi≤N）<BR>THU&nbsp;集团的CS&T&nbsp;公司可以有选择的建立一些中转站（投入成本），为一些用户提供服务并获得收益（获益之和）。那么如何选择最终建立的中转站才能让公司的净获利最大呢？（净获利&nbsp;=&nbsp;获益之和&nbsp;–&nbsp;投入成本之和）<BR> 

 
 # 输入格式 
输入文件中第一行有两个正整数N&nbsp;和M&nbsp;。<BR>第二行中有N&nbsp;个整数描述每一个通讯中转站的建立成本，依次为P1,&nbsp;P2,&nbsp;…,PN&nbsp;。<BR>以下M&nbsp;行，第(i&nbsp;+&nbsp;2)行的三个数Ai,&nbsp;Bi&nbsp;和Ci&nbsp;描述第i&nbsp;个用户群的信息。<BR>所有变量的含义可以参见题目描述。 

 
 # 输出格式 
你的程序只要向输出文件输出一个整数，表示公司可以得到的最大净获利。 

 
 # 提示 
选择建立1、2、3&nbsp;号中转站，则需要投入成本6，获利为10，因此得到最大<BR>收益4。<BR><BR>80%的数据中：N≤200，M≤1&nbsp;000。<BR>100%的数据中：N≤5&nbsp;000，M≤50&nbsp;000，0≤Ci≤100，0≤Pi≤100。 
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
<tr><td>5 5
1 2 3 4 5
1 2 3
2 3 4
1 3 3
1 4 2
4 5 3</td><td>4</td></tr></table>
