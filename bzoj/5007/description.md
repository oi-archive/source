
# Description

<div class="content"><div>在如今的网络中，TCP是一种被广泛使用的网络协议，它在传输层提供了可靠的通信服务。众所周知，网络是存在</div>
<div>时延的，例如用户先后向服务器发送了两个指令op1和op2，并且希望服务器先处理指令op1，再处理指令op2；但由</div>
<div>于网络时延，这两个指令可能会失序到达，而导致服务器先执行了指令op2，这是我们不希望看到的。TCP协议拥有</div>
<div>将失序到达的报文按顺序重组的功能，一种方法是给每一个报文打上一个时间戳。而你今天要实现的功能比这个要</div>
<div>简单很多。我们需要你维护一个服务器，这个服务器的功能是一个简单的栈，你会接收三种用户的指令：</div>
<div>push x t --- 表示将x元素入栈，这条指令的时间戳为t</div>
<div>pop t --- 表示将栈顶元素弹出，这条指令的时间戳为t</div>
<div>peak t --- 用户询问现在栈顶元素的值，这条指令的时间戳为t</div>
<div></div>
<div>当一条时间戳为t的指令到达时，你需要进行如下处理：</div>
<div>1.将所有之前执行的时间戳大于t的push和pop指令全部撤销</div>
<div>2.执行当前这条指令</div>
<div>3.按时间戳顺序重新执行在第1步被撤销的指令</div>
<div></div>
<div>注意你不需要撤销以及重新执行之前已经执行过的peak指令</div>
<div>也就是说每一条peak指令只有在它到达的时候会被执行一次。</div>
<div></div>
<div>我们保证每一条指令的时间戳都是唯一的；</div>
<div>若你在需要执行一条pop指令时发现当前栈为空，则当前你可以忽略这条指令。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数n，表示指令总数。</div>
<div>接下来n行按指令到达服务器的顺序给出每一条指令，有三种类型</div>
<div>push x t</div>
<div>pop t</div>
<div>peak t</div>
<div>1 &lt;= n &lt;= 300000，0 &lt;= x，t &lt;= 1000000000</div>
<p></p></div>

# Output

<div class="content"><div>对于每一条peak指令，输出对应的答案占一行；若栈为空，输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
push 100 3<br/>
push 200 7<br/>
peak 4<br/>
push 50 2<br/>
pop 5<br/>
peak 6<br/>
peak 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">100<br/>
50<br/>
200</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

