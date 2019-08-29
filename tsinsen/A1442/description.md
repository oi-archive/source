<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Zeyad 想要在埃及犯下N项罪行并且不想受到惩罚。有若干种类的罪行。例如，行贿是一项罪行但是当行贿重复两次的时候就不被认为是犯罪。因此，行贿在犯偶数次的时候不被当做犯罪。超速是一项罪行，但是当重复的次数是五的倍数的时候就不被认为是犯罪。<br/>
　　更特别的，现在已知有C个犯罪的条件。每个条件描述罪行的种类Ti和倍数Mi。如果Zeyad的犯Ti这罪名的次数是Mi的倍数，那么Zeyad就不会因此受到惩罚。有些罪名可能在条件中出现多次。那么只要满足至少一个条件Zeyad就不会受罚。当然如果Zeyad犯某种罪行的次数为0，他自然由于遵守法律而不会受罚。<br/>
　　现在Zeyad想知道他有多少种犯罪方式使得他恰好犯下n次罪却不会受到任何惩罚。<br/>
　　犯罪的顺序是有关系的。更正式的说，两个犯罪序列W1与W2被认为相同，当且仅当对于所有 1 ≤ <i>i</i> ≤ <i>n，</i><i>w</i>1<sub><i>i</i></sub> = <i>w</i>2<i>i</i>成立。</div>
# 输入格式

<div class="pdcont">　　第一行有两个整数n,c 分别表示Zeyad想要犯罪的次数和他所知的条件的数目<br/>
　　紧接着是c个条件。共有26种罪名，分别用A-Z表示。每个条件包含一个大写字母表示罪名的类型和一个正整数表示倍数。<br/>
　　所有条件中倍数的乘积不超过123。某些条件可以出现多次。<br/>
　　当倍数是1时表示无论犯罪多少次都不会受到惩罚。<br/>
　　显而易见，对于那些没有在条件中列出的罪名Zeyad不会考虑去犯它们因为这会不可避免地受到惩罚。</div>
# 输出格式

<div class="pdcont">　　输出一个非负整数，表示Zeyad恰好犯下n次罪却不会受到任何惩罚的犯罪方式数目模12345的值。</div>
# 样例输入

<div class="pddata">5 2<br/>
A 1<br/>
B 2</div>
# 样例输出

<div class="pddata">16</div>
# 样例说明

<div class="pdcont">　　对于样例，一下16中犯罪方法均符合题意：AAAAA, AAABB, AABAB, AABBA, ABAAB, ABABA, ABBAA, BAAAB, BAABA, BABAA, BBAAA, ABBBB, BABBB, BBABB, BBBAB, BBBBA.</div>
# 数据规模和约定

<div class="pdcont">　　0 ≤ <i>n</i> ≤ 10<sup>18</sup>, 0 ≤ <i>c</i> ≤ 1000</div>

</div>