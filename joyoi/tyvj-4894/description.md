# 

 
 # 题目背景 
<p>（本题纯属作者原创，难度约为NOIP联赛普及组第二题，适合即将参加NOIP的选手们练练手）</p>

<p>（P.S.因作者水平有限，题目可能会有小bug，请多多谅解）</p>

<p>clz终于光荣地从小学毕业，升入初中，成为一名初中生啦~~~有一天，clz在网上看到许多神犇编写的&ldquo;英汉互译机&rdquo;非常有意思：该程序的具体功能是可以实现英语和中文间的转换。刚刚摆脱&ldquo;小学生&rdquo;这个称号的clz越看觉得越神奇，但他有些不明白：这些程序到底是怎样实现语言间的转换的呢？于是，他也萌生了想编一个简易版&ldquo;英汉互译机&rdquo;的念头。但他的编程能力不是很好，于是他就找到了在编程界大名鼎鼎的你，请你来帮助他解决这个问题。</p> 

 
 # 题目描述 
<p>由于你和clz的水平都有限，所以需要翻译的句子<strong>只可能是两种类型</strong>：疑问句和陈述句。</p>

<p><em><u><strong>疑问句的格式为：&ldquo;be动词+指示代词+形容词性物主代词+名词（物品名）？&rdquo;</strong></u></em></p>

<p>举个栗子：Is&nbsp;this&nbsp;your&nbsp;schoolbag?</p>

<p>翻译应为：这是你的书包吗？</p>

<p><u><em><strong>陈述句的格式为：&ldquo;指示代词+be动词+形容词性物主代词+名词（物品名）.&rdquo;</strong></em></u></p>

<p>举个栗子：These&nbsp;are&nbsp;my&nbsp;books.</p>

<p>翻译应为：这些是我的书。</p>

<p>（如果输入的为中文，则输出应为英文。）</p>

<p>----------------------------------------------------</p>

<p>下面给出所有测试样例中可能出现的be动词：</p>

<p>is/are&nbsp;对应翻译：是</p>

<p><br />
所有测试样例中可能出现的指示代词：</p>

<p>this&nbsp;对应翻译：这</p>

<p>that&nbsp;对应翻译：那</p>

<p>these&nbsp;对应翻译：这些</p>

<p>those&nbsp;对应翻译：那些</p>

<p><br />
所有测试样例中可能出现的形容词性物主代词：</p>

<p>my&nbsp;对应翻译：我的&nbsp;</p>

<p>your&nbsp;对应翻译：你的&nbsp;</p>

<p>his&nbsp;对应翻译：他的&nbsp;</p>

<p>her&nbsp;对应翻译：她的&nbsp;</p>

<p>its&nbsp;对应翻译：它的</p>

<p><br />
所有测试样例中可能出现的名词（物品名）：</p>

<p><em><u><strong>★注意复数形式可能不是加s★</strong></u></em></p>

<p>book(复数books)&nbsp;翻译：书</p>

<p>eraser(复数erasers)&nbsp;翻译：橡皮</p>

<p>key(复数keys)&nbsp;翻译：钥匙</p>

<p>ring(复数rings)&nbsp;翻译：戒指</p>

<p>computer(复数computers)&nbsp;翻译：电脑</p>

<p>ball(复数balls)&nbsp;翻译：球</p>

<p>leaf(复数leaves)&nbsp;翻译：叶子</p>

<p>pen(复数pens)&nbsp;翻译：钢笔</p>

<p>schoolbag(复数schoolbags)&nbsp;翻译：书包</p>

<p>----------------------------------------------------</p>

<p>输入一个中文/英文字符串，输出翻译后的字符串。请注意：</p>

<p>1.输入输出应严格按照上表中的翻译</p>

<p>2.中文字符与英文字符应严格区分，切勿混淆</p> 

 
 # 输入格式 
<p>输入文件只有一行，为一个待翻译的字符串。字符串末尾一定是英文的&ldquo;.&rdquo;&ldquo;?&rdquo;或中文的&ldquo;。&rdquo;&ldquo;？&rdquo;。当末尾为中文标点时，待翻译的字符串为中文字符串，否则为英文字符串。</p>

<p>如果输入的字符串无法翻译或翻译过程中出现错误，则输出&ldquo;ERROR&rdquo;（当然不包括引号）</p> 

 
 # 输出格式 
<p>输出文件只有一行，为翻译后的字符串。<strong>行尾没有换行</strong>。</p> 

 
 # 提示 
<p>---------------------------------------------</p>

<p>【输入样例1】</p>

<p>This&nbsp;is&nbsp;your&nbsp;ring.</p>

<p>【输出样例1】</p>

<p>这是你的戒指。</p>

<p>【输入样例2】</p>

<p>Those&nbsp;are&nbsp;my&nbsp;leaves.</p>

<p>【输出样例2】</p>

<p>那些是我的叶子。</p>

<p>【输入样例3】</p>

<p>Is&nbsp;that&nbsp;your&nbsp;pen?</p>

<p>【输出样例3】</p>

<p>那是你的钢笔吗？</p>

<p>【输入样例4】</p>

<p>这些是它的球吗？</p>

<p>【输出样例4】</p>

<p>Are&nbsp;these&nbsp;its&nbsp;balls?</p>

<p>【输入样例5】</p>

<p>（）*#&amp;。</p>

<p>【输出样例5】</p>

<p>ERROR</p>

<p>----------------------------------------------</p>

<p>【数据范围】</p>

<p>1.1&le;字符串长度&le;30。</p>

<p>2.80%的数据，输入字符串保证有对应翻译；</p>

<p>&nbsp;&nbsp;另20%的数据，不保证一定可以翻译。</p>

<p>3.所有数据保证以&ldquo;.&rdquo;&ldquo;?&rdquo;&ldquo;。&rdquo;&ldquo;？&rdquo;结尾。</p>

