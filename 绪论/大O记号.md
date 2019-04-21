### 大 O 记号 （big-O notation）

![](../images/introduction/big_o_notation_1.png)

- 常系数可忽略：O(f(n)) = O(c x f(n))
- 低次项可忽略：O(n<sup>a</sup> + n<sup>b</sup>) = O(n<sup>a</sup>) a > b > 0



### 其他记号

![](../images/introduction/other_notation.png)

大 O 悲观， 大 Ω 乐观



#### 常数复杂度 O(1)

2 / 2013 / 2013 x 2013 / 2013<sup>2013</sup> = O(1) 		// 含 RAM 各基本操作



#### 对数多项式复杂度 O(log<sup>c</sup>*n*)

对数 O(log*n*)

ln*n* | lg*n* | log<sub>100</sub>*n* | log<sub>2013</sub>*n* 

- 常底数无所谓，可以忽略
- 常数次幂无所谓



对数多项式 （ploy-log function）

**对数多项式复杂度，无限接近于常数复杂度**

![](../images/introduction/ploy_log_function_1.png)



#### 多项式复杂度 O(n<sup>c</sup>)

##### 线性（linear function）：所有 O(n) 类函数

![](../images/introduction/n.png)



#### 指数复杂度 O(2<sup>n</sup>)

指数 (exponential function) : T(n) = a<sup>n</sup>

![](../images/introduction/exponential_1.png)

这类算法的计算成本增长极快，通常被认为不可忍受



增长速度

![](../images/introduction/speed.png)

