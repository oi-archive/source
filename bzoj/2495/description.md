
# Description

<div class="content"><div class="panel_content"><span style="font-size: medium">  Every student needs help from getting new knowledge by asking questions. Surveys are suggesting that some similar questions are repeated frequently. So it will be nice to develop an automatic question-answering system to answer these questions. Your algorithm should not have any prior knowledge, but it must be able to read sentences and remember the mentioned facts. Whenever the question is asked about such a fact, the system has to answer it properly.</span></div>
<div class="panel_bottom"></div>
<p><span style="font-size: medium"><br/>
给你两种陈述句的格式，通过其给定的关系建立一张关系网，然后在给定的疑问句中确认两个东西在关系网中是否存在关系。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"> The input consists of many dialogues.<br/>
  There is a single positive integer T on the first line of input. (T &lt;= 500, but note that 95% of them are relatively small) It denotes the number of following dialogues. Each dialogue includes one or more lines. Each line contains one sentence: either a statement or a question. Statements end with a dot character (.) while questions end with a question mark (?). There is one extra line after each dialogue. That line ends with an exclamation mark (!). The definitions of the statements and questions will be discussed later.<br/>
<br/>
Sentences can contain words, spaces and punctuation characters. All words contain only Latin letters and are case-sensitive. Unlike the normal English writing rules, the first letter of a sentence should keep lowercase unless the first word itself should begin with a capital letter. There are no extra spaces between words. No word will have more than 10 characters. There will be at most 1000 lines per dialogue.<br/>
<b>Statements</b><br/>
Each statement has one of the following forms:<br/>
<i><br/>
noun_phrase are noun_phrase.<br/>
noun_phrase can verb_phrase.<br/>
everything which can verb_phrase can verb_phrase.<br/>
everything which can verb_phrase are noun_phrase.<br/>
</i><br/>
noun_phrase and verb_phrase are both single word. The meanings of the four forms are:<br/>
<br/>
A are B: If X is A, then X is B.<br/>
A can B: If X is A, then X has the ability to B.<br/>
everything which can A can B: If X has the ability to A, X has the ability to B.<br/>
everything which can A are B: If X has the ability to A, X is B.<br/>
<br/>
<b>Questions</b><br/>
Each question has one of the following forms:<br/>
<i><br/>
are noun_phrase noun_phrase?<br/>
can noun_phrase verb_phrase?<br/>
can everything which can verb_phrase verb_phrase?<br/>
are everything which can verb_phrase noun_phrase?<br/>
</i><br/>
<br/>
They are the question form of the statements.<br/>
<br/>
In each test case, the number of different noun phrases will not exceed 100; the number of different verb phrases will not exceed 100.<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">  For each test case, output two lines. The first line describes the test case number counting from 1, while the second line contains the same number of characters as the number of questions in this test case. Each character is either ‘Y’(denoting you can get that fact logically) or ‘M’(otherwise), without quotes.</span></p>
<div class="panel_bottom"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
flies can fly.<br/>
flies are insects.<br/>
everything which can fly are animals.<br/>
are everything which can fly insects?<br/>
are flies animals?<br/>
can flies eat?<br/>
everything which can fly can eat.<br/>
can flies eat?<br/>
Bye!<br/>
 <br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
MYMY<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Acm 2011 上海">Acm 2011 上海</a></p></div>

