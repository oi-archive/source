
# Description

<div class="content"><p>　　“余”人国的国王想重新编制他的国家。他想把他的国家划分成若干个省，每个省都由他们王室联邦的一个成<br/>
员来管理。他的国家有n个城市，编号为1..n。一些城市之间有道路相连，任意两个不同的城市之间有且仅有一条<br/>
直接或间接的道路。为了防止管理太过分散，每个省至少要有B个城市，为了能有效的管理，每个省最多只有3B个<br/>
城市。每个省必须有一个省会，这个省会可以位于省内，也可以在该省外。但是该省的任意一个城市到达省会所经<br/>
过的道路上的城市（除了最后一个城市，即该省省会）都必须属于该省。一个城市可以作为多个省的省会。聪明的<br/>
你快帮帮这个国王吧！</p></div>

# Input

<div class="content"><p>　　第一行包含两个数N，B（1&lt;=N&lt;=1000, 1 &lt;= B &lt;= N）。接下来N－1行，每行描述一条边，包含两个数，即这<br/>
条边连接的两个城市的编号。</p></div>

# Output

<div class="content"><p>　　如果无法满足国王的要求，输出0。否则输出数K，表示你给出的划分方案中省的个数，编号为1..K。第二行输<br/>
出N个数，第I个数表示编号为I的城市属于的省的编号，第三行输出K个数，表示这K个省的省会的城市编号，如果<br/>
有多种方案，你可以输出任意一种。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 2 <br/>
1 2 <br/>
2 3 <br/>
1 8 <br/>
8 7 <br/>
8 6 <br/>
4 6 <br/>
6 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3 <br/>
2 1 1 3 3 3 3 2 <br/>
2 1 8 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

