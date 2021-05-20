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

A parede interna como um sistema macroscópico, é composto a partir de um grande número de átomos, todos dispostos de forma que seus constituintes internos positivamente carregados no núcleo permaneçam relativamente fixos na estrutura molecular, enquanto seus elétrons, negativamente carregados, se concentrem na vizinhança imediata deste último, sob a ação de uma força restauradora $-m\omega_0^2 x$ (em primeira ordem) devido as forças internas de coesão.

Aquecendo a configuração a uma temperatura constante $T$, conforme é transferido energia na forma de calor para parede e a agitação molecular é incrementanda na forma de vibração, os seus átomos (que são nada mais que padrões complicados de seus constituintes eletricamente carregados), devem ser excitados e em resposta (como cargas elétricas aceleradas), emitir radiação eletromagnética, preenchendo assim cavidade interna com ondas eletromagnéticas.
Essa emissão de radiação e consequente perca de energia dos osciladores pode ser levada em conta por uma força dissipativa

$$ -\frac{2e^2}{3c^3} \dot{a}$$

também chamada de força de Abraham-Lorentz, que é a força experienciada por partículas pontuais eletricamente carregadas quando aceleradadas. 

Tal radiação eletromagnética no interior da cavidade, caracterizada por superposições de ondas planas de várias frequências $\omega $ e cuja a intensidade do campo elétrico varia harmonicamente com o tempo, deve mediar nos elétrons dos átomos da parede uma força elétrica periódica $eE\cos(\omega t)$. Tais elétrons, por estarem sob ação de uma força restauradora de frequência natural de oscilação $\omega_0$, quando forçados a oscilar na frequência das ondas planas $\omega$ devem responder com a emissão de radiação na mesma frequência, e portanto, o termo dissipativo pode ser simplificado para a forma:

$$ -\frac{2e^2}{3c^3}\left(-\omega^2 \dot{x}\right)=\frac{2e^2}{3c^3}\omega^2\dot{x}$$

Assim, individualmente, os elétrons na parede devem se comportar como pequenos osciladores forçados pelo campo elétrico e amortecidos pela emissão de radiação na forma da equação diferencial ordinária não-homegênea 

$$ m\ddot{x} -\frac{2e^2}{3c^3}\omega^2\dot{x} + m\omega_0^2x = eE\cos(\omega t), $$

que é caracterizada pela solução complexa,

$$ z(t) = e^{\frac{\gamma}{2m}t}[Ae^{i\omega t}+Be^{-i\omega t}] + \frac{eE}{m\left((\omega_0^2-\omega^2)-\frac{i\omega\gamma}{m}\right)} e^{i\omega t}.$$

onde $\gamma = \frac{2e^2}{3c^3}$.

Como a cavidade providencia as condições de um sistema isolado, tal comportamento se extende até sistema atingir uma situação de equilíbrio em que a taxa de emissão de energia por parte desses osciladores microscópicos é a mesma que a taxa de absorção. Logo, o sistema deve a longo prazo exibir o comportamento não-transiente, que é a parte real da solução particular

$$ x(t) =\left(\frac{eE}{m\sqrt{(\omega_0^2-\omega^2)^2-\left(\frac{\omega\gamma}{m}\right)^2}}\right)\cos(\omega t) =A\cos(\omega t). $$
  
</details>

 Seja a expressão para a energia de um oscilador individual:

<details>
  <summary>{% include important.html content="$u = \frac{1}{2}m\omega_0^2 A^2$" %} </summary>
  {% include note.html content="
   Seja a energia de um oscilador harmônico

   $$ u= \frac{1}{2}m\dot{x}^2+\frac{1}{2}m\omega_0^2 x^2 $$ 

   para uma solucção da forma $x(t)=A\cos(\omega_0t+\phi)$ onde $A$ é a amplitude de oscilação, substituindo-a na expressão acima, obtém-se

   $$ u =\frac{1}{2}m\left[\left(-A\omega_0\sin(\omega_0t+\phi)\right)^2+\frac{1}{2}m\omega_0 \left(A\cos(\omega_0t+\phi)\right)^2\right]  $$ 
   
   $$ =\frac{1}{2}mA^2\omega_0^2\left(\sin^2(\omega_0t+\phi)+\cos^2(\omega_0t+\phi)\right) =\frac{1}{2}m\omega_0^2 A^2$$
  " %}
</details>


Temos da amplitude obtida em nosso modelo, que a energia indivual de tais osciladores pode ser expressa na forma

$$ u =\frac{1}{2}m\omega_0^2\frac{e^2E^2}{m^2\left((\omega_0^2-\omega^2)^2-\left(\frac{\omega\gamma}{m}\right)^2\right)} =\frac{1}{2}m\omega_0^2\frac{e^2E^2}{m^2(\omega_0^2-\omega^2)^2-\left(\omega\gamma\right)^2}
 $$


Para valores de frequência $\omega \approx \omega_0$, temos que $\omega_0^2-\omega^2 = (\omega_0 - \omega)(\omega_0 + \omega) \approx 2 \omega_0(\omega_0 - \omega)$

$$ u =\frac{1}{2}m\omega_0^2\frac{e^2E^2}{4m^2\omega_0^2(\omega_0-\omega)^2-\left(\omega_0\gamma\right)^2} =\frac{1}{8m}\frac{e^2E^2}{(\omega_0-\omega)^2-\left(\frac{\gamma}{2m}\right)^2}.
 $$ 

Mas como discutido anteriormente, no interior da cavidade temos uma superposição de ondas planas de todas as frequências possíveis, de forma para encontrar a expressão para energia dos pequenos osciladores da parede, é necessário realizar uma soma contínua de u em todos os valores possíveis de $\omega$

$$ u_{total} =\int_{-\infty}^{\infty} $$

Como a equação se refere apenas ao campo elétrico que oscila de forma estacionária unidimensionalmente. Para a cavidade como um todo, a relação entre a energia total do corpo negro e o campo elétrico é dado por três vezes essa forma, ou ainda

$$ E^2= \dfrac{8\omega^2}{\pi c^3}U$$

Logo, a densidade de energia da radiação eletromagnética $\rho$, dada em unidade gaussinas, é expressa como:

$$    u(\omega_0,t)=\frac{1}{2}\epsilon_0 E^2 \equiv \frac{1}{8\pi}E^2=\frac{\omega_0^2}{\pi^2c^3}U $$

Mundando  da representação da frequência angular $\omega_0$ para a da frequência $\nu$, temos

$$
    u(\nu,t)=\dfrac{\left(2\pi\nu\right)^2}{\pi^2c^3}2\pi U = \dfrac{8\pi\nu^2}{c^3}U(\nu, t)
$$


Uma vez determinada a relação entre a densidade de energia irradiada e a energia dos osciladores da cavidade, Plack se concentrou em encontrar a expressão para a entropia dos osciladores. 

Pela já bem conhecida Lei de deslocamento de Wien, sabia-se que a curva que representava a densidade de energia emitida por um corpo negro deveria seguir um formato específico $\rho(\nu,T)=\alpha \nu^3 f(\frac{\nu}{T})$.

Em 1893, o próprio Wien deu como palpite baseado nos dados experimentais da época que tal relação poderia ser expressa na forma,  

$$
    u(\nu,T)=\alpha \nu^3 \exp{\dfrac{\beta \nu}{T}}.
$$

Com a expresssão (\ref{eq7}) de Wien, Planck pode encontrar a expressão para a energia dos osciladores como \cite{Planck-a}

$$
    U(\nu,t)=\dfrac{\alpha c^3}{8\pi}\nu \exp{\left(-\dfrac{\beta \nu}{T}\right)}
$$

Que são os ingredientes necessários para obter a expressão para a entropia dos osciladores que descrevem a radiação de um corpo negro a altas frequências. Onde,


$$\begin{matrix}
   S=\displaystyle \int{\dfrac{dU}{T}}  & ~com~~~dU=\dfrac{\alpha c^3 \beta \nu^2}{8\pi T^2}\exp{\left(-\dfrac{\beta \nu}{T}\right)} dT 
\end{matrix}$$


Temos

$$
    S=\dfrac{\alpha c^3 \beta \nu^2}{8\pi}\int{\exp{\left(-\dfrac{\beta \nu}{T}\right)}\dfrac{dT}{T^3}}=\dfrac{\alpha c^3 \beta \nu^2}{8\pi(\beta \nu)^2}\exp{\left(-\dfrac{\beta \nu}{T}\right)}\left[\dfrac{\beta \nu}{T}+1\right]
$$
E usando (\ref{eq8}) em (\ref{eq9}), temos

$$ S=-\dfrac{U}{\beta \nu}\left[\ln{\left(\dfrac{8\pi}{\alpha c^3 \nu}U\right)}-1\right] $$

Permitindo Planck encontrar

$$
    \dfrac{\partial^2S}{\partial U^2}=-\dfrac{1}{\beta \nu U}.
$$

Entretanto, ainda no mesmo ano, em 1900. Novos experimentos mostravam que para baixas frequências a intensidade da radiação dependia de $\nu^2$ e não de $\nu^3$ como na expressão de Wiens (\ref{eq7}). E ainda, a expressão para baixas frequências era proporcional a temperaatura da forma $\rho (\nu,T)\propto\nu^2 T \implies U(T) \propto T$.

Significando que para baixas frequências a radiação da energia dos osciladores satisfazem a equipartição de energia $U(T)=\kappa_B T$, de modo que:

$$
 S=\int \dfrac{dU}{T}=\kappa_B\int\dfrac{dT}{T}=\kappa_B\ln{T}=\kappa_B\ln{\dfrac{U}{\kappa_B}} \implies \dfrac{\partial^2U}{\partial U^2}=-\dfrac{\kappa_B}{U^2}   
$$

Assim, com (\ref{eq10}) e (\ref{eq11}) é possível condensar os resultados na forma

$$\begin{matrix}
  \dfrac{\partial^2S}{\partial U^2}=-\dfrac{1}{\beta \nu U}   & para \nu \gg 0 \\
   \dfrac{\partial^2 U}{\partial U^2}=-\dfrac{\kappa_B}{U^2}  & \nu  \to 0
\end{matrix}$$

Para acomodar esses resultados limites na descrição de uma única entropia mais geral, Planck fez como palpite que a segunda derivada fosse expressa por meio da expressão

$$
    \dfrac{\partial^2 S}{\partial U^2}=-\dfrac{\kappa_B}{U\left(h\nu+U\right)}
$$

Onde $h=\kappa_B \beta = 6{,}628\times10^{-34}~ J\cdot s$.

Uma vez com a expressão adequada para segunda derivada da entropia, foi possível rederivar a expressão correta da energia dos osciladores harmônicos responsáveis por irradiar radiação de corpo negro.
Integrando a equação em respeito a U, temos

$$
 \dfrac{dS}{dU}=-\kappa_B \int{\dfrac{dU}{U\left(h\nu+U\right)}}=-\dfrac{\kappa_B}{h\nu}\int{\dfrac{dU}{U}}+\dfrac{\kappa_B}{h\nu}\int{\dfrac{dU}{h\nu+U}}=\dfrac{\kappa_B}{h\nu}\left[\ln{\left(1+\dfrac{U}{h\nu}\right)}-\ln{\left(\dfrac{U}{h \nu}\right)}\right] $$

mas $\frac{dS}{dU}=\frac{1}{T}$, logo

$$\dfrac{\kappa_B}{h\nu}\left[\ln{\left(1+\dfrac{U}{h\nu}\right)}-\ln{\left(\dfrac{U}{h \nu}\right)}\right]=\dfrac{1}{T}~\implies~ \ln\left(\dfrac{1+\frac{U}{h\nu}}{\frac{U}{h\nu}}\right)=\dfrac{h\nu}{\kappa_B T} $$

Permitindo usar $U(T)$ na forma


$$
    U(T)=\dfrac{h\nu}{\exp{\left(\frac{h\nu}{\kappa_B T}\right)}-1} 
$$

### Lei de Stefan-Boltzmann

A primeira conjectura quantitativa com relação o comportamento de um corpo negro, foi realizada em 1879 por Joseph Stefan na forma

$$ j\left(T\right) = u/A = \sigma T^4 $$,

onde $\sigma = 5{,}67\times10^{-8} \frac{W}{m^2 K^4}$ é a constante de Stefan-Boltzmann e e $j(T)$ é a densidade de energia radiada por metro quadrado de uma determinada superfície a uma temperatura $T$.

Tal expressão foi novamente deduzida em $1884$ por Ludwig Boltzmann utilizando as grandezas termodinâmicas associadas as ondas eletromagnético emitidas por corpos negros.

Seja a expressão para a densidade de enegia eletromagnética volumétrica $u$

<details>  
<summary>{% include important.html content=" $$u = \frac{\epsilon_0}{2}\left(E^2+c^2B^2\right)$$ " %} </summary>  {% include note.html content="
  Seja o trabalho realizada pela força de lorentz

  $$ dW=\vec{F}\cdot d\vec{l} = q\left(\vec{E}+\vec{v}\times\vec{B}\right)\cdot\vec{v}dt= q\vec{E}\cdot\vec{v}dt $$
  
  
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

  $$\scriptsize{\frac{dW}{dt}=-\frac{d}{dt}\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\int_V d^3r \frac{1}{\mu_0}\vec{\nabla}\cdot(\vec{E}\times\vec{B})} $$

  $$ \small{-\dfrac{d}{dt}\displaystyle\int_V d^3r \frac{\epsilon_0}{2}(E^2+c^2B^2)-\oint_S \frac{1}{\mu_0}(\vec{E}\times\vec{B})\cdot\hat{n} d^2r} $$
  
  Ou ainda
  
  $$\frac{dW}{dt}=-\frac{d}{dt} \int_V u d^3r-\oint_S \vec{S}\cdot\hat{n} d^2r $$
  
  Onde  $u=\frac{\epsilon_0}{2}(E^2+c^2B^2)$  e $\vec{S}=\frac{1}{\mu_0}(\vec{E}\times\vec{B})$, constituindo a teorema de Poyting que correlaciona a densidade energia do campo eletromagnético  $u$ com o fluxo do vetor de poyting  $\vec{S}$.

  " %}
  </details>
  
 
e a densidade volumétrica de momento linear do campo eletromagnético $\vec{p_v}$



<details>
  <summary>{% include important.html content="$$ \vec{p_v}=\epsilon_0\left(\vec{E}\times\vec{B}\right).$$" %} </summary>
  {% include note.html content="
Seja,

Para  $q \rightarrow \int_V \rho d^3r$, temos que a expressão anterior pode ser reescrita da forma

 $$ \frac{d}{dt}\vec{P_Mec}= \int_V \rho \left(\vec{E}+\vec{v}\times\vec{B} \right)d^3r= \int_V \left(\rho\vec{E}+\vec{J}\times\vec{B} \right)d^3r $$

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








$$ $$

