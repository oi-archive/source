
# Content

读入三个整数$a$、$b$、$c$，找出中间数并输出。若有两个数相同，最大数作为中间数。

# Standard Input

有多组测试数据。每一组测试数据只有一行，分别为整数$a$、$b$和$c$，相邻两数之间有一个空格。该行没有其它多余的符号。如果一行三个数字均为$0$，表示输入结束，该行不需要处理。$-2^{31}<a,b,c<2^{31}$。

# Standard Output

对应每组输入，输出一行三个数的中间数。该行不能有其它多余的符号。

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
<tr><td>2 3 4
12 35 12
13 13 10
0 0 0</td><td>3
35
13</td></tr></table>


# Constraints



# Note

1. 提交前若程序中有标准输入输出重定向（或文件操作）语句，请删除或注释掉。比如：`freopen`等。
2. 提交前若程序中有停顿语句，请删除或注释掉。比如：`system(“pause”)`、`getch()`等。
3. 处理每一组测试数据前，建议变量恢复到初始状态，以免受前一组数据处理的影响。

对于本题规定的输入格式，你可以参考以下代码：
```
#include <stdio.h>

int main()
{
  int a,b,c,i,T;
  while(scanf("%d%d%d",&a,&b,&c))
  {
    if(a==0 && b==0 && c==0)
      break;
    //读入并处理当前组数据 
  }
  return 0;
}
```

# Source


