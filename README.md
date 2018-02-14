# Mirana CSS Framework

## Introdução
Mirana é uma ferramenta que tem por objetivo facilitar o desenvolvimento de layouts responsivos, no menor espaço de tempo possível, o que proporciona ao desenvolvedor um aumento de sua produtividade. O diferencial do framework é sua simplicidade, possui classes intuitívas e é bem leve. Os grids são compostos por 12 níveis, estes devem ficar dentro de linhas .line que por sua vez ficam dentro de blocos de conteúdo .block, a codificação deve, de preferência, seguir essa hierarquia de classes, para um alinhamento adequado do conteúdo.  
[Ver documentação](https://fmm312.github.io/mirana/)

## Características
- Leve: Arquivo minificado com menos de 4kb
- 100% responsivo: Sistema de grid baseado no flexbox layout e inspirado no bootstrap
- Intuitívo: Classe fáceis de decorar e com nomenclatura bem intuitíva
- Open Source: A ferramenta é gratuita e todo o código está disponibilizado no Github

## Instalação
Faça o download, adicione a pasta CSS na raiz do seu projeto, por último coloque o código abaixo no head do html
```
<link rel="stylesheet" href="css/normalize.css">
<link rel="stylesheet" href="css/mirana.min.css">

```

## Grid
- **grid-sm** (smarthphones) --> @media screen and (max-width: 600px)
- **grid-md** (tablets/ipads) --> @media screen and (min-width: 601px)
- **grid-lg** (desktops/laptops) --> @media screen and (min-width: 992px)
- **grid-xlg** (telas grandes) --> @media screen and (min-width: 1600px)


## Alinhamento
- .align-start
- .align-end
- .align-center
- .align-around
- .align-between
