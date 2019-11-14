
# Description

<div class="content"><div>A 国共有 n 座城市，这些城市由 n-1 条道路相连，使得任意两座城市可以互达，且路径唯一。每座城市都有一个</div>
<div>幸运数字，以纪念碑的形式矗立在这座城市的正中心，作为城市的象征。一些旅行者希望游览 A 国。旅行者计划</div>
<div>乘飞机降落在 x 号城市，沿着 x 号城市到 y 号城市之间那条唯一的路径游览，最终从 y 城市起飞离开 A 国。</div>
<div>在经过每一座城市时，游览者就会有机会与这座城市的幸运数字拍照，从而将这份幸运保存到自己身上。然而，幸</div>
<div>运是不能简单叠加的，这一点游览者也十分清楚。他们迷信着幸运数字是以异或的方式保留在自己身上的。例如，</div>
<div>游览者拍了 3 张照片，幸运值分别是 5，7，11，那么最终保留在自己身上的幸运值就是 9（5 xor 7 xor 11）。</div>
<div>有些聪明的游览者发现，只要选择性地进行拍照，便能获得更大的幸运值。例如在上述三个幸运值中，只选择 5 </div>
<div>和 11 ，可以保留的幸运值为 14 。现在，一些游览者找到了聪明的你，希望你帮他们计算出在他们的行程安排中</div>
<div>可以保留的最大幸运值是多少。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含 2 个正整数 n ，q，分别表示城市的数量和旅行者数量。第二行包含 n 个非负整数，其中第 i 个整</div>
<div>数 Gi 表示 i 号城市的幸运值。随后 n-1 行，每行包含两个正整数 x ，y，表示 x 号城市和 y 号城市之间有一</div>
<div>条道路相连。随后 q 行，每行包含两个正整数 x ，y，表示这名旅行者的旅行计划是从 x 号城市到 y 号城市。N</div>
<div>&lt;=20000,Q&lt;=200000,Gi&lt;=2^60</div>
<div></div></div>

# Output

<div class="content"><p> 输出需要包含 q 行，每行包含 1 个非负整数，表示这名旅行者可以保留的最大幸运值。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 <br/>
11 5 7 9 <br/>
1 2 <br/>
1 3 <br/>
1 4 <br/>
2 3 <br/>
1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">14 <br/>
11</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

