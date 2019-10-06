# 题目描述

<p>跳蚤OS 是跳蚤国自主研发的功能强大的操作系统。</p>
<p>跳蚤OS的文件系统与普通的文件系统类似，是个文件夹套文件夹的结构。文件系统根目录称为“$\texttt{/}$”。我们可以用文件路径来表明文件所在的位置，比如“$\texttt{/flea/uoj}$”表示根目录下的$\texttt{flea}$文件夹下的$\texttt{uoj}$文件。</p>
<p>跳蚤OS的文件系统中。快捷方式是一种特殊的文件夹，点开该快捷方式相当于打开该快捷方式指向的文件夹。</p>
<p>比如，如果有一个快捷方式 “$\texttt{/etc/abc}$”，该快捷方式指向 “$\texttt{/flea/def}$”这个文件夹，那么一旦访问“$\texttt{/etc/abc}$”就相当于访问“$\texttt{/flea/def}$”。</p>
<p>这一天，跳蚤国王正在使用跳蚤OS。初始时文件系统为空，只有根目录。他每次会进行如下操作：</p>
<ol><li>首先，随便写出两个文件路径 $s$ 和 $t$。</li>
<li>接着，如果位置 $t$ 处不存在文件，则在该处创建一个空文件夹。</li>
<li>最后，跳蚤国王<strong>保证 $s$ 这个位置没有文件</strong>，于是在 $s$ 处创建一个快捷方式指向 $t$。如果 $t$ 是个快捷方式，那么 $s$ 将指向 $t$ 所指向的文件夹。</li>
</ol><p>上文所说的“创建”在父级目录不存在的时候要一并创建其父级目录。比如，假设文件系统里只有 “$\texttt{/v}$” 这个文件夹，那么现在我创建 “$\texttt{/v/flea/king/qaq}$” 就会在文件系统中新增三个文件夹：“$\texttt{/v/flea}$”, “$\texttt{/v/flea/king}$”, “$\texttt{/v/flea/king/qaq}$”。</p>
<p>跳蚤国王进行了 $n$ 次这样的操作后，开始不断问他的助手伏特：现在我如果在 $p$ 这个路径处创建一个文件夹（如果已存在则不创建），那么这个文件夹的真实路径是什么？</p>
<p>于是伏特只好向你求助了，请你帮一帮他吧！<strong>请参照样例来更清晰地理解题意。</strong></p>

# 输入格式


<p>第一行两个正整数$n, m$，表示跳蚤国王进行了$n$个操作，提了$m$个问题。</p>
<p>接下来$n$行每行两个用空格隔开的字符串$s, t$，表示跳蚤国王的一次操作。</p>
<p>接下来 $m$ 行每行一个字符串 $p$ 表示跳蚤国王的一个询问。</p>
<p>保证所有的 $s, t, p$ 都是合法的文件路径。即，文件夹名一定是由小写英文字母组成的非空字符串，路径名一定形如“$\texttt{/xxx/xxx/xxx/.../xxx}$”这样子。保证当路径不为根目录“$\texttt{/}$”时，路径不以“$\texttt{/}$”结尾。</p>

# 输出格式


<p>对于跳蚤国王的每个询问输出真实路径。</p>

# 样例一


<h4>input</h4>
<pre>6 5
/root /
/duliu /picks
/vfk /vfleaking
/orz/orz/orz /duliu
/otl /duliu/duliu
/vfk/sb /vfleaking
/vfk/sb/nothing/nothing
/orz
/orz/orz/orz
/qaq
/otl

</pre>

<h4>output</h4>
<pre>/vfleaking/nothing/nothing
/orz
/picks
/qaq
/picks/duliu

</pre>

<h4>explanation</h4>
<p>创建的快捷方式分别为：</p>
<ul><li>$\texttt{/root} \rightarrow \texttt{/}$</li>
<li>$\texttt{/duliu} \rightarrow \texttt{/picks}$</li>
<li>$\texttt{/vfk} \rightarrow \texttt{/vfleaking}$</li>
<li>$\texttt{/orz/orz/orz} \rightarrow \texttt{/picks}$</li>
<li>$\texttt{/otl} \rightarrow \texttt{/picks/duliu}$</li>
<li>$\texttt{/vfleaking/sb} \rightarrow \texttt{/vfleaking}$</li>
</ul>
# 样例二


<h4>input</h4>
<pre>2 3
/ba/la /
/w/o/w /w
/ba/la/ba/la/ba/la/ba/la/ba/la/ba/la/ba/la
/ba/la/ba/la/ba/la/ba/la/ba/la/ba/la/ba/la/ba
/w/o/w/o/w/o/w/o

</pre>

<h4>output</h4>
<pre>/
/ba
/w/o

</pre>


# 样例三


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$\leq 200$</td><td rowspan="10">$\leq 10$</td><td rowspan="3">保证单个字符串长度不会超过 $40$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\leq 20000$</td><td rowspan="3">保证每个输入的路径字符串中仅包含一个“$\texttt{/}$”且位于字符串开头。<br/> 保证单个字符串长度不超过$15$。</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\leq 20000$</td><td rowspan="4"></td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，输入中路径字符串总长度不会超过 $5 \times 10^5$。</p>
<p><strong>时间限制：</strong>$1 \texttt{s}$</p>
<p><strong>空间限制：</strong>$256 \texttt{MB}$</p>
<p><br/></p>
<p>为了防止有些同学看晕了，我还是再罗嗦几句。下面的路径名都是非法的：</p>
<ul><li>$\texttt{/orz/}$</li>
<li>$\texttt{/orz//otl}$</li>
<li>$\texttt{/233}$ （注意，只能含有小写英文字母）</li>
</ul><p>下面的路径名都是合法的：</p>
<ul><li>$\texttt{/}$</li>
<li>$\texttt{/orz/otl/oorrzz/oottll}$</li>
<li>$\texttt{/a}$</li>
</ul>
# 下载


<p><a href="/download.php?type=problem&amp;id=13">样例数据下载</a></p>
