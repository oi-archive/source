# 题目描述


<h3>
	Problem
</h3>
<p>
	You&#39;re watching a show where Googlers (employees of Google) dance, and then each dancer is given a triplet of scores by three judges. Each triplet of scores consists of three integer scores from 0 to 10 inclusive. The judges have very similar standards, so it&#39;ssurprising if a triplet of scores contains two scores that are 2 apart. No triplet of scores contains scores that are more than 2 apart.
</p>
<p>
	For example: (8, 8, 8) and (7, 8, 7) are not surprising. (6, 7, 8) and (6, 8, 8) are surprising. (7, 6, 9) will never happen.
</p>
<p>
	The total points for a Googler is the sum of the three scores in that Googler&#39;s triplet of scores. The best result for a Googler is the maximum of the three scores in that Googler&#39;s triplet of scores. Given the total points for each Googler, as well as the number of surprising triplets of scores, what is the maximum number of Googlers that could have had a best result of at least p?
</p>
<p>
	For example, suppose there were 6 Googlers, and they had the following total points: 29, 20, 8, 18, 18, 21. You remember that there were 2 surprising triplets of scores, and you want to know how many Googlers could have gotten a best result of 8 or better.
</p>
<p>
	With those total points, and knowing that two of the triplets were surprising, the triplets of scores could have been:
</p>
10 9 10
6 6 8 (*)
2 3 3
6 6 6
6 6 6
6 7 8 (*)The cases marked with a (*) are the surprising cases. This gives us 3 Googlers who got at least one score of 8 or better. There&#39;s no series of triplets of scores that would give us a higher number than 3, so the answer is 3.
<p>
	<br/>
</p>
<h3>
	Input
</h3>
<p>
	The first line of the input gives the number of test cases, T. T test cases follow. Each test case consists of a single line containing integers separated by single spaces. The first integer will be N, the number of Googlers, and the second integer will be S, the number of surprising triplets of scores. The third integer will be p, as described above. Next will be Nintegers ti: the total points of the Googlers.
</p>
<h3>
	Output
</h3>
<p>
	For each test case, output one line containing &#34;Case #x: y&#34;, where x is the case number (starting from 1) and y is the maximum number of Googlers who could have had a best result of greater than or equal to p.
</p>
<h3>
	Limits
</h3>
<p>
	1 ≤ T ≤ 100.<br/>
0 ≤ S ≤ N.<br/>
0 ≤ p ≤ 10.<br/>
0 ≤ ti ≤ 30.<br/>
At least S of the ti values will be between 2 and 28, inclusive.
</p>
<h4>
	Small dataset
</h4>
<p>
	1 ≤ N ≤ 3.
</p>
<h4>
	Large dataset
</h4>
<p>
	1 ≤ N ≤ 100.
</p>
<h3>
	Sample
</h3>
<div>
	<table>
		<tbody>
			<tr>
				<td>
					<br/>
Input <br/>
				</td>
				<td>
					<br/>
Output <br/>
				</td>
			</tr>
			<tr>
				<td>
					4<br/>
3 1 5 15 13 11<br/>
3 0 8 23 22 21<br/>
2 1 1 8 0<br/>
6 2 8 29 20 8 18 18 21<br/>
				</td>
				<td>
					Case #1: 3<br/>
Case #2: 2<br/>
Case #3: 1<br/>
Case #4: 3<br/>
<br/>
				</td>
			</tr>
		</tbody>
	</table>
</div>
