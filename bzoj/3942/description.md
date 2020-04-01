
# Description

<div class="content"><p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">Farmer John has purchased a subscription to Good Hooveskeeping magazine for his cows, so they have plenty of material to read while waiting around in the barn during milking sessions. Unfortunately, the latest issue contains a rather inappropriate article on how to cook the perfect steak, which FJ would rather his cows not see (clearly, the magazine is in need of better editorial oversight).</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">FJ has taken all of the text from the magazine to create the string S of length at most 10^6 characters. From this, he would like to remove occurrences of a substring T to censor the inappropriate content. To do this, Farmer John finds the _first_ occurrence of T in S and deletes it. He then repeats the process again, deleting the first occurrence of T again, continuing until there are no more occurrences of T in S. Note that the deletion of one occurrence might create a new occurrence of T that didn&#39;t exist before.</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">Please help FJ determine the final contents of S after censoring is complete</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">有一个S串和一个T串，长度均小于1,000,000，设当前串为U串，然后从前往后枚举S串一个字符一个字符往U串里添加，若U串后缀为T，则去掉这个后缀继续流程。</p>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">The first line will contain S. The second line will contain T. The length of T will be at most that of S, and all characters of S and T will be lower-case alphabet characters (in the range a..z).</span></div>
<div>
<pre style="font-size: 14px;"></pre>
</div>
<p></p></div>

# Output

<div class="content"><h4 style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">The string S after all deletions are complete. It is guaranteed that S will not become empty during the deletion process.</h4>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">whatthemomooofun<br/>
moo</span></div>

# Sample Output

<div class="content"><span class="sampledata">whatthefun</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

