# 题目描述


<div style="line-height: 15pt" align="left"><b><span style="font-size: 10pt">【问题描述】</span></b><span style="font-size: 10pt"><br/>
    </span><span style="font-size: 10pt">话说由于 Z4 的共同努力，SARS终于被成功击退了。大家都松了一口气。回想之前，当 jakrinchose 患SARS，其它人采取急救措施时，可真有过一段胆颤心惊的经历！ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">当时 jakrinchose 表现出一点像是SARS的症状，大家都怕了！要是真的得了SARS可就麻烦了！于是一向十分冷静的立方立刻提出最好采取一些预防措施的十分明智的建议，之后 hongyan 和 worm 丢下一句“包在我身上”就出去了，立方只好留下来照顾 jakrinchose 。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">原来他们是找草药去了。把采来的草药调配好后，就叫 jakrinchose 喝下。谁知 jakrinchose 才喝了一两口，就突然吐了出来，并当场晕倒（正在看题的 jakrinchose 说：立方这小子真黑心）！ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">大家都当场惊呆了。幸亏又是立方，他有一位朋友是在 ZSU 学医的，立方从这位朋友处学得一点急救常识，经过一番抢救， jakrinchose 终于醒过来了。看样子他是中毒了。后经立方了解，发现他们把两种不能相混的药材一起调配了。可立方对于药物的知识有限，不知道解药该如何调配。怎么办呢？ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">立方只好决定把一切可能的配药方案先列出来，进行选择，再外出采药。也许还能弄出一些治SARS的药也说不定呢，到时 Z4 可扬名啦…… ：） 一种配药方案可以由任意 n 种（ 0&lt;n&lt;=N ， N 为药材种类数目）没有冲突的药材组成，总质量 m 满足 0&lt;m&lt;=n ，其功效 p = ( 组成它的药材的功效之和 ) × (m/n)×sqrt(n) ,(sqrt表示算术平方根)。由于立方只有一个大袋子，而时间又有限，他们把袋装满或不能再装后就必须赶回来了，不再找第二次，因此，就必须先对配药方案作慎重选择。同一种配药方案只采一份。</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">由于立方对药材比较了解，这次当然要他亲自出马了（！！！）。 hongyan 帮忙去抬药，而 worm 就留下来照顾 jakrinchose 了。现在问题是，已知所有药材种类以及它们能起的功效，所有冲突的药材对，应该选择哪些配药方案，才能使功效达到最大？ jakrinchose 危在旦夕了，你快快行动，帮帮立方他们吧！ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入格式】</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">    </span><span style="font-size: 10pt">输入文件 drug.in 的第一行包括三个整数 V （ 0&lt;=V&lt;=50000 ） ， N(0&lt;=N&lt;=16) 和 M ，分别表示袋子能装的总质量 (g) ，药材种类数和冲突的药材对数。第二行有 N 个不大于 100 整数，分别表示这 N 种药材的功效。接下来有 M 行，每行有两个整数，表示这两种药材是不可相混的。同一对药材只会出现一次。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输出格式】 <br/>
    输出文件 drug .out 仅有一个实数，表示最大功效。保留一位小数。 <br/>
【输入输出样例】 <b><br/>
</b>输入:<br/>
drug.in<br/>
6 4 2<br/>
1 2 3 4<br/>
1 3<br/>
2 4</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">输出:<br/>
drug.out<br/>
24.5</span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【样例说明】</span></div>
<p><span style="font-size: 10pt">    </span><span style="font-size: 10pt">将药材按 1..N 编号。可能的配药方案有：（ 1 ），（ 2 ），（ 3 ），（ 4 ），（ 1+2 ），（ 1+4 ），（ 2+3 ），（ 3+4 ）。最终选择的配药方案分别是（不唯一）：（ 4 ） 1g ，（ 1+4 ） 1g ，（ 2+3 ） 2g ，（ 3+4 ） 2g 。其功效之和为 4+ [ （ 1+4 ） ×(1/2) ×sqrt(2) ] + [ (2+3) ×sqrt(2) ] + [ (3+4) ×sqrt(2) ] = 24.5 。 </span></p>
