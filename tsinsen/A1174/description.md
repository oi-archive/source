<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　R 国和S 国正陷入战火之中，双方都互派间谍，潜入对方内部，伺机行动。 历尽艰险后，潜伏于 S 国的R 国间谍小C 终于摸清了S 国军用密码的编码规则：<br/>
　　1． S 国军方内部欲发送的原信息经过加密后在网络上发送，原信息的内容与加密后所 得的内容均由大写字母‘A’-‘Z’构成（无空格等其他字符）。<br/>
　　2． S 国对于每个字母规定了对应的“密字”。加密的过程就是将原信息中的所有字母替 换为其对应的“密字”。<br/>
　　3． 每个字母只对应一个唯一的“密字”，不同的字母对应不同的“密字”。“密字”可以 和原字母相同。 例如，若规定‘A’的密字为‘A’，‘B’的密字为‘C’（其他字母及密字略），则原信 息“ABA”被加密为“ACA”。<br/>
　　现在，小 C 通过内线掌握了S 国网络上发送的一条加密信息及其对应的原信息。小C 希望能通过这条信息，破译S 国的军用密码。<br/>
　　小C 的破译过程是这样的：扫描原信息，对 于原信息中的字母x（代表任一大写字母），找到其在加密信息中的对应大写字母y，并认为 在密码里y 是x 的密字。如此进行下去直到停止于如下的某个状态：<br/>
　　1． 所有信息扫描完毕，‘A’-‘Z’ 所有 26 个字母在原信息中均出现过并获得了相应 的“密字”。<br/>
　　2． 所有信息扫描完毕，但发现存在某个（或某些）字母在原信息中没有出现。<br/>
　　3． 扫描中发现掌握的信息里有明显的自相矛盾或错误（违反S 国密码的编码规则）。例 如某条信息“XYZ”被翻译为“ABA”就违反了“不同字母对应不同密字”的规则。<br/>
　　在小 C 忙得头昏脑涨之际，R 国司令部又发来电报，要求他翻译另外一条从S 国刚刚 截取到的加密信息。现在请你帮助小C：通过内线掌握的信息，尝试破译密码。然后利用破 译的密码，翻译电报中的加密信息。</div>
# 输入格式

<div class="pdcont">　　输入共3 行，每行为一个长度在1 到100 之间的字符串。 第 1 行为小C 掌握的一条加密信息。 第 2 行为第1 行的加密信息所对应的原信息。 第 3 行为R 国司令部要求小C 翻译的加密信息。 输入数据保证所有字符串仅由大写字母‘A’-‘Z’构成，且第1 行长度与第2 行相等。</div>
# 输出格式

<div class="pdcont">　　输出共1 行。 若破译密码停止时出现 2，3 两种情况，请你输出“Failed”（不含引号，注意首字母大 写，其它小写）。 否则请输出利用密码翻译电报中加密信息后得到的原信息。</div>
# 样例输入

<div class="pddata">AA<br/>
AB<br/>
EOWIE</div>
# 样例输出

<div class="pddata">Failed</div>
# 输入输出样例 1 说明

<div class="pdcont">　　原信息中的字母‘A’和‘B’对应相同的密字，输出“Failed”。</div>
# 样例输入

<div class="pddata">QWERTYUIOPLKJHGFDSAZXCVBN<br/>
ABCDEFGHIJKLMNOPQRSTUVWXY<br/>
DSLIEWO</div>
# 样例输出

<div class="pddata">Failed</div>
# 输入输出样例2 说明

<div class="pdcont">　　字母‘Z’在原信息中没有出现，输出“Failed”。</div>
# 样例输入

<div class="pddata">MSRTZCJKPFLQYVAWBINXUEDGHOOILSMIJFRCOPPQCEUNYDUMPP<br/>
YIZSDWAHLNOVFUCERKJXQMGTBPPKOIYKANZWPLLVWMQJFGQYLL<br/>
FLSO</div>
# 样例输出

<div class="pddata">NOIP</div>

</div>