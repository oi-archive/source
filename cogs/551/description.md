# 题目描述


<div><span style="font-size: 12pt">fj</span><span style="font-size: 12pt">有</span><span style="font-size: 12pt">n (1 &lt;= N &lt;= 25,000)</span><span style="font-size: 12pt">个矩形牛棚，它们的墙均与坐标轴平行，而且其坐标在</span><span style="font-size: 12pt">0..1,000,000</span><span style="font-size: 12pt">之间，任意两个牛棚不能重叠，但可能会有公共的墙。</span></div>
<div><span style="font-size: 12pt">由于</span><span style="font-size: 12pt">fj</span><span style="font-size: 12pt">的奶牛持续增加，他不得不考虑扩张牛棚，一个牛棚可以扩张，当且仅当他的四周均不与其他牛棚接触，如果两个牛棚有一个公共角，那他们都是不可扩张的。</span></div>
<div><span style="font-size: 12pt">统计有多少牛棚可以扩张。</span></div>
<pre>输入说明:</pre>
<pre>* Line 1: 一个整数表示有 N个牛棚</pre>
<pre> </pre>
<pre>* Lines 2..N+1:每行四个整数，表示一个牛棚的左下角的坐标和右上角的坐标。.</pre>
<pre> </pre>
<pre>SAMPLE INPUT (expand.in):</pre>
<pre> </pre>
<pre>5</pre>
<pre>0 2 2 7</pre>
<pre>3 5 5 8</pre>
<pre>4 2 6 4</pre>
<pre>6 1 8 6</pre>
<pre>0 0 8 1</pre>
<pre> </pre>
<pre>样例解释:</pre>
<pre>有5个牛棚. 第一个牛棚的左上角的坐标为 (0,2) 并且右上角的坐标是(2,7), and so on.</pre>
<pre>输出格式:</pre>
<pre>* Line 1:一个整数表示有几个牛棚可以扩张.</pre>
<pre>SAMPLE OUTPUT (file expand.out):2</pre>
<pre>OUTPUT DETAILS:</pre>
<pre>有2个牛棚可以扩张，前两个可以，其他的都不可以。</pre>
<pre> </pre>
<div>40% n&lt;=6000</div>
<div> </div>
<table style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse" cellspacing="0" cellpadding="0" border="1">
    <tbody>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div>2</div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div><span style="color: #993300">1</span></div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc99; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div>4</div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: fuchsia; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div>3</div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: fuchsia; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ff99cc; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: fuchsia; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: fuchsia; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #ffcc00; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
        <tr>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div>5</div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
            <td style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; background: #00ccff; padding-bottom: 0cm; border-left: #ece9d8; width: 53.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid" valign="top" width="71">
            <div> </div>
            </td>
        </tr>
    </tbody>
</table>
