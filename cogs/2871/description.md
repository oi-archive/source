

# 题目描述



# 输入格式



# 输出格式



# 样例输入


<pre>2 2 3
1 1
2 2
1 2
</pre>

# 样例输出


<pre>1
1
4</pre>

# 样例解释


<p align="center">
$\begin{bmatrix}1&amp;2\\3&amp;4\end{bmatrix}\Rightarrow\begin{bmatrix}&amp;2\\3&amp;4\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;\\3&amp;4\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;1\end{bmatrix}$
</p>
<p align="center">
$\begin{bmatrix}2&amp;4\\3&amp;1\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;4\\3&amp;1\end{bmatrix}$
</p>
<p align="center">
$\begin{bmatrix}2&amp;4\\3&amp;1\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;\\3&amp;1\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;\\3&amp;1\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;1\\3&amp;\end{bmatrix}\Rightarrow\begin{bmatrix}2&amp;1\\3&amp;4\end{bmatrix}$
</p>

# 提示



# 来源


<p>
NOIP 2017 Day 2 T3
</p>
