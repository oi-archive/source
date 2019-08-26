
# Description

<div class="content"><div>农夫约翰的N（2 &lt;= N&lt;=10,000）头奶牛，编号为1.. N，一共会流利地使用M（1&lt;= M &lt;=30,000）种语言，编号从1</div>
<div> .. M.，第i头，会说K_i（1 &lt;= K_i&lt;= M）种语言，即L_i1, L_i2,..., L_{iK_i} (1 &lt;= L_ij &lt;= M)。 FJ的奶牛</div>
<div>不太聪明，所以K_i的总和至多为100,000。两头牛，不能直接交流，除非它们都会讲某一门语言。然而，没有共同</div>
<div>语言的奶牛们，可以让其它的牛给他们当翻译。换言之，牛A和B可以谈话，当且仅当存在一个序列奶牛T_1，T_2，</div>
<div>...，T_k，A和T_1都会说某一种语言，T_1和T_2也都会说某一种语言……，并且T_k和B会说某一种语言。农夫约翰</div>
<div>希望他的奶牛更加团结，所以他希望任意两头牛之间可以交流。他可以买书教他的奶牛任何语言。作为一个相当节</div>
<div>俭的农民，FJ想要购买最少的书籍，让所有他的奶牛互相可以说话。帮助他确定：*他必须购买的书籍的最低数量</div></div>

# Input

<div class="content"><div>*第1行：两个用空格隔开的整数：N和M</div>
<div>*第2..N+1行：第i+1行描述的牛i的语言，K_i+1个空格隔开的整数：</div>
<div>K_iL_i1 L_i2，...，L_I{K_i}。</div>
<p></p></div>

# Output

<div class="content"><p>*第1行：一个整数，FJ最少需要购买的书籍数量</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
2 3 2<br/>
1 2<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
//给三号牛买第二本书即可</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

