

#  任务 



#  输入格式 



#  输出格式 



#  输入样例 



#  输出样例 



#  数据约束和评分方法 



# 对 



# UPD：2017.7.12 By Mike



# 原题应该是数据有误，我用Byvoid学长的程序，和我的跑出了相同的答案，而且和标准答案不同！此题数据已更换为我和Byvoid学长程序跑出的结果。



# 原题时间限制是1s，如果有哪位神犇知道能在时限中跑出的方法，请给我发邮件联系，感激不尽！



# 解决爆栈，我们加两行代码就好了：


<p>
<strong>
</strong></p><pre class="prettyprint lang-cpp"><strong>int __size__=64&lt;&lt;20;
char *__p__=(char*)malloc(__size__)+__size__;
__asm__(&#34;movl %0, %%esp\n&#34;::&#34;r&#34;(__p__));</strong></pre><strong>
小心炸内存……<br/>
</strong> 
<p></p>
