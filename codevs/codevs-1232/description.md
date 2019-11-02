<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">第二次世界大战时期，英国皇家空军从沦陷国征募了大量外籍飞行员。由皇家空军派出的每一架飞机都需要配备在航行技能和语言上能互相配合的 2 名飞行员，其中 1 名是英国飞行员，另 1 名是外籍飞行员。在众多的飞行员中，每一名外籍飞行员都可以与其他若干名英国飞行员很好地配合。如何选择配对飞行的飞行员才能使一次派出最多的飞机。对于给定的外籍飞行员与英国飞行员的配合情况，试设计一个算法找出最佳飞行员配对方案，使皇家空军一次能派出最多的飞机。</span></p>
<p><span style="">对于给定的外籍飞行员与英国飞行员的配合情况，编程找出一个最佳飞行员配对方案，使皇家空军一次能派出最多的飞机。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第</span><span style=""> 1 </span><span style="">行有</span><span style=""> 2 </span><span style="">个正整数</span><span style=""> m</span><span style="">和</span><span style=""> n</span><span style="">。</span><span style="">n </span><span style="">是皇家空军的飞行员总数</span><span style="">(n&lt;100)</span><span style="">；</span><span style="">m </span><span style="">是外籍飞行员数。外籍飞行员编号为</span><span style=""> 1~m</span><span style="">；英国飞行员编号为</span><span style=""> m+1~n</span><span style="">。接下来每行有</span><span style=""> 2 </span><span style="">个正整数</span><span style=""> i </span><span style="">和</span><span style=""> j</span><span style="">，表示外籍飞行员</span><span style=""> i </span><span style="">可以和英国飞行员</span><span style=""> j </span><span style="">配合。文件最后以</span><span style=""> 2</span><span style="">个</span><span style="">-1 </span><span style="">结束。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">第</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> 1 </span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">行是最佳飞行员配对方案一次能派出的最多的飞机数</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> M</span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">。接下来</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> M </span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">行是最佳飞行员配对方案。每行有</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> 2</span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">个正整数</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> i </span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">和</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> j</span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">，表示在最佳飞行员配对方案中，飞行员</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> i </span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">和飞行员</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US"> j </span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">配对。如果所求的最佳飞行员配对方案不存在，则输出&lsquo;</span><span style="font-family: 'Calibri','sans-serif'; mso-ascii-theme-font: minor-latin; mso-fareast-font-family: 宋体; mso-fareast-theme-font: minor-fareast; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;" lang="EN-US">No Solution!</span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-ascii-theme-font: minor-latin; mso-fareast-theme-font: minor-fareast; mso-hansi-font-family: Calibri; mso-hansi-theme-font: minor-latin; mso-bidi-font-size: 11.0pt; mso-bidi-font-family: 'Times New Roman'; mso-bidi-theme-font: minor-bidi; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA;">&rsquo;。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 10</span></p>
<p><span style="">1 7 </span></p>
<p><span style="">1 8 </span></p>
<p><span style="">2 6 </span></p>
<p><span style="">2 9 </span></p>
<p><span style="">2 10</span></p>
<p><span style="">3 7</span></p>
<p><span style="">3 8</span></p>
<p><span style="">4 7 </span></p>
<p><span style="">4 8 </span></p>
<p><span style="">5 10 </span></p>
<p><span style="">-1 -1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">4 </span></p>
<p><span style="">1 7 </span></p>
<p><span style="">2 9 </span></p>
<p><span style="">3 8 </span></p>
<p><span style="">5 10</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>