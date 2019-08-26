
# Description

<div class="content"><div>人们选择手机号码时都希望号码好记、吉利。比如号码中含有几位相邻的相同数字、不含谐音不</div>
<div>吉利的数字等。手机运营商在发行新号码时也会考虑这些因素，从号段中选取含有某些特征的号</div>
<div>码单独出售。为了便于前期规划，运营商希望开发一个工具来自动统计号段中满足特征的号码数</div>
<div>量。</div>
<div>工具需要检测的号码特征有两个：号码中要出现至少3个相邻的相同数字，号码中不能同</div>
<div>时出现8和4。号码必须同时包含两个特征才满足条件。满足条件的号码例如：13000988721、</div>
<div>23333333333、14444101000。而不满足条件的号码例如：1015400080、10010012022。</div>
<div>手机号码一定是11位数，前不含前导的0。工具接收两个数L和R，自动统计出[L,R]区间</div>
<div>内所有满足条件的号码数量。L和R也是11位的手机号码。</div></div>

# Input

<div class="content"><div>输入文件内容只有一行，为空格分隔的2个正整数L,R。</div>
<div>10^10 &lt; =  L &lt; =  R &lt; 10^11</div></div>

# Output

<div class="content"><p>输出文件内容只有一行，为1个整数，表示满足条件的手机号数量。</p></div>

# Sample Input

<div class="content"><span class="sampledata">12121284000 12121285550</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
样例解释<br/>
满足条件的号码： 12121285000、 12121285111、 12121285222、 12121285333、 12121285550</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

