
# Description

<div class="content"><div>The cows have once again tried to form a startup company, failing to remember from past experience t</div>
<div>hat cows make terrible managers!The cows, conveniently numbered 1…N1…N (1≤N≤100,000), organize t</div>
<div>he company as a tree, with cow 1 as the president (the root of the tree). Each cow except the presid</div>
<div>ent has a single manager (its &#34;parent&#34; in the tree). Each cow ii has a distinct proficiency rating, </div>
<div>p(i), which describes how good she is at her job. If cow ii is an ancestor (e.g., a manager of a man</div>
<div>ager of a manager) of cow jj, then we say jj is a subordinate of ii.</div>
<div></div>
<div>Unfortunately, the cows find that it is often the case that a manager has less proficiency than seve</div>
<div>ral of her subordinates, in which case the manager should consider promoting some of her subordinate</div>
<div>s. Your task is to help the cows figure out when this is happening. For each cow ii in the company, </div>
<div>please count the number of subordinates jj where p(j)&gt;p(i).</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">n只奶牛构成了一个树形的公司，每个奶牛有一个能力值pi，1号奶牛为树根。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">问对于每个奶牛来说，它的子树中有几个能力值比它大的。</span></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N</div>
<div>The next N lines of input contain the proficiency ratings p(1)…p(N) </div>
<div>for the cows. Each is a distinct integer in the range 1…1,000,000,000</div>
<div>The next N-1 lines describe the manager (parent) for cows 2…N </div>
<div>Recall that cow 1 has no manager, being the president.</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">n，表示有几只奶牛 n&lt;=100000</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">接下来n行为1-n号奶牛的能力值pi</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">接下来n-1行为2-n号奶牛的经理（树中的父亲）</span><span style="font-family: arial, verdana, helvetica, sans-serif;"><br/>
</span></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please print N lines of output. The ith line of output should tell the number of </div>
<div>subordinates of cow ii with higher proficiency than cow i.</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">共n行，每行输出奶牛i的下属中有几个能力值比i大</span></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
804289384<br/>
846930887<br/>
681692778<br/>
714636916<br/>
957747794<br/>
1<br/>
1<br/>
2<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
1<br/>
0<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum鸣谢Acty提供译文">Platinum鸣谢Acty提供译文</a></p></div>

