# 题目描述


<p style="margin-bottom: 0cm;" class="cjk"><b>奥术能量环流</b></p>
<p style="margin-bottom: 0cm;" class="cjk">为了对抗巫妖王的天灾军团新一轮的入侵，暴风城正在被改建为一个港口城市。这个港口将会有通向诺森德的船只，以支援在诺森德战斗的联盟勇士。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">在教堂广场和花园区之间的运河的尽头，有一堵坚固的城墙。然而 现在这里却被规划成为了通向港口的唯一途径，于是矮人们正在考虑如何将这堵墙拆掉。这堵墙是在六年前暴风城石工会建成的，它是当年为了抵抗兽人的入侵而建 立的，因而异常的坚固。然而现在石工会背叛了暴风城，他们组成了迪菲亚兄弟会，请他们来帮暴风城的贵族们是绝无可能的。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">矮人们准备使用尽可能多的炸药炸掉它，但是大主教本尼斯塔九世强烈反对这一愚蠢的做法，因为这样会使大教堂如世界末日来临一般的震动。侏儒们认为把砖一块一块地卸下来是个不错的方法，但是砖与砖之间连接得异常紧密。于是，如何拆掉它便成了一个棘手的问题。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">聪明的侏儒大工匠梅卡托克带领他的学徒工程师们彻底研究了这一堵墙，他们发现了这堵墙精妙的内部结构。墙内每块砖与其相邻的砖之间由奥术能量连接了起来，连接砖与砖之间的奥术能量是有极性的，发射方向总是从正极指向负极。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">墙的内部存在着若干个<b>奥术能量环流</b>。所谓奥术能量环流，就是指在由多块砖组成的一个系统中，从<b>每一块</b>砖沿着奥术极性能量的发射方向出发，在该系统中进行若干次传递以后，都能够回到这块砖来。他们还发现，拆砖的时候，只有把所有的奥术能量环流都破坏掉，才能取下砖。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">例如下面图样，这是大工匠梅卡托克带回实验室进行进一步研究的一个模型。</p>
<p lang="" style="margin-bottom: 0cm;" class="cjk"><img src="../../mw/images/3/35/Arcane.gif" alt=""/></p>
<p style="margin-bottom: 0cm;" class="cjk">在这个模型中，有<font face="Times New Roman, serif"><span lang="en-US">2*4=8</span></font>块砖，相邻的砖之间已经用箭头标出了奥术极性能量的方向，由正极指向负极。经过分析不难发现，这个结构中存在着<font face="Times New Roman, serif"><span lang="en-US">{1,2,5,6},{3,4}</span></font>两个<b>极大奥术能量环流</b><span style="">（再也加不进去另外一块砖使其仍为奥术能量环流）</span>。当然<font face="Times New Roman, serif"><span lang="en-US">{1,5}</span></font>也是一个奥术能量环流，但是它不是极大的，因为它是环流<font face="Times New Roman, serif"><span lang="en-US">{1,2,5,6}</span></font>的一个子环流。极大奥术能量环流就是一种环流，这种环流不是其他环流的子环流。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">暴风城的贵族们采纳了梅卡托克的方案，尽管如此，实际执行工作的矮人们还是无法理解。他们请你来帮助编写一个程序，在动工前算出这堵墙中存在的极大奥术能量环流的个数。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>输入格式</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">第<font face="Times New Roman, serif"><span lang="en-US">1</span></font>行，两个整数<font face="Times New Roman, serif"><span lang="en-US">N,M</span></font>，表示这堵墙由<font face="Times New Roman, serif"><span lang="en-US">N</span></font>行<font face="Times New Roman, serif"><span lang="en-US">,M</span></font>列块砖组合起来。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">第<font face="Times New Roman, serif"><span lang="en-US">2-N+1</span></font>行，第<font face="Times New Roman, serif"><span lang="en-US">i</span></font>行有<font face="Times New Roman, serif"><span lang="en-US">M</span></font>个整数，第<font face="Times New Roman, serif"><span lang="en-US">j</span></font>个整数<font face="Times New Roman, serif"><span lang="en-US">Pij</span></font>表示这块砖的状态。<font face="Times New Roman, serif"><span lang="en-US">Pij</span></font>为一个小于<font face="Times New Roman, serif"><span lang="en-US">16</span></font>的非负整数，把它转化为二进制以后，每个二进制位表示这块砖是否向一个方向发出极性奥术能量。二进制数从左到右第<font face="Times New Roman, serif"><span lang="en-US">1</span></font>位为上，第<font face="Times New Roman, serif"><span lang="en-US">2</span></font>为下，第<font face="Times New Roman, serif"><span lang="en-US">3</span></font>位为左，第<font face="Times New Roman, serif"><span lang="en-US">4</span></font>位为右，<font face="Times New Roman, serif"><span lang="en-US">1</span></font>表示发射，<font face="Times New Roman, serif"><span lang="en-US">0</span></font>表示没有。状态转换如下表。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<table cellspacing="0" cellpadding="7" bordercolor="#000000" border="1" width="531">
    <colgroup><col width="81"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/>
    </colgroup><tbody>
        <tr valign="top">
            <td width="81">
            <p class="cjk">状态</p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">2</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">3</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">4</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">5</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">6</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">7</span></font></p>
            </td>
        </tr>
        <tr valign="top">
            <td width="81">
            <p class="cjk">二进制表示</p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0000</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0001</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0010</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0011</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0100</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0101</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0110</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">0111</span></font></p>
            </td>
        </tr>
    </tbody>
</table>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<table cellspacing="0" cellpadding="7" bordercolor="#000000" border="1" width="529">
    <colgroup><col width="81"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="40"/> 	<col width="39"/> 	<col width="39"/>
    </colgroup><tbody>
        <tr valign="top">
            <td width="81">
            <p class="cjk">状态</p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">8</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">9</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">10</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">11</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">12</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">13</span></font></p>
            </td>
            <td width="39">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">14</span></font></p>
            </td>
            <td width="39">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">15</span></font></p>
            </td>
        </tr>
        <tr valign="top">
            <td width="81">
            <p class="cjk">二进制表示</p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1000</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1001</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1010</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1011</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1100</span></font></p>
            </td>
            <td width="40">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1101</span></font></p>
            </td>
            <td width="39">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1110</span></font></p>
            </td>
            <td width="39">
            <p class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1111</span></font></p>
            </td>
        </tr>
    </tbody>
</table>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>输出格式</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">第<font face="Times New Roman, serif"><span lang="en-US">1</span></font>行，一个整数，极大奥术能量环流的个数。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>样例输入</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><font face="Times New Roman, serif"><span lang="en-US">2 4</span></font></p>
<p style="margin-bottom: 0cm;" class="cjk"><font face="Times New Roman, serif"><span lang="en-US">5 5 1 2</span></font></p>
<p style="margin-bottom: 0cm;" class="cjk"><font face="Times New Roman, serif"><span lang="en-US">8 2 3 0</span></font></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>样例输出</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><font face="Times New Roman, serif"><span lang="en-US">2</span></font></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>样例说明</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk">样例如题中所给出的图所示。有<font face="Times New Roman, serif"><span lang="en-US">{1,2,5,6},{3,4}</span></font>两个极大奥术能量环流。</p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><b>数据规模</b></p>
<p style="margin-bottom: 0cm;" class="cjk"> </p>
<p style="margin-bottom: 0cm;" class="cjk"><font face="Times New Roman, serif"><span lang="en-US">1&lt;=N , M &lt;=100</span></font></p>
