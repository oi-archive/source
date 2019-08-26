
# Description

<div class="content"><div>Farmer John and Bessie the cow love to exchange math puzzles in their free time. The last puzzle FJ gave Bessie</div>
<div>was quite difficult and she failed to solve it. Now she wants to get even with FJ by giving him a challenging puzzle.</div>
<div>Bessie gives FJ the expression (B+E+S+S+I+E)(G+O+E+S)(M+O+O), containing the seven variables B,E,S,I,G,O,M</div>
<div>(the &#34;O&#34; is a variable, not a zero). For each variable, she gives FJ a list of up to 500 integer values the variable can</div>
<div>possibly take. She asks FJ to count the number of different ways he can assign values to the variables so the entire</div>
<div>expression evaluates to a multiple of 7.</div>
<div></div>
<div>Note that the answer to this problem can be too large to fit into a 32-bit integer, so you probably want to use 64-bit</div>
<div>integers (e.g., &#34;long long&#34;s in C or C++).</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">七个变量B,E,S,I,G,O,M;使得(B+E+S+S+I+E)(G+O+E+S)(M+O+O)被7整除的方案有多少种.</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of the input contains an integer N. The next N lines each contain a variable and a possible value for</div>
<div>that variable. Each variable will appear in this list at least once and at most 500 times. No possible value will be</div>
<div>listed more than once for the same variable. All possible values will be in the range −10^5 to 10^5.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">第一行一个整数N,接下来N行</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">每行一个字母C,一个数字k;表示变量C可以为k.</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">保证每个变量有不超过500种可能的值</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;"></div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>Print a single integer, giving the number of ways FJ can assign values to variables so the expression</div>
<div>above evaluates to a multiple of 7.</div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">一个整数方案数</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">注意使用64位变量来存储</div>
</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
B 2<br/>
E 5<br/>
S 7<br/>
I 10<br/>
O 16<br/>
M 19<br/>
B 3<br/>
G 1<br/>
I 9<br/>
M 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
The two possible assignments are<br/>
<br/>
(B,E,S,I,G,O,M) = (2, 5, 7, 9,  1, 16, 19) -&gt; 51,765<br/>
                = (2, 5, 7, 9,  1, 16, 2 ) -&gt; 34,510</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver 鸣谢yeguanghao提供译文">Silver 鸣谢yeguanghao提供译文</a></p></div>

