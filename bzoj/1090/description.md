
# Description

<div class="content"><p><span style="font-size: medium;">折叠的定义如下： 1. 一个字符串可以看成它自身的折叠。记作S  S 2. X(S)是X(X&gt;1)个S连接在一起的串的折叠。记作X(S)  SSSS…S(X个S)。 3. 如果A  A’, BB’，则AB  A’B’ 例如，因为3(A) = AAA, 2(B) = BB，所以3(A)C2(B)  AAACBB，而2(3(A)C)2(B)AAACAAACBB 给一个字符串，求它的最短折叠。例如AAAAAAAAAABABABCCD的最短折叠为：9(A)3(AB)CCD。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium;">仅一行，即字符串S，长度保证不超过100。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium;">仅一行，即最短的折叠长度。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">NEERCYESYESYESNEERCYESYESYES</span></div>

# Sample Output

<div class="content"><span class="sampledata">14</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium;">一个最短的折叠为：2(NEERC3(YES))</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

