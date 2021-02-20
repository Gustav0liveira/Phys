---
title: "O Problema do Corpo Negro"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: Corpo_negro.html
summary: A Black Body can be understood as a.
---

## Introdução

Um corpo negro é um modelo físico que representa a idealização de um objeto que absorve e reemite radiação eletromagnética de forma perfeita.


### 1. Lei de Stefan-Boltzmann

A primeira conjectura quantitativa com relação o comportamento de um corpo negro, foi realizada em 1879 por Joseph Stefan na forma

\begin{equation} j\left(T\right) = u/A = \sigma T^4 \end{equation},

onde $\sigma = 5{,}67\times10^{-8} \frac{W}{m^2 K^4}$ é a constante de Stefan-Boltzmann e e $j(T)$ é a densidade de energia radiada por metro quadrado de uma determinada superfície a uma temperatura $T$.

Tal expressão foi novamente deduzida em $1884$ por Ludwig Boltzmann utilizando as grandezas termodinâmicas associadas as ondas eletromagnético emitidas por corpos negros.

Seja a expressão para a densidade de enegia eletromagnética volumétrica $u$

\begin{equation} u = \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) \end{equation}




<details>  
<summary>{% include important.html content="$u$ pode ser deduzido pelo teorema de Poynting da seguinte forma (clique aqui)" %} </summary>  {% include note.html content="
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

  \begin{equation}\vec{E}\cdot\vec{J}=-\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)-\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B}) \end{equation}
  
  Integrando a última expressão sobre todo o espaço temos a expressão para a potência $\frac{dW}{dt}$ transferida pela força eletromagnética, que tem a forma:

  \begin{equation}\scriptsize{\frac{dW}{dt}=-\frac{d}{dt}\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\int_V d^3r \frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} \end{equation}

  \begin{equation} \small{-\dfrac{d}{dt}\displaystyle\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\oint_S \frac{1}{\mu_0}(\vec{E}\times\vec{B})\cdot\hat{n} d^2r} \end{equation}
  
  Ou ainda
  
  \begin{equation}\frac{dW}{dt}=-\frac{d}{dt} \int_V u d^3r-\oint_S \vec{S}\cdot\hat{n} d^2r \end{equation}
  
  Onde  $u=\frac{\epsilon_0}{2}(E^2+c^2B^2)$  e $\vec{S}=\frac{1}{\mu_0}(\vec{E}\times\vec{B})$, constituindo a teorema de Poyting que correlaciona a densidade energia do campo eletromagnético  $u$ com o fluxo do vetor de poyting  $\vec{S}$.

  " %}
  </details>
  
 
 

e a densidade volumétrica de momento linear do campo eletromagnético $\vec{p_v}$

\begin{equation} \vec{p_v}=\epsilon_0\left(\vec{E}\times\vec{B}\right).\end{equation}



<details>
  <summary>{% include important.html content="$\vec{P}$ pode ser deduzido na forma (clique aqui)" %} </summary>
  {% include note.html content="
Seja,

Para  $q \rightarrow \int_V \rho d^3r$, temos que a expressão anterior pode ser reescrita da forma

 \begin{equation} \frac{d}{dt}\vec{P_Mec}= \int_V \rho \left(\vec{E}+\vec{v}\times\vec{B} \right)d^3r= \int_V \left(\rho\vec{E}+\vec{J}\times\vec{B} \right)d^3r \end{equation}

 Onde  $ P_{Mec} $ é o momento total do sistema. Através das equações de maxwell,  $\rho=\epsilon_0\vec{\nabla}\vec{E}$ e  $\vec{J}=\frac{1}{\mu_0} (\vec{\nabla}\times\vec{B})-\epsilon_0\frac{\partial \vec{E}}{\partial t}$ é possível reescrever a expressão  $\rho\vec{E}+\vec{J}\vec{B}$ na forma:

 \begin{equation} \rho\vec{E}+\vec{J}\vec{B}=\epsilon_0\vec{E}(\vec{\nabla}\cdot\vec{E})+\epsilon_0\vec{B}\times\frac{\partial \vec{E}}{\partial t}-\frac{1}{\mu_0}\vec{B}\times(\vec{\nabla}\times\vec{B})  \end{equation}
 
  
 Para  $\vec{B}\times\dfrac{\partial}{\partial t}\vec{E}$ $=\frac{\partial}{\partial t}(\vec{E}\times\vec{B})$ $+\vec{E}\times\dfrac{\partial }{\partial t}\vec{B}$, temos que a última expressão também pode ser reconhecida como:

 \begin{equation} \rho\vec{E}+\vec{J}\vec{B}=\epsilon_0 \left(\vec{E}(\vec{\nabla}\cdot\vec{E})+c^2\vec{B}(\vec{\nabla}\cdot\vec{B}) \right)+\epsilon_0\vec{E}\times\frac{\partial \vec{B}}{\partial t} \end{equation}
 $$- \epsilon_0\frac{\partial}{\partial t}(\vec{E}\times\vec{B})-\epsilon_0 c^2\vec{B}\times(\vec{\nabla}\times\vec{B}) $$
 
Temos que,

 \begin{equation} \frac{d}{dt}\vec{P_{Mec}}+\frac{d}{dt} \int_V \epsilon_0(\vec{E}\times\vec{B})d^3r \end{equation} 
 
 \begin{equation} =\epsilon_0 \int_V \left(\vec{E}\cdot(\vec{\nabla}\cdot\vec{E})+c^2\vec{B}\cdot(\vec{\nabla}\cdot\vec{B})+\vec{E}\times\frac{\partial}{\partial t}\vec{B}-c^2\vec{B}(\vec{\nabla}\times\vec{B}) \right)d^3r \end{equation}
 
 Possibilitando identificar o momento do campo eletromagnético como  $\vec{P_{Campo}}= \int_V \vec{p_v} d^3r $ onde  $\vec{p_v}=\epsilon_0(\vec{E}\times\vec{B})$ é a densidade de momento do campo eletromagnético.
 
" %}
</details>




Imaginando que o corpo negro transmita sua radiação eletromagnética por meio de ondas planas (na direção $\vec{k}$), cujo campo magnético fica definido em termos do campo elétrico através da relação $\vec{B} = \frac{1}{ck}\vec{K}\times\vec{E}$,



<details>
  <summary>{% include important.html content="$\small{\vec{B} = \frac{1}{ck}\vec{K}\times\vec{E}}$ é facilmente obtido na forma: (clique aqui)" %} </summary>
  {% include note.html content="
    No vácuo, onde não há fontes de cargas nem de correntes, as equações de Maxwell podem ser mostradas a satisfazer as equações de onda
  
  \begin{matrix} \nabla^2 \vec{E} = \frac{1}{c^2} \frac{\partial^2 \vec{E}}{\partial t^2} \\ \nabla^2 \vec{B} = \frac{1}{c^2} \frac{\partial^2 \vec{B}}{\partial t^2} \end{matrix}
  
  que possuem como solução
  
 \begin{equation} \vec{E}=\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \qquad \vec{B}=\vec{B_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)}. \end{equation}
 
  Pela lei de Gauss nessas circunstânicas, $\vec{\nabla}\cdot\vec{E}=0$, assim, inserindo a solução para a onda plana na mesma, obtém-se:
 
 \begin{equation} \scriptsize{0=\vec{\nabla}\cdot\left(\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right ) = \sum_i \frac{\partial}{\partial x_i} E_{0i} e^{i(\sum_l k_l x_l-\omega t)}=\sum_i  E_{0i} \frac{\partial}{\partial x_i}  e^{i(\sum_l k_l x_l-\omega t)}} \end{equation}
 
 \begi{equation} \scriptsize{\sum_i E_{0i} \left(\sum_l ik_l \frac{\partial x_l}{\partial x_i}\quad e^{i(\sum_l k_l x_l-\omega t)} \right )=\sum_i E_{0i} \left(\sum_l ik_l \delta_{il} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right)} \end{equation}
 
 \begin{equation} \scriptsize{=\sum_i E_{0i} \left(ik_i e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) = i\vec{k}\cdot\vec{E_0}e^{i(\vec{k}\cdot\vec{r}-\omega t)}=i \vec{k}\cdot\vec{E}} \end{equation}
 
" %}
</details>






é possível mostrar que a densidade de energia $u$ e de momento $\vec{p_v}$ das ondas planas são dadas por


\begin{equation} u = \epsilon_0 E^2 \quad \quad e \quad \quad \vec{p_v}=\frac{\epsilon_0}{c}E^2 \hat{k} \end{equation}



<details>
  <summary>{% include important.html content="Tais expressões podem ser verificadas da seguinte maneira (clique aqui)" %} </summary>
  {% include note.html content="
   $\vec{F}$
" %}
</details>

revelando uma conexão entre $u$ e $p_v$ a partir da expressão

\begin{equation} p_v=\frac{\epsilon_0}{c}E^2=\frac{1}{c}\left(\epsilon_0 E^2\right)=\frac{u}{c} \end{equation}

ou ainda

\begin{equation} u = cp_v. \end{equation}

Seja a contribuição infinitesimal do momento $p$

\begin{equation} dp = p_v dV = p_v dl dA = p_v (cdt)dA = (cp_v)dAdt \end{equation}

logo

\begin{equation} \frac{dp}{dt}=dF=(cp_v)dA=udA\end{equation}.

De forma que definimos a pressão eletromagnética $P$ como


\begin{equation} P = \frac{dF}{dA}=u\end{equation}.

Mas como desenvolvemos quantidade escalares até o momento, e as três componentes da radiação eletromagnética tem o mesmo peso para a definição da pressão, temos que a mesma ao longo de uma direção ( de $\vec{k}$ por exemplo), deve ser dada por

\begin{equation} P=\frac{1}{3}u \end{equation}

\begin{equation} \end{equation}






### 2. Como Funciona $\vec{F}=m\vec{a}$

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

*[Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
*[Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

### 3. Melhoras

kjkj
