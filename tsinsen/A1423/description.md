<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　Nick 有一个 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1tZ3FKQXlNQg==.do"/> 到 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1yMjlIcWpiaA==.do"/> 的排列 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1uUnQ3SlI3cg==.do"/>。<br/>
<br/>
　　Nick 定义一个区间 <img width="27" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1HMmZBakZmNA==.do"/> <img width="42" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1lQkpiQlk1UQ==.do"/> 是所有满足 <img width="53" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1uRDk0RjYzZA==.do"/> 的 <img width="12" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1SbnFiSGFlZw==.do"/> 所构成的集合；而一个区间组 <img width="43" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD00MlFMdHJqaA==.do"/> 和 <img width="42" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1IRnFOTllKcQ==.do"/> <img width="174" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1uTU5RQUhZcQ==.do"/> 是<b>好的</b>当且仅当其 <img width="141" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1HYTNFNkFOZQ==.do"/> 个元素，按升序排序后，形成公差为 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1ocXk2OW44Mg==.do"/> 的数列。也就是说，当把他们按升序排序后，可表示为 <img width="178" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1xNlJ5N0p5eQ==.do"/> 的形式。<br/>
<br/>
　　您的任务就是帮助 Nick 统计，在当前给定的排列中，所有<b>好的</b>区间组的数量。定义两个区间组不同当且仅当他们所包含的元素所构成的集合不同。例如，对于任意区间 <img width="72" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1kcmhmNkpGSg==.do"/> ，其可以表示为区间组 <img width="25" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD02RG10Um4yZA==.do"/> 和 <img width="51" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1ZTWd0UW5mUQ==.do"/> <img width="65" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD04ZFlNQjhSQg==.do"/> 。因为这些区间组包含的元素构成了相同的集合，所以它们都是相同的。<br/>
<br/>
　　更多细节，请参见样例解释。</div>
# 输入格式

<div class="pdcont">　　第一行只有一个数 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD0yNmhOMkZyNQ==.do"/> <img width="110" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1nYmpNOEc5QQ==.do"/> ，表示排列的大小。<br/>
　　第二行有 <img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD05R0RBVERFdA==.do"/> 个由空格分隔开的数 <img width="12" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1MM0dHR044VA==.do"/> ，描述该排列。</div>
# 输出格式

<div class="pdcont">　　输出所有<b>好的</b>区间组的数量。<br/>
　　对于 C++ 语言，请不要使用 %lld 格式符来输入输出 64 位整数。 cin, cout 或 %I64 格式符推奖。</div>
# 样例输入

<div class="pddata">3<br/>
1 2 3</div>
# 样例输出

<div class="pddata">3<br/>
<br/>
在该样例中，下列区间组是好的：<br/>
<img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1GZm4zTXliZQ==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1FcWpRTUdRRw==.do"/> <img width="73" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1EcWp0ZW15TQ==.do"/> 。<br/>
根据定义，区间组 <img width="76" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD01WXJZZDUzdA==.do"/> 等价于区间组 <img width="73" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1RMnl0cTQ4QQ==.do"/> ，因为它们所包含的元素构成了同一集合，即 <img width="45" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD02MlJHOGJnZA==.do"/> 。</div>
# 样例输入

<div class="pddata">5<br/>
1 4 5 3 2</div>
# 样例输出

<div class="pddata">10</div>
# 样例输入

<div class="pddata">5<br/>
5 4 3 1 2</div>
# 样例输出

<div class="pddata">10<br/>
<br/>
该样例中以下数对是好的：<br/>
<img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1uQXk0QThOZA==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1obkp0ZHJNZQ==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1BUWR0MlRxVA==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD03QkUzRUU1Zw==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD0yNDdZZzk1Ug==.do"/><br/>
<img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1ROHlhOXlhcg==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD15ZjdoN05FeQ==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1tRmZoZm5tZw==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1KNjY3R21FZg==.do"/> <img width="78" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD1RTDc5aGo0UQ==.do"/></div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">#</td><td style="border:solid 1.0pt"><img width="8" height="21" src="source/tsinsen/A1423/img/aHR0cDovL3RzaW5zZW4uY29tL1JlcXVpcmVGaWxlLmRvP2ZpZD0yNmhOMkZyNQ==.do"/> 的值</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">1</td><td align="right" style="border:solid 1.0pt">5</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">2</td><td align="right" style="border:solid 1.0pt">5</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">3</td><td align="right" style="border:solid 1.0pt">5</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">4</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">5</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">6</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">7</td><td align="right" style="border:solid 1.0pt">9</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">8</td><td align="right" style="border:solid 1.0pt">99</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">9</td><td align="right" style="border:solid 1.0pt">99</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">10</td><td align="right" style="border:solid 1.0pt">999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">11</td><td align="right" style="border:solid 1.0pt">999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">12</td><td align="right" style="border:solid 1.0pt">999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">13</td><td align="right" style="border:solid 1.0pt">9999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">14</td><td align="right" style="border:solid 1.0pt">9999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">15</td><td align="right" style="border:solid 1.0pt">9999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">16</td><td align="right" style="border:solid 1.0pt">9999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">17</td><td align="right" style="border:solid 1.0pt">9999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">18</td><td align="right" style="border:solid 1.0pt">99999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">19</td><td align="right" style="border:solid 1.0pt">99999</td></tr><tr style="border:solid 1.0pt"><td align="right" style="border:solid 1.0pt">20</td><td align="right" style="border:solid 1.0pt">299999</td></tr></tbody></table></div>

</div>