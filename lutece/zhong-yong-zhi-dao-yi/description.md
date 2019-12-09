
# Content

读入三个整数$a$、$b$、$c$，找出中间数并输出。
中间数是这样定义的：若三数不相等，则第2大的数是中间数；若有两个数相同，则最大数是中间数。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 2000$），表示测试数据的组数。随后有$T$行输入，每行是一组测试数据，由整数$a$、$b$和$c$构成，且相邻两整数间有一个空格。$-2^{31}<a,b,c<2^{31}$。

# Standard Output

对应每组输入，输出这一行三个数的中间数。

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
<tr><td>3
2 3 4
12 35 12
13 13 10</td><td>3
35
13</td></tr></table>


# Constraints



# Note

1. 提交前若程序中有标准输入输出重定向（或文件操作）语句，请删除或注释掉。比如：`freopen`等。
2. 提交前若程序中有停顿语句，请删除或注释掉。比如：`system(“pause”)`、`getch()`等。
3. 处理每一组测试数据前，建议变量恢复到初始状态，以免受前一组数据处理的影响。

对于本题给予的输入格式，你可以参考以下代码：

```
#include <stdio.h>

int main()
{
  int a,b,c,i,T;
  scanf("%d",&T);
  for(i=0;i<T;i++)
  {
    //处理当前组数据 
  }
  return 0;
}
```
或者
```
#include <stdio.h>

int main()
{
  int a,b,c,T;
  scanf("%d",&T);
  while(T--)
  {
    //读入并处理当前组数据 
  }
  return 0;
}
```

# Source


