
# Description

<div class="content"><div>Farmer John has purchased a subscription to Good Hooveskeeping magazine for his cows, so they have plenty </div>
<div>of material to read while waiting around in the barn during milking sessions. Unfortunately, the latest </div>
<div>issue contains a rather inappropriate article on how to cook the perfect steak, which FJ would rather his </div>
<div>cows not see (clearly, the magazine is in need of better editorial oversight).</div>
<div>FJ has taken all of the text from the magazine to create the string S of length at most 10^5 characters. </div>
<div>He has a list of censored words t_1 ... t_N that he wishes to delete from S. To do so Farmer John finds </div>
<div>the earliest occurrence of a censored word in S (having the earliest start index) and removes that instance </div>
<div>of the word from S. He then repeats the process again, deleting the earliest occurrence of a censored word </div>
<div>from S, repeating until there are no more occurrences of censored words in S. Note that the deletion of one </div>
<div>censored word might create a new occurrence of a censored word that didn&#39;t exist before.</div>
<div>Farmer John notes that the censored words have the property that no censored word appears as a substring of </div>
<div>another censored word. In particular this means the censored word with earliest index in S is uniquely </div>
<div>defined.Please help FJ determine the final contents of S after censoring is complete.</div>
<div>FJ把杂志上所有的文章摘抄了下来并把它变成了一个长度不超过10^5的字符串S。他有一个包含n个单词的列表，列表里的n个单词</div>
<div>记为t_1...t_N。他希望从S中删除这些单词。 </div>
<div>FJ每次在S中找到最早出现的列表中的单词(最早出现指该单词的开始位置最小)，然后从S中删除这个单词。他重复这个操作直到S中</div>
<div>没有列表里的单词为止。注意删除一个单词后可能会导致S中出现另一个列表中的单词 </div>
<div>FJ注意到列表中的单词不会出现一个单词是另一个单词子串的情况，这意味着每个列表中的单词在S中出现的开始位置是互不相同的 </div>
<div>请帮助FJ完成这些操作并输出最后的S</div>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Input

<div class="content"><div>The first line will contain S. The second line will contain N, the number of censored words. The next N lines contain the strings t_1 ... t_N. Each string will contain lower-case alphabet characters (in the range a..z), and the combined lengths of all these strings will be at most 10^5.</div>
<div>第一行包含一个字符串S </div>
<div>第二行包含一个整数N </div>
<div>接下来的N行，每行包含一个字符串，第i行的字符串是t_i</div>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">The string S after all deletions are complete. It is guaranteed that S will not become empty during the deletion process.</span></div>
<div>
<div>一行，输出操作后的S</div>
<div></div>
</div>
<div>
<pre style="font-size: 14px;"></pre>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">begintheescapexecutionatthebreakofdawn<br/>
2<br/>
escape<br/>
execution</span></div>

# Sample Output

<div class="content"><span class="sampledata">beginthatthebreakofdawn</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

