<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sheldon and Leonard are physicists who are ﬁxated on the BIG BANG theory. In order to exchange secret insights they have devised a code that encodes UPPERCASE words by shifting their letters forward.</p>
<p>谢耳朵和莱纳德是研究BB理论的物理学家。要用暗号（大写字母）联系。</p>
<p><br>Shifting a letter by S positions means to go forward S letters in the alphabet. For example, shifting B by S = 3 positions gives E. However, sometimes this makes us go past Z, the last letter of the alphabet. Whenever this happens we wrap around, treating A as the letter that follows Z. For example, shifting Z by S = 2 positions gives B.</p>
<p>（读懂这段话是解题的关键，翻译了就没意义了）</p>
<p><br>Sheldon and Leonard’s code depends on a parameter K and also varies depending on the position of each letter in the word. For the letter at position P, they use the shift value of S = 3P + K.</p>
<p>他们有一个密钥K。第P个字母有S = 3P + K。</p>
<p><br>For example, here is how ZOOM is encoded when K = 3. The ﬁrst letter Z has a shift value of S = 3 × 1 + 3 = 6; it wraps around and becomes the letter F. The second letter, O, has S = 3 × 2 + 3 = 9 and becomes X. The last two letters become A and B. So Sheldon sends Leonard the secret message: FXAB<br>Write a program for Leonard that will decode messages sent by Sheldon.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The input will be two lines. The ﬁrst line will contain the positive integer K (K &lt; 10), which is used to compute the shift value. The second line of input will be the word, which will be a sequence of uppercase characters of length at most 20.</p>
<p>输入有两行。第一行一个正整数K（〈10）。第二行是最多20个大写字母组成的信。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The output will be the decoded word of uppercase letters.</p>
<p>输入就是解密后的信。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>3</p>
<p>FXAB</p>
<p>样例2:</p>
<p>5</p>
<p>JTUSUKG</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>ZOOM</p>
<p>样例2：</p>
<p>BIGBANG</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>