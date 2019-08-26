
# Description

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium">最近阳阳接下了一个任务：编写一个操作系统。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">编写操作系统可是一个大工程，阳阳花费了很多时间在上面，他本想很快完成的，但是IOI在即，再怎么样也不能耽误了世界赛啊！但是雇主的要求有很严格，要求阳阳一定要在IOI之前完成这个系统的编写，所以他不得不找到你请求帮助，人多力量大嘛，你就帮帮他咯。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">你的任务很简单，只要编写一个内存管理系统就可以了。你的程序需要支持以下9个操作：</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">CreateProcess(PID,Memory,Priority)：新建一个过程，编号为PID，其占用的内存为Memory，优先级（称为外部优先级）为Priority；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">AddMessage(PID,Priority)：在过程PID中新建一个任务，其优先级（称为内部优先级）为Priority；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">Run：在当前所有任务中间找出一个优先级最高的运行并输出’Run: Priority’，这里的优先级定义为其内部优先级与外部优先级的积，如果两个任务的优先级一样则优先运行PID较小的任务，如果没有任何任务则输出’Empty’；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">ChangePriority(PID,NewValue)：将过程PID的外部优先级改变为NewValue；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">GetMemory(PID,Memory)：将过程PID的内存占用增加Memory；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">FreeMemory(PID,Memory)：将过程PID的内存占用减少Memory；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">RunProcess(PID)：将过程PID中找出一个内部优先级最高的运行并输出’Run Process: Priority’，如果该过程中如果没有任何任务则输出’Empty’；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">CloseMaxMemory：将当前所有过程中内存占用最高的过程关闭，占用内存一样则选择PID较小的关闭，如果当前没有任何过程则输出’Empty’；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">CloseProcess(PID)：将过程PID关闭。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">PS：</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">1)   任务运行后自动被删除；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">2)   对于CreateProcess，如果PID已经存在则输出’Error’，对于其他操作，如果PID不存在则输出’Error’，这种情况下该操作将被忽略；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">3)   当一个过程的内存占用小于等于0时则该过程将被自动关闭；</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 21.75pt"><span style="font-size: medium">第一行一个正整数N，表示操作总数，开始内存中过程为空；</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">然后N行每行按照如上格式描述一个任务；</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">按照如上描述输出。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">11<br/>
CloseMaxMemory<br/>
CreateProcess(1,100,1)<br/>
CreateProcess(2,200,1)<br/>
CreateProcess(3,300,1)<br/>
AddMessage(1,9)<br/>
AddMessage(2,19)<br/>
AddMessage(1,10)<br/>
GetMemory(2,999)<br/>
CloseMaxMemory<br/>
Run<br/>
RunProcess(1)<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Empty<br/>
Run: 10<br/>
Run Process: 9<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">0 &lt; N &lt;= 100,000<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">对于</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">65%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">的数据范围</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">N &lt;= 1,000</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">；</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">对于</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">90%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">的数据范围将只出现</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">CreateProcess</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">、</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">AddMessage</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">、</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">Run</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">、</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">RunProcess</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">操作；</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">对于</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">90%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">的数据</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">PID</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">的范围为</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">[1 .. N]</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt">；</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><o:p></o:p></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=模拟题系列">模拟题系列</a></p></div>

