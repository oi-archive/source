

# 题目描述



#  \sum\limits_{i = 0} ^ {n - 1} \sum\limits_{j = 0} ^ {m - 1} (i \ {\rm xor} \ j) \



#  \sum\limits_{i = 0} ^ {n - 1} \sum\limits_{j = 0} ^ {m - 1} \max((i \ {\rm xor} \ j) - k, 0) \



# 输入格式



# 输出格式



# 样例输入


<pre>3
2 2 0 100
3 3 0 100
3 3 1 100
</pre>

# 样例输出


<pre>2
12
6
</pre>

# 提示



# 来源


<p>
SDOI2016 Round1 Day1
</p>
<style>span.math span { border-left-width: 0 !important; }</style>
<script type="text/x-mathjax-config">
if (typeof MathJaxListener !== 'undefined') {
  MathJax.Hub.Register.StartupHook('End', function () {
    MathJaxListener.invokeCallbackForKey_('End');
  });
}
</script>
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
