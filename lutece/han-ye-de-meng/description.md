
# Content

一天，韩爷去百度面试，面试官给了他这么一个问题。
>#####给你2万个字符串，每个字符串长度都是100，然后把2万个字符串丢入一个 set< string \>g 中，问最终set里含有多少个元素？
>#####g 是一个用来存储字符串、具有去重功能的容器，即相同字符串在 g 中只能保留一个。
>#####两个字符串相等，当且仅当，长度一样且对应位置的字符都一样。

韩爷前晚没睡好，随手写了一个程序交给面试官，然后就gg了。
```
#include<iostream>
#include<string>
#include<set>
using namespace std;
string s;
set<string>g;
int main(){
    for(int k=1;k<=20000;k++){
        cin>>s;
        g.insert(s);
    }
    cout<<g.size()<<endl;
    return 0;
}
```
韩爷醒来之后，发现这只是一个梦（还好只是个梦）。他回忆起梦中的面试官给他的内存限制和时间限制非常低，这么做肯定过不了，那么，现在你不在梦中，你能解决这个问题么？

# Standard Input

单case

每个case有且只有2万行，每一行包含一个字符串，每行字符串的长度都为100 `（样例除外）`

字符集：大写英文字母（A－Z），小写英文字母（a－z），数字（0－9）

# Standard Output

输出一个整数，表示最终set里含有多少个元素。

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
<tr><td>aaAa
aaAa
bbbb
1234
bbbb
bbbb
ee09</td><td>4</td></tr></table>


# Constraints



# Note

`样例只是样例，不在test中`

`注意时间限制和内存限制非常低`

# Source


