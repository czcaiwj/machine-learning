# Markdown符号和公式

## 数学符号

|                      符号                      |                      代码                       |    描述    |
| :--------------------------------------------: | :---------------------------------------------: | :--------: |
|                     $\sum$                     |                     \$\sum$                     |    求和    |
|                 $\sum_{i=0}^n$                 |                 \$\sum_{i=0}^n$                 | 求和上下标 |
|                 $\frac{a}{b}$                  |                 \$\frac{a}{b}$                  |    分数    |
|                    $\times$                    |                    \$\times$                    |     乘     |
|                     $\pm$                      |                     \$\pm$                      |    加减    |
|                     $\div$                     |                     \$\div$                     |     除     |
|                     $\mid$                     |                     \$\mid$                     |    竖线    |
|                    $\circ$                     |                    \$\circ$                     |     圆     |
|                    $\star$                     |                    \$\star$                     |    星号    |
|                  $\bigotimes$                  |                  \$\bigotimes$                  | 克罗内克积 |
|                  $\bigoplus$                   |                  \$\bigoplus$                   |    异或    |
|                     $\leq$                     |                     \$\leq$                     |  小于等于  |
|                     $\geq$                     |                     \$\geq$                     |  大于等于  |
|                     $\neq$                     |                     \$\neq$                     |   不等于   |
|                   $\approx$                    |                   \$\approx$                    |   约等于   |
|                    $\prod$                     |                    \$\prod$                     |  N元乘积   |
|                   $\coprod$                    |                   \$\coprod$                    |  N元余积   |
|                    $\cdots$                    |                    \$\cdots$                    |   省略号   |
|                     $\int$                     |                     \$\int$                     |    积分    |
|                    $\iint$                     |                    \$\iint$                     |  多重积分  |
|                    $\oint$                     |                    \$\oint$                     |  曲线积分  |
|                    $\infty$                    |                    \$\infty$                    |    无穷    |
|                    $\nabla$                    |                    \$\nabla$                    |    梯度    |
|                   $\because$                   |                   \$\because$                   |    因为    |
|                  $\therefore$                  |                  \$\therefore$                  |    所以    |
|                   $\forall$                    |                   \$\forall$                    |    任意    |
|                   $\exists$                    |                   \$\exists$                    |    存在    |
|                 $\not\subset$                  |                 \$\not\subset$                  |   不属于   |
|                  $\emptyset$                   |                  \$\emptyset$                   |    空集    |
|                     $\in$                      |                     \$\in$                      |    属于    |
|                    $\notin$                    |                    \$\notin$                    |   不属于   |
|                   $\subset$                    |                   \$\subset$                    |    子集    |
|                  $\subseteq$                   |                  \$\subseteq$                   |   真子集   |
|                   $\bigcup$                    |                   \$\bigcup$                    |    并集    |
|                   $\bigcap$                    |                   \$\bigcap$                    |    交集    |
|                   $\bigvee$                    |                   \$\bigvee$                    |   逻辑或   |
|                  $\bigwedge$                   |                  \$\bigwedge$                   |   逻辑与   |
|                  $\biguplus$                   |                  \$\biguplus$                   |   多重集   |
|                  $\bigsqcup$                   |                  \$\bigsqcup$                   |            |
|                   $\hat{y}$                    |                   \$\hat{y}$                    |   期望值   |
|                  $\check{y}$                   |                  \$\check{y}$                   |            |
|                  $\breve{y}$                   |                  \$\breve{y}$                   |            |
|              $\overline{a+b+c+d}$              |              \$\overline{a+b+c+d}$              |    平均    |
|             $\underline{a+b+c+d}$              |             \$\underline{a+b+c+d}$              |    平均    |
| $\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$ | \$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$ |            |
|                   $\uparrow$                   |                   \$\uparrow$                   |     上     |
|                   $\Uparrow$                   |                   \$\Uparrow$                   |     上     |
|                  $\downarrow$                  |                  \$\downarrow$                  |     下     |
|                  $\Downarrow$                  |                  \$\Downarrow$                  |     下     |
|                 $\rightarrow$                  |                 \$\rightarrow$                  |     右     |
|               $\longrightarrow$                |               \$\longrightarrow$                |     右     |
|                 $\Rightarrow$                  |                 \$\Rightarrow$                  |     右     |
|               $\Longrightarrow$                |               \$\Longrightarrow$                |     右     |
|                  $\leftarrow$                  |                  \$\leftarrow$                  |     左     |
|                $\Longleftarrow$                |                \$\Longleftarrow$                |     左     |
|                $\longleftarrow$                |                \$\longleftarrow$                |     左     |
|               $\lbrace \rbrace$                |               \$\lbrace \rbrace$                |   大括号   |
|         $\begin{cases}a\\b\end{cases}$         |         \$\begin{cases}a\\b\end{cases}$         |   大括号   |
|                 $\overline{a}$                 |                 \$\overline{a}$                 |            |
|                     $\lim$                     |                     \$\lim$                     |    极限    |
|                                                |                                                 |            |

## 矩阵

1. 普通矩阵

   \$\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix}$

   $\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix}$

2. 带方括号的矩阵

   \$\left[\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right]$

   $\left[\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right]$

3. 带大括号的矩阵

   \$\left\{\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right\}$

   $\left\{\begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right\}$

4. 带省略号的矩阵

   \cdots为水平方向的省略号
    \vdots为竖直方向的省略号
    \ddots为斜线方向的省略号

   \A= \left\{ \begin{matrix} a & b & \cdots & e\\ f & g & \cdots & j \\ \vdots & \vdots & \ddots & \vdots \\ p & q & \cdots & t \end{matrix} \right\}

   A=$\left\{ \begin{matrix} a & b & \cdots & e\\ f & g & \cdots & j \\ \vdots & \vdots & \ddots & \vdots \\ p & q & \cdots & t \end{matrix} \right\}$

## 希腊字母

|    大写    |     代码     |     小写      |      代码      |
| :--------: | :----------: | :-----------: | :------------: |
|  $\Alpha$  |  \$\Alpha$   |   $\alpha$    |   \$\alpha$    |
|  $\Beta$   |   \$\Beta$   |    $\beta$    |    \$\beta$    |
|  $\Gamma$  |  `$\Gamma$`  |   $\gamma$    |   `$\gamma$`   |
|  $\Delta$  |  `$\Delta$`  |   $\delta$`   |   `$\delta$`   |
| $\Epsilon$ | `$\Epsilon$` |  $\epsilon$   |  `$\epsilon$`  |
|            |              | $\varepsilon$ | \$\varepsilon$ |
|  $\Zeta$   |  `$\Zeta$`   |    $\zeta$    |   `$\zeta$`    |
|   $\Eta$   |   \$\Eta$    |    $\eta$     |    \$\eta$     |
|  $\Theta$  |  `$\Theta$`  |   $\theta$    |   `$\theta$`   |
|  $\Iota$   |  `$\Iota$`   |    $\iota$    |   `$\iota$`    |
|     K      |    \Kappa    |       κ       |   \$\kappa$    |
|     Λ      |   \Lambda    |       λ       |   \$\lambda$   |
|     M      |     \Mu      |       μ       |     \$\mu$     |
|     N      |     \Nu      |       ν       |     \$\nu$     |
|     Ξ      |     \Xi      |     $\xi$     |     \$\xi$     |
|     O      |   \Omicron   |       ο       |  \$\omicron$   |
|     Π      |    \$\Pi$    |       π       |     \$\pi$     |
|     R      |   \$\Rho$    |       ρ       |    \$\rho$     |
|     Σ      |  \$\Sigma$   |       σ       |   \$\sigma$    |
|     T      |    \Tau$     |       τ       |    \$\tau$     |
|     Υ      | \$\Upsilon$  |       υ       |  \$\upsilon$   |
|     Φ      |   \$\Phi$    |       ϕ       |    \$\phi$     |
|            |              |   $\varphi$   |   \$\varphi$   |
|     X      |   \$\Chi$    |       χ       |    \$\chi$     |
|     Ψ      |   \$\Psi$    |       ψ       |    \$\psi$     |
|     Ω      |  \$\Omega$   |       ω       |   \$\omega$    |
|            |              |               |                |
|            |              |               |                |
|            |              |               |                |



