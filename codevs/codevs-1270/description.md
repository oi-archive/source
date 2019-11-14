<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Linguists are currently studying Mhocskian, the language of the native inhabitants of Mhocsky island. The linguists have found a description of how the natives construct words in Mhocskian, and a list of words. The linguists would now like to know which of the words in the list are valid Mhocskian words.</p>
<p>语言学家现在在研究霍克斯语，一种霍克斯岛当地居民的语言。语言学家找到了关于当地人如何构造单词的描述，和一个单词列表。语言学家想知道这个列表里哪些词是非法的霍克斯单词。</p>
<p>Words in Mhocskian are constructed according to a set of rules. These rules involve two types of components: variables and terminals. A variable is an uppercase letter used in the description of the rules. A terminal is a lowercase letter that is part of a Mhocskian word.</p>
<p><span style="">霍克斯单词是按照一系列的规则进行构造的。这些规则中有两个部分的基本组成，变量和结束符。变量是一个大写字符，结束符是一个小写字母。</span></p>
<p><span style="">There are two types of rules. The ﬁrst type of rule allows you to replace a variable V by two variables V1V2 in that order, and we write V → V1V2 as a short form for this type of rule. The second type of rule allows you to replace a variable V by a terminal t, and we write V → t as a short form for this type of rule.</span></p>
<p><span style="">规则一共有两种类型。第一种规则允许你用两个变量V1和V2</span><span style="">替换变量V，替换为V1V2。我们用V → V1V2作为这种类型规则的简写。第二种类型的规则允许你用结束符t替换V，我们写作 V → t。</span></p>
<p> </p>
<p>One of the variables is the start variable. A word w is composed of lowercase letters from the English alphabet. It is a valid Mhocskian word if, starting from the start variable, it is possible to follow a sequence of rules to obtain w.</p>
<p>变量中的一个是起始变量。一个霍克斯词是由英文小写字母组成的。如果一个霍克斯词w是一个非法词，当且仅当他无法由起始变量经过一系列的规则变化到w。</p>
<p>Suppose we have variables {S,A,B}, terminals {a,b}, and rules<br>{S → AB,S → a,A → a,B → b}.</p>
<p>假设我们有变量集合{S,A,B}，结束符集合{a,b}，和规则集合 <span style="">{S → AB,S → a,A → a,B → b}.</span></p>
<p>The word “ab” is a valid Mhocskian word because it can be constructed in the following way: S → AB → aB → ab. The word “a” can be constructed simply by S → a. The word “b” cannot be constructed.</p>
<p>单词ab是一个合法的霍克斯词，因为他能通过如下的方式被构造出来：S → AB → aB → ab. 单词a也能通过S → a被构造出来。单词b不是一个合法词汇，因为他无法被构造出来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>On the ﬁrst line, two integers V and T in that order.</p>
<p>第一行包含2个整数V和T。代表有V个变量和T和结束符。</p>
<p><span style="">On the second line, V space separated uppercase letters, the variables. The ﬁrst variable on the line is always the start variable.</span></p>
<p>第二行，有V个大写字符以空格隔开，代表变量。第一个变量总代表起始变量。</p>
<p><span style="">On the third line, T space separated lowercase letters, the terminals.</span></p>
<p>第三行，T个小写字符以空格隔开，代表结束符。</p>
<p>On the fourth line, there is an integer R1. R1 lines follow, each of which is of the form V t, representing a rule V → t.</p>
<p>第四行，有一个整数R1，代表第一类规则的个数，接下来有R1行，每行一个规则V t，代表有一个规则V → t。</p>
<p><span style="">On the next line, there is an integer R2. R2 lines follow, each of the form V V1 V2, representing the rule V → V1V2.</span></p>
<p>接下来一行，有一个整数R2，代表第二类规则的个数，接下来R2行，每行一个规则V V1 V2，代表一个规则V → V1V2。</p>
<p>On the next line, there is an integer W. W lines follow, each contains a single word made entirely of lowercase letters.</p>
<p>再接下来一行，有一个整数W，然后跟着W行，每行一个全部由小写字母组成的单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The output must contain W lines. On line i, output a 1 if the ith word is a valid Mhocskian word, and 0 otherwise.</p>
<p>输出包含W行，第i行如果是1表示第i个单词是一个合法的霍克斯单词，如果是0表示不是合法的霍克斯单词。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p>
<p>I S A B C</p>
<p>a b</p>
<p>2</p>
<p>A a</p>
<p>B b</p>
<p>7</p>
<p>I A B</p>
<p>I A C</p>
<p>C S B</p>
<p>S A B</p>
<p>S A C</p>
<p>I S S</p>
<p>S S S</p>
<p>4</p>
<p>abababaaabbbaabbaabb</p>
<p>abab</p>
<p>bbaa</p>
<p>aaabababbaaabbbb</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>
<p>0</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ≤ V,T ≤ 26 1 ≤ R1 + R2 ≤ 30 1 ≤ W ≤ 20 Each of the words in the linguists’ list will have length between 1 and 30.</p>
<p>数据范围：</p>
<p>1 ≤ V,T ≤ 26</p>
<p>1 ≤ V,T ≤ 26</p>
<p>1 ≤ W ≤ 20</p>
<p>单词列表中的每个单词的长度在1到30之间</p>
</div>
</div>