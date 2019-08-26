
# Description

<div class="content"><div>有N位客户希望工厂为他们加工产品。每位客户都提供了需要加工的产品的类型，产品到达工厂的时间r、最迟完成</div>
<div>加工的时间d和每个产品加工所需的时间t。工厂里的生产车间一共有M台机器。每个产品在每台机器上都可以加工</div>
<div>，但是，一台机器在任何时候最多只能加工一件产品，而一件产品在任何时候也最多只能被一台机器加工。同时，</div>
<div>我们可以在某台机器正在加工时将工作打断，换另一个产品加工。问你能否找到一个方案，使得所有的产品都在规</div>
<div>定的时间内完成加工？</div></div>

# Input

<div class="content"><div>第一行包含一个整数Q，表示数据组数。接下来Q组数据，</div>
<div>每组数据的第一行包含两个整数N，M，表示需要加工的产品的数量、机器的数量。</div>
<div>接下来N行，每行三个整数ti、ri、di，表示加工产品所需的时间，产品到达工厂的时间以及最迟完成加工的时间</div>
<div>即产品可以在[ri，di)内被加工</div>
<div>1&lt;=N&lt;=300，1&lt;=M&lt;=300</div></div>

# Output

<div class="content"><div>包含Q行，每行对应一组数据的答案。</div>
<div>如果第i组数据能搞找到一个方案，则第i行包含一个Yes，否则包含一个No</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 1<br/>
3 6 10<br/>
4 8 12<br/>
3 1<br/>
2 2 9<br/>
2 3 5<br/>
3 5 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">No<br/>
Yes</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

