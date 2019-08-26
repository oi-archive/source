
# Description

<div class="content"><div>这是一个美好的下午，小W和小C在竹林里切磋捆竹竿的技艺。</div>
<div>竹林里有无数根完全一样的短竹子，每一根竹子由n节组成。</div>
<div>这些竹子比较特别，每一节都被染上了颜色。可能的颜色一共26种，分别用小写英文字母a到z表示。也就是说，如果把竹子的底端到顶端的颜色按顺序写出来可以排成一个由小写英文字母组成的字符串。</div>
<div>小W和小C都是捆竹竿的高手，他们知道怎样才能把零散的短竹子捆成一整根长竹竿。初始时你拿着一根短竹子作为当前的竹竿。每次你可以选择一根短竹子，短竹子底端若干节（可以是0节）与竹竿的最上面若干节对应地一节一节捆起来，而短竹子前面剩下的节伸出去，这样就得到了一根更长的竹竿。注意，竹子的底端是靠近根部的那一端，不可以颠倒。</div>
<div>小W对竹竿的审美要求很高，他捆竹竿时有一个癖好：如果两根竹子的某两节被捆在了一起，那么它们的颜色必须相同。</div>
<div>我们假设一根短竹子从底端到顶端每节的颜色为aba。</div>
<div>那么两根竹子可以首尾捆在一起，可以得到一根颜色为abaaba的竹竿；也可以将第一根顶端的一节a与第二根底端的一节a捆在一起，得到一根颜色为ababa的竹竿；还可以直接将每一节都对应起来，捆成一根颜色为aba的竹竿。</div>
<div>假设我们在颜色为ababa的竹竿顶端再捆一根竹子，则可以捆成ababaaba，abababa和ababa三种不同的情况。</div>
<div>但是小C在这个问题上有不同的看法，他认为小W捆不出很多种长度不同的竹竿。小W非常不服，于是他找到了你——现在请你求出在竹竿长度不超过w的情况下，小W可以捆出多少种长度不同的竹竿。其中，竹竿的长度指从底端到顶端的竹子的节的个数。</div>
<div>注意：如果w&lt;n，则没有合法的长度，此时答案为0。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包含1个正整数T，为数据组数。</p>
<div>每组数据的第一行包含2个正整数n和w，表示短竹子的长度和竹竿的长度上限。</div>
<div>每组数据的第二行包含一个长度为n的字符串，该字符串仅由小写英文字母构成，表示短竹子从底端到顶端每节的颜色。</div></div>

# Output

<div class="content"><p>输出共T行，每行包含一个整数表示捆成竹竿的不同长度种数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
4 11<br/>
bbab</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p> N&lt;=5*10^5</p><br/>
<div>M&lt;=10^18</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

