# 题目背景

Tyvj全新升级至JoyOI！欢迎您参与JoyOI公测，本题用于测试JoyOI全新评测机以及全新Web门户~

# 题目描述

请编程实现计算两个正整数之和。

# 输入格式

输入包括一行，两个正整数a和b，用一个空格分隔。

# 输出格式

输出内容包括一行，即a+b的结果。

# 样例程序

C:

```
#include <stdio.h>

int main()
{
    int a, b;
    scanf("%d%d", &a, &b);
    printf("%d\n", a + b);
}
```

C++:

```
#include <iostream>

using namespace std;

int main()
{
    int a, b;
    cin >> a >> b;
    cout << a + b << endl;
}
```

Pascal:

```
var a, b:longint;
begin
    readln(a, b);
    writeln(a + b);
end.
```

C#:

```
using System;
using System.Linq;

class Program {
    public static void Main() => Console.WriteLine(Console.ReadLine().Split().Select(int.Parse).Sum());
}
```

Python 3:

```
print(sum(map(int, input().split())))
```

VB.NET:

```
Module Program
    Sub Main()
        Console.WriteLine(Console.ReadLine().Split(" ").Select(Function(x) Convert.ToInt32(x)).Sum())
    End Sub
End Module
```

Java:

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) throws IOException {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println(a + b);
    }
}
```

# 数据范围约束
0 ＜ a, b < 32768# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1 2</td><td>3</td></tr><tr><td>5 5</td><td>10</td></tr></table>
