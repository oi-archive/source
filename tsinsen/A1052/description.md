<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Tom教授正在给研究生讲授一门关于基因的课程，有一件事情让他颇为头疼：一条染色体上有成千上万个碱基对，它们从0开始编号，到几百万，几千万，甚至上亿。<br/>
　　比如说，在对学生讲解第1234567009号位置上的碱基时，光看着数字是很难准确的念出来的。<br/>
　　所以，他迫切地需要一个系统，然后当他输入12 3456 7009时，会给出相应的念法：<br/>
　　十二亿三千四百五十六万七千零九<br/>
　　用汉语拼音表示为<br/>
　　shi er yi san qian si bai wu shi liu wan qi qian ling jiu<br/>
　　这样他只需要照着念就可以了。<br/>
　　你的任务是帮他设计这样一个系统：给定一个阿拉伯数字串，你帮他按照中文读写的规范转为汉语拼音字串，相邻的两个音节用一个空格符格开。<br/>
　　注意必须严格按照规范，比如说“10010”读作“yi wan ling yi shi”而不是“yi wan ling shi”，“100000”读作“shi wan”而不是“yi shi wan”，“2000”读作“er qian”而不是“liang qian”。</div>
# 输入格式

<div class="pdcont">　　有一个数字串，数值大小不超过2,000,000,000。</div>
# 输出格式

<div class="pdcont">　　是一个由小写英文字母，逗号和空格组成的字符串，表示该数的英文读法。</div>
# 样例输入

<div class="pddata">1234567009</div>
# 样例输出

<div class="pddata">shi er yi san qian si bai wu shi liu wan qi qian ling jiu</div>

</div>