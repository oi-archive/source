
# Description

<div class="content"><p><span style="font-size: medium">Phorni 是一个音之妖精,喜欢在你的打字机上跳舞。<br/>
一天,阳光映射到刚刚淋浴过小雨的城市上时,Phorni 用魔法分裂出了许多个幻影,从 1 到 n 编号。<br/>
她的每一个幻影都站在打出的字符串的一个位置上,多个幻影可以站在同一个位置上。<br/>
每一个幻影代表的字符串即为从它站立位置开始的后缀,注意站立位置是从右往左数的。<br/>
让我们形式化地描述一下,若第 i 个幻影站在 Pi 上,那么它所代表的字符串就是 S[L-Pi+1…L],其中 L 是字符串 S 的长度。<br/>
每一次,她会选一段编号区间 [l..r],而编号在这个区间中的幻影中,字典序最小的一个将跳一支舞,若有多个幻影字典序相同,选编号最小的。<br/>
当然由于 Phorni 还会在打字机上跳动,所以有时字符串的前面会加入一个字符。<br/>
当然这个打字机是带加密功能的。<br/>
字典序的比较:<br/>
将两个字符串逐位比较,长度不足的向后补 0 ( 0 小于任何字符) 。直到比出大小或判定相等。<br/>
比如 “pho” &gt; “ph” , “pb” &gt; “pab” 。<br/>
下标从 1 开始,保证涉及到的所有字符都为小写字母。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入共 m + 3 行,<br/>
第一行为三个整数 n, m, len, type, 分别代表幻影个数,操作次数,初始字符串长度。type = 1 时表示所有的字符都经过了加密。<br/>
第二行为初始字符串 S 。<br/>
第三行,n 个数 Pi ,意义如题面所示。<br/>
接下来 m 行,每行表示一个操作。<br/>
1. I c 若 type = 0 表示在字符串前面加入第 c + 1 个小写字母,若 type = 1 则表示加入第 (c xor lastans) + 1 个小写字母,lastans 表示上一次的答案,初始为 0 。<br/>
2. C x pos 表示第 x 个幻影跳到了从右向左数 pos 的位置上。<br/>
3. Q l r 表示询问[l..r] 。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每个询问操作输出一行,表示去跳舞的幻影编号。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 5 0<br/>
horni<br/>
3 2 5<br/>
I 15<br/>
C 1 6<br/>
Q 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
样例解释</span></p><br/>
<p><span style="font-size: medium">前2个操作后，三个幻影代表的后缀分别为phorni,ni,horni。</span></p><br/>
<p><span style="font-size: medium">数据范围与约定</span></p><br/>
<p><span style="font-size: medium">数据范围与约定<br/><br/>
对于 100% 的数据, 1 ≤ n ≤ 500000, 1 ≤ m ≤ 800000, 1 ≤ Pi ≤ len ≤ 100000。<br/><br/>
若 type = 0,保证 I 操作中 0 ≤ c ≤ 25;否则 0 ≤ c xor lastans ≤ 25 。<br/><br/>
C 操作中 1 ≤ x ≤ n, 1 ≤ pos ≤ 当前字符串长度。<br/><br/>
Q 操作中 1 ≤ l, r ≤ n,I 操作数量约占总操作数量的 1/5,C,Q 操作数量约各占总操作数量的 2/5。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Shinrein祭 #1">Shinrein祭 #1</a></p></div>

