
# Description

<div class="content"><div>一只带着先进设备和药物的医疗团队来到了埃博拉病毒疫区的某个非洲国家。这个国家有n个村庄，均坐落在该国唯一的一条公路旁，n个村庄依次标号为1,2,…n。第i个村庄有a_i个埃博拉感染者。</div>
<div>到来后的第一天早晨，医疗团队在第1个村庄。每天他们可以选择治疗所在村庄的村民，这样所有感染者都会痊愈；他们也可以选择前往相邻的一个村庄，路程需要1天。每天结束时，如果第i个村庄的a_i个感染者没有痊愈，那么他们会死去，同时会有另外a_i个人被感染。也就是说，如果第i个村庄没有被治疗，那么每天这个村庄会死去a_i个人。</div>
<div>医疗团队在经过村庄i时，可能选择不治疗这个村庄而前往下一个村庄i+1。但为了不让村民失去希望，如果医疗团队在村庄j决定往回走时，则他们要治疗村庄j之前所有没有被治疗的村庄，同时在返回的过程中，如果经过没有接受治疗的村庄，他们需要停下来进行治疗。</div>
<div>医疗团队最终会治愈所有村民。作为团队的领导人，你需要得出在合理规划行程下最少的死亡人数。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><p><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">第一行为一个正整数</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:
AR-SA">n</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">，表示村庄的个数。接下来一行是</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:
AR-SA">n</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">个正整数</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:
AR-SA">a_i</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">（</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:
AR-SA">1&lt;=a_i&lt;=10^9</span><span style="font-size:10.5pt;mso-bidi-font-size:
11.0pt;font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">），为每个村庄的感染人数</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">输出一个整数，表示在治愈所有村民前最少的死亡人数。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
40 200 1 300 2 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1950</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" align="left"><span lang="EN-US">100%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">的数据，</span><span lang="EN-US">n&lt;=3000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

