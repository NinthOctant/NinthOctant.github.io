## 量子场论 Quantum Field Theory

### 预备知识 
* 基本粒子指尚未发现内部结构的粒子
* 夸克的种类称为味(flavor)，六种味道的夸克d、u、s、c、b、t质量不同。而每一味夸克又具有三种颜色(color)
* 标准模型中，传递夸克间强相互作用的规范玻色子称为胶子(gluon)，传递电磁相互作用的规范玻色子称为是光子(photon)，传递弱相互作用的规范玻色子是 $W^{\pm}$和 $Z^{0}$玻色子。此外，还存在Higgs玻色子，与电弱规范对称性的自发破缺及基本粒子的质量起源有关
#### 1.1量子场论的必要性
* 量子场论结合了量子力学、相对性原理和场(field)的概念
* 由Klein Gordon方程  
  $$-\hbar^{2}\frac{\partial^{2}}{\partial t^{2} }\psi(\textbf{x},t)=(-\hbar^{2}c^{2}\nabla^{2}+m^{2}c^{4})\psi(\textbf{x},t)$$ 
  给出的自由粒子能量是 $E=\pm\sqrt{\textbf{p}^{2}c^{2}+m^{2}c^{4}}$，存在负能量困难。
* 概率密度定义为 $$\rho=\frac{i\hbar}{2mc^{2}}(\psi^* \frac{ \partial\psi}{\partial t}-\frac{\partial\psi^*}{\partial t}\psi)$$
  存在负概率困难。Dirac方程解决了该问题，但只能描述自旋为1/2的粒子，而不能描述整数自旋的粒子
* 我们可以在每个空间点 $\textbf{x}$ 处定义一个算符 $\hat{\Phi}(\textbf{x})$，所有这些算符的集合称为量子场(quantum field)。在海森堡绘景中，量子场算符还依赖于时间 $t$， $\hat{\Phi}(\textbf{x},t)=e^{i\hat{H}t/\hbar}\hat{\Phi}(\textbf{x})e^{-i\hat{H}t/\hbar}$。由此，量子化的对象变为由依赖于时空坐标的场组成的动力学系统，这就是量子场论
* 真空是量子场的基态，包含粒子的态则是激发态
#### 1.2自然单位制
* 在自然单位制中，速度没有量纲(dimension)；长度量纲与时间量纲相同，是能量量纲的倒数；能量、质量和动量具有相同的量纲。可以将能量单位与电子伏特(eV)视作上述有量纲物理量的基本单位
#### 1.3Lorentz变换和Lorentz群
* Lorentz变换的形式 $t'=\gamma(t-\beta x)$, $x'=\gamma(x-\beta t)$, $y'=y$, $z'=z$, 其中Lorentz因子 $\gamma=(1-\beta^{2})^{-1/2}$
* $t^{2}-x^{2}-y^{2}-z^{2}$是一个Lorentz不变量，在不同惯性系中值不变
* Minkowski度规(metric) $$g_{\mu\nu}=g_{\nu\mu}=diag(1,-1,-1,-1)$$,使用Einstein求和约定，将内积化为求和式
  $x^{2}=(x^{0})^{2}-(x^{1})^{2}-(x^{2})^{2}-   (x^{3})^{2}= \sum_{\mu,\nu=0}^{3}g_{\mu\nu}x^{\mu}x^{\nu}=g_{\mu\nu}x^{\mu}x^{\nu}$
* 逆变矢量与协变矢量一一对应，是对同一Lorentz矢量的两种等价描述
* 保度规条件 $g_{\mu\nu}\Lambda^{\mu}_ \alpha\Lambda^{\nu}_ {\beta}=g_{\alpha\beta}$
* 可以用 $\\rm det(\Lambda)$的值给Lorentz变换分类。 $\rm det(\Lambda)=1$的变换称为固有(proper)Lorentz变换， $\rm  det(\Lambda)=-1$的变换称为非固有(improper)Lorentz变换； $\Lambda^{0}_{0}\geq1$的变换称为保时向(orthochronous)Lorentz变换，$\Lambda^{0}_{0}\leq1$的变换称为反时向(antichronous)Lorentz变换


#### Lorentz矢量
#### Lorentz张量
#### 作用量原理
##### 经典力学中的作用量原理
##### 经典场论中的作用量原理
#### Noether定理、对称性与守恒定律
##### 场论中的Noether定理
##### 时空平移对称性
##### Lorentz对称性
##### U(1)整体对称性
