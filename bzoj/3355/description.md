
# Description

<div class="content"><div><span style="font-size: medium">    约翰的N(1≤N≤1500)头牛排成一行挤奶时，有确定的顺序．牛被编成连续的号码1．.N,他拥有L条关于奶牛顺序的信息，所有的信息都写成“A在B的前面”这样的形式，而且他知道最后一条是多余的．他觉得，有些冗余信息可以由其他信息推出，可以对这些信息进行精减．请帮助约翰删除尽可能多的冗余信息，但要保证能推出原有的顺序．可以保证的是，答案唯一，且最初的信息没有矛盾，如A在B前面，B在A前面．</span></div></div>

# Input

<div class="content"><div> </div>
<div><span style="font-size: medium">    第1行：两个整数N和L．</span></div>
<div><span style="font-size: medium">    第2到L+1行：每行两个整数X和Y(1≤X，y≤N)，表示X在Y前．无重复．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    第1行：整数U.</span></div>
<div><span style="font-size: medium">    第2到U+I行：输出精减后的信息，每行2个数字，按第1列数字排序．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
3 5<br/>
4 2<br/>
5 2<br/>
2 1<br/>
3 1<br/>
4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2 1<br/>
3 5<br/>
4 2<br/>
5 2</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">    3在1前，4在1前可推．输出的每一行，不能被其他推出．</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Green">Green</a></p></div>

