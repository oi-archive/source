
# Content

UESTC - ICPC新人交流群 里的复读机越来越多啦，每天都会进行很多次复读。

对此，秦皇发出铁令：如果有复读机不听话随意复读，就会被拖出去做成炒饭。

“秦皇不要啊！”
“不要啊！”
“啊！”
——来自一名可怜的复读机临终三连

可是，人类的本质就是复读，作为一名复读机，实在忍受不了不复读的憋屈。
他们多方打听，发现如果每个小组中复读机的编号两两互素（或者只有一个复读机），那么就能作为一个集体进行一条复读而不被禁言。
但是秦皇很严格，说假如复读机们不能尽可能最小化所分的组数，就发起一起大清洗，把所有的复读机都做成炒饭。

复读机们感到十分不安，于是他们想知道他们可以被分成几组进行复读，从而既可以避免被做成炒饭，又可以享受到复读的快乐。（当然现在，之前的炒饭全都成了兵马俑）

# Standard Input

一个正整数$N$，表示复读机有$N$个，且复读机顺序编号为$1$至$N$中的自然数，$1 \leq N \leq 100,000$。

# Standard Output

一行，每有一组复读机复读一次*Wed.Strong*

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1</td><td>Wed.Strong</td></tr><tr><td>2</td><td>Wed.Strong</td></tr><tr><td>4</td><td>Wed.StrongWed.Strong</td></tr></table>


# Constraints



# Note

样例1中，只有编号为1的一个复读机，那么显然只能分1组。

样例2中，只有编号为1和2的两个复读机，由于1和2是互素的，所以可以分到同1组里。

样例3中，有编号为1,2,3,4四个复读机，存在多种合理的分组方法，但经过检查可以发现，最小的组数只能是2。

# Source


