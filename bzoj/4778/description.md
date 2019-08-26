
# Description

<div class="content"><div>Bessie has invented a new programming language, but since there is no compiler yet, she needs your h</div>
<div>elp to actually run her programs.COWBASIC is a simple, elegant language. It has two key features: ad</div>
<div>dition and MOO loops. Bessie has devised a clever solution to overflow: all addition is done modulo </div>
<div>109+7. But Bessie&#39;s real achievement is the MOO loop, which runs a block of code a fixed number of t</div>
<div>imes. MOO loops and addition can, of course, be nested.Given a COWBASIC program, please help Bessie </div>
<div>determine what number it returns.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>You are given a COWBASIC program at most 100 lines long, with each line being at most 350 characters</div>
<div> long. A COWBASIC program is a list of statements.</div>
<div></div>
<div>There are three types of statements:</div>
<div></div>
<div>&lt;variable&gt; = &lt;expression&gt;</div>
<div></div>
<div>&lt;literal&gt; MOO {</div>
<div>  &lt;list of statements&gt;</div>
<div>}</div>
<div></div>
<div>RETURN &lt;variable&gt;</div>
<div></div>
<div>There are three types of expressions:</div>
<div></div>
<div>&lt;literal&gt;</div>
<div></div>
<div>&lt;variable&gt;</div>
<div></div>
<div>( &lt;expression&gt; ) + ( &lt;expression&gt; )</div>
<div></div>
<div>A literal is a positive integer at most 100,000.</div>
<div></div>
<div>A variable is a string of at most 10 lowercase English letters.</div>
<div></div>
<div>It is guaranteed that no variable will be used or RETURNed before it is defined. It is guaranteed th</div>
<div>at RETURN will happen exactly once, on the last line of the program.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>Output a single positive integer, giving the value of the RETURNed variable.</div>
<div></div>
<div>Scoring</div>
<div></div>
<div>In 20 percent of all test cases - MOO loops are not nested.</div>
<div>In another 20 percent of all test cases - The program only has 1 variable. MOO loops can be nested.</div>
<div>In the remaining test cases, there are no further restrictions. </div>
<div></div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">x = 1<br/>
10 MOO {<br/>
  x = ( x ) + ( x )<br/>
}<br/>
RETURN x<br/>
<br/>
SAMPLE OUTPUT:<br/>
<br/>
1024<br/>
<br/>
This COWBASIC program computes 210.<br/>
SAMPLE INPUT:<br/>
<br/>
n = 1<br/>
nsq = 1<br/>
100000 MOO {<br/>
  100000 MOO {<br/>
    nsq = ( nsq ) + ( ( n ) + ( ( n ) + ( 1 ) ) )<br/>
    n = ( n ) + ( 1 )<br/>
  }<br/>
}<br/>
RETURN nsq<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4761<br/>
This COWBASIC program computes (10^5+10^5+1)^2 (modulo 10^9+7). </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

