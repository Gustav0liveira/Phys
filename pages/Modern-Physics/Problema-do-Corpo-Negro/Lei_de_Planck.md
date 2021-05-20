---
title: "Lei de Planck"
keywords: Física
tags: [Física]
sidebar: mydoc_sidebar
permalink: Lei_de_Planck.html
summary: Um corpo negro é um modelo físico que representa a idealização de um objeto que absorve e reemite radiação eletromagnética de forma perfeita.
---
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





