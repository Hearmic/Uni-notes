A derivative is the instantaneous rate of change of a function at a specific point, which is equivalent to the slope of the line tangent to the function's graph at that point.

It can be computed using derivative rules or [[M 1013 Limits|limits]]. 

Derivative has two main notations:
1. $f'(x)$ -  **Lagrange notation**
2. $\frac{df}{dx}$ - **Leibniz notation**
Leibniz notation is used to explicitly state which variable is a constant and to respect to which variable the function differentiated with respect to.

One can also take a derivative of a derivative, therefore taking a second derivative, which can be denoted as:
1. $f''(x) or f^{(2)} (x)$ 
2. $\frac{d^2f}{dx^2}$ 

Higher derivatives can be denoted as such:
 1. $f^{(n)}(x)$
 2. $\frac {d^nf}{fx^n}$
### Derivative rules
#### Basic derivative rules:

| Name (rule)       | Formula                                                                | Example                                                                                                    |
| ----------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Constant          | $\frac{d}{dx} c =0$                                                    | $5' = 0$                                                                                                   |
| Constant multiple | $\frac{d}{dx} cf(x)= cf'(x)$                                           | $(5x+5)'= 5(x+1)'=5*1=5$                                                                                   |
| Power             | $\frac{d}{dx}x^n = nx^{n-1}$                                           | $(x^2)' = 2x^1 =2x$                                                                                        |
| Sum               | $\frac{d}{dx}f(x)+g(x) = \frac{d}{dx}f(x)+\frac{d}{dx}g(x)$            | $((3x+10)+(10x+9))'=(3x+10)'+(10x+9)'=3+10=13$                                                             |
| Difference        | $\frac{d}{dx}f(x)-g(x)=\frac{d}{dx}f(x)-\frac{d}{dx}g(x)$              | $((3x+10)-(10x+9))'=(3x+10)'-(10x+9)'=3-10=-7$                                                             |
| Product           | $\frac{d}{dx}f(x)g(x)=\frac{d}{dx}f(x)g(x)+f(x)\frac{d}{dx}g(x)$       | $(3x +10)*(10x+9)' = (3x+10)'*(10x+9) + (3x+10)(10x+9)' = 3(10x+9) + 10(3x+9) =30x +27 + 30x+90 = 60x+117$ |
| Quotent           | $\frac{d}{dx}\frac{f(x)}{g(x)} = \frac{g(x)f'(x)-f(x)g'(x)}{(g(x))^2}$ |                                                                                                            |
| Chain             | $\frac{d}{dx}f(g(x))=f'(g(x))*g(x)'$                                   |                                                                                                            |

#### [[M 1013 Exponential functions||Exponential functions]]

| Formula                                      | Example |
| -------------------------------------------- | ------- |
| $\frac{d}{dx}e^x = e^x$                      |         |
| $\frac{d}{dx}(a^x) = a^x*ln(a)$              |         |
| $\frac{d}{dx}e^{g(x)}= e^{g(x)}*g'(x)$       |         |
| $\frac{d}{dx} a^{g(x)}=a^{g(x)}*ln(a)*g'(x)$ |         |
#### [[M 1013 Logarithmic function|Logarithmic functions]]

| Formula                                          | Chain rule formula                                          |
| ------------------------------------------------ | ----------------------------------------------------------- |
| $\frac{d}{dx} ln(x)=\frac1x, x>0$                | $\frac{d}{dx} ln(g(x))=\frac{g'(x)}{g(x)}$,$g(x)>0$         |
| $\frac{d}{dx}log_a{x} = \frac{1}{xln{a}}$, $x>0$ | $\frac{d}{dx}(log_a{g(x)}=\frac{g'(x)}{g(x)ln{a}}$,$g(x)>0$ |

#### [[ M 1013 Trigonometric functions|Trigonometric functions]]

| Formula (x)                                               | Chain Rule Formula(g(x))                                                          |
| :-------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| $\frac{d}{dx}sin(x)=cos(x)$                               | $\frac{d}{dx}sin(g(x)) = cos(g(x))*g'(x)$                                         |
| $\frac{d}{dx}cos(x)=-sin(x)$                              | $\frac{d}{dx}cos(g(x))= -sin(g(x))*g'(x)$                                         |
| $\frac{d}{dx}tan(x)=sec^2(x)=\frac1{cos^2(x)}$            | $\frac{d}{dx}tan(g(x)) = sec^2(g(x))*g'(x) = \frac{g'(x)}{cos^2(g(x))}$           |
| $\frac{d}{dx}cot(x)=-csc^2(x)=-\frac{1}{sin^2(x)}$        | $\frac{d}{dx}cot(g(x))=-csc^2(g(x))*g'(x)$                                        |
| $\frac{d}{dx}sec(x)=sec(x)tan(x)=\frac{sin(x)}{cos^2(x)}$ | $\frac{d}{dx}sec(g(x))=sec(g(x))tan(g(x))*g'(x)=\frac{sin(g(x))*g'(x)}{cos^2(x)}$ |
| $\frac{d}{dx}csc(x)=-csc^2(x)=-\frac{1}{sin^2(x)}$        | $\frac{d}{dx}csc^2(g(x)) = -csc^2(x)*g'(x)=-\frac{g'(x)}{sin^2(g(x))}$            |
#### Inverse trig functions

| Formula (x)                                                              | Chain rule(g(x)) |
| ------------------------------------------------------------------------ | ---------------- |
| $\frac{d}{dx}sin^{-1}(x) =\frac{d}{dx}arcsin(x)= \frac{1}{\sqrt{1-x^2}}$ |                  |
| $\frac{d}{dx}cos^{-1}(x)=\frac{d}{dx}arccos(x)=-\frac1{\sqrt{1-x^2}}$    |                  |
| $\frac{d}{dx}tan^{-1}(x)-=\frac{d}{dx}arctan(x)=\frac1{1+x^2}$           |                  |
| $\frac{d}{dx}cot^{-1}(x)=\frac{d}{dx}arccot(x)=-\frac{1}{1+x^2}$         |                  |
| $\frac{d}{dx}sec^{-1}=\frac{d}{dx}arcsec(x)=\frac1{x\sqrt{x^2-1}}$       |                  |
| $\frac{d}{dx}csc^{-1}=\frac{d}{dx}arccsc(x)=-\frac1{x\sqrt{x^2-1}}$      |                  |

