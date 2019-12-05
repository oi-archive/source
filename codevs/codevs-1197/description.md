<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>
<p>16 世纪法国外交家Blaise de Vigen<span style="font-family: 'Times New Roman';">è</span><span style="">re设计了一种多表密码加密算法——Vigen</span><span style="font-family: 'Times New Roman';">è</span><span style="">re密码。Vigen</span><span style="font-family: 'Times New Roman';">è</span><span style="">re 密码的加密解密算法简单易用，且破译难度比较高，曾在美国南北战争中为南军所广泛使用。</span></p>
<p>在密码学中，我们称需要加密的信息为明文，用 M 表示；称加密后的信息为密文，用C 表示；而密钥是一种参数，是将明文转换为密文或将密文转换为明文的算法中输入的数据，记为k。 在Vigen<span style="font-family: 'Times New Roman';">è</span><span style="">re密码中， 密钥k是一个字母串， k=k</span>1k2…kn。当明文M=m1m2…mn时，得到的密文C=c1c2…cn，其中ci=mi®<span style="">k</span>i，运算<span style="font-family: 'Times New Roman';">®</span><span style="">的规则如下表所示：</span></p>
<p> </p>
<p>Vigen<span style="font-family: 'Times New Roman';">è</span><span style="">re加密在操作时需要注意：</span></p>
<p> </p>
<p>1.  <span style="font-family: 'Times New Roman';">®</span><span style="">运算忽略参与运算的字母的大小写，并保持字母在明文 M中的大小写形式；</span></p>
<p> </p>
<p>2.  当明文M的长度大于密钥k的长度时，将密钥k 重复使用。</p>
<p> </p>
<p>例如，明文M=Helloworld，密钥k=abc 时，密文C=Hfnlpyosnd。</p>
<p> </p>
<table>
<tbody>
<tr>
<td valign="top" width="51">
<p>明文</p>
</td>
<td valign="top" width="51">
<p>H</p>
</td>
<td valign="top" width="51">
<p>e</p>
</td>
<td valign="top" width="51">
<p>l</p>
</td>
<td valign="top" width="51">
<p>l</p>
</td>
<td valign="top" width="51">
<p>o</p>
</td>
<td valign="top" width="51">
<p>w</p>
</td>
<td valign="top" width="51">
<p>o</p>
</td>
<td valign="top" width="51">
<p>r</p>
</td>
<td valign="top" width="51">
<p>l</p>
</td>
<td valign="top" width="51">
<p>D</p>
</td>
</tr>
<tr>
<td valign="top" width="51">
<p>密钥</p>
</td>
<td valign="top" width="51">
<p>a</p>
</td>
<td valign="top" width="51">
<p>b</p>
</td>
<td valign="top" width="51">
<p>c</p>
</td>
<td valign="top" width="51">
<p>a</p>
</td>
<td valign="top" width="51">
<p>b</p>
</td>
<td valign="top" width="51">
<p>c</p>
</td>
<td valign="top" width="51">
<p>a</p>
</td>
<td valign="top" width="51">
<p>b</p>
</td>
<td valign="top" width="51">
<p>c</p>
</td>
<td valign="top" width="51">
<p>a</p>
</td>
</tr>
<tr>
<td valign="top" width="51">
<p>密文</p>
</td>
<td valign="top" width="51">
<p>H</p>
</td>
<td valign="top" width="51">
<p>f</p>
</td>
<td valign="top" width="51">
<p>n</p>
</td>
<td valign="top" width="51">
<p>l</p>
</td>
<td valign="top" width="51">
<p>p</p>
</td>
<td valign="top" width="51">
<p>y</p>
</td>
<td valign="top" width="51">
<p>o</p>
</td>
<td valign="top" width="51">
<p>s</p>
</td>
<td valign="top" width="51">
<p>n</p>
</td>
<td valign="top" width="51">
<p>d</p>
</td>
</tr>
</tbody>
</table>
<p><span style=""><br></span></p>
</div>

<img src="/source/codevs/codevs-1197/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzExOTcucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共2行。</p>
<p>第一行为一个字符串，表示密钥k，长度不超过100，其中仅包含大小写字母。第二为一个字符串，表示经加密后的密文，长度不超过1000，其中仅包含大小写字母</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出共1行，一个字符串，表示输入密钥和密文所对应的明文</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>CompleteVictory</p>
<p>Yvqgpxaimmklongnzfwpvxmniytm</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Wherethereisawillthereisaway</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 100%的数据，输入的密钥的长度不超过 100，输入的密文的长度不超过 1000，且都仅包含英文字母。</p>
</div>
</div>