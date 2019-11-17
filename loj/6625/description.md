
# 题目描述

一年半前，在 `nantf` 是个连线性筛和 $O(\sqrt{n})$ 判断素数都不会的蒟蒻时，他遇到了这样一道题：

> 给定正整数 $n$，求在 $1$ 到 $n$ 之间有多少个质数。  
> $1\le n\le 10^{11}$。

`nantf` 当然知道暴力会超时，但是他也没有办法。

突然，他想到了：判断素数的复杂度是跑不满的！

于是他打了下面的暴力：（`C++` 代码）
```cpp
typedef long long ll;
bool check(ll x){
    if(x == 1) return false;
    for(ll i = 2; i < x; i++)
        if(x % i == 0) return false;
    return true;
}
int main(){
    ll n, ans = 0;
    cin >> n;
    for(ll i = 1; i <= n; i++)
        if(check(i)) ans++;
    cout << ans << endl;
}
```
虽然这个程序复杂度跑不满 $O(n^2)$，但是它还是毫无疑问地挂了。

`nantf` 不服气，他把 `check` 函数改写了一下：
```cpp
typedef long long ll;
ll cnt = 0;
bool check(ll x){
    if(x == 1) return false;
    for(ll i = 2; i < x; i++){
        cnt++;
        if(x % i == 0) return false;
    }
    return true;
}
```
众所周知程序结束时 $cnt$ 的值能反应程序的实际复杂度。

所以 `nantf` 找到了你，想让你帮忙算一下程序结束时 $cnt$ 的值。**不需要考虑溢出。**

---
以上是一年半前 `nantf` 的惨痛回忆。

现在 `nantf` 已经会做这题了，但他现在对这个 $cnt$ 很感兴趣，想要计算它的值。

`nantf` 当然知道怎么做啦！但是他想考考你……

另外，`nantf` 已经不关心这个程序的时间复杂度了，于是他决定让你求出 $cnt$ 对 $20190601$（一个质数）取模的值。

# 输入格式

仅一行，包含一个正整数 $n$。

# 输出格式

仅一行，输出 $cnt$ 对 $20190601$ 取模的值。**不需要考虑溢出。**

# 样例

#### 样例输入1
```plain
10
```
#### 样例输出1
```plain
15
```
#### 样例输入2
```plain
20190601
```
#### 样例输出2
```plain
10608902
```

# 数据范围与提示

对于 $10\%$ 的数据，$1\le n\le 10^2$。

对于 $20\%$ 的数据，$1\le n\le 10^3$。

对于 $40\%$ 的数据，$1\le n\le 10^7$。

对于 $70\%$ 的数据，$1\le n\le 10^9$。

对于 $100\%$ 的数据，$1\le n\le 10^{11}$。

