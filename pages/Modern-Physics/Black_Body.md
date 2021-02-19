---
title: "O Problema do Corpo Negro"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: Corpo_negro.html
summary: A Black Body can be understood as a.
---

## Introdução

Um corpo negro pode ser entendendido como um objeto que absorve toda a radiação nele incidido.


### 1. Lei de Stefan-Boltzmann

A primeira conjectura quantitativa com relação o comportamento de um corpo negro, foi realizada em 1879 por Joseph Stefan na forma

\begin{equation} j\left(T\right) = u/A = \sigma T^4 \end{equation},

onde $\sigma = 5{,}67\times10^{-8} \frac{W}{m^2 K^4}$ e $j(T)$ é a desnidade de energia total radiada a partir de um metro quadro da superfície a uma temperatura $T$.

Tal expressão foi novamente deduzida em $1884$ por Ludwig Boltzmann utilizando os seguintes argumentos clássicos:
Sejam as expressões para a densidade de enegia eletromagnética volumétrica $u$ e o vetor de Poyting $\vec{S}$,

\begin{equation} \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) \quad\quad e \quad\quad \vec{S}= \vec{E}\times\vec{B} \end{equation}

<details>
  <summary>{% include important.html content="$u$ e $\vec{S}$ podem ser deduzidos pelo teorema de Poynting da seguinte forma (clique aqui)" %} </summary>
  {% include note.html content="
    Seja o trabalho realizada pela força de lorentz
  
  
  $$ dW=\vec{F}\cdot d\vec{l} = q\left(\vec{E}+\vec{v}\times\vec{B}\right)\cdot\vec{v}dt= q\vec{E}\cdot\vec{v}dt $$
  
  
  sendo $q\leftarrow \rho d^3r \implies q\vec{v}=\rho\vec{v}d^3r=\vec{J}d^3r$
  
 
 $$ \frac{dW}{dt}=-\frac{d}{dt}\int \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)d^3r-\oint \vec{S}\cdot\hat{n}d^2r $$
 
 Logo, tem-se que
 
 $$ \frac{dW}{dt}=\int d^3r \left(\vec{E}\cdot\vec{J} \right ) $$
 
 A partir da lei de Àmpere, a qual $\vec{J}=\frac{1}{\mu_0}\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\dfrac{\partial\vec{E}}{\partial t}$, temos que
 
 $$ \vec{E}\cdot\vec{J}=\frac{1}{\mu_0}\vec{E}\cdot\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\vec{E}\cdot\frac{\partial \vec{E}}{\partial t}$$
 
 <!-- wp:paragraph -->
<p>mas  \vec{E}\cdot (\vec{\nabla}\times\vec{E}) = \vec{B}\cdot(\vec{\nabla}\times\vec{B})-\vec{\nabla}\cdot(\vec{E}\times\vec{B}) [/latex], e para  [latex] \vec{\nabla}\times\vec{E}=-\frac{\partial \vec{E}}{\partial t} [/latex] então  [latex] \vec{E}\cdot (\vec{\nabla}\times\vec{E}) = -\vec{B}\cdot\frac{\partial \vec{B}}{\partial t}-\vec{\nabla}\cdot(\vec{E}\times\vec{B}) [/latex]. Permitindo reescrever a expressão para  [latex] \vec{E}\cdot\vec{J} na forma,</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center"} -->
<p class="has-text-align-center"> \vec{E}\cdot\vec{J} = -c^2\epsilon_0\vec{B}\cdot\frac{\partial \vec{B}}{\partial t} -\epsilon_0 \vec{E} \cdot \dfrac{\partial\vec{E}}{\partial t} -\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Seja ainda,  \vec{B}\cdot\frac{\partial \vec{B}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}B^2 [/latex] e [latex] \vec{E}\cdot\frac{\partial \vec{E}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}E^2, temos que</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center"} -->
<p class="has-text-align-center"> \vec{E}\cdot\vec{J}=-\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)-\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Integrando a última expressão sobre todo o espaço temos a expressão para a potência \frac{dW}{dt} transferida pela força eletromagnética, que tem a forma:</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center"} -->
<p class="has-text-align-center"> \frac{dW}{dt}=-\frac{d}{dt}\displaystyle\iiint{\frac{\epsilon_0}{2}(E^2+c^2B^2)dV}-\displaystyle\iiint{\frac{1}{\mu_0}\vec{\nabla}}\cdot(\vec{E}\times\vec{B})dV </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center"} -->
<p class="has-text-align-center"> -\dfrac{d}{dt}\displaystyle\iiint{\frac{\epsilon_0}{2}(E^2+c^2B^2)dV}-\displaystyle\oint_S{\frac{1}{\mu_0}(\vec{E}\times\vec{B})}d^3r</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Ou ainda</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"center"} -->
<p class="has-text-align-center">=\frac{dW}{dt}=-\frac{d}{dt}\displaystyle\iiint{udV}-\displaystyle\oint_S{S}dV</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Onde  u=\frac{\epsilon_0}{2}(E^2+c^2B^2) [/latex]  e  [latex] \vec{S}=\frac{1}{\mu_0}(\vec{E}\times\vec{B}) [/latex], constituindo a teorema de Poyting que correlaciona a densidade energia do campo eletromagnético  [latex] u [/latex] com o fluxo do vetor de poyting  [latex] \vec{S}.</p>
<!-- /wp:paragraph -->
  " %}
</details>


### 2. Como Funciona $\vec{F}=m\vec{a}$

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

*[Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
*[Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

### 3. Melhoras

kjkj
