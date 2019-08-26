
# Description

<div class="content"><p><span style="font-size: medium">　农夫约翰(Farmer John)的奶牛们平时喜好一起学习英文单词。奶牛Bessie是其中最聪明的牛，她发明了一个游戏，叫做《单词争霸》。<br/>
　　这个游戏是由两个人来玩，两人轮流进行。轮到每个人时，他要说出一个正确的单词（即字典中的单词），要求这个单词在之前没有被他或他的对手说过，并且这个单词不是之前他或他的对手说过的某个单词的前缀。如果轮到一个人，他无法说出这样的单词，那么他被判败。<br/>
　　显然，拥有词汇量较多的奶牛玩起这个游戏来更有优势，因为他有更多的单词可以说。这样，奶牛们天天玩这个游戏，他们的词汇量越来越大……<br/>
　　直到有一天，Bessie发现他们已经把世界上所有的英文单词学会了，因此她再也无法依赖自己较大的词汇量取胜了。她是记忆单词的天才，但并不是游戏好手，所以她来请教聪明的你。<br/>
　　她告诉你，这个世界上一共有N个英文单词，每个单词的长度不超过maxLen。她将这些单词按字典序排列，并输入。她想知道如果她是先手，那么她是否能取得胜利。<br/>
　　你需要做的是，判断在给定字典的情况下，先手是否有必胜策略。如果没有，那么告诉Bessie:“Can’t win at all!!”，否则，你需要确定先手在第一回合可以说出哪些单词，为了让Bessie多一些思考的乐趣，你决定不把这些单词一一列举。你把这些单词按某个排列连接起来，组成一个大的字符串，当然，不同的排列可能得到不同的串，你要告诉Bessie那个字典序最先的串，记作answerString。<br/>
　　为了使输出更加美观，如果那个串的长度大于50,你要分行输出，除了最后一行以外，其他行每行50个字符，最后一行不多于50个字符。</span></p>
<div class="pdcont"></div></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输入的第一行包含两个整数,N和maxLen,用一个空格隔开。<br/>
　　接下来的N行，每行为一个长度不大于maxLen的字符串。</span></div>
<div class="pdcont"></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　按题目描述中的要求输出：<br/>
　　可能为一行,“Can’t win at all!!”(不包含引号)<br/>
　　或者多行，除了最后一行之外每行50个字符，最后一行不超过50个字符，将所有行的字符连接起来是answerString。</span></div>
<div id="pcont2" style="margin-top: 20px; display: none">
<h3></h3>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 9<br/>
word<br/>
wordcraft<br/>
样例输出<br/>
wordcraft<br/>
样例1解释<br/>
　　先手说出单词“wordcraft”之后,后手没有单词可说，因为单词“word”是单词“wordcraft”的子串。<br/>
样例输入<br/>
5 9<br/>
ac<br/>
car<br/>
care<br/>
careful<br/>
carefully<br/>
样例输出<br/>
careful<br/>
样例2解释<br/>
　　先手说“careful”之后，后手只能说“ac”或者“carefully”。如果他说了前者，那么先手说后者；反之，如果他说了后者，那先手说前者。之后，后手都将无单词可说。<br/>
样例输入<br/>
2 100<br/>
noonecansolvethisproblem<br/>
thisproblemisverydifficult<br/>
样例输出<br/>
Can’t win at all!!<br/>
样例输入<br/>
9 8<br/>
theworda<br/>
thewordb<br/>
thewordc<br/>
thewordd<br/>
theworde<br/>
thewordf<br/>
thewordg<br/>
thewordh<br/>
thewordi<br/>
样例输出<br/>
thewordathewordbthewordctheworddthewordethewordfth<br/>
ewordgthewordhthewordi<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">cgy4evercowboy<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">100%的数据中N≤100000,maxLen≤100。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

