# 
全班人都知道你暗恋谁,这一听就非常的恐怖.不巧的是,我的朋友的朋友刚遇到了这个问题,他的暗恋对象被损友知道了,大概再过1天,可能1个小时之后所有人就都会知道.情况紧急,他有个任务要交给你,你要马上推断他的暗恋对象会不会也知道这个消息.

为了对你隐瞒暗恋对象,他将给出N(N < 10000)对朋友关系的描述和Q(Q⩽200000)个操作,每个操作形如o u v(1⩽u,v⩽10000,o=1 or 2),o=1(操作1)描述u和v是朋友关系.朋友之间会互相告诉这些八卦信息.也就是说,若A与B是朋友,B与C是朋友,那么C也会从B那知道A说了什么.o=2(操作2)询问u是否会从v那知道些什么.# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 7
2 1 2
1 1 2
2 1 2
1 3 4
2 1 4
1 2 3
2 1 4</td><td>N
Y
N
Y
</td></tr></table>
