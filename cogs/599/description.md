# 题目描述


<div style="line-height: 15pt" align="left"><b><span style="font-size: 10pt">【问题描述】</span></b><span style="font-size: 10pt"><br/>
    </span><span style="font-size: 10pt">这天入夜后， jakrinchose 忽然发起烧来，伴随头晕胸闷呼吸不畅等症状—— jakrinchose 得了SARS！幸得 jakrinchose 强健的体魄（！！！！！），以及其他人有效的预防措施，总算度过一劫！ </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">看来 SARS 病毒是随着 Z4 一起被吹来的。 jakrinchose 带着强烈报复心理，确定要攻克这种病毒 ! 首先就要找到它的繁殖规律。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">jakrinchose </span><span style="font-size: 10pt">以 Z4 起居的木屋作为原点建立了一个 <b>坐标轴 </b>（单位都为 m ），病毒也可以理解为坐标轴上的一点。病毒的增值规律是这样的：第一代病毒只有一个，而任何一代的病毒只会存活 1s ， 1s 后每一个病毒都会分离成 2 个下一代的子体病毒，分别沿坐标轴的正负 2 个方向移动一段距离（移动的时间忽略不计），然后又生存 1s ，再按同样的规则但移动的距离变为上一代的 1/2 再分裂。直到某一代的子体 <b>分裂移动的距离 &lt; 1m </b>时，将由于空间过度狭小难以吸收足够养分而不能存活。但任意一代的病毒侵袭的范围，都是以该病毒体所处点为中心，半径始终为 R 的圆。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">另外，有一点必须考虑的就是岛上时刻吹着沿坐标轴反向吹的风，必将会推移非典病毒。但冰雪聪明的 jakrinchose （呕心！）利用运动的相对性， <b>把风的因素理解为木屋从原点上以风速沿 x 轴正方向移动 </b>。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">现在 jakrinchose 想知道小木屋共会接受到多少代的病毒袭击。 <b>（在病毒侵袭范围以内以及距离病毒侵袭范围 0.00001 的范围内 , 小木屋也会受到病毒的袭击）。 </b></span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入格式】 <br/>
    输入文件 sars.in 只有一行 x,r,l,v(l&lt;=2^20) 分别是第一代病毒个体的坐标，病毒侵袭范围的半径，第一代病毒分裂出的子病毒将移动的距离以及“木屋移动”的速度。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输出格式】 <br/>
   输出文件 sars.out 只有一个整数，表示小木屋将受到多少代非典病毒的袭击。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">【输入输出样例】<br/>
 <b><br/>
</b>输入： <br/>
sars.in<br/>
3 1 3 2 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">输出：<br/>
sars.out<br/>
2<br/>
<b>[ </b><b>样例说明 ] </b></span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">木屋第一秒从 0 移动到 2 ，而第一秒内第一代病毒侵袭的范围为以 3 为中心，半径为 1 的圆，所以木屋将受到第一代病毒的侵袭。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">木屋第二秒从 2 移动到 4 这一过程中，没经过任意一个第二代病毒的侵袭范围。 </span></div>
<div style="line-height: 15pt" align="left"><span style="font-size: 10pt">木屋第三秒从 4 移动到 6 这一过程中，经过了以 4.5 为中心的病毒体的侵袭。所以木屋受到了第三代病毒的侵袭。 </span></div>
<p><span style="font-size: 10pt">第四秒开始，病毒分裂后移动的距离为 0.75&lt;1 ，所以没有病毒能够在存活。</span></p>
