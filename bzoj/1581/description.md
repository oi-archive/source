
# Description

<div class="content"><div><span style="font-size: medium">    约翰在屋顶上唱歌，以此来与奶牛们交流．但是奶牛们的听力很奇怪，她们只能听到约翰的歌声变成0和1构成的信息串时的样子．    约翰的声音里有N(1≤N≤2000)个0或1，奶牛听到的也是N个，而且0和1的数量不会变化，但是一部分0或1可能偏离原来的位置，这就是约翰的歌声在传输时发生的“传输延迟”现象．0或1的偏离距离不会超过D(O≤D&lt;N)，也就是说某一个码的原本位置和现在的位置之差的绝对值不大于D.</span></div>
<div><span style="font-size: medium">    比如，对于0110，D=1，传输延迟发生后可能出现0101，0110，1001，1010这四种串．</span></div>
<div><span style="font-size: medium">    给出约翰歌声的01串形式和一个整数K(1≤K≤108)，请计算传输延迟发生后一共有多少种可能的01串，以及其中第K大的串是什么．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行输入 n , d , k 第二行输入那个N位的数字,用二进制表示 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">分别输出受到整数的种数(将结果Mod 100,000,000)，和这些整数第K小的那个</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1 3<br/>
0110<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1001<br/>
</span></div>

# Hint

<div class="content"><p></p><p>1&lt;=n&lt;=2000 0&lt;=k<n body=""></n></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

