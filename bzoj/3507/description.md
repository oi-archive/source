
# Description

<div class="content"><p><span style="font-size: medium">几乎所有操作系统的命令行界面(CLI)中都支持文件名的通配符匹配以方便用户。最常见的通配符有两个，一个<br/>
是星号(“”’)，可以匹配0个及以上的任意字符：另一个是问号(“？”)，可以匹配恰好一个任意字符。<br/>
现在需要你编写一个程序，对于给定的文件名列表和一个包含通配符的字符串，判断哪些文件可以被匹配。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行是一个由小写字母和上述通配符组成的字符串。<br/>
第二行包含一个整数n，表示文件个数。<br/>
接下来n行，每行为一个仅包含小写字母字符串，表示文件名列表。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出n行，每行为“YES”或“NO”，表示对应文件能否被通配符匹配。</font><br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">*aca?ctc<br/>
6<br/>
acaacatctc<br/>
acatctc<br/>
aacacatctc<br/>
aggggcaacacctc<br/>
aggggcaacatctc<br/>
aggggcaacctct<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
YES<br/>
YES<br/>
YES<br/>
YES<br/>
NO<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于1 00%的数据<br/><br/>
  ·字符串长度不超过1 00000<br/><br/>
  ·  1 &lt;=n&lt;=100<br/><br/>
  ·通配符个数不超过10</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

