
# Description

<div class="content"><p><span class="Apple-style-span" style="word-spacing: 0px; font: medium Arial,Microsoft Yahei,Simsun,sans-serif; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; border-collapse: separate; orphans: 2; widows: 2; webkit-border-horizontal-spacing: 0px; webkit-border-vertical-spacing: 0px; webkit-text-decorations-in-effect: none; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">
</span></p><p align="justify"><font face="Times New Roman" size="3">Consider m natural numbers n<sub>1</sub>, n<sub>2</sub>, …, n<sub>m<span class="Apple-converted-space"> </span></sub>with the property n<sub>1³<span class="Apple-converted-space"> </span></sub>n<sub>2³<span class="Apple-converted-space"> </span></sub>…³ n<sub>m</sub>&gt;0.</font></p>
<p align="justify"><font face="Times New Roman" size="3">We define a Young table as an arrangement in a table of n<sub>1</sub>+n<sub>2</sub>+…+n<sub>m</sub><span class="Apple-converted-space"> </span>natural numbers (bigger than 0 and any two different), so that the i<sup>th</sup><span class="Apple-converted-space"> </span>line has n<sub>i</sub><span class="Apple-converted-space"> </span>elements (1£ i£ m) in ascending order from left to right, and the elements from the same column are in ascending order from bottom to top.</font></p>
<p align="justify"><font face="Times New Roman" size="3">An example of Young table for m=4, n<sub>1</sub>=6, n<sub>2</sub>=4, n<sub>3</sub>=4, n<sub>4</sub>=1 is the following:</font></p>
<p align="center"></p>
<center>
<table cellspacing="1" cellpadding="7" width="224">
    <tbody>
        <tr>
            <td valign="top" width="16%">
            <p><font face="Courier New" size="3"><font face="Courier New">1</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">2</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">5</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">9</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">10</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">15</font></font></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="16%">
            <p><font face="Courier New" size="3"><font face="Courier New">3</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">6</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">7</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">13</font></font></p>
            </td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
        </tr>
        <tr>
            <td valign="top" width="16%">
            <p><font face="Courier New" size="3"><font face="Courier New">4</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">8</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">12</font></font></p>
            </td>
            <td valign="top" width="17%">
            <p><font face="Courier New" size="3"><font face="Courier New">14</font></font></p>
            </td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
        </tr>
        <tr>
            <td valign="top" width="16%">
            <p><font face="Courier New" size="3"><font face="Courier New">11</font></font></p>
            </td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
            <td valign="top" width="17%"></td>
        </tr>
    </tbody>
</table>
</center>
<p></p>
<b>
<p><font face="Times New Roman">Task:</font></p>
</b>
<p><font face="Times New Roman" size="3">Given n<sub>1</sub>, n<sub>2</sub>, …, n<sub>m</sub></font><font face="Times New Roman"><sub><font size="3"><span class="Apple-converted-space"> </span></font></sub><font size="3">determine the number of Young tables containing the elements<span class="Apple-converted-space"> </span></font></font><font face="Times New Roman" size="3">1, 2, …, n<sub>1</sub>+n<sub>2</sub>+…+n<sub>m</sub>.</font></p>
<p></p></div>

# Input

<div class="content"><ul>
    <li><font face="Times New Roman" size="3"><i>on the first line is</i>: the natural number m;</font></li>
</ul>
<ul>
    <li><font face="Times New Roman" size="3"><i>on the second line are</i>: the numbers n<sub>1</sub>, n<sub>2</sub>, …, n<sub>m</sub><span class="Apple-converted-space"> </span>separated by a space.</font></li>
</ul></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">contain the number of Young tables that can be built.</font></p>
<p><font size="3"><b>
</b></font></p><p><font size="3"><b><font face="Times New Roman">Constraints:</font></b></font></p><font size="3"><b>
</b></font><p></p>
<ul><font face="Courier New" size="3">
    <ul>
        <li>1&lt;= m&lt;= 20</li>
    </ul>
    </font>
    <li><font face="Courier New" size="3">n<sub>1&lt;=</sub>12</font></li>
</ul></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
<br/>
3 2<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Romania2002">Romania2002</a></p></div>

