
# Description

<div class="content"><p>有N个可爱的小猴子，有一天，妈妈摘了M个桃子，可是怎么分都分不平均。于是妈妈偷偷地把桃子藏了起来，准备第二天再想办法。可是孩子们到了晚上，纷纷去偷吃。第一只猴子去的时候发现把桃子分成N份相等的量，会剩下1（注：是数字1不是字母l，下同）个桃子，于是拿走了自己的一份，并把多余的1个桃子也拿走了。第二只猴子去的时候发现平分成N份时会剩下2个桃子，于是拿走了自己的一份，并把多余的2个桃子也拿走了……第K只猴子去的时候发现平分成N份时会剩下K个桃子，于是拿走了自己的一份，并把多余的K个桃子也拿走了，第K+1只猴子去的时候发现平分成N份后只剩下1个桃子，于是拿走了自己的一份，并拿走了多余的1个桃子，第K+2只猴子去的时候发现平分成N份后剩下2个桃子，于是拿走了自己的一份，并拿走了多余的2个桃子……如此K个一循环。第N个猴子去的时候，把剩下的桃子（至少一个）全都吃了。试问M至少是多少？ 任务：输入正整数N，K（K&lt; N），求出最小的正整数M，桃子不能分割。</p></div>

# Input

<div class="content"><p>输入仅包含一行，包括两个用空格隔开的正整数N，K.</p></div>

# Output

<div class="content"><p>输出一个正整数，表示最小的M，答案有可能超过264（2的64次方）.</p></div>

# Sample Input

<div class="content"><span class="sampledata">	4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">73</span></div>

# Hint

<div class="content"><p></p><p>30%的数据满足，0 &lt; K &lt; N &lt; 12; 另外15%的数据满足，K+1=N; 100%的数据满足，0 &lt; K &lt; N &lt; 100.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

