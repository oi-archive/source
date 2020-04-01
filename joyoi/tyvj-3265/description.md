# 

 
 # 题目描述 
<p>
税收问题<br>提交文件：tax<br>问题描述：<br>　　依法纳税是每个公民的义务，明明的哥哥是某市的公务员，当然公务员的工资也是要纳税的，该市的纳税制度是这样的，如果工资额小于等于1000元，则按工资的5%纳税，如果工资额大于1000元小于等于1500元，则超出1000元部分按10%纳税（1000元以内还是按5%纳税，如工资额为1200元，则有1000元按5%纳税，200元按10%纳税），如果工资额大于1500元，则超出1500元的部分按15%纳税，1500以内的部分还是按上面规则纳税（如工资额为1800元，则有1000元按5%纳税，500元按10%纳税，300元按15%纳税）现在已知东东某个月的工资金额（单位：元，是一个正整数），请你算出东东的工资纳税的金额是多少？（单位：元，四舍五入到小数点后两位），如果是整数也要输出两位小数。如是：1250元，则输出为：1250.00。<br></p> 

 
 # 输入格式 
<p>
　　从文件tax.in中读入数据，只有一个数，就是东东的工资金额a(1 < a <= 32767的整数)。<br></p> 

 
 # 输出格式 
<p>
　　结果输出到文件tax.out中，只有一个数，就是根据纳税制度，算出东东工资该纳税的金额（元，四舍五入到小数点后二位）。<br></p> 

 
 # 提示 
<p>
<br><br><br>=======================================================================================================================<br>2011科普杯东莞市中小学程序设计邀请赛成绩表<br>=======================================================================================================================<br>学生姓名　　　　　　　　总分成绩　　　　　　　　第一题　　　　　第二题　　　　　第三题　　　　第四题　　　　　获奖等级<br>东城一中初二黄少豪　　　　　400	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	一等奖<br>东城一中初二刘伟杰　　　　　400	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	----------	一等奖<br>东莞中学初中部初二冯灏帆　　400	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	一等奖<br>东莞中学初中部初一杨宇通　　400	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	一等奖<br>可园中学初一（17）麦辉煜　　400	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	一等奖<br>东莞中学初中部初二袁嘉豪　　390	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	AWAAAAAAAA	一等奖<br>东莞中学初中部初二伍舜豪　　350	AAAAAAAAAA	AAAAAAAAAA	AAWAWWAWAW	AAAAAAAAAA	二等奖<br>石龙三中—九年级—周雪颖　　320	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WAWWWWWWWA	二等奖<br>东城一中初二黃少伟	　　　　　310	WWWWWWWWWW	AAAAAAAAAA	AAAAAAAAAA	??????????	二等奖<br>东城一中初二谢东　　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>东城一中初三周志超　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>东莞石龙三中初一级周柱森　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙第三中学初二胡杰仁　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>东莞中学初中部初三孔智谦　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙第三中学初一陈健朗　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙二中 初一 吴宗培　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙二中初二李铭男　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙二中初二徐詠琪　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙二中初一王滢滢　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>石龙三中初二级李航	　　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>阳光一小六(3)班刘佳荣　　　　310	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	二等奖<br>东城一中初二黄仁昌	　　　　　300	AAAAAWAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	三等奖<br>东城一中初二张凯敏	　　　　　300	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWW	三等奖<br>东莞中学初中部初一潘熙　　　300	AAAAAWAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	三等奖<br>石龙二中 初三 叶璨铭　　　　300	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	??????????	三等奖<br>石龙二中初二赖玮晖	　　　　300	WAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWA	三等奖<br>石龙二中初一冯子晋	　　　　　300	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	WWWWWWWWWW	三等奖<br>莞中初中部初三张嘉曦　　　　300	AAAAAAAAAA	AAAAAAAAAA	AAAAAAAAAA	??????????	三等奖<br>东城一中初二郑达豪	　　　　　270	AAAAAAAAAA	WAWAAAWAAW	AAAAAAAAAA	WWWWWWWWWA	三等奖<br>可园中学初二周君泰　	　270	AAAAAAAAAA	AAAAAAAAAA	AAWAWWAWAW	WAWWWWWWWA	三等奖<br>阳光中心小学五年级贺刘丁　　　270	AAAAAAAAAA	AAAAAAAAAA	AAAAAWAAWW	??????????	三等奖<br>东城一中初一曾非凡	　　　　　230	AAAAAAAAAA	AAAAAAAAAA	AWAWWBWWBB	WWWWWWWWWA	优胜奖<br>东城一中初三钟梓濠	　　　　　210	WWWWWWWWWW	AAAAAAAAAA	AAAAAAAAAA	WWAWWWWWWW	优胜奖<br>东莞中学初中部初三钟嘉声　　　210	AAAAAAAAAA	AAAAAAAAAA	YYYYYYYYYY	WWWWWWWWWA	优胜奖<br>东莞中学初中部初一林雪晴　　　210	AAAAAAAAAA	AAAAAAAAAA	AWWWWWWWWW	??????????	优胜奖<br>东城一中初一吴浩贤	　　　　　200	AAAAAAAAAA	AAAAAAAAAA	WWWWWTWWWT	??????????	优胜奖<br>东莞市石龙三中初一杨卓滨　　　200	AAAAAAAAAA	AAAAAAAAAA	??????????	??????????	优胜奖<br>可园中学初二梁子杰　　　　　190	AAAAWAAAAW	AAAAAAAAAA	??????????	WWWWWWWWWA	优胜奖<br>阳光一小六（6）班邓宇志　　170	AAAAAAAAAA	AAAAAAWWWW	??????????	WWWWWWWWWW	优胜奖<br>阳光一小六（6）班唐晓剑　　　160	AAAAAAAAAA	AAAAAAWWWW	??????????	??????????	优胜奖<br>东莞市石龙第三中学初二李靖怡　　　150	AAAAWAWWWW	----------	AAAAAAAAAA	??????????	优胜奖<br>阳光一小 四(3)班 黄唯涛　　　　110	　AAAAAWAAAA	??????????	AWAWWWWWWW	??????????	优胜奖<br>东城一中初三刘育松	　　　　　　100	　AAAAAAAAAA	??????????	??????????	YYYYYYYYYY	优胜奖<br>南城阳光中心小学五4班贺震阳	　　　100	　AAAAAAAAAA	??????????	??????????	??????????	优胜奖<br>可园中学初二周俊伟　　　　　　　70	WAAAWAWWWW	WWAAWAWWWW	??????????	WWWWWWWWWW	优胜奖<br>=======================================================================================================================</p> 
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
<tr><td>1000
</td><td>50.00
</td></tr></table>
