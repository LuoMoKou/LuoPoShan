# Obsidian 公式速查表

## 基础语法

| 写法 | 效果 | 说明 |
|------|------|------|
| `$x$` | 行内公式 | 单 `$` 包裹 |
| `$$x$$` | 独立公式 | 双 `$` 包裹，独占一行 |
| `x^2` | $x^2$ | 上标 |
| `x_1` | $x_1$ | 下标 |
| `x^{10}` | $x^{10}$ | 多于一个字符用 `{}` |

## 希腊字母

| 写法 | 输出 | | 写法 | 输出 |
|------|------|-|------|------|
| `\alpha` | $\alpha$ | | `\beta` | $\beta$ |
| `\gamma` | $\gamma$ | | `\delta` | $\delta$ |
| `\epsilon` | $\epsilon$ | | `\theta` | $\theta$ |
| `\lambda` | $\lambda$ | | `\mu` | $\mu$ |
| `\pi` | $\pi$ | | `\sigma` | $\sigma$ |
| `\phi` | $\phi$ | | `\omega` | $\omega$ |
| `\Gamma` | $\Gamma$ | | `\Delta` | $\Delta$ |
| `\Omega` | $\Omega$ | | `\Sigma` | $\Sigma$ |
| `\partial` | $\partial$ | | `\infty` | $\infty$ |

## 算子与关系

| 写法 | 输出 | 说明 |
|------|------|------|
| `\frac{a}{b}` | $\frac{a}{b}$ | 分数 |
| `\sqrt{x}` | $\sqrt{x}$ | 平方根 |
| `\sqrt[n]{x}` | $\sqrt[n]{x}$ | n 次根 |
| `\int` | $\int$ | 积分 |
| `\iint` | $\iint$ | 二重积分 |
| `\iiint` | $\iiint$ | 三重积分 |
| `\oint` | $\oint$ | 回路积分 |
| `\sum` | $\sum$ | 求和 |
| `\prod` | $\prod$ | 连乘 |
| `\lim` | $\lim$ | 极限 |
| `\to` | $\to$ | 箭头 |
| `\infty` | $\infty$ | 无穷 |

## 上下标与修饰

| 写法 | 输出 | 说明 |
|------|------|------|
| `\int_0^1` | $\int_0^1$ | 积分上下限 |
| `\sum_{n=1}^\infty` | $\sum_{n=1}^\infty$ | 求和上下限 |
| `\bar{x}` | $\bar{x}$ | 上划线 |
| `\vec{F}` | $\vec{F}$ | 向量 |
| `\dot{x}` | $\dot{x}$ | 一点导数 |
| `\ddot{x}` | $\ddot{x}$ | 二点导数 |
| `\mathrm{d}` | $\mathrm{d}$ | 正体 d |

## 括号与矩阵

| 写法 | 输出 |
|------|------|
| `\left( \frac{1}{2} \right)` | 自适应大小括号 |
| `\begin{pmatrix} a & b \\ c & d \end{pmatrix}` | 矩阵 |
| `\begin{vmatrix} a & b \\ c & d \end{vmatrix}` | 行列式 |
| `\begin{cases} x & x>0 \\ 0 & x\le0 \end{cases}` | 分段函数 |

## 特殊字体

| 写法 | 输出 | 用途 |
|------|------|------|
| `\mathrm{d}` | $\mathrm{d}$ | 微分算子 |
| `\mathbf{F}` | $\mathbf{F}$ | 向量/矩阵 |
| `\mathcal{L}` | $\mathcal{L}$ | 变换/集合 |
| `\varepsilon` | $\varepsilon$ | 另一种 epsilon |

## 常用组合示例

```
$$ \int_a^b f(x)\,\mathrm{d}x $$
$$ \frac{\partial f}{\partial x} $$
$$ \lim_{x\to 0} \frac{\sin x}{x} = 1 $$
$$ \sum_{k=1}^n k = \frac{n(n+1)}{2} $$
$$ \iint_D \left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right)\mathrm{d}x\mathrm{d}y $$
```

## 快捷键

| 快捷键 | 效果 |
|--------|------|
| `Ctrl+Shift+M` | 插入/切换 `$$` 公式块 |
| `Ctrl+/` | 切换源码/预览 |
