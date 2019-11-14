
# Description

<div class="content"><div>在这个有话不直说的年代，密码学越来越被广泛接受。我们引用经典的“凯撒密码”。在英文中，凯撒加密只对26</div>
<div>个字母生效（分大小写）我们按照a到z来排字母。凯撒加密的原理就是把原文的每一个字母都按顺序往后移K位。</div>
<div>这个K将被作为密钥。（’a’往后移变成’b’，’z’往后移会变成’a’）（0&lt;=K&lt;=25）现在给出一系列用凯撒</div>
<div>加密的英文句子，请你编写程序逐句翻译。也就是说，请你确定一个密钥，使得解码以后的文字最符合英文的规则</div>
<div>与规范。数据保证存在唯一的解码方案，使得明码是完全可以分辨的英文句子。</div></div>

# Input

<div class="content"><p>输入一定包括10行每一行都是用同一密钥加密的英文。</p></div>

# Output

<div class="content"><p>输出10行，为解密结果。不允许格式上有任何不同。</p></div>

# Sample Input

<div class="content"><span class="sampledata">Welcome to the test. This is the 1st sample test case.<br/>
Vdkbnld sn sgd sdrs. Sghr hr sgd 2mc rzlokd sdrs bzrd.<br/>
Welcome to the test. This is the 3rd sample test case.<br/>
Nvctfdv kf kyv kvjk. Kyzj zj kyv 4ky jrdgcv kvjk trjv.<br/>
Govmywo dy dro docd. Drsc sc dro 5dr ckwzvo docd mkco.<br/>
Nvctfdv kf kyv kvjk. Kyzj zj kyv 6ky jrdgcv kvjk trjv.<br/>
Jrypbzr gb gur grfg. Guvf vf gur 7gu fnzcyr grfg pnfr.<br/>
Ucjamkc rm rfc rcqr. Rfgq gq rfc 8rf qyknjc rcqr ayqc.<br/>
Ckriusk zu znk zkyz. Znoy oy znk 9zn ygsvrk zkyz igyk.<br/>
Xfmdpnf up uif uftu. Uijt jt uif mbtu tbnqmf uftu dbtf.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Welcome to the test. This is the 1st sample test case.<br/>
Welcome to the test. This is the 2nd sample test case.<br/>
Welcome to the test. This is the 3rd sample test case.<br/>
Welcome to the test. This is the 4th sample test case.<br/>
Welcome to the test. This is the 5th sample test case.<br/>
Welcome to the test. This is the 6th sample test case.<br/>
Welcome to the test. This is the 7th sample test case.<br/>
Welcome to the test. This is the 8th sample test case.<br/>
Welcome to the test. This is the 9th sample test case.<br/>
Welcome to the test. This is the last sample test case.<br/>
【数据说明】<br/>
数据将从不同的方面考察。请尽量保证程序的准确性。<br/>
每一行长度不会太短(不少于3个单词的完整句)。没有全角字符和其他语言符号，可能包含半角空格和标点。<br/>
单个测试点不超过5kB。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

