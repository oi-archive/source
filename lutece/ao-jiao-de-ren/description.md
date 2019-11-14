
# Content

有 $N$ 个傲娇的人，你要指派他们去完成工作。`只有当现在被指派的人完成了工作，你才能指派下一个。`每个人完成工作需要花费 $T_i$ 分钟，但！他们都好傲娇，他们都希望你马上就指派他，如果你拖延了 $t$ 分钟才指派他，那么就需要付给他 $t\cdot C_i$ 元钱作为补偿。问，最少需要花费多少元钱才能去指派所有傲娇的人？

# Standard Input

第一行输入一个整数$N\ (1 \leq N \leq 10^5)$

第二行输入四个种子数$a，b，c，d\ (1 \leq a，b，c，d \leq 10007)$。你需要通过这4个种子数来得到 $T_i$ 和 $C_i$，方法如下：
```
const int mod=10007;
typedef long long ll;
void getdata(int a,int b,int c,int d,int N,int *T,int *C){
    T[0]=C[0]=0;
    for(int i=1;i<=N;i++){
        T[i]=(T[i-1]*a+b)%mod+1;
        C[i]=(C[i-1]*c+d)%mod+1;
    }
}
```

# Standard Output

第一行输出一个整数，表示最少需要花费多少钱去指派这些傲娇的人。

第二行输出 $N$ 个整数，表示每次指派哪个人去，即按指派顺序输出被指派人的编号。比如，有5个人，按顺序指派他们，则输出"1 2 3 4 5"。`如果有多解，输出字典序最小解。`

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
<tr><td>5
1 1 1 1</td><td>340
1 2 3 4 5</td></tr><tr><td>5
1 10007 123 12</td><td>60366
3 5 2 4 1</td></tr><tr><td>10
1 2 3 3</td><td>947511
9 10 7 8 6 5 4 3 2 1</td></tr><tr><td>7
10007 10007 10007 10007</td><td>21
1 2 3 4 5 6 7</td></tr></table>


# Constraints



# Note



# Source


