# 

 
 # 题目背景 
<p><a href="http://blog.sengxian.com/tag/%E6%90%9C%E7%B4%A2" style="box-sizing: border-box; color: rgb(102, 102, 102); text-decoration: none; font-size: 12px; margin-right: 10px; font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; text-align: right; background-color: rgb(253, 253, 253);">#搜索</a><a href="http://blog.sengxian.com/tag/%E4%BA%8C%E5%88%86%E5%9B%BE%E5%AE%8C%E7%BE%8E%E5%8C%B9%E9%85%8D" style="box-sizing: border-box; color: rgb(102, 102, 102); text-decoration: none; font-size: 12px; margin-right: 10px; font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; text-align: right; background-color: rgb(253, 253, 253);">#二分图完美匹配</a></p> 

 
 # 题目描述 
<p><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">一共有n(n&lt;=200)&nbsp;</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">种花，现在给出&nbsp;</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; background-color: rgb(253, 253, 253); font-size: 20.8px; line-height: normal; white-space: nowrap;">m(1&lt;=m&lt;=n)</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">行&nbsp;</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; background-color: rgb(253, 253, 253); font-size: 20.8px; line-height: normal; white-space: nowrap;">n</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">列的花的摆放方式，要求每行每列的任意的两盆花的种类不同。问如果新添加一行，所有的合理摆放方法中，字典序为&nbsp;</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; background-color: rgb(253, 253, 253); font-size: 20.8px; line-height: normal; white-space: nowrap;">k</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">中合理方案，输出方案，否则输出&nbsp;</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; background-color: rgb(253, 253, 253); font-size: 20.8px; line-height: normal; white-space: nowrap;">-1</span><span style="font-family: 'Helvetica Neue', Arial, 'Hiragino Sans GB', 'Microsoft YaHei', sans-serif; font-size: 16px; line-height: 32px; background-color: rgb(253, 253, 253);">。</span></p> 

 
 # 输入格式 
<p>样例输入</p>

<p>4<br />
2&nbsp;1&nbsp;2<br />
2&nbsp;1&nbsp;2<br />
2&nbsp;2&nbsp;3<br />
2&nbsp;3&nbsp;4<br />
1&nbsp;2&nbsp;3&nbsp;4</p> 

 
 # 输出格式 
<p><br />
样例输出</p>

<p>2&nbsp;1&nbsp;2<br />
2&nbsp;1&nbsp;2<br />
1&nbsp;3<br />
1&nbsp;4</p> 
