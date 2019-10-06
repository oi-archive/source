# 题目描述

<p>在出发讨伐圣诞老人前，元旦三侠想起了在圣诞老人到来以前那个灿烂的下午。</p>
<p>这天，生蛋侠、圆蛋侠和零蛋侠正在玩游戏。零蛋侠每次会一拍脑袋给出三个整数 $a, b, n$，保证 $a \geq 2$，$b \geq 1$，$a^b \leq n$。然后生蛋侠和圆蛋侠两人轮流进行操作，生蛋侠先手，每人每次可以选择将 $ a $ 的值加上 $ 1  $，或者将 $ b $ 的值加上 $ 1 $。但是任何人操作以后都不能违背 $ a^b \leq n$ 这个条件，无法再进行操作的人就输掉了这一场游戏。</p>
<p>因为 $ n $ 的值很大，生蛋侠和圆蛋侠愉快的玩了一个下午。最后，他们约定第二天再继续没有玩完的游戏。</p>
<p>但是第二天圣诞老人来了，降落时的冲击波摧毁了所有所有的一切。于是那个灿烂的下午终究是回不去，元旦三侠不禁头岑岑而泪潸潸了。现在，生蛋侠只记得零蛋侠给他们的数字 $ n $ 了，却不记得数字 $ a $ 和数字 $ b $ 了。他提出了 $ m $ 对数字 $ a $ 和数字 $ b $，希望你能告诉他，对每一对数字 $ a $ 和 $ b $，假设双方都足够聪明，他是否一定能在这场游戏中获胜？</p>

# 输入格式


<p>第一行两个正整数 $ n $ 和 $ m $。</p>
<p>接下来 $ m $ 行，每行两个正整数 $ a $ 和 $ b $。保证 $a \geq 2$，$b \geq 1$，$a^b \leq n$。</p>

# 输出格式


<p>$ m $ 行，如果对于这一对数字 $ a $ 和 $ b $，生蛋侠能赢得这场游戏，输出 “<samp>Yes</samp>”。否则输出 “<samp>No</samp>” （不含引号）。</p>

# 样例一


<h4>input</h4>
<pre>5 3
2 1
2 2
3 1

</pre>

<h4>output</h4>
<pre>Yes
No
No

</pre>



# 样例二


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$ 的规模</th>
<th>$m$ 的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n = 2$</td><td rowspan="10">$m \leq 10^5$</td></tr><tr><td>2</td><td rowspan="6">$n \leq 1000$</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10^9$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=51">样例数据下载</a></p>
