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

\begin{equation} u = \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) \quad\quad e \quad\quad \vec{S}= \vec{E}\times\vec{B} \end{equation}

<details>
  <summary>{% include important.html content="$u$ e $\vec{S}$ podem ser deduzidos pelo teorema de Poynting da seguinte forma (clique aqui)" %} </summary>
  {% include note.html content="
    Seja o trabalho realizada pela força de lorentz
  
  \begin{equation} dW=\vec{F}\cdot d\vec{l} = q\left(\vec{E}+\vec{v}\times\vec{B}\right)\cdot\vec{v}dt= q\vec{E}\cdot\vec{v}dt \end{equation}
  
  
  sendo $q\leftarrow \rho d^3r \implies q\vec{v}=\rho\vec{v}d^3r=\vec{J}d^3r$
  
 
 \begin{equation} \frac{dW}{dt}=-\frac{d}{dt}\int \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)d^3r-\oint \vec{S}\cdot\hat{n}d^2r \end{equation}
 
 Logo, tem-se que
 
 \begin{equation} \frac{dW}{dt}=\int d^3r \left(\vec{E}\cdot\vec{J} \right ) \end{equation}
 
 A partir da lei de Àmpere, a qual $\vec{J}=\frac{1}{\mu_0}\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\dfrac{\partial\vec{E}}{\partial t}$, temos que
 
\begin{equation} \vec{E}\cdot\vec{J}=\frac{1}{\mu_0}\vec{E}\cdot\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\vec{E}\cdot\frac{\partial \vec{E}}{\partial t} \end{equation}
 
mas  $\small{\vec{E}\cdot (\vec{\nabla}\times\vec{E}) = \vec{B}\cdot(\vec{\nabla}\times\vec{B})-\vec{\nabla}\cdot(\vec{E}\times\vec{B})}$, e para  $\small{\vec{\nabla}\times\vec{E}=-\frac{\partial \vec{E}}{\partial t}}$ então  $\small{\vec{E}\cdot (\vec{\nabla}\times\vec{E}) = -\vec{B}\cdot\frac{\partial \vec{B}}{\partial t}-\vec{\nabla}\cdot(\vec{E}\times\vec{B})}$.

Permitindo reescrever a expressão para $\vec{E}\cdot\vec{J}$ na forma,


\begin{equation} \small{\vec{E}\cdot\vec{J} = -c^2\epsilon_0\vec{B}\cdot\frac{\partial \vec{B}}{\partial t} -\epsilon_0 \vec{E} \cdot \dfrac{\partial\vec{E}}{\partial t} -\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} \end{equation}


Seja ainda,  $\vec{B}\cdot\frac{\partial \vec{B}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}B^2 $ e $ \vec{E}\cdot\frac{\partial \vec{E}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}E^2$, temos que



\begin{equation}\vec{E}\cdot\vec{J}=-\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)-\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B} \end{equation}


Integrando a última expressão sobre todo o espaço temos a expressão para a potência $\frac{dW}{dt}$ transferida pela força eletromagnética, que tem a forma:


\begin{equation}\\footnotesize{\frac{dW}{dt}=-\frac{d}{dt}\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\int_V d^3r \frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} \end{equation}


\begin{equation} \small{-\dfrac{d}{dt}\displaystyle\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\oint_S \frac{1}{\mu_0}(\vec{E}\times\vec{B})\cdot\hat{n} d^2r} \end{equation}


Ou ainda


\begin{equation}\frac{dW}{dt}=-\frac{d}{dt} \int_V u d^3r-\oint_S \vec{S}\cdot\hat{n} d^2r \end{equation}


Onde  $u=\frac{\epsilon_0}{2}(E^2+c^2B^2)$  e $\vec{S}=\frac{1}{\mu_0}(\vec{E}\times\vec{B})$, constituindo a teorema de Poyting que correlaciona a densidade energia do campo eletromagnético  $u$ com o fluxo do vetor de poyting  $\vec{S}$.


  " %}
</details>


### 2. Como Funciona $\vec{F}=m\vec{a}$

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

*[Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
*[Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

### 3. Melhoras

kjkj
