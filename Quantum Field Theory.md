## 量子场论 Quantum Field Theory
该笔记经由中山大学余钊焕老师的《量子场论讲义》整理而来，仅记录重要结论或定理，以帮助记忆和建立物理图像，不记录推导过程
### 预备知识 
* 基本粒子指尚未发现内部结构的粒子
* 夸克的种类称为味(flavor)，六种味道的夸克d、u、s、c、b、t质量不同。而每一味夸克又具有三种颜色(color)
* 标准模型中，传递夸克间强相互作用的规范玻色子称为胶子(gluon)，传递电磁相互作用的规范玻色子称为是光子(photon)，传递弱相互作用的规范玻色子是 $W^{\pm}$和 $Z^{0}$玻色子。此外，还存在Higgs玻色子，与电弱规范对称性的自发破缺及基本粒子的质量起源有关
#### 1.1量子场论的必要性
* 量子场论结合了量子力学、相对性原理和场(field)的概念
* 由Klein Gordon方程  
  <center>$-\hbar^{2}\frac{\partial^{2}}{\partial t^{2} }\psi(\textbf{x},t)=(-\hbar^{2}c^{2}\nabla^{2}+m^{2}c^{4})\psi(\textbf{x},t)$<center>   
  给出的自由粒子能量是 $E=\pm\sqrt{\textbf{p}^{2}c^{2}+m^{2}c^{4}}$，存在负能量困难。概率密度定义为  
  $\rho=\frac{i\hbar}{2mc^{2}}(\psi^*\frac{\partial\psi}{\partial t}-\frac{\partial\psi^*}{\partial t}\psi)$
  存在负概率困难。Dirac方程解决了该问题，但只能描述自旋为1/2的粒子，而不能表述整数自旋的粒子
* 我们可以在每个空间点 $\textbf{x}$ 处定义一个算符 $\hat{\Phi}(\textbf{x})$，所有这些算符的集合称为量子场(quantum field)。在海森堡绘景中，量子场算符还依赖于时间 $t$， $\hat{\Phi}(\textbf{x},t)=e^{i\hat{H}t/\hbar}\hat{\Phi}(\textbf{x})e^{-i\hat{H}t/\hbar}$。由此，量子化的对象变为由依赖于时空坐标的场组成的动力学系统，这就是量子场论
* 真空是量子场的基态，包含粒子的态则是激发态
#### 自然单位制
#### Lorentz变换和Lorentz群
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
