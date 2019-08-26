
# Description

<div class="content"><div class="problem-text" align="left"><span style="font-size: medium; "><span class="mono prewrap" id="probtext-text">Bessie is playing a video game! In the game, the three letters &#39;A&#39;, &#39;B&#39;, and &#39;C&#39; are the only valid buttons. Bessie may press the buttons in any order she likes; however, there are only N distinct combos possible (1 &lt;= N &lt;= 20). Combo i is represented as a string S_i which has a length between 1 and 15 and contains only the letters &#39;A&#39;, &#39;B&#39;, and &#39;C&#39;. Whenever Bessie presses a combination of letters that matches with a combo, she gets one point for the combo. Combos may overlap with each other or even finish at the same time! For example if N = 3 and the three possible combos are &#34;ABA&#34;, &#34;CB&#34;, and &#34;ABACB&#34;, and Bessie presses &#34;ABACB&#34;, she will end with 3 points. Bessie may score points for a single combo more than once. Bessie of course wants to earn points as quickly as possible. If she presses exactly K buttons (1 &lt;= K &lt;= 1,000), what is the maximum number of points she can earn? </span></span></div>
<div class="problem-text" align="left"><span style="font-size: medium; "><br type="_moz"/>
</span></div>
<div class="problem-text" align="left"><span style="font-size: medium; "><span class="Apple-style-span" style="font-family: simsun; color: rgb(70, 70, 70); line-height: 21px; ">给出n个ABC串combo[1..n]和k，现要求生成一个长k的字符串S，问S与word[1..n]的最大匹配数</span></span></div></div>

# Input

<div class="content"><p><font size="4"> Line 1: Two space-separated integers: N and K. * Lines 2..N+1: Line i+1 contains only the string S_i, representing combo i.</font></p>
<p><font size="4"> </font></p></div>

# Output

<div class="content"><p><span style="font-size: medium">Line 1: A single integer, the maximum number of points Bessie can obtain.<br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata"> 3 7 ABA CB ABACB </span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
  4 </span></div>

# Hint

<div class="content"><p></p><p> The optimal sequence of buttons in this case is ABACBCB, which gives 4 points--1 from ABA, 1 from ABACB, and 2 from CB.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

