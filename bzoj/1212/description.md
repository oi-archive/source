
# Description

<div class="content"><p>标点符号的出现晚于文字的出现，所以以前的语言都是没有标点的。现在你要处理的就是一段没有标点的文章。 一段文章T是由若干小写字母构成。一个单词W也是由若干小写字母构成。一个字典D是若干个单词的集合。 我们称一段文章T在某个字典D下是可以被理解的，是指如果文章T可以被分成若干部分，且每一个部分都是字典D中的单词。 例如字典D中包括单词{‘is’, ‘name’, ‘what’, ‘your’}，则文章‘whatisyourname’是在字典D下可以被理解的 因为它可以分成4个单词：‘what’, ‘is’, ‘your’, ‘name’，且每个单词都属于字典D，而文章‘whatisyouname’ 在字典D下不能被理解，但可以在字典D’=D+{‘you’}下被理解。这段文章的一个前缀‘whatis’，也可以在字典D下被理解 而且是在字典D下能够被理解的最长的前缀。 给定一个字典D，你的程序需要判断若干段文章在字典D下是否能够被理解。 并给出其在字典D下能够被理解的最长前缀的位置。</p></div>

# Input

<div class="content"><p>输入文件第一行是两个正整数n和m，表示字典D中有n个单词，且有m段文章需要被处理。 之后的n行每行描述一个单词，再之后的m行每行描述一段文章。 其中1&lt;=n, m&lt;=20，每个单词长度不超过10，每段文章长度不超过1M。</p></div>

# Output

<div class="content"><p>对于输入的每一段文章，你需要输出这段文章在字典D可以被理解的最长前缀的位置。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
is<br/>
name<br/>
what<br/>
your<br/>
whatisyourname<br/>
whatisyouname<br/>
whaisyourname<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
6<br/>
0	整段文章’whatisyourname’都能被理解<br/>
前缀’whatis’能够被理解<br/>
没有任何前缀能够被理解<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

