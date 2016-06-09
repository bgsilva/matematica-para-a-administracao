
## Primeira Prova - MAC 119 - Turma A

![Média turma A](https://drive.google.com/uc?id=0B2hurzTPk6MGaElsMmJwalpFdms)
A média da turma foi 5.41, a mediana 5.70 e o desvio padrão 2.56.

**Questão 1.** (2 pontos) Determine o domínio das funções dadas. Justifique a resposta.

(a) $f(x) = \dfrac{(x + 1)^3}{x^2 + 5x + 6}$  

(b) $h(x) = \dfrac{\sqrt{x - 2}}{x^2 + 1}$  

(c) $f(t) = \dfrac{t^4}{\sqrt{16 - t^2}}$  

(d) $j(x) = \sqrt{5x + 6} + \sqrt{x^2 - 9}$     


### **Solução**

O **domínio de uma função** corresponde aos valores da variável independente ($x$) nos quais a função ($f(x)$) é definida.

Neste problema, devemos verificar para quais valores da variável independente a função está, ou não, definida. O domínio será dado por $\mathbb{R}$ excluído os valores da variável independende que tornam a função indefinida.

**(a)** O numerador é uma função potência que é definida para todo $x$. Porém, o denominador será nulo quando a função $x^2 + 5x + 1 = 0$. Para encontrar as raízes de $x^2 + 5x + 1$, utilizamos a fórmula de Bhaskara:  
x = $\dfrac{-b \pm \sqrt{\Delta}}{2a}$, onde $\Delta = b^2 - 4\cdot a\cdot c$  

Onde encontramos que $x = -3$ ou $x = -2$. Portanto, o domínio da função será:  

D = $\{x \in \mathbb{R} : x \neq -3$ e $x \neq -2\}$

**(b)** O denominador é sempre positivo, para qualquer valor de $x$. Porém, o numerador é uma função raiz, que é apenas definida para valores de seu argumento maiores que zero. Logo, temos que:

$x - 2 \geq 0$. Portanto: $x \geq 2$. O domínio da função poderá ser escrito como: 

D = $\{x \in \mathbb{R} : x \geq 2\}$

**Questão 2.** Faça um esboço do gráfico das funções dadas, mostrando as interseções com os eixos $x$ e $y$.

(a) $f(x) = 2x^2 - 5x - 3$  

(b) $f(x) = \begin{cases} 1 - x^2, & \mbox{se } x\mbox{ $\leq 0$} \\ 3x - 1, & \mbox{se } x\mbox{ > 0} \end{cases}$


### **Solução**

**(a)** $f(x) = 2x^2 - 5x - 3$  

A parábola tem concavidade para cima, pois $a > 0$ (lembrando a forma geral $ax^2 + bx + c$)

O intercepto com o eixo y, ou seja: $f(0)$:  
$f(0) = - 3$  
$\fbox{$(0, -3)$}$

Os interceptos com o eixo x, ou seja: $f(x) = 0$:  
As raízes são:  
$x = -\dfrac{1}{2}$ e $x = 3$  
$\fbox{$(-\dfrac{1}{2}, 0)$, (3, 0)}$  

Juntando essas informações, o gráfico fica, portanto:

![Image of Yaktocat](https://drive.google.com/uc?id=0B2hurzTPk6MGblI2Z3hFY3JjWm8)

**(b)** $f(x) = \begin{cases} 1 - x^2, & \mbox{se } x\mbox{ $\leq 0$} \\ 3x - 1, & \mbox{se } x\mbox{ > 0} \end{cases}$

A função é definida para duas regiões:  
I. $(-\infty, 0]$  
II. $(0, \infty)$

I. Para a primeira região, $(-\infty, 0]$, a função assume a forma $f(x) = 1 - x^2$  
O intercepto com o eixo y, ou seja: $f(0)$ é:  
$f(0) = 1$  
$\fbox{$(0, 1)$}$

Com o eixo x, ou seja: $f(x) = 0$:   
As raízes são:  
$x = -1$ e $x = 1$. Como a raiz $x = 1$ está fora do intervalo de definição, temos apenas o intercepto:
$\fbox{$(-1, 0)$}$  

II. Para a segunda região, $(0, \infty)$, a função assume a forma $f(x) = 3x - 1$  
O intercepto com o eixo y, ou seja: $f(0)$ é:  
$f(0) = -1$. Notando que este será um ponto aberto, pois a função está definida apenas para valores maiores que zero.  
$\fbox{$(0, -1)$}$

Com o eixo x, ou seja: $f(x) = 0$:   
A raiz é:  
$x = \dfrac{1}{3}$  
$\fbox{$(\dfrac{1}{3}, 0)$}$  

Juntando essas informações, o gráfico fica, portanto:

![Image of Yaktocat](https://drive.google.com/uc?id=0B2hurzTPk6MGSktPWWVFN0s2dTA)

**Questão 3.** (2 pontos) Uma fábrica pode produzir estantes a um custo de R$\$$ 80,00 a unidade.
Os analistas da empresa estimam que se as estantes forem vendidas por $x$ reais a unidade, aproximadamente 150 - x unidades serão vendidas por mês.
Expresse o lucro mensal do fabricante em função do preço de venda, x, desenhe o gráfico associado e estime o preço ótimo de venda.

**Questão 4.** (2 pontos) Determine todos os números $x$ reais que satisfazem a equação dada.

(a) $5^x = e^4$  
(b) $\log_3 (2x + 1) = 2$  
(c) $\ln(x - 3) = \ln20 - \ln5$  
(d) $e^{2x} - 7e^x + 12 = 0$  

### **Solução**

**(a)** $5^x = e^4$  

Aplicando o logaritmo natural em ambos os lados da equação e usando as propriedades dos logarítmicos:  

$\ln 5^x = \ln e^4$  
$x\ln 5 = 4$  
$\fbox{$x = \dfrac{4}{\ln 5}$}$

**(b)** $\log_3 (2x + 1) = 2$  

Usando a definição de logaritmo, $\log_a x = y$ é equivalente a $a^y = x$, logo:  

$\log_3 (2x + 1) = 2$ equivale a: $3^2 = 2x + 1$  

$2x + 1 = 9$  
$2x = 10$  
$\fbox{$x = 5$}$

**(c)** $\ln(x - 3) = \ln20 - \ln5$  

Primeiramente, simplificamos os termos à direita da igualdade, usando as propriedades dos logarítmicos:  
$\ln20 - \ln5 = \ln\left(\dfrac{20}{5}\right) = \ln 4$  
Para resolver, usamos outra propriedade logarítmica: se $\ln x$ = $\ln y$, então x = y, ou seja:  

$\ln(x - 3) = \ln 4$  
$x - 3 = 4$  
$\fbox{x = 7}$

**(d)** $e^{2x} - 7e^x + 12 = 0$  

Fazendo a substituição: $y = e^x$, temos:  

$y^2 - 7y + 12 = 0$  

As raízes desta equação são: $y = 3$ e $y = 4$. 'Desfazendo' a substituição:  

$e^x = 3 \rightarrow x = \ln 3$  
$e^x = 4 \rightarrow x = \ln 4 = \ln 2^2 = 2\ln 2$  

$\fbox{$x = \ln 3$ e $x = 2\ln 2$}$


**Questão 5.** (2 pontos) Determine os limites indicados. Se o valor for infinito, indique se é $+\infty$ ou $-\infty$.

(a) $\lim\limits_{x\rightarrow 3} \dfrac{3x^2 - 8}{x - 2}$  
(b) $\lim\limits_{x\rightarrow + \infty} \dfrac{7x^2 + 3}{2x^2 + 5x + 6}$  
(c) $\lim\limits_{x\rightarrow 0} (6 + \dfrac{1}{x^2})$  
(d) $\lim\limits_{x\rightarrow 2} \dfrac{x - 2}{x(x^2 - 4)}$  


```python

```
