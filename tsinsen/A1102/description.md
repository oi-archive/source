<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　从键盘输入一个字符串（长度&lt;=40个字符），并以字符 ’.’ 结束。编辑功能有：<br/>
　　1    D：删除一个字符，命令的方式为： D  a  其中a为被删除的字符，例如：D  s  表示删除字符 ’s’ ，若字符串中有多个 ‘s’，则删除第一次出现的。<br/>
　　2    I：插入一个字符，命令的格式为：I  a1  a2  其中a1表示插入到指定字符前面，a2表示将要插入的字符。例如：I  s  d  表示在指定字符 ’s’ 的前面插入字符 ‘d’ ，若原串中有多个 ‘s’ ，则插入在最后一个字符的前面。<br/>
　　3   R：替换一个字符，命令格式为：R  a1  a2  其中a1为被替换的字符，a2为替换的字符，若在原串中有多个a1则应全部替换。</div>
# 输入格式

<div class="pdcont">　　输入共两行，第一行为原串(以’.’结束)，第二行为命令（输入方式参见“问题描述”)。</div>
# 输出格式

<div class="pdcont">　　输出共一行，为修改后的字符串或输出指定字符不存在的提示信息。</div>
# 样例输入

<div class="pddata">This is a book.<br/>
D s</div>
# 样例输出

<div class="pddata">Thi is a book.</div>
# 输入输出样例解释

<div class="pdcont">　　命令为删去s，第一个在字符中出现的s在This中，即得到结果。</div>

</div>