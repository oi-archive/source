<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个静谧安详的下午，无聊的YPZ小朋友正一个人坐在教室发呆.无聊的同时ta开始在本子上画括号（注：括号只有(),&lt;&gt;,{},[]），画了很久很久。善于思考的YPZ突然想到一个问题：这些括号是否匹配呢？于是ta就制定了一个匹配原则。匹配原则如下：如果括号有互相包含的形式，从内到外必须是&lt;&gt;,(),[],{}。例如：YPZ写下[()],你应该回答:YES,而YPZ写下([]),([)]你都应该回答NO。YPZ认为这个任务太难了，所以就请求你帮ta完成这一任务。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个整数n,表示以下有多少个由括号组成的字符串。<br></p><p>接下来n行，每行都是一个由扩号组成的长度不超过<span style="">360</span>的字符串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>以下有n行，每行都是YES或NO。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p><p>&lt;]</p><p>{)(}</p><p>[]</p><p>&lt;()&gt;</p><p>[&lt;}]</p><p>{()}</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">NO</p><p style="">NO</p><p>YES</p><p>NO</p><p>NO</p><p>YES</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=100.<br></p><p>字符串长度不超过360.</p><p><br></p>
</div>
</div>