# 题目描述


<div>
	<div>
		<div>
			<div>
				<div>
					<div>
						<div>
							<h3>
								Problem
							</h3>
							<p>
								Do you ever become frustrated with television because you keep seeing the same things, recycled over and over again? Well I personally don&#39;t care about television, but I do sometimes feel that way about numbers.
							</p>
							<p>
								Let&#39;s say a pair of distinct positive integers (n, m) is recycled if you can obtain m by moving some digits from the back of n to the front without changing their order. For example, (12345, 34512) is a recycled pair since you can obtain 34512 by moving 345 from the end of 12345 to the front. Note that n and m must have the same number of digits in order to be a recycled pair. Neither n nor m can have leading zeros.
							</p>
							<p>
								Given integers A and B with the same number of digits and no leading zeros, how many distinct recycled pairs (n, m) are there with A ≤ n &lt; m ≤ B?
							</p>
							<h3>
								Input
							</h3>
							<p>
								The first line of the input gives the number of test cases, T. T test cases follow. Each test case consists of a single line containing the integers A and B.
							</p>
							<h3>
								Output
							</h3>
							<p>
								For each test case, output one line containing &#34;Case #x: y&#34;, where x is the case number (starting from 1), and y is the number of recycled pairs (n, m) with A ≤ n &lt; m ≤ B.
							</p>
							<h3>
								Limits
							</h3>
							<p>
								1 ≤ T ≤ 50.<br/>
A and B have the same number of digits.
							</p>
							<h4>
								Small dataset
							</h4>
							<p>
								1 ≤ A ≤ B ≤ 1000.
							</p>
							<h4>
								Large dataset
							</h4>
							<p>
								1 ≤ A ≤ B ≤ 2000000.
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
1 9<br/>
10 40<br/>
100 500<br/>
1111 2222<br/>
											</td>
											<td>
												Case #1: 0<br/>
Case #2: 3<br/>
Case #3: 156<br/>
Case #4: 287<br/>
<br/>
											</td>
										</tr>
									</tbody>
								</table>
							</div>
							<h4>
								Are we sure about the output to Case #4?
							</h4>
							<p>
								Yes, we&#39;re sure about the output to Case #4.
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<br/>
