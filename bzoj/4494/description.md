
# Description

<div class="content"><div>一群生物学家正在找一个病毒性疾病的解药。他们已经尝试了许多来源不同的抗体， 它</div>
<div>们都有可能消灭病毒抗原。他们选出了 n 种在试验中看起来最有效的抗体。</div>
<div>每种抗体通过它们的重链（一种氨基酸）来识别。</div>
<div>符合以下任意一个条件的一群抗体，形成一个“相似群体”：</div>
<div>1. 它们的重链中的 K-前缀全部都是相同的</div>
<div>2. 它们的重链中的 K-后缀全部都是相同的</div>
<div>为了简化将来的研究，生物学家想把所有抗体分成几个“相似群体”。因此你需要将给</div>
<div>定的抗体分成数量最少的几个“相似群体”。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数 n 和 k ，分别表示重链的数量和需要相同的重链的长度。</div>
<div>以下 n 行每行包括一个重链。每个重链是用一串大写英文字母表示，并且长度在 k 与550 之间。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行包括一个整数，最少的相似群数目。</div>
<div>以下每行描述一个相似群：</div>
<div>描述以 mi 开都，表示在该群内抗体的数量。后面跟着 mi 个整数，表示这些抗体的编号。</div>
<div>编号按输入的顺序从小到大。每个抗体只能出现在一个群内。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
AA<br/>
AB<br/>
BB<br/>
BA</span></div>

# Sample Output

<div class="content"><span class="sampledata">22</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=5000,K&lt;=300</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

