
# Description

<div class="content"><p><img border="0" alt="" src="/source/bzoj/1501/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1MDFfMS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><div>文件中包含初始的盘件描述，一共有10行，第i行有i个字符。</div>
<div>如果第i行的第j个字符是字母”A”至”L”中的一个，则表示第i行第j列的格子上已经放了零件，零件的编号为对应的字母。</div>
<div>如果第i行的第j个字符是”.”，则表示第i行第j列的格子上没有放零件。</div>
<div>输入保证预放的零件已摆放在盘件中。</div></div>

# Output

<div class="content"><div>如果能找到解，向输出文件打印10行，为放完全部12个零件后的布局。</div>
<div>其中，第i行应包含i个字符，第i行的第j个字符表示第i行第j列的格子上放的是哪个零件。</div>
<div>如果无解，输出单独的一个字符串‘No solution’(不要引号，请注意大小写)。</div>
<div>所有的数据保证最多只有一组解。</div></div>

# Sample Input

<div class="content"><span class="sampledata">.<br/>
..<br/>
...<br/>
....<br/>
.....<br/>
.....C<br/>
...CCC.<br/>
EEEHH...<br/>
E.HHH....<br/>
E.........</span></div>

# Sample Output

<div class="content"><span class="sampledata">B<br/>
BK<br/>
BKK<br/>
BJKK<br/>
JJJDD<br/>
GJGDDC<br/>
GGGCCCI<br/>
EEEHHIIA<br/>
ELHHHIAAF<br/>
ELLLLIFFFF</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

