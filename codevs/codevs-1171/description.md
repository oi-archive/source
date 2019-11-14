<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】<br>R 国和S 国正陷入战火之中，双方都互派间谍，潜入对方内部，伺机行动。<br>历尽艰险后，潜伏于 S 国的R 国间谍小C 终于摸清了S 国军用密码的编码规则：<br>1． S 国军方内部欲发送的原信息经过加密后在网络上发送，原信息的内容与加密后所<br>得的内容均由大写字母‘A’-‘Z’构成（无空格等其他字符）。<br>2． S 国对于每个字母规定了对应的“密字”。加密的过程就是将原信息中的所有字母替<br>换为其对应的“密字”。<br>3． 每个字母只对应一个唯一的“密字”，不同的字母对应不同的“密字”。“密字”可以<br>和原字母相同。<br>例如，若规定‘A’的密字为‘A’，‘B’的密字为‘C’（其他字母及密字略），则原信<br>息“ABA”被加密为“ACA”。<br>现在，小 C 通过内线掌握了S 国网络上发送的一条加密信息及其对应的原信息。小C<br>希望能通过这条信息，破译S 国的军用密码。小C 的破译过程是这样的：扫描原信息，对<br>于原信息中的字母x（代表任一大写字母），找到其在加密信息中的对应大写字母y，并认为<br>在密码里y 是x 的密字。如此进行下去直到停止于如下的某个状态：<br>1． 所有信息扫描完毕，‘A’-‘Z’ 所有 26 个字母在原信息中均出现过并获得了相应<br>的“密字”。<br>2． 所有信息扫描完毕，但发现存在某个（或某些）字母在原信息中没有出现。<br>3． 扫描中发现掌握的信息里有明显的自相矛盾或错误（违反S 国密码的编码规则）。例<br>如某条信息“XYZ”被翻译为“ABA”就违反了“不同字母对应不同密字”的规则。<br>在小 C 忙得头昏脑涨之际，R 国司令部又发来电报，要求他翻译另外一条从S 国刚刚<br>截取到的加密信息。现在请你帮助小C：通过内线掌握的信息，尝试破译密码。然后利用破<br>译的密码，翻译电报中的加密信息。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行为小C 掌握的一条加密信息。<br>第 2 行为第1 行的加密信息所对应的原信息。<br>第 3 行为R 国司令部要求小C 翻译的加密信息。<br>输入数据保证所有字符串仅由大写字母‘A’-‘Z’构成，且第1 行长度与第2 行相等。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若破译密码停止时出现 2，3 两种情况，请你输出&ldquo;Failed&rdquo;（不含引号，注意首字母大<br />写，其它小写）。<br />否则请输出利用密码翻译电报中加密信息后得到的原信息。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例 1】<br>AA<br>AB<br>EOWIE</p>
<p> </p>
<p>【输入输出样例 2】</p>
<p>QWERTYUIOPLKJHGFDSAZXCVBN</p>
<p>ABCDEFGHIJKLMNOPQRSTUVWXY</p>
<p>DSLIEWO</p>
<p>【输入输出样例 3】<br>MSRTZCJKPFLQYVAWBINXUEDGHOOILSMIJFRCOPPQCEUNYDUMPP<br>YIZSDWAHLNOVFUCERKJXQMGTBPPKOIYKANZWPLLVWMQJFGQYLL<br>FLSO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例 1】<br>Failed</p>
<p>【输入输出样例 2】</p>
<p>Failed</p>
<p>【输入输出样例 3】<br>NOIP</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例 1 说明】<br>原信息中的字母‘A’和‘B’对应相同的密字，输出“Failed”。</p>
<p>【输入输出样例2 说明】<br>字母‘Z’在原信息中没有出现，输出“Failed”。</p>
</div>
</div>