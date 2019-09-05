# 题目描述


<pre>Bessie烘焙了一块巧克力蛋糕。这块蛋糕是由R*C(1 &lt;= R,C &lt;= 500)个小的巧克力蛋糕组成的。

第i行，第j列的蛋糕有N_ij(1 &lt;= N_ij &lt;= 4,000)块巧克力碎屑。



Bessie想把蛋糕分成A*B块，(1 &lt;= A &lt;= R,1 &lt;= B &lt;= C): 给A*B只奶牛。蛋糕先水平地切A-1刀

（只能切沿整数坐标切）来把蛋糕划分成A块。然后再把剩下来的每一块独立地切B-1刀，

也只能切沿整数坐标切。其他A*B-1只奶牛就每人选一块，留下一块给Bessie。由于贪心，

他们只会留给Bessie巧克力碎屑最少的那块。



求出Bessie最优情况下会获得多少巧克力碎屑。



例如，考虑一个5*4的蛋糕，上面的碎屑分布如下图所示：



         1 2 2 1

         3 1 1 1

         2 0 1 3

         1 1 1 1

         1 1 1 1



Bessie必须把蛋糕切成4条，每条分成2块。Bessie能像这样切蛋糕:



       1 2 | 2 1

       ---------

       3 | 1 1 1

       ---------

       2 0 1 | 3

       ---------

       1 1 | 1 1

       1 1 | 1 1



因此，其他贪得无厌的牛拿完后，Bessie仍能够拿走3个巧克力碎屑。



问题名称: brownie



输入格式:



* 第1行: 四个空格隔开的数: R, C, A ，B



* 第2-R+1行: 第i+1行有C个整数, N_i1 , N_i2 .. N_iC



样例输入 (brownie.in):



5 4 4 2

1 2 2 1

3 1 1 1

2 0 1 3

1 1 1 1

1 1 1 1



输出格式:



* 第1行: 一个整数: Bessie保证能拿到的最多碎屑数



样例输出 (brownie.out):



3

</pre>