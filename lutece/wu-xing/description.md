
# Content

大家都知道liverliu有在课堂上睡觉的坏习惯。有一天，liverliu又在上课时睡了，老师非常生气，当然后果也非常严重。老师知道liverliu非常讨厌几何，所以专门出了几何题目来惩罚他。老师给出一个$n$，表示一个$n$重的五角星（如图，分别为1重，2重，3重五角星），要liverliu给出这个图形的锐角有多少个。由于liverliu经常上课睡觉，常年不听讲（小朋友们不要学他），所以liverliu的成绩很差。这下liverliu吓坏了，因为老师说了如果他做不出来就要请家长，这下他就只好向你求助，请你写一个程序让他能够度过难关~

![title](/source/lutece/wu-xing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjk5LzIwMTQwNDA5MjEzNTQzMjk3NC5qcGc=.jpg)

# Standard Input

输入的第一行是一个整数$t$，表示有$t$组数据。接下来有$t$行，每行一个整数$n$($0<n<40$),表示$n$重五角星。

# Standard Output

对于第$k$组数据，输出一行。先输出`Case #k: ` ，随后输出该图形的锐角的个数。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
1
2</td><td>Case #1: 5
Case #2: 15</td></tr></table>


# Constraints



# Note

对于一个角，我们定义在图形内部的角度为该角的度数。

如图所示。

![title](/source/lutece/wu-xing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjk5LzIwMTQwNDA5MjEzNjQzODY3NS5qcGc=.jpg)

**答案可能会超过`int`范围。**

需使用$64$位整型，一个`A+B`的例子

#### for GNU C++
```
#include <iostream>
using namespace std;
int main()
{
  long long a,b;
  cin >> a >> b;
  cout << a+b << endl;
  return 0;
}
```
#### for GNU C
```
#include <stdio.h>
int main()
{
  long long a,b;
  scanf("%lld %lld",&a, &b);
  printf("%lld\n",a+b);
  return 0;
}
```

# Source


