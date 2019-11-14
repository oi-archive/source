# 题目描述


<h3>
【题目描述】
</h3>
<p>
在这个有话不直说的年代，密码学越来越被广泛接受。
</p>
<p>
我们引用经典的“凯撒密码”。
</p>
<p>
在英文中，凯撒加密只对26个字母生效（分大小写）
</p>
<p>
我们按照’a’到’z’来排字母。
</p>
<p>
凯撒加密的原理就是把原文的每一个字母都按顺序往后移K位。这个K将被作为密钥。（’a’往后移变成’b’，’z’往后移会变成’a’）
</p>
<p>
<img src="/upload/image/20141203/20141203162824_21822.png" alt=""/> 
</p>
<p>
（0 ≤ K ≤ 25）
</p>
<p>
现在给出一系列用凯撒加密的英文句子，请你编写程序逐句翻译。
</p>
<p>
也就是说，请你确定一个密钥，使得解码以后的文字最符合英文的规则与规范。
</p>
<p>
数据保证存在唯一的解码方案，使得明码是完全可以分辨的英文句子。
</p>
<h3>
【输入格式】
</h3>
<p>
输入一定包括10行
</p>
<p>
每一行都是用同一密钥加密的英文。
</p>
<h3>
【输出格式】
</h3>
<p>
输出10行，为解密结果。不允许格式上有任何不同。
</p>
<h3>
【样例输入】
</h3>
<p>
Welcome to the test. This is the 1st sample test case.
</p>
<p>
Vdkbnld sn sgd sdrs. Sghr hr sgd 2mc rzlokd sdrs bzrd.
</p>
<p>
Welcome to the test. This is the 3rd sample test case.
</p>
<p>
Nvctfdv kf kyv kvjk. Kyzj zj kyv 4ky jrdgcv kvjk trjv.
</p>
<p>
Govmywo dy dro docd. Drsc sc dro 5dr ckwzvo docd mkco.
</p>
<p>
Nvctfdv kf kyv kvjk. Kyzj zj kyv 6ky jrdgcv kvjk trjv.
</p>
<p>
Jrypbzr gb gur grfg. Guvf vf gur 7gu fnzcyr grfg pnfr.
</p>
<p>
Ucjamkc rm rfc rcqr. Rfgq gq rfc 8rf qyknjc rcqr ayqc.
</p>
<p>
Ckriusk zu znk zkyz. Znoy oy znk 9zn ygsvrk zkyz igyk.
</p>
<p>
Xfmdpnf up uif uftu. Uijt jt uif mbtu tbnqmf uftu dbtf.
</p>
<h3>
【样例输出】
</h3>
<p>
Welcome to the test. This is the 1st sample test case.
</p>
<p>
Welcome to the test. This is the 2nd sample test case.
</p>
<p>
Welcome to the test. This is the 3rd sample test case.
</p>
<p>
Welcome to the test. This is the 4th sample test case.
</p>
<p>
Welcome to the test. This is the 5th sample test case.
</p>
<p>
Welcome to the test. This is the 6th sample test case.
</p>
<p>
Welcome to the test. This is the 7th sample test case.
</p>
<p>
Welcome to the test. This is the 8th sample test case.
</p>
<p>
Welcome to the test. This is the 9th sample test case.
</p>
<p>
Welcome to the test. This is the last sample test case.
</p>
<h3>
【提示】
</h3>
<p>
数据将从不同的方面考察。请尽量保证程序的准确性。
</p>
<p>
每一行长度不会太短(不少于3个单词的完整句)。没有全角字符和其他语言符号，可能包含半角空格和标点。
</p>
<p>
单个测试点不超过5kB。
</p>
<h3>
【来源】
</h3>
<p>
国家集训队2011 何朴藩
</p>
