
# 题目描述

司令部的将军们打算在 $N\times M$ 的网格地图上部署他们的炮兵部队。一个 $N\times M$ 的地图由 $N$ 行 $M$ 列组成，地图的每一格可能是山地（用“`H`”表示），也可能是平原（用“`P`”表示），如下图。在每一格平原地形上最多可以布置一支炮兵部队（山地上不能够部署炮兵部队）；一支炮兵部队在地图上的攻击范围如图中黑色区域所示：

<body>
<table class="MsoNormalTable" style="border-collapse: collapse; border: none; margin-left: 6.75pt; margin-right: 6.75pt; height: 241px;" border="1" width="360" cellspacing="0" cellpadding="0" align="left">
<tbody>
<tr style="height: 15.0pt;">
<td style="width: 28px; border: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 6pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: 1pt solid windowtext; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-image: initial; border-left: none; padding: 0cm 5.4pt; height: 15pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
</tr>
<tr style="height: 15.6pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 15.6pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
</tr>
<tr style="height: 18.0pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
</tr>
<tr style="height: 18.0pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: #8c8c8c; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
</tr>
<tr style="height: 18.0pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 18pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
</tr>
<tr style="height: 13.2pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 6pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; background: black; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #ecf0f1; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 13.2pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
</tr>
<tr style="height: 17.4pt;">
<td style="width: 28px; border-right: 1pt solid windowtext; border-bottom: 1pt solid windowtext; border-left: 1pt solid windowtext; border-image: initial; border-top: none; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 28.8px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>P</strong></span></p>
</td>
<td style="width: 30.4px; border-top: none; border-left: none; border-bottom: 1pt solid windowtext; border-right: 1pt solid windowtext; padding: 0cm 5.4pt; height: 17.4pt;" valign="top">
<p style="margin: 0cm 0cm 0.0001pt; text-align: justify; font-size: 10.5pt; font-family: 'Times New Roman';"><span style="color: #000000; font-size: 14pt;"><strong>H</strong></span></p>
</td>
</tr>
</tbody>
</table>
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
</body>

如果在地图中的灰色所标识的平原上部署一支炮兵部队，则图中的黑色的网格表示它能够攻击到的区域：沿横向左右各两格，沿纵向上下各两格。图上其它白色网格均攻击不到。从图上可见炮兵的攻击范围不受地形的影响。

现在，将军们规划如何部署炮兵部队，在防止误伤的前提下（保证任何两支炮兵部队之间不能互相攻击，即任何一支炮兵部队都不在其他支炮兵部队的攻击范围内），在整个地图区域内最多能够摆放多少我军的炮兵部队。


# 输入格式

文件的第一行包含两个由空格分割开的正整数，分别表示 $N$ 和 $M$；

接下来的 $N$ 行，每一行含有连续的 $M$ 个字符（“`P`”或者“`H`”），中间没有空格。按顺序表示地图中每一行的数据。


# 输出格式

文件仅在第一行包含一个整数 $K$，表示最多能摆放的炮兵部队的数量。

# 样例

#### 样例输入
```plain
5 4
PHPP
PPHH
PPPP
PHPP
PHHP
```

#### 样例输出
```plain
6
```


# 数据范围与提示

$N\leqslant 100$，$M\leqslant 10$。

