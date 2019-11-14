
# Description

<div class="content"><div>ZCC is playing a RPG game named “kenji’s life VI”.</div>
<div>In this game, as an advanturer, ZCC has N kinds of energy, labeled 1 to N. Before set off for an adventure, ZCC can charge some of his energy, which allow he to set the amount of every kind of energy (a_i) a non-negative integer arbitrarily. Different kind of energy is set independently.</div>
<div>When different energy mix, they become unstable. If there exist two integers u and v (u≤v), where a_u, a_u+1, ..., a_v are all positive number, and sum of those v-u+1 number exceed K, a horrific explosion occurs, and of course, Game Over.</div>
<div>During the adventure, the story may develop differently depending on the amount of a certain kind of energy. Sometimes there will be some CGs, but some of CGs may only appear in some certain sub-story.</div>
<div>ZCC has played this game many times, but failed to collect some of the CGs. Now he wonders, How many kinds of CGs is collectable?</div>
<div>The Scenario is given in the form of C++ like code.</div>
<div><img src="/source/bzoj/3842/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9hYSgxKS5qcGc=.jpg" width="576" height="204" alt=""/></div>
<div></div>
<div></div>
<div>As an explanation:</div>
<div>The Scenario is presented as a non-type function game(n, k).</div>
<div>game(n, k) has 2 arguments, n and k, which are actually 2 constants. n is the number of energy type available, k is the limitation of sum of consecutive positive number. There may be 3 types of statement:</div>
<div>1.cg(p1), means a CG numbered p1 appears here.</div>
<div>2.if (a[p1] &gt;= p2) &lt;statement&gt; [else &lt;statement&gt;], is just like the branch statement in other programming languages. else is matched with the nearest if, just like the way C++ works.</div>
<div>3.{ &lt;statements&gt;* }, a block contains zero, one or several statements.</div>
<div>Note that though the scenario is guaranteed to satisfy the grammar above, the code-style(space, bracket, line break) may not strictly obeys the explanation above.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>A scenario with total length do not exceed 3MB.</div>
<div>It’s guaranteed:</div>
<div>n≤10^5; </div>
<div>in cg(p1), p1 is a non-negative number between 0 and 2^20-1;</div>
<div>in if (a[p1] &gt;= p2), 1≤p1≤n，0≤p2≤10^9.</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>An integer: the number of CGs collectable.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">game(3, 1){<br/>
  cg(0);<br/>
  if (a[1] &gt;= 1)<br/>
    cg(1);<br/>
  else if (a[1] &gt;= 2) cg(2);<br/>
  if (a[2] &gt;= 1)<br/>
    if (a[3] &gt;= 1) cg(3); <br/>
    else cg(4);<br/>
  {cg(0);}<br/>
}</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
//CGs collectable are CG#0, CG#1 and CG#4.<br/>
Though CG#0 appears 2 times, the answer is 3, instead of 4.</span></div>

# Hint

<div class="content"><p></p><div>数据是在win下制作的，要要过滤\r才能过。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

