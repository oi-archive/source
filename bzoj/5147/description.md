
# Description

<div class="content"><div>
<div>赌城拉斯维加斯的米高梅大赌场最近推出了一种新式赌法。它的玩法是由庄家设局(所用赌具是一批五颜六色的筹</div>
<div>码)，赌徒只要交付一定数额的赌资即可入局。开赌前庄家将手中的筹码依次排开铺成一排构成一局，然后公布若</div>
<div>干个筹码序列供赌徒选择，赌徒可以从庄家设的局中取走与公布序列相一致的筹码，然后庄家将余下的筹码拼接好</div>
<div>，赌徒再继续取筹码，直到赌徒没有筹码可取为止，此时赌徒用他取得的筹码到总台换取相应面值的现金。例如：</div>
<div>庄家设的局为rrrgggbbb，r,g,b为筹码的颜色，庄家公布给赌徒选择的筹码序列为rg和gb，则赌徒可以取走第3和</div>
<div>第4个筹码rg，庄家将余下的筹码拼接后组成rrggbbb；赌徒继续取走第3和第4个筹码rg，庄家将余下的筹码拼接后</div>
<div>组成rgbbb；赌徒还是取走第3和第4个筹码rg，此时剩下的筹码为bbb，赌局结束；如果赌徒第二和第三次不取rg，</div>
<div>而改取gb的话，终局时剩下的筹码为rrb。类似地终局时剩下的筹码也可以是rrr或rbb。已知每种颜色筹码的面值</div>
<div>，给定庄家设的局和公布给赌徒选择的筹码序列，编程计算赌徒的最大收益。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行为一个正整数 K (1 ≤ K ≤26)，表示筹码的颜色种类，一种颜色对应一个小写英文字母。</div>
<div>接下来的K行每行有一个小写英文字母和一个正整数，二者之间用空格隔开，表示该小写英文字母代表的一个筹码的面额。 </div>
<div>第K+2行为一个长度不超过150的由小写英文字母组成的字符串，表示庄家设的局。</div>
<div>第K+3行为一个正整数N (1 ≤ N ≤ 150)，表示公布给赌徒选择的筹码序列总数。</div>
<div>接下来的N行每行一个由小写英文字母组成的字符串，表示一个筹码序列，所有N个字符串的长度总和不超过150。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出文件仅有一行包含一个整数表示赌徒在这一局中可能获得的最大收益。</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
a 1<br/>
b 4<br/>
d 2<br/>
x 3<br/>
f 1<br/>
e 3<br/>
fxeeabadd<br/>
2<br/>
aba<br/>
ed	<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">16</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

