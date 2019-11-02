# 

 
 # 题目描述 
<p>
　　单词接龙是一个与我们经常玩的成语接龙相类似的游戏，现在我们已知一组单词，且给定一个开头的字母，要求出以这个字母开头的最长的“龙”（每个单词都最多在“龙”中出现两次,且每个单词的长度小于等于20个字符），在两个单词相连时，其重合部分合为一部分，例如 beast和astonish，如果接成一条龙则变为beastonish，另外相邻的两部分不能存在包含关系，例如at 和 atide 间不能相连。</p> 

 
 # 输入格式 
<p>
　　输入的第一行为一个单独的整数n (n <= 100)表示单词数，以下n 行每行有一个单词，输入的最后一行为一个单个字符，表示“龙”开头的字母。你可以假定以此字母开头的“龙”一定存在.</p> 

 
 # 输出格式 
<p>
　　只需输出以此字母开头的最长的“龙”的长度</p> 

 
 # 提示 
<p>
　　经典深度搜索</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5
at
touch
cheat
choose
tact
a
</td><td>23</td></tr></table>
