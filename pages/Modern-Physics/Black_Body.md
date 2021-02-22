---
title: "O Problema do Corpo Negro"
keywords: Física
tags: [Física]
sidebar: mydoc_sidebar
permalink: Corpo_negro.html
summary: A Black Body can be understood as a.
---

## Introdução

Um corpo negro é um modelo físico que representa a idealização de um objeto que absorve e reemite radiação eletromagnética de forma perfeita.

### Corpo negro como uma cavidade

Talvez a melhor exemplificação de um corpo negro seja a de um objeto material onde em seu interior exista uma cavidade de paredes foscas com um pequeno orifício conectando ao exterior.

A parede interna como um sistema macroscópico, é composto a partir de um grande número de átomos, todos dispostos de forma que seus constituintes internos positivamente carregados no núcleo permaneçam relativamente fixos na estrutura molecular, enquanto seus elétrons, negativamente carregados, se concentrem na vizinhança imediata deste último, em primeira ordem, sob a ação de uma força restaurada $-m\omega_0^2 x$ devido as forças internas de coesão.

Aquecendo a configuração a uma temperatura constante $T$, conforme é transferido energia na forma de calor para parede e a agitação molecular é incrementanda na forma de vibração, os seus átomos (que são nada mais que padrões complicados de seus constituintes eletricamente carregados), devem ser excitados e em resposta(como cargas elétricas aceleradas), emitir radiação eletromagnética, preenchendo assim cavidade interna com ondas eletromagnéticas.
Essa emissão de radiação e consequente perca de energia dos osciladores pode ser levada em conta por uma força dissipativa

\begin{equation} -\frac{2e^2}{3c^3} \dot{a}\end{equation}

também chamada de força de Abraham-Lorentz, que é a força experienciada por partículas pontuais eletricamente carregadas quando aceleradadas. 

Tal radiação eletromagnética no interior da cavidade, caracterizada por superposições de ondas planas de várias frequências $\omega $ e cuja a intensidade do campo elétrico varia harmonicamente com o tempo, deve mediar nos elétrons dos átomos da parede uma força elétrica periódica $eE\cos(\omega t)$. Tais elétrons, por estarem sob ação de uma força restauradora de frequência natural de oscilação $\omega_0$, quando forçados a oscilar na frequência das ondas planas $\omega$ devem responder com a emissão de radiação na mesma frequência, e portanto, o termo dissipativo pode ser simplificado para a forma:

\begin{equation} -\frac{2e^2}{3c^3}\left(-\omega^2 \dot{x}\right)=\frac{2e^2}{3c^3}\omega^2\dot{x}\end{equation}

Assim, individualmente, os elétrons na parede devem se comportar como pequenos osciladores forçados pelo campo elétrico e amortecidos pela emissão de radiação na forma da equação diferencial ordinária não-homegênea 

\begin{equation} m\ddot{x} -\frac{2e^2}{3c^3}\omega^2\dot{x} + m\omega_0^2x = eE\cos(\omega t), \end{equation}

que é caracterizada pela solução complexa,

\begin{equation} z(t) = e^{\frac{\gamma}{2m}t}[Ae^{i\omega t}+Be^{-i\omega t}] + \frac{eE}{m\left((\omega_0^2-\omega^2)-\frac{i\omega\gamma}{m}\right)} e^{i\omega t}.\end{equation}

onde $\gamma = \frac{2e^2}{3c^3}$.

Como a cavidade providencia as condições de um sistema isolado, tal comportamento se extende até sistema atingir uma situação de equilíbrio em que a taxa de emissão de energia por parte desses osciladores microscópicos é a mesma que a taxa de absorção. Logo, o sistema deve a longo prazo exibir o comportamento não-transiente, que é a parte real da solução particular


<details>
  <summary>{% include important.html content="\begin{equation} x(t) =\frac{eE\cos(\omega t)}{m\sqrt{\left((\omega_0^2-\omega^2)-\left(\frac{\omega\gamma}{m}\right)^2\right)}}. \end{equation}" %} </summary>
  {% include note.html content="
    Seja a expressão não-transiente.
    
     \begin{equation} x(t) =\frac{eE\cos}{m\left((\omega_0^2-\omega^2)-\frac{i\omega\gamma}{m}\right)} e^{i\omega t}. \end{equation}
  
  " %}
</details>

 Seja a expressão para a energia de um oscilador individual:

<details>
  <summary>{% include important.html content="\begin{equation} u = \frac{1}{2}m\omega_0 A^2\end{equation}" %} </summary>
  {% include note.html content="
   Seja a energia de um oscilador harmônico

   \begin{equation} u= \frac{1}{2}m\dot{x}^2+\frac{1}{2}m\omega_0 x^2 \end{equation} 

   para uma solucção da forma $x(t)=A\cos(\omega_0t+\phi)$ onde $A$ é a amplitude de oscilação, substituindo-a na expressão acima, obtém-se

   \begin{equation} u =\frac{1}{2}m\left[-A\omega_0\sin(\omega_0t+\phi)\right)^2+\frac{1}{2}m\omega_0 \left(A\cos(\omega_0t+\phi)\right)^2  =\frac{1}{2}mA^2\omega_0^2\left(\sin^2(\omega_0t+\phi)+\cos^2(\omega_0t+\phi)\right] =\frac{1}{2}m\omega_0^2 A^2\end{equation}
  
   
  
  " %}
</details>

Temos da amplitude obtida em nosso modelo, que a energia indivual de tais osciladores pode ser expressa na forma

\begin{equation} u =\frac{1}{2}m\omega_0^2\end{equation}


### Lei de Stefan-Boltzmann

A primeira conjectura quantitativa com relação o comportamento de um corpo negro, foi realizada em 1879 por Joseph Stefan na forma

\begin{equation} j\left(T\right) = u/A = \sigma T^4 \end{equation},

onde $\sigma = 5{,}67\times10^{-8} \frac{W}{m^2 K^4}$ é a constante de Stefan-Boltzmann e e $j(T)$ é a densidade de energia radiada por metro quadrado de uma determinada superfície a uma temperatura $T$.

Tal expressão foi novamente deduzida em $1884$ por Ludwig Boltzmann utilizando as grandezas termodinâmicas associadas as ondas eletromagnético emitidas por corpos negros.

Seja a expressão para a densidade de enegia eletromagnética volumétrica $u$

<details>  
<summary>{% include important.html content=" \begin{equation} u = \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) \end{equation} " %} </summary>  {% include note.html content="
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



<details>
  <summary>{% include important.html content="\begin{equation} \vec{p_v}=\epsilon_0\left(\vec{E}\times\vec{B}\right).\end{equation}" %} </summary>
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



Imaginando que o corpo negro transmita sua radiação eletromagnética por meio de ondas planas (na direção $\vec{k}$), cujo campo magnético fica definido em termos do campo elétrico através da relação

<details>
  <summary>{% include important.html content="\begin{equation}\vec{B} = \frac{1}{ck}\vec{K}\times\vec{E}$ \end{equation}" %} </summary>
  {% include note.html content="
    No vácuo, onde não há fontes de cargas nem de correntes, as equações de Maxwell podem ser mostradas a satisfazer as equações de onda
  
  \begin{matrix} \nabla^2 \vec{E} = \frac{1}{c^2} \frac{\partial^2 \vec{E}}{\partial t^2} \\ \nabla^2 \vec{B} = \frac{1}{c^2} \frac{\partial^2 \vec{B}}{\partial t^2} \end{matrix}
  
  que possuem como solução
  
 \begin{equation} \vec{E}=\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \qquad \vec{B}=\vec{B_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)}. \end{equation}
 
  Pela lei de Gauss nessas circunstânicas, $\vec{\nabla}\cdot\vec{E}=0$, assim, inserindo a solução para a onda plana na mesma, obtém-se:  
  
 \begin{equation} 0=\vec{\nabla}\cdot\left(\vec{E_0} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =\sum_i \frac{\partial}{\partial x_i} E_{0i} e^{i(\sum_l k_l x_l-\omega t)} \end{equation}
 
 \begin{equation} =\sum_i  E_{0i} \frac{\partial}{\partial x_i}  e^{i(\sum_l k_l x_l-\omega t)} =\sum_i E_{0i} \left(\sum_l ik_l \frac{\partial x_l}{\partial x_i}e^{i(\sum_l k_l x_l-\omega t)} \right) \end{equation}
 
 \begin{equation} =\sum_i E_{0i} \left(\sum_l ik_l \delta_{il} e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =\sum_i E_{0i} \left(ik_i e^{i(\vec{k}\cdot\vec{r}-\omega t)} \right) =i\vec{k}\cdot\vec{E_0}e^{i(\vec{k}\cdot\vec{r}-\omega t)}=i \vec{k}\cdot\vec{E} \end{equation}
 
 Logo se deduz que $\vec{k}\cdot\vec{E}=0$. 
 
 De forma análoga, é possível mostrar que $\vec{k}\cdot\vec{B}=0$, ou seja, tanto o campo elétrico quanto o magnético, devem oscilar perpendicularmente a direção de propagação da onda plana.
 
 E por último, pela Lei de Faraday nestas circunstâncias, seja, $\vec{\nabla}\times\vec{E}=-\frac{\partial \vec{B}}{\partial t}$, temos
 
 \begin{equation}\sum_{ijk} \epsilon_{ijk}\frac{\partial}{\partial x_j}E_k \hat{x_i} = \sum_{ijk} \epsilon_{ijk}E_{0k}\frac{\partial}{\partial x_j} e^{i(\sum_l k_l x_l-\omega t)} \hat{x_i} \end{equation}
 \begin{equation} \sum_{ijk} \epsilon_{ijk}E_{0k}\sum_l i k_l\frac{\partial  x_l}{\partial x_j} e^{i(\sum_l k_l x_l-\omega t)} \hat{x_i} =i\sum_{ijk} \epsilon_{ijk}  k_j \left(E_{0k}e^{i(\vec{k}\cdot \vec{r}-\omega t)} \right) \hat{x_i} \end{equation}
 \begin{equation}   i \sum_{ijk} \epsilon_{ijk}  k_j E_k \hat{x_i}=i\vec{k}\times\vec{E}=-\frac{\partial \vec{B}}{\partial t} =-\sum_i E_{0i}\frac{\partial}{\partial t}e^{i(\vec{k}\cdot \vec{r}-\omega t)} \end{equation}
 
 \begin{equation} =-(-i\omega)\vec{B} \implies \vec{k}\times\vec{E} = \omega\vec{B} \end{equation}
 
 Ou ainda, a expressão a ser provada
 
 \begin{equation} \vec{B} = \frac{1}{\omega}\vec{k}\times\vec{E} = \frac{1}{ck}\vec{k}\times\vec{E}  \end{equation}
 
" %}
</details>

é possível mostrar que a densidade de energia $u$ e de momento $\vec{p_v}$ das ondas planas são dadas por:


<details>
  <summary>{% include important.html content="\begin{equation} u = \epsilon_0 E^2 \quad \quad e \quad \quad \vec{p_v}=\frac{\epsilon_0}{c}E^2 \hat{k} \end{equation} " %} </summary>
  {% include note.html content="
   Introduzindo a expressão de $B$ numa onda plana como obtido anteriormente na expressão para a densidade de energia eletromagnética
  
   \begin{equation} u =\frac{\epsilon_0}{2}\left(E^2+c^2B^2\right) =\frac{\epsilon_0}{2}\left(E^2+\frac{c^2}{c^2 k^2}(\vec{k}\times\vec{E})\cdot(\vec{k}\times\vec{E})\right),\end{equation}
   
  mas $(\vec{k}\times\vec{E})\cdot(\vec{k}\times\vec{E}) = \vec{k}\cdot\[\vec{E}\times(\vec{k}\times\vec{E})]=\vec{k}\cdot\[\vec{k}\cdot(\vec{E}\cdot\vec{E})-\vec{E}(\vec{E}\cdot\vec{k})]=k^2E^2$. 
  
  Logo
  
  \begin{equation} u=\frac{\epsilon_0}{2}\left(E^2+\frac{1}{k^2}k^2E^2\right) =\epsilon_0E^2\end{equation}
  
   
  
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

Mas como desenvolvido apenas quantidade escalares e as três componentes da radiação eletromagnética no interior de uma cavidade fechada tem o mesmo peso para a definição da pressão, temos que a mesma ao longo de uma direção ( de $\vec{k}$ por exemplo), deve ser dada por

\begin{equation} P=\frac{1}{3}u. \end{equation}

Através da equação fundamental da termodinâmica

\begin{equation} dU =TdS-PdV\end{equation},

temos que para uma variação isotérmica a equação de estado deve ser expressa como,

\begin{equation} \left(\frac{\partial U}{\partial V} \right)_T =T\left(\frac{\partial S}{\partial V}\right)_T -P. \end{equation}

Com ajuda a relação de Maxwell $\left(\frac{\partial S}{\partial V}\right)_T = \left(\frac{\partial P}{\partial T}\right)_V$ e da relação volumétrica $U=u(T)V$, temos que

\begin{equation} \frac{\partial}{\partial V}\left(uV\right)_T =T\left( \frac{\partial P}{\partial T}\right)_V - P. \end{equation}

Logo,

\begin{equation} u = T\frac{dP}{dT} - P. \end{equation}

Das relações que deduzimos para ondas planas, $P=\frac{u}{3}$ e $dP=\frac{du}{3}$, é possível transformar a última expressão na seguinte forma

\begin{equation} \frac{4}{3}u =\frac{T}{3}\frac{du}{dT}. \end{equation}

Que pode ainda ser separada,

\begin{equation} 4\frac{dT}{T}=\frac{du}{u} \implies d\left(4\ln T\right)=d\left(\ln u\right)\end{equation}

e integrada para obter

\begin{equation}\ln u =\ln T^4 + C, \end{equation}

que é equivalente á

\begin{equation} u(T)=\sigma T^4\end{equation}








\begin{equation} \end{equation}

