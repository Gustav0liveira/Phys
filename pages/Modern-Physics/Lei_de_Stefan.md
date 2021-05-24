---
title: "A Lei de Stefan-Boltzmann"
keywords: Física
tags: [Física]
sidebar: mydoc_sidebar
permalink: Lei_de_Stefan.html
summary: Primeira Conjectura quantititativa realizada com relação ao comportamento de um corpo negro.
---

### Lei de Stefan-Boltzmann

A primeira conjectura quantitativa com relação o comportamento de um corpo negro, foi realizada em 1879 por Joseph Stefan na forma

$$ j\left(T\right) = u/A = \sigma T^4 $$,

onde $\sigma = 5{,}67\times10^{-8} \frac{W}{m^2 K^4}$ é a constante de Stefan-Boltzmann e e $j(T)$ é a densidade de energia radiada por metro quadrado de uma determinada superfície a uma temperatura $T$.

Tal expressão foi novamente deduzida em $1884$ por Ludwig Boltzmann utilizando as grandezas termodinâmicas associadas as ondas eletromagnético emitidas por corpos negros.

Seja a expressão para a densidade de enegia eletromagnética volumétrica $u$

<details>  
<summary>{% include important.html content=" $$u = \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)$$ "} </summary>  {% include note.html content="
  Seja o trabalho realizada pela força de lorentz

  \\( dW=\vec{F}\cdot d\vec{l} = q\left(\vec{E}+\vec{v}\times\vec{B}\right)\cdot\vec{v}dt= q\vec{E}\cdot\vec{v}dt \\)
  
  
  sendo $q\leftarrow \rho d^3r \implies q\vec{v}=\rho\vec{v}d^3r=\vec{J}d^3r$
  
 
 $$ \frac{dW}{dt}=-\frac{d}{dt}\int \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)d^3r-\oint \vec{S}\cdot\hat{n}d^2r $$
 
 Logo, tem-se que
 
 $$ \frac{dW}{dt}=\int d^3r \left(\vec{E}\cdot\vec{J} \right ) $$
 
 A partir da lei de Àmpere, a qual $\vec{J}=\frac{1}{\mu_0}\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\dfrac{\partial\vec{E}}{\partial t}$, temos que
 
  $$ \vec{E}\cdot\vec{J}=\frac{1}{\mu_0}\vec{E}\cdot\left(\vec{\nabla}\times\vec{B} \right )-\epsilon_0\vec{E}\cdot\frac{\partial \vec{E}}{\partial t} $$
 
  mas  $\small{\vec{E}\cdot (\vec{\nabla}\times\vec{E}) = \vec{B}\cdot(\vec{\nabla}\times\vec{B})-\vec{\nabla}\cdot(\vec{E}\times\vec{B})}$, e para  $\small{\vec{\nabla}\times\vec{E}=-\frac{\partial \vec{E}}{\partial t}}$ então  $\small{\vec{E}\cdot (\vec{\nabla}\times\vec{E}) = -\vec{B}\cdot\frac{\partial \vec{B}}{\partial t}-\vec{\nabla}\cdot(\vec{E}\times\vec{B})}$.

  Permitindo reescrever a expressão para $\vec{E}\cdot\vec{J}$ na forma,


  $$ \small{\vec{E}\cdot\vec{J} = -c^2\epsilon_0\vec{B}\cdot\frac{\partial \vec{B}}{\partial t} -\epsilon_0 \vec{E} \cdot \dfrac{\partial\vec{E}}{\partial t} -\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} $$


  Seja ainda,  $\vec{B}\cdot\frac{\partial \vec{B}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}B^2 $ e $ \vec{E}\cdot\frac{\partial \vec{E}}{\partial t}=\frac{1}{2}\frac{\partial}{\partial t}E^2$, temos que

  $$\vec{E}\cdot\vec{J}=-\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)-\frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B}) $$
  
  Integrando a última expressão sobre todo o espaço temos a expressão para a potência $\frac{dW}{dt}$ transferida pela força eletromagnética, que tem a forma:

  $$\begin{equation}\scriptsize{\frac{dW}{dt}=-\frac{d}{dt}\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\int_V d^3r \frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} \end{equation}$$

  $$ \small{-\dfrac{d}{dt}\displaystyle\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\oint_S \frac{1}{\mu_0}(\vec{E}\times\vec{B})\cdot\hat{n} d^2r} $$
  
  Ou ainda
  
  $$\frac{dW}{dt}=-\frac{d}{dt} \int_V u d^3r-\oint_S \vec{S}\cdot\hat{n} d^2r $$
  
  Onde  $u=\frac{\epsilon_0}{2}(E^2+c^2B^2)$  e $\vec{S}=\frac{1}{\mu_0}(\vec{E}\times\vec{B})$, constituindo a teorema de Poyting que correlaciona a densidade energia do campo eletromagnético  $u$ com o fluxo do vetor de poyting  $\vec{S}$.

  " %}
  </details>
  
 
e a densidade volumétrica de momento linear do campo eletromagnético $\vec{p_v}$



<details>
  <summary>{% include important.html content="$$\begin{equation} \vec{p_v}=\epsilon_0\left(\vec{E}\times\vec{B}\right).\end{equation}$$" %} </summary>
  {% include note.html content="
Seja,

Para  $q \rightarrow \int_V \rho d^3r$, temos que a expressão anterior pode ser reescrita da forma

 $$\begin{equation} \frac{d}{dt}\vec{P_Mec}= \int_V \rho \left(\vec{E}+\vec{v}\times\vec{B} \right)d^3r= \int_V \left(\rho\vec{E}+\vec{J}\times\vec{B} \right)d^3r \end{equation}$$

 Onde  $ P_{Mec} $ é o momento total do sistema. Através das equações de maxwell,  $\rho=\epsilon_0\vec{\nabla}\vec{E}$ e  $\vec{J}=\frac{1}{\mu_0} (\vec{\nabla}\times\vec{B})-\epsilon_0\frac{\partial \vec{E}}{\partial t}$ é possível reescrever a expressão  $\rho\vec{E}+\vec{J}\vec{B}$ na forma:

 $$ \rho\vec{E}+\vec{J}\vec{B}=\epsilon_0\vec{E}(\vec{\nabla}\cdot\vec{E})+\epsilon_0\vec{B}\times\frac{\partial \vec{E}}{\partial t}-\frac{1}{\mu_0}\vec{B}\times(\vec{\nabla}\times\vec{B})  $$
 
  
 Para  $\vec{B}\times\dfrac{\partial}{\partial t}\vec{E}$ $=\frac{\partial}{\partial t}(\vec{E}\times\vec{B})$ $+\vec{E}\times\dfrac{\partial }{\partial t}\vec{B}$, temos que a última expressão também pode ser reconhecida como:

 $$ \rho\vec{E}+\vec{J}\vec{B}=\epsilon_0 \left(\vec{E}(\vec{\nabla}\cdot\vec{E})+c^2\vec{B}(\vec{\nabla}\cdot\vec{B}) \right)+\epsilon_0\vec{E}\times\frac{\partial \vec{B}}{\partial t} $$
 $$- \epsilon_0\frac{\partial}{\partial t}(\vec{E}\times\vec{B})-\epsilon_0 c^2\vec{B}\times(\vec{\nabla}\times\vec{B}) $$
 
Temos que,

 $$ \frac{d}{dt}\vec{P_{Mec}}+\frac{d}{dt} \int_V \epsilon_0(\vec{E}\times\vec{B})d^3r $$ 
 
 $$ =\epsilon_0 \int_V \left(\vec{E}\cdot(\vec{\nabla}\cdot\vec{E})+c^2\vec{B}\cdot(\vec{\nabla}\cdot\vec{B})+\vec{E}\times\frac{\partial}{\partial t}\vec{B}-c^2\vec{B}(\vec{\nabla}\times\vec{B}) \right)d^3r $$
 
 Possibilitando identificar o momento do campo eletromagnético como  $\vec{P_{Campo}}= \int_V \vec{p_v} d^3r $ onde  $\vec{p_v}=\epsilon_0(\vec{E}\times\vec{B})$ é a densidade de momento do campo eletromagnético.
 
" %}
</details>



Imaginando que o corpo negro transmita sua radiação eletromagnética por meio de ondas planas (na direção $\vec{k}$), cujo campo magnético fica definido em termos do campo elétrico através da relação

<details>
  <summary>{% include important.html content="$$\vec{B} = \frac{1}{ck}\vec{K}\times\vec{E} $$" %} </summary>
  {% include note.html content="
    No vácuo, onde não há fontes de cargas nem de correntes, as equações de Maxwell podem ser mostradas a satisfazer as equações de onda
  
  $$\begin{matrix} \nabla^2 \vec{E} = \frac{1}{c^2} \frac{\partial^2 \vec{E}}{\partial t^2} \\ \nabla^2 \vec{B} = \frac{1}{c^2} \frac{\partial^2 \vec{B}}{\partial t^2} \end{matrix}$$
  
  que possuem como solução
  
 $$ \vec{E}=\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \qquad \vec{B}=\vec{B_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)}. $$
 
  Pela lei de Gauss nessas circunstânicas, $\vec{\nabla}\cdot\vec{E}=0$, assim, inserindo a solução para a onda plana na mesma, obtém-se:  
  
 $$ 0=\vec{\nabla}\cdot\left(\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =\sum_i \frac{\partial}{\partial x_i} E_{0i} e^{i(\sum_l k_l x_l-\omega t)} $$
 
 $$ =\sum_i  E_{0i} \frac{\partial}{\partial x_i}  e^{i(\sum_l k_l x_l-\omega t)} =\sum_i E_{0i} \left(\sum_l ik_l \frac{\partial x_l}{\partial x_i}e^{i(\sum_l k_l x_l-\omega t)} \right) $$
 
 $$ =\sum_i E_{0i} \left(\sum_l ik_l \delta_{il} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =\sum_i E_{0i} \left(ik_i e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =i\vec{k}\cdot\vec{E_0}e^{i(\vec{k}\cdot\vec{r}-\omega t)}=i \vec{k}\cdot\vec{E} $$
 
 Logo se deduz que $\vec{k}\cdot\vec{E}=0$. 
 
 De forma análoga, é possível mostrar que $\vec{k}\cdot\vec{B}=0$, ou seja, tanto o campo elétrico quanto o magnético, devem oscilar perpendicularmente a direção de propagação da onda plana.
 
 E por último, pela Lei de Faraday nestas circunstâncias, seja, $\vec{\nabla}\times\vec{E}=-\frac{\partial \vec{B}}{\partial t}$, temos
 
 $$\sum_{ijk} \epsilon_{ijk}\frac{\partial}{\partial x_j}E_k \hat{x_i} = \sum_{ijk} \epsilon_{ijk}E_{0k}\frac{\partial}{\partial x_j} e^{i(\sum_l k_l x_l-\omega t)} \hat{x_i} $$
 $$ \sum_{ijk} \epsilon_{ijk}E_{0k}\sum_l i k_l\frac{\partial  x_l}{\partial x_j} e^{i(\sum_l k_l x_l-\omega t)} \hat{x_i} =i\sum_{ijk} \epsilon_{ijk}  k_j \left(E_{0k}e^{i(\vec{k}\cdot \vec{r}-\omega t)} \right) \hat{x_i} $$
 $$   i \sum_{ijk} \epsilon_{ijk}  k_j E_k \hat{x_i}=i\vec{k}\times\vec{E}=-\frac{\partial \vec{B}}{\partial t} =-\sum_i E_{0i}\frac{\partial}{\partial t}e^{i(\vec{k}\cdot \vec{r}-\omega t)} $$
 
 $$ =-(-i\omega)\vec{B} \implies \vec{k}\times\vec{E} = \omega\vec{B} $$
 
 Ou ainda, a expressão a ser provada
 
 $$ \vec{B} = \frac{1}{\omega}\vec{k}\times\vec{E} = \frac{1}{ck}\vec{k}\times\vec{E}  $$
 
" %}
</details>

é possível mostrar que a densidade de energia $u$ e de momento $\vec{p_v}$ das ondas planas são dadas por:


<details>
  <summary>{% include important.html content="$u = \epsilon_0 E^2 \quad \quad e \quad \quad \vec{p_v}=\frac{\epsilon_0}{c}E^2 \hat{k}$ " %} </summary>
  {% include note.html content="
   Introduzindo a expressão de $B$ numa onda plana como obtido anteriormente na expressão para a densidade de energia eletromagnética
  
   $$ u =\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) =\frac{\epsilon_0}{2}\left(E^2+\frac{c^2}{c^2 k^2}(\vec{k}\times\vec{E})\cdot(\vec{k}\times\vec{E})\right),$$
   
  mas $(\vec{k}\times\vec{E})\cdot(\vec{k}\times\vec{E}) = \vec{k}\cdot\[\vec{E}\times(\vec{k}\times\vec{E})]=\vec{k}\cdot\[\vec{k}\cdot(\vec{E}\cdot\vec{E})-\vec{E}(\vec{E}\cdot\vec{k})]=k^2E^2$. 
  
  Logo
  
  $$ u=\frac{\epsilon_0}{2}\left(E^2+\frac{1}{k^2}k^2E^2\right) =\epsilon_0E^2$$
  
   
  
  " %}
</details>

revelando uma conexão entre $u$ e $p_v$ a partir da expressão

$$ p_v=\frac{\epsilon_0}{c}E^2=\frac{1}{c}\left(\epsilon_0 E^2\right)=\frac{u}{c} $$

ou ainda

$$ u = cp_v. $$

Seja a contribuição infinitesimal do momento $p$

$$ dp = p_v dV = p_v dl dA = p_v (cdt)dA = (cp_v)dAdt $$

logo

$$ \frac{dp}{dt}=dF=(cp_v)dA=udA$$.

De forma que definimos a pressão eletromagnética $P$ como


$$ P = \frac{dF}{dA}=u$$.

Mas como desenvolvido apenas quantidade escalares e as três componentes da radiação eletromagnética no interior de uma cavidade fechada tem o mesmo peso para a definição da pressão, temos que a mesma ao longo de uma direção ( de $\vec{k}$ por exemplo), deve ser dada por

$$ P=\frac{1}{3}u. $$

Através da equação fundamental da termodinâmica

$$ dU =TdS-PdV$$,

temos que para uma variação isotérmica a equação de estado deve ser expressa como,

$$ \left(\frac{\partial U}{\partial V} \right)_T =T\left(\frac{\partial S}{\partial V}\right)_T -P. $$

Com ajuda a relação de Maxwell $\left(\frac{\partial S}{\partial V}\right)_T = \left(\frac{\partial P}{\partial T}\right)_V$ e da relação volumétrica $U=u(T)V$, temos que

$$ \frac{\partial}{\partial V}\left(uV\right)_T =T\left( \frac{\partial P}{\partial T}\right)_V - P. $$

Logo,

$$ u = T\frac{dP}{dT} - P. $$

Das relações que deduzimos para ondas planas, $P=\frac{u}{3}$ e $dP=\frac{du}{3}$, é possível transformar a última expressão na seguinte forma

$$ \frac{4}{3}u =\frac{T}{3}\frac{du}{dT}. $$

Que pode ainda ser separada,

$$ 4\frac{dT}{T}=\frac{du}{u} \implies d\left(4\ln T\right)=d\left(\ln u\right)$$

e integrada para obter

$$\ln u =\ln T^4 + C, $$

que é equivalente á

$$ u(T)=\sigma T^4$$