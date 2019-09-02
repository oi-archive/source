
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【问题描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">组合数C(N, K)表示了N个数字不重复地选取K个作组合的方案数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">C(N, K) = N!/(N-M)!M!</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">当然，在取余数的条件下，由于除法的限制，上述公式求C(N, K) mod H不方便，并且高精度除法也不容易写，所以一般情况下我们采取的是下列方法。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">若N，K不大，可以通过递推的方法求出所有组合数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">首先，N个数取0个数显然只有1种方案，那就是什么都不取；</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接着，N个数取N个数的组合显然也只有1种方案。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">所以C(N, 0) = 1，C(N, N) = 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">其他情况下，C(N, K) = C(N - 1, K) + C(N – 1, K – 1)，这样就可以通过递推求出所有组合数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">你可以看到，其实结果其实就是杨辉三角形。</span><br/>

# 输入



# 输出


