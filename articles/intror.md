# Uma breve introdução ao R

**Mauro Campos**. *Departamento de Estatística, UFES*.

R é um software livre que proporciona um ambiente para análise de dados. R compila e roda em diversas plataformas: Linux, Windows e MacOS. Para download R visite a página web do [Projeto R](https://www.r-project.org/) e escolha um CRAN mirror de sua preferência. Conheça também o [RStudio](https://www.rstudio.com/) que é um IDE (Integrated Development Environment) para R.

Este artigo proporciona uma breve introdução ao R para alunos matriculados em disciplinas tais como: **Estatística Básica** ou **Probabilidade e Estatística**.

## Operadores aritméticos

```
> # Comentário
> 2+3 
[1] 5
> 2-3
[1] -1
> 2*3
[1] 6
> 2/3
[1] 0.6666667
> 2^(3)
[1] 8
```

## Atribução

```
> pi
[1] 3.141593
> x <- sqrt(2*pi) # Armazena em x o valor raiz de pi
> x
[1] 2.506628
> x = sqrt(2*pi);x  # = pode ser usado no lugar de <-
[1] 2.506628
> x = x+2
> x
[1] 4.506628
```

## Operadores lógicos

```
> y <- (3==3)|(5>=7) # operador OR 
> y
[1] TRUE
> w <- (3>6)&(5!=7) # operador AND 
> w
[1] FALSE
> !w # operador NOT 
[1] TRUE
```

## Funções matemáticas

```
> abs(-3)
[1] 3
> sqrt(9)
[1] 3
> exp(2)
[1] 7.389056
> log(2); log2(2); log10(2)
[1] 0.6931472
[1] 1
[1] 0.30103
> log(2,base=10) 
[1] 0.30103
> sin(pi/6); cos(pi/6); tan(pi/6)
[1] 0.5
[1] 0.8660254
[1] 0.5773503
> floor(pi) # funcao piso
[1] 3
> ceiling(pi) # funcao teto
[1] 4
> factorial(3) # retorna o fatorial de 3
[1] 6
> 25%%3 # retorna o resto de 25/3 (25 mod 3)
[1] 1
```
## Equações e equações em bloco

An inline math equation can be written as: $\omega = d\phi / dt=A\times\pi^{3}$. An equation block is given by:
$$
I = \int\rho R^{2} dV
$$

## Programando em R

```
if(cond){expr}
if(cond){expr1}else{expr2}
for(var in seq){expr}
while(cond){expr}
repeat{expr;... if(cond){break}}

> x <- 1
> repeat{
+   print(x)
+   x <- x+1
+   if(x==6){break}
+ }
[1] 1
[1] 2
[1] 3
[1] 4
[1] 5
```

Pessoal, espero que ajude. Visite minha [página](http://www.maurocampos.com/).

> <p align="justify">UFES - Universidade Federal do Espírito Santo, Centro de Ciências Exatas, Departamento de Estatística. Av. Fernando Ferrari 514, 29075-910, Vitória ES, Brasil.</p>



