<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　现在我们使用的公历，又称为格里历（Gregorian Calendar），其前身为罗马的儒略历(Julian Calendar)。儒略历与格里历的区别主要在于置闰规则上。我们讨论的这种格里历的置闰规则可以归纳为为4 年一闰，100 年不闰，400 年又闰，3200 年又不闰，172800 年还得闰。而儒略历的置闰规则仅仅是4 年一闰而已。所以说，儒略历与回归年的差距大约是每400 年差3 天。公元前45 年颁布的儒略历，到公元1582 年已经能明显感觉到二至点的提前。于是，罗马教皇格里高利十三世颁布了格里历。他首先规定儒略历1582 年10 月5 日对应格里历1582 年10 月15 日，一举消除了千年来积累的误差；之后修改置闰法则为现行的规则，这样就形成了一套更为科学的历法。<br>　　在儒略历颁行的前几十年，其历法本身也经历过若干次修改。儒略历最初规定大月为1、3、5、7、11 月，每月31 天；小月为2、4、6、8、10 月，每月30 天；平年12 月为29 天，闰年12 月为30 天。但是，由于当时的僧侣错误理解了“隔三年设置一次闰年”的规则，导致前45 年，前42 年，前39 年，前36 年直到前9 年每三年就设置了一次闰年，这样就导致了与回归年的差距扩大到了3 天。前8 年，奥古斯都修改各月天数为现行规则，并且重新修改为四年一闰。为了补上与回归年的差距，奥古斯都取消了前5 年，前1 年和公元4 年的闰年，于公元8 年起重新开始设置闰年。这就形成了沿用了一千五百多年的儒略历。<br>　　在格里历颁行之前的年份，闰年也可以按照规则设置，从而逆推得到历史上任意一天的格里历日期，这称为外推格里历。需要注意的是，公元1 年的上一年为前1 年，所以说，外推格里历中前1 年、前5 年、前9 年等皆为闰年。<br>　　由于世界各国开始使用格里历的时间不同，导致历史上出现过格里历和儒略历并行使用的时期。例如牛顿出生于格里历1643 年1 月4 日，但是很多国家在12 月25 日举行纪念活动，因为在十七世纪中叶英国还在使用儒略历，牛顿出生的那一天在儒略历中为1642 年12 月25 日。这样就造成了很多麻烦。现在applepi 在阅读他的编年史的时候发现了这个问题，他希望你帮助他写一个程序，把格里历（或外推格里历）日期转换成儒略历日期。这个儒略历日期需要按照历史的真实情况处理，即前45 年至公元7 年的日期要按照当时的历法给出日期。现行格里历仍然与回归年有微小差距，历法可能继续修改，但是现在请你无视这一点。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　输入数据包含多组询问。<br>　　每组询问包含一行。首先是两个整数M 和D，表示格里历的月份和日期，之后是一个年份。如果是公元X 年，就表示成AD X 的形式，否则表示成X BC 的形式。<br>　　输入数据以EOF 结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　对于每组询问，在一行内输出其对应的儒略历日期。格式与输入格式相同。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 15 AD 1582<br>1 4 AD 1643<br>2 28 36 BC<br>12 31 1 BC<br>7 6 AD 1993<br>11 11 AD 11111111</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10 5 AD 1582<br>12 25 AD 1642<br>2 30 36 BC<br>1 1 AD 1<br>6 23 AD 1993<br>5 19 AD 11110874</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　对于30% 的数据，所给日期早于3200 年2 月28 日。<br>　　对于100% 的数据，所给日期晚于前45 年1 月1 日，早于格里历109 年12 月31 日。<br>　　每个测试点询问不多于10000 组。<br><br>来源：Nescafe XIII</p>
</div>
</div>