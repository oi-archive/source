# 
1.  成绩
【问题描述】
牛牛最近学习了 C++入门课程，这门课程的总成绩计算方法是：
总成绩 = 作业成绩 × 20% + 小测成绩 × 30% + 期末考试成绩 × 50%
牛牛想知道，这门课程自己最终能得到多少分。
【输入格式】
输入文件名为 score.in。
输入文件只有 1 行，包含三个非负整数A、B、C，分别表示牛牛的作业成绩、小测
成绩和期末考试成绩。相邻两个数之间用一个空格隔开，三项成绩满分都是 100 分。
【输出格式】
输出文件名为 score.out。
输出文件只有 1 行，包含一个整数，即牛牛这门课程的总成绩，满分也是 100 分。
【输入输出样例 1】
输入：100 100 80
输出：90
【输入输出样例 1 说明】
牛牛的作业成绩是 100 分，小测成绩是 100 分，期末考试成绩是 80 分，总成
绩是 100 × 20% + 100 × 30% + 80 × 50% = 20 + 30 + 40 = 90。
【输入输出样例 2】
输入：60 90 80
输出：79
【输入输出样例 2 说明】
牛牛的作业成绩是 60 分，小测成绩是 90 分，期末考试成绩是 80 分，总成绩是
60 × 20% + 90 × 30% + 80 × 50% = 12 + 27 + 40 = 79。
【数据说明】
30% 的数据，A = B = 0。
对于另外 30% 的数据，A = B = 100。
对于 100% 的数据， 0 ≤ A、B、C ≤ 100 且 A、B、C 都是 10 的整数倍。# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>0 0 80</td><td>40</td></tr></table>