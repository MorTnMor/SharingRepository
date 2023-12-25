## 其他方法论

### 求分式（低次幂）

##### x -> a 直接代入法

##### x -> a 0/0型
###### 洛必达法则
###### 约公因子
##### x -> $\infty$ 最高次幂抓大头

### 求非分式 
##### 变为分式形式，如带根号的去根号过程

### 求带三角函数

##### 和差化积

##### 积化和差

##### 等价无穷小
$$\sin {x}  \rightarrow{x} $$
$$\tan{x} \to x$$
$$\arcsin{x} \to x$$
$$\arctan{x} \to x$$
$$1-\cos{x}\to \frac{1}{2}x^2$$


##### 找1
 $$\lim_{x\to\infty} (\sin \frac{1}{x} + \cos \frac{1}{x})^x $$
### 求带有对数或幂函数

##### 幂指项考虑用重要极限
$$\lim_{x\to\infty}(\frac{1}{x} +1)^x = e$$
##### 等价无穷小
注意前提条件$\lim_{x\to0}$
$$ (a^x - 1) \rightarrow{x\ln{a}} $$
特殊情况为 $e^x - 1\to x$
$$ \log_{a}^{1+x}  \to \frac{x}{\ln{a}} $$
特殊情况为 $\ln{(x-1)} \to x$
$$ \color{aqua}(1+x)^a -1 \rightarrow{ax} $$
$$\color{aqua}\sqrt[n]{1+x} -1  \rightarrow{\frac{x}{n}} $$

### 幂次数出现x
重要极限$$\lim_{x\to\infty}(\frac{1}{x}+1)^x$$
变式   $x\to0 \Leftrightarrow \frac{1}{x}\to\infty$
$$\lim_{x\to0}(x+1)^\frac{1}{x}$$

### 求带有阶乘
$$\lim_{x\to\infty} \frac{a^n}{n!}$$
##### 展开后，用无穷小性质求解（有界乘无穷小为无穷小）

### 求数列极限
##### 三步走
###### 先用后一项除以前一项判断单调性
$$\frac{x_{n+1}}{x_{n}}$$
###### 用放缩法判断有界性
单调有界，同时可以证明极限存在

###### 根据放缩结果，凑出夹逼定理求极限

## 夹逼定理

## 超偏门

##### lim下标为自变量，换元 x = t^n!
$$\color{red}\lim_{x\to{1}}\frac{(1-\sqrt[1]{x})(1-\sqrt[2]{x})...(1-\sqrt[n]{x})}{(1-x)^{n-1}}$$

