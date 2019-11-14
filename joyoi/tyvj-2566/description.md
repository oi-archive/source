# 

 
 # 题目描述 
<p>
Farmer John's N (1 <= N <= 500) cows are trying to select the<br>milking team for the world-famous Multistate Milking Match-up (MMM)<br>competition. As you probably know, any team that produces at least<br>X (1 <= X <= 1,000,000) gallons of milk is a winner.<br><br>Each cow has the potential of contributing between -10,000 and<br>10,000 gallons of milk. (Sadly, some cows have a tendency to knock<br>over jugs containing milk produced by other cows.)<br><br>The MMM prides itself on promoting family values. FJ's cows have<br>no doubt that they can produce X gallons of milk and win the contest,<br>but to support the contest's spirit, they want to send a team with<br>as many parent-child relationships as possible (while still producing<br>at least X gallons of milk). Not surprisingly, all the cows on FJ's<br>farm are female.<br><br>Given the family tree of FJ's cows and the amount of milk that each<br>would contribute, compute the maximum number of parent-child<br>relationships that can exist in a winning team. Note that a set of<br>cows with a grandmother-mother-daughter combination has two<br>parent-child relationships (grandmother-mother, mother-daughter).<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers, N and X.<br><br>* Lines 2..N+1: Line i+1 contains two space-separated integers<br>        describing cow i. The first integer is the number of gallons<br>        of milk cow i would contribute. The second integer (range<br>        1..N) is the index of the cow's mother. If the cow's mother is<br>        unknown, the second number is 0. The family information has no<br>        cycles: no cow is her own mother, grandmother, etc.<br><br><br>N头牛,要选出一些来使其产奶量大于等于X.<br>问最多可选出几对父子关系出来.<br>如果选出来的集合中有爷爷点,父亲点,儿子点，则交有两对父子关系.</p> 

 
 # 输出格式 
<p>
* Line 1: The maximum number of parent-child relationships possible on<br>        a winning team. Print -1 if no team can win.<br></p> 
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
<tr><td>5 8
-1 0   //第一个数字代表这头奶的产量,第二个数字代表其父亲点是哪一个.
3 1
5 1
-3 3
2 0

INPUT DETAILS:

There are 5 cows. Cow 1 can produce -1 gallons and has two daughters, cow
2 and 3, who can produce 3 and 5 gallons, respectively. Cow 3 has a
daughter (cow 4) who can produce -3 gallons. Then there's cow 5, who can
produce 2 gallons.

</td><td>2

OUTPUT DETAILS:

The best team consists of cows 1, 2, 3, and 5. Together they produce
(-1)+3+5+2 = 9 >= 8 gallons and have 2 parent-child relationships
(1--2 and 1--3). Note that a team with cows 2, 3, and 5 would be
able to produce more milk (10 gallons), but would have fewer
parent-child relationships (0).</td></tr></table>
