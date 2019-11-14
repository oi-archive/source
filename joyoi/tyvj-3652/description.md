# 

 
 # 题目描述 
<p>
标点符号的出现晚于文字的出现，所以以前的语言都是没有标点的。现在你要处理的就是一段没有标点的文章。 <br>一段文章T是由若干小写字母构成。一个单词W也是由若干小写字母构成。一个字典D是若干个单词的集合。 <br>我们称一段文章T在某个字典D下是可以被理解的，是指如果文章T可以被分成若干部分，且每一个部分都是字典D中的单词。 <br>例如字典D中包括单词{‘is’, ‘name’, ‘what’, ‘your’}，则文章‘whatisyourname’是在字典D下可以被理解的 <br>因为它可以分成4个单词：‘what’, ‘is’, ‘your’, ‘name’，且每个单词都属于字典D，而文章‘whatisyouname’ <br>在字典D下不能被理解，但可以在字典D’=D+{‘you’}下被理解。这段文章的一个前缀‘whatis’，也可以在字典D下被理解 <br>而且是在字典D下能够被理解的最长的前缀。 <br>给定一个字典D，你的程序需要判断若干段文章在字典D下是否能够被理解。 <br>并给出其在字典D下能够被理解的最长前缀的位置。 <br></p> 

 
 # 输入格式 
<p>
输入文件第一行是两个正整数n和m，表示字典D中有n个单词，且有m段文章需要被处理。 <br>之后的n行每行描述一个单词，再之后的m行每行描述一段文章。 <br>其中1<=n, m<=20，每个单词长度不超过10，每段文章长度不超过1M。 <br></p> 

 
 # 输出格式 
<p>
对于输入的每一段文章，你需要输出这段文章在字典D可以被理解的最长前缀的位置。 <br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 3
is
name
what
your
whatisyourname
whatisyouname
whaisyourname
</td><td>
14
6
0	整段文章’whatisyourname’都能被理解
前缀’whatis’能够被理解
没有任何前缀能够被理解

</td></tr></table>
