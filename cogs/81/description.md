# 题目描述


<p><span style="font-family: 宋体;"><b>问题描述</b><br/>
</span>设有一个长度为 N 的数字字符串，分成 K+1 个部分，使得 K+1 个部 分的乘积最大。 例如 N=6 ，且数字字符串为 ‘ 310143 &#39; ， K=3. 此时可能有的情况有以 下各种：</p>
<p>3 ＊ 1 ＊ 0 ＊ 143=0<br/>
3 ＊ 1 ＊ 01 ＊ 43=129<br/>
3 ＊ 1 ＊ 014 ＊ 3=126<br/>
3 ＊ 10 ＊ 1 ＊ 43=1290<br/>
3 ＊ 10 ＊ 14 ＊ 3=1260<br/>
3 ＊ 101 ＊ 4 ＊ 3=3636<br/>
31 ＊ 0 ＊ 1 ＊ 43=0<br/>
31 ＊ 01 ＊ 4 ＊ 3=372<br/>
310 ＊ 1 ＊ 4 ＊ 3=3720</p>
<p>问题：当 N ，数字串， K 给出之后，找出一种分法使其乘积最大。</p>
<p class="MsoNormal">【输入格式】</p>
<p class="MsoNormal"><span lang="EN-US"><span style="">    </span>输入由两行组成，第一行有两个整数，n（1≤n≤30）、k<span lang="EN-US">（1≤n≤30）</span>；n表示数字串长度、k表示乘号个数。</span><span lang="EN-US">第二行是数字串。</span></p>
<p class="MsoNormal"><span lang="EN-US"><o:p></o:p></span>【输出格式】</p>
<p class="MsoNormal"><span lang="EN-US"><span style="">    </span><span lang="EN-US">输出</span>为一个整数，为乘积最大值。</span></p>
<p class="MsoNormal">【输入样例】</p>
<p class="MsoNormal">输入文件名：<span class="SpellE"><span lang="EN-US">chf.in</span></span></p>
<p class="MsoNormal">9 4<br/>
321044105</p>
<p class="MsoNormal">输出文件名：<span class="SpellE"><span lang="EN-US">chf.out</span></span></p>
<p class="MsoNormal"><span lang="EN-US">5166000<o:p></o:p></span></p>
