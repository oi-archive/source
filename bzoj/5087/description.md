
# Description

<div class="content"><div>你有三个系数为0,1的多项式f(x),g(x),h(x)</div>
<div>求f(g(x)) mod h(x)</div>
<div>为方便起见，将答案多项式所有系数对2取模输出即可</div>
<div>如果f(x)=Sigma(Ak * X<sup>k</sup>)</div>
<div>则f(g(x))=Sigma(Ak(g(x))<sup>K</sup></div>
<div></div>
<p></p>
<div></div>
<p></p></div>

# Input

<div class="content"><div>一共三行，每行一个多项式,分别为f,g,h</div>
<div>对于一个多项式描述为n P0,P1...Pn其中Pi为0或1</div>
<div>多项式P(x)=P<sub>0</sub>+P<sub>1</sub>*x+....+P<sub>n</sub>*x<sup>n</sup></div>
<div>记n表示多项式最高项的次数,n&lt;=4000</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>用同样的格式输出答案多项式</div>
<div>如果答案为0，输出0 0</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 0 1 0 1 0 1<br/>
2 1 1 1<br/>
4 0 1 1 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1 1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By clj">By clj</a></p></div>

