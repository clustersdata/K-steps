# K-steps
K steps
描述
Here are n beautiful towns and m roads(directional edge). yjx wants to visit these towns for relaxation when he suddenly 
got a question. He wants to know the number of schemes  to walk from town A to town B in exactly k steps.A road can be 
visited more then once. It takes exactly one step to walk from one town to another if they are directly connected by a road.
yjx is very entangled with this matter, please help him.
输入
First line is a number T, the number of the cases.
Each case is as follows:
First line includes four number: n, m, k, l which means n(1 <= n <= 100)towns, m(1 <= m<=1000)roads, k(1<=k<=1000)steps,
and l (1<=l<=1000) lines test data.
Then there are m lines, and each line is made up of two number u, v (u != v, 1<= u,v <= n) which means one road from u to v.
Then l lines test data, and each line is made up of two number p, q (so you must help yjx to know the number of the scheme that just walk k steps from town p to town q).
hint: maybe there are more than one road from u to v .
输出
For each test data, output the number of the scheme(the number is big, so you must make the number mod 1991).
样例输入
2
2 2 1 2
1 2
2 1
1 2
2 1
3 2 2 1
1 2
2 3
1 3
样例输出
1
1
1
