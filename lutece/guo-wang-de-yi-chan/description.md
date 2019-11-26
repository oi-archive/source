
# Content

哈丁国的国王一生善于管理，勤于政务，于是聚积了大量的财富。但他众多的孩子都不争气，相互间时常勾心斗角，却没有一个真正能接受国王传位的人。为了避免将来某儿子一人独揽大权，又出于不能让权力过度分散的考虑，临终前，国王决定将他一生的财富打造出了一条很大的金块链，这条金块链的形状比较特别，它由$n$大块的黄金组成，国王准备了$n-1$条链条，将某些相邻的两块大黄金用链条连接起来，最后构成一条连通的金块链，如下图：

![title](/source/lutece/guo-wang-de-yi-chan/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODU0LzIwMTQwOTE2MjEzNDU2NTE1My5qcGc=.jpg)

国王对每块黄金编上号（$1\sim n$），然后立下了遗嘱：
1. 儿子们按照年龄大小顺序，在现存的金块链中获得遗产。
2. 对于某个儿子，他可以在现存金块链中剪掉某条链条，获得不超过现有金块总数一半的那一部分。
3. 某个儿子获得他那部分金块后，剩下的部分由他后面的弟弟们继续操作。
4. 最后一个儿子获得剩下的那些金块，国王将保证每个儿子都能获得遗产。

国王的儿子们都是贪婪的，他们都会选取使自己得到最多的金块的那条链条来剪，当然，有时选取的方案不是唯一的，但是儿子们都会选择使自己获得的“金块组编号”最小的那一条链来剪。“金块组编号”大小定义为：对于长度相同为L的两个有序数组$A$和$B$，$A<B$当且仅当存在一个整数$i$($0<i\le L$)，使得$A\_1=B\_1,\cdots ,A\_{i-1}=B\_{i-1}$且$A\_i<B\_i$。

# Standard Input

输入数据的第$1$行为一个整数$n$($1\le n\le 30000$)和一个整数$k$($1\le k\le 100$)，分别表示金块的总数与国王儿子的数量。接下来$n-1$行，每行两个整数$x$和$y$，表示编号为$x$的金块与编号为$y$的金块用链条连接起来。

# Standard Output

输出数据只有一行，包含有$k$个整数，分别表示每个儿子获得金块的数量(由大儿子到最小的儿子)。

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
<tr><td>6 3
1 2
2 3
3 4
2 5
3 6</td><td>3 1 2</td></tr></table>


# Constraints



# Note



# Source


