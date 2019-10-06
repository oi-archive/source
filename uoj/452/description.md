# 题目描述

<pre><code>“有的人浅薄,有的人金玉其表败絮其中。
 有一天，你会遇到一个彩虹般绚烂的人，
 当你遇到这个人后，会觉得其他人都只是浮云而已。”                                    
                                                     ——《怦然心动》</code></pre>
<p>Y看完这部电影，产生了很大共鸣。 </p>
<p>在Y眼中，y就是这个彩虹般绚烂的人。</p>
<p>可是Y并不清楚y的想法，对自己也没有自信。</p>
<p>Y常常这样安慰自己，现在时机未到，要等待，要有耐心。</p>
<p>日有所思，夜游所梦，某一天，Y在梦境中遇到了y，他傻站在y的面前，想说些什么却又说不出口。突然，天空中传来一个声音&#34;这不过是个梦&#34;，他眼前的y便如烟云一般消散了，只见一个背后长有翅膀的长者从远处缓缓靠近。</p>
<p>此人自称是爱神丘比特，Y对此深信不疑，甚至大呼“我从来不迷信，只信爱神”。</p>
<p>爱神告诉Y“我可以帮你向y表白，但有一个条件”，爱神随即写下两个函数: 
$$
f(i)=(k∗i)^{k∗i∗[i是素数]}\\
(i\text{是素数时},f(i)=(k∗i)^{k∗i}\text{否则}f(i)=1)\\
g(i)=(k∗i)^{k∗\varphi(i)}\\
(\varphi(i)表示小于或等于i的数中与i互质的数的个数)
$$</p>
<p>接着又写下了四个式子: 
$$
1.\prod\limits_{i=1}^n f(i)\\
2.\prod\limits_{i=1}^n g(i)\\
3.\prod_{i=1}^n\prod_{j=1}^{\lfloor \frac{n}{i}\rfloor}f(j)^{\lfloor\frac{n}{j}\rfloor}\\
4.\prod_{i=1}^n\prod_{j=1}^{\lfloor \frac{n}{i}\rfloor}g(j)^{\lfloor\frac{n}{j}\rfloor}\\
$$
爱神给出了n和k的值，并要求Y回答前m个式子的值，答案对1000000007取模。</p>

# 输入格式


<p>一行3个正整数n,k,m，如题所述。</p>

# 输出格式


<p>  输出m行，每行一个整数，第i行的整数表示编号为i的式子的答案。</p>

# 样例一


<h4>input</h4>
<pre><code>233 233 4</code></pre>
<h4>output</h4>
<pre><code>591645143
124162718
818917434
181711594</code></pre>

# 样例二


<h4>input</h4>
<pre><code>166666667 1 2</code></pre>
<h4>output</h4>
<pre><code>734298437
771861883</code></pre>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>$k\le$</th><th>$m\le$</th><th>时间限制</th><th>空间限制</th><th>分数</th></tr></thead><tbody><tr><td>1</td><td>$10^7$</td><td>$10^9$</td><td>4</td><td>3s</td><td>512MB</td><td>9</td></tr><tr><td>2</td><td>$10^9$</td><td>1</td><td>1</td><td>2s</td><td>512MB</td><td>9</td></tr><tr><td>3</td><td>$10^9$</td><td>1</td><td>2</td><td>2s</td><td>512MB</td><td>11</td></tr><tr><td>4</td><td>$10^9$</td><td>$10^9$</td><td>2</td><td>2s</td><td>512MB</td><td>13</td></tr><tr><td>5</td><td>$10^9$</td><td>$10^9$</td><td>3</td><td>2s</td><td>512MB</td><td>11</td></tr><tr><td>6</td><td>$10^9$</td><td>$10^9$</td><td>4</td><td>4s</td><td>512MB</td><td>13</td></tr><tr><td>7</td><td>$10^9$</td><td>$10^9$</td><td>4</td><td>3s</td><td>512MB</td><td>19</td></tr><tr><td>8</td><td>$10^9$</td><td>$10^9$</td><td>4</td><td>2s</td><td>512MB</td><td>15</td></tr></tbody></table></div>


# 下载


<p><a href="/download.php?type=problem&amp;id=452">样例数据下载</a></p>
