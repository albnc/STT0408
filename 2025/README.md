# STT0408 - Fundamentos de Engenharia de Transportes (2025)
Prof. André Luiz Cunha, Prof. José Reynaldo Setti

- [<span class="toc-section-number">1</span> Revisão de Planilhas
  Eletrônicas](#revisão-de-planilhas-eletrônicas)
- [<span class="toc-section-number">2</span> Veículos
  Ferroviários](#veículos-ferroviários)
  - [<span class="toc-section-number">2.1</span> Força Motriz em
    Veículos Ferroviários](#força-motriz-em-veículos-ferroviários)
    - [<span class="toc-section-number">2.1.1</span> Forças
      Atuantes](#forças-atuantes)
    - [<span class="toc-section-number">2.1.2</span> Equilíbrio de
      Forças](#equilíbrio-de-forças)
    - [<span class="toc-section-number">2.1.3</span> Força Motriz em
      motores elétricos](#força-motriz-em-motores-elétricos)
    - [<span class="toc-section-number">2.1.4</span> Eficiência de
      Transmissão](#eficiência-de-transmissão)
    - [<span class="toc-section-number">2.1.5</span> Tração por
      aderência em locomotivas](#tração-por-aderência-em-locomotivas)
  - [<span class="toc-section-number">2.2</span> Resistências em
    Veículos Ferroviários](#resistências-em-veículos-ferroviários)
    - [<span class="toc-section-number">2.2.1</span> Resistência ao
      Rolamento](#resistência-ao-rolamento)
    - [<span class="toc-section-number">2.2.2</span> Resistência
      Aerodinâmica](#resistência-aerodinâmica)
    - [<span class="toc-section-number">2.2.3</span> Resistência de
      Rampa](#resistência-de-rampa)
    - [<span class="toc-section-number">2.2.4</span> Resistência de
      Curva](#resistência-de-curva)
  - [<span class="toc-section-number">2.3</span> Comprimento máximo do
    trem](#comprimento-máximo-do-trem)
- [<span class="toc-section-number">3</span> Veículos
  Rodoviários](#veículos-rodoviários)
  - [<span class="toc-section-number">3.1</span> Força Motriz em
    Veículos Rodoviários](#força-motriz-em-veículos-rodoviários)
    - [<span class="toc-section-number">3.1.1</span> Força motriz em
      motor à combustão](#força-motriz-em-motor-à-combustão)
    - [<span class="toc-section-number">3.1.2</span> Força de aderência
      em veículo rodoviário](#força-de-aderência-em-veículo-rodoviário)
    - [<span class="toc-section-number">3.1.3</span> Velocidade em
      caminhões](#velocidade-em-caminhões)
  - [<span class="toc-section-number">3.2</span> Resistências em
    Veículos Rodoviários](#resistências-em-veículos-rodoviários)
    - [<span class="toc-section-number">3.2.1</span> Resistência ao
      Rolamento](#resistência-ao-rolamento-1)
    - [<span class="toc-section-number">3.2.2</span> Resistência
      Aerodinâmica](#resistência-aerodinâmica-1)
    - [<span class="toc-section-number">3.2.3</span> Resistência de
      Rampa](#resistência-de-rampa-1)

------------------------------------------------------------------------

# Revisão de Planilhas Eletrônicas

**Objetivo**  
Aula introdutória e de nivelamento em programação aplicada a planilhas
eletrônicas. A automação de cálculos é uma ferramenta fundamental no
desenvolvimento de projetos de Engenharia, além de desempenhar um papel
essencial no planejamento e execução do projeto desta disciplina.

**Material de referência**  
Aqui estão alguns livros recomendados para quem deseja se aprofundar em
programação eficiente com planilhas.

- “*[Crie Planilhas Inteligentes com o Microsoft Office Excel 2003.
  Avançado](https://www.amazon.com.br/Planilhas-Inteligentes-Microsoft-Office-Avan%C3%A7ado/dp/8571949921)*” -
  Haddad & Haddad

- “*[Ctrl+shift+enter: A Book about Building Efficient
  Formulas](https://www.amazon.com/Shift-Enter-Mastering-Excel-Formulas/dp/1615470077)*” -
  Mike Girvin

- “*[Microsoft 365 Excel: The Only App That
  Matters](https://www.amazon.com/Microsoft-365-Excel-Calculations-Analytics/dp/1615470700)*” -
  Mike Girvin

------------------------------------------------------------------------

# Veículos Ferroviários

## Força Motriz em Veículos Ferroviários

### Forças Atuantes

- Força Motriz ou Tratora ($F_{t}$)
- Resistências ($R_{t}$)
- Força Peso ($G$)
- Força Normal ($N$)

<img src="_img/locomotive.png" style="width:50.0%" alt="Forces" />

### Equilíbrio de Forças

- $F_{t} < R_{t} \Rightarrow$ desacelerando
- $F_{t} > R_{t} \Rightarrow$ acelerando
- $F_{t} = R_{t} \Rightarrow$ velocidade constante

### Força Motriz em motores elétricos

A *Potência* é derivada do *Trabalho de uma Força*, portanto:

$$
P = \frac{dW}{dt} \Rightarrow \frac{d(F \cdot S )}{dt} \Rightarrow F \cdot \frac{dS}{dt} \Rightarrow F \cdot v
$$

Sendo:

- $W$ o Trabalho da Força \[W - *Watt*\]

- $F$ a resultante da Força \[N - *Newton*\]

- $S$ o deslocamento \[m - *metros*\]

- $v$ a velocidade do veículo \[m/s\]

Para o cálculo da Força Motriz em função da Potência, utilizamos a
seguinte equação com as unidades métricas:

$$
F_{t} = 3,6 \cdot \frac{P}{v}
$$

Sendo:

- $F$ força motriz \[kN\]

- $P$ a potência máxima do motor **\[kW\]**

- $v$ a velocidade do veículo \[km/h\]

Para outras unidades temos:

$$
F_{t} = 2,685 \cdot \frac{P}{v}
$$

Em que:

- $F$ força motriz \[kN\]

- $P$ a potência máxima do motor **\[hp\]**

- $v$ a velocidade do veículo \[km/h\]

$$
F_{t} = 2,649 \cdot \frac{P}{v}
$$

Tal que:

- $F$ força motriz \[kN\]

- $P$ a potência máxima do motor **\[cv\]**

- $v$ a velocidade do veículo \[km/h\]

### Eficiência de Transmissão

Em todo motor existem perdas resultante do atrito das peças, do sistema
de transmissão, dos sistemas auxiliares (compressor, corrente,
alternador, etc.). Portanto admitimos uma eficiência $\eta$, em
locomotivas, em torno de **0,82**:

$$
F_{t} = \eta \cdot 3,6 \cdot \frac{P}{v}
$$

Dessa forma, o gráfico da $F_{t} = f(V)$, para uma **Potência**
constante de, por exemplo, $1.500$ kW será de:

$$
F_{t} = \eta \cdot 3,6 \cdot \frac{P}{v} \rightarrow 0,82 \cdot 3,6 \cdot \frac{1500}{v_i}
$$ $$
F_{t} = \frac{4428}{v_i}~[kN], \forall v_i \in [0,90]~km/h
$$

![](README_files/figure-commonmark/unnamed-chunk-2-1.png)

É importante observar que este gráfico apresenta valores tendendo ao
infinito nas extremidades, e sabemos que os motores tem limitações, a
saber:

1.  da corrente elétrica (máxima força tratora disponível) no eixo Y,
2.  da voltagem ou rotação do motor (máxima velocidade disponível) no
    eixo X.

Dessa forma, a função anterior fica limita a esses dois limites. Como
exemplo, considere a velocidade máxima de 90 km/h e a força tratora
máxima pela corrente elétrica ($F_{CE}$), limitada pela **Velocidade
Mínima de Operação Constante** (VMOC) de 20 km/h.

$$
F_{CE} = \eta \cdot 3,6 \cdot \frac{P}{VMOC} \rightarrow 0,82 \cdot 3,6 \cdot \frac{1500}{20}
$$ $$
F_{CE} = 221.4~kN
$$

![](README_files/figure-commonmark/unnamed-chunk-3-1.png)

### Tração por aderência em locomotivas

Para que as rodas da locomotiva não patinem, a **Força Tratora** que o
motor despeja nas rodas deve ser menor que a **Força de aderência**
entre o trilho e as rodas: $F_{t} \leq F_{a}$.

Portanto a **Força Motriz Máxima** está limitada pela **aderência** da
interface roda-trilho:

$$
Ft_{max} \leq f \cdot T_{d}
$$

Em que:

- $T_{d}$ é o peso aderente \[kN\]

- $f$ é a aderência

A tabela abaixo[^1] descreve valores típicos do *coeficiente de
aderência* $f$ para várias condições do trilho.

| ***Estado do trilho*** | ***Aderência*** |
|:-----------------------|----------------:|
| Totalmente seco        |            0,33 |
| Lavado pela chuva      |            0,33 |
| Seco e limpo           |            0,22 |
| Seco                   |            0,20 |
| Molhado pela chuva     |            0,14 |
| Úmido de orvalho       |           0,125 |
| Úmido e sujo           |            0,11 |
| Sujo de óleo           |            0,10 |

*Coeficientes de aderência para condições do trilho*

------------------------------------------------------------------------

**EXEMPLO: Força Tratora**

Considere uma locomotiva com Massa Bruta Total ($G_{loc}$) de 100
toneladas – como todos os eixos são tratores, o peso aderente será
$T_d = G_{loc} \cdot g$, em que $g$ é aceleração da gravidade – e um
fator de aderência $f$ de 0,20, portanto:

$$
Ft_{max} = f \cdot T_{d} \rightarrow 0,20 \cdot (100 \cdot 10)
$$

$$
Ft_{max} = 200~kN
$$

![](README_files/figure-commonmark/unnamed-chunk-4-1.png)

> [**ATIVIDADE 1**](_atividades/ATV01.pdf)

## Resistências em Veículos Ferroviários

As forças resistivas ao movimento de um veículo ferroviário podem ser
representadas por:

$$
R_t = R_r + R_a + R_g + R_c
$$

Sendo,

- $R_t$ : resistência total \[kN\]

- $R_r$ : resistência ao rolamento \[kN\]

- $R_a$ : resistência aerodinâmica \[kN\]

- $R_g$ : resistência de rampa \[kN\]

- $R_c$ : resistência de curva \[kN\]

Dentre todas as parcelas, as resistências **ao rolamento e
aerodinâmica** sempre existirão, o que denominamos de ***Resistência
Básica*** ou ***Resistência Inerente***.

### Resistência ao Rolamento

Segundo o modelo proposto por Davis (1910):

$$
R_r = \left( c_1 + \frac{c_2 \cdot x}{G} + c_3 \cdot V \right) \cdot \frac{G}{1000}
$$

Em que,

- $R_r$ : resistência ao rolamento \[kN\]

- $x$ : número de eixos da locomotiva ou vagão

- $G$ : peso da locomotiva ou vagão \[kN\]

- $V$ : velocidade do veículo \[km/h\]

- $c_1$ : constante que incorpora o efeito da deformação da roda e do
  trilho ($\approx 0,65$)

- $c_2$ : constante que incorpora o efeito do atrito dos mancais
  ($\approx 125$)

- $c_3$ : constante que incorpora o efeito do atrito entre friso das
  rodas e trilho (passageiro e locomotiva $\approx 0,009$; vagão
  $\approx 0,013$)

### Resistência Aerodinâmica

$$
R_a = \frac{c_a \cdot A \cdot V^2}{1000}
$$

Tal que,

- $R_a$ : resistência aerodinâmica \[kN\]

- $c_a$ : coeficiente aerodinâmico [^2]

- $A$ : área frontal do veículo \[m²\]

| **Tipo de veículo**       | **Área frontal (m²)** | **$c_a$** |
|:--------------------------|:----------------------|----------:|
| Locomotiva de carga       | 9 – 14,5              |     0,046 |
| Locomotiva de passageiros | 9 – 11                |     0,031 |
| Vagões de carga           | 7,5 – 8,5             |     0,009 |
| Carros de passageiros     | 10 – 11               |     0,006 |

*Coeficientes aerodinâmico para veículos ferroviários*

### Resistência de Rampa

$$
R_g = G \cdot i
$$

Em que,

- $R_g$ : resistência de rampa em \[kN\]

- $G$ : peso do veículo (locomotiva ou vagão) \[kN\]

- $i$ : declividade da rampa \[% – em decimal\]

### Resistência de Curva

$$
R_c = 0,698 \cdot \frac{G}{r}
$$

Sendo,

- $R_c$ : resistência de curva \[kN\]

- $G$ : peso do veículo (locomotiva ou vagão) \[kN\]

- $r$ : raio de curva \[m\]

------------------------------------------------------------------------

**EXEMPLO: Resistências**

Considere a locomotiva descrita anteriormente, área frontal de 10 m² e 6
eixos, rebocando 10 vagões com massa de 80 toneladas, área frontal de 8
m² e 4 eixos cada. Considere o trecho plano e um aclive de 1,0%, sem
curva. Utilizando as equações e parâmetros anteriores teremos:

![](README_files/figure-commonmark/unnamed-chunk-5-1.png)

Perceba que no trecho plano, a velocidade de equilíbrio para o trem do
exemplo (1 locomotiva + 10 vagões) é em torno de 44 km/h. Já no aclive
de 1,0%, a composição tem velocidade de equilíbrio de 22 km/h. Ambas as
situações considerando a Potência máxima da locomotiva, portanto
cruzando com a curva da Froça Tratora ($F_t$). Lembre-se que toda a área
abaixo da curva de $F_t$ é possível de ser operada.

> [**ATIVIDADE 2**](_atividades/ATV02.pdf)

## Comprimento máximo do trem

Para determinar o máximo comprimento que um trem pode trafegar, é
necessário analisar o **trecho mais crítico**, ou seja, a rampa mais
íngreme. Assim, dimensionando o número de locomotivas e vagões para o
prior trecho, todos os demais segmentos da via serão atendidos.

Portanto o dimensionamento segue o seguinte procedimento:

1.  Determine o **trecho crítico**, aclive mais íngreme;

2.  Para este trecho, determine a velocidade de operação ($V_{op}$) a
    ser adotada, lembrando que não se pode operar a locomotiva abaixo da
    **VMOC** – *Velocidade Mínima de Operação Constante*;

3.  Para a $V_{op}$, determine a relação do ***número de vagões que uma
    locomotiva consegue rebocar***:

$$
F_t - R_t = m \cdot a \rightarrow F_t = R_t
$$

$$
F_t(V_{op}) = R_t^{Loc}(V_{op}) + n^{Vag} \cdot R_t^{Vag}(V_{op})
$$

$$
n^{Vag} = \frac{F_t(V_{op}) - R_t^{Loc}(V_{op})}{R_t^{Vag}(V_{op})}
$$

Esta última equação mostra que a **Força Disponível para tracionar os
vagões** nada mais é do que a força resultante da diferença entre a
Força Máxima do motor na Velocidade Operacional pela Resistência da
Locomotiva.

4.  Guarde esta relação: 1 Locomotiva $\rightarrow n^{Vag}$.

5.  A partir da **Força Máxima do Engate** ($F_{eng}$), em torno de
    1.200 a 1.500 kN, determine qual a quantidade máxima de vagões que o
    engate é capaz de suportar:

$$ 
n_{max.Vag} = \frac{F_{eng}}{R_{t}^{Vag}(V_{op})} 
$$

6.  A patir dos valores dos itens (4) e (5), determine o tamanho da
    composição em termos de: $n_{Loc}$ locomotivas transportanto
    $n_{vag}$ vagões.

> [**ATIVIDADE 3**](_atividades/ATV03.pdf)

------------------------------------------------------------------------

# Veículos Rodoviários

## Força Motriz em Veículos Rodoviários

As equações de Força Motriz seguem os mesmos princípios de **Veículos
Ferroviárias**.

### Força motriz em motor à combustão

O cálculo da Força Motriz nos indica as forças que o motor é capaz de
gerar.

$$
F_{t} = \eta \cdot 3,6 \cdot \frac{P}{v}
$$

Sendo:

- $F$ força motriz \[kN\]

- $\eta$ eficiência de transmissão ($\approx 0,82$)

- $P$ a potência máxima do motor **\[kW\]**

- $v$ a velocidade do veículo \[km/h\]

### Força de aderência em veículo rodoviário

A **Força Máxima de aderência** é o limite disponível que determinado
tipo de pavimento oferece para o uso, ou seja, se o veículo aplicar uma
força maior que a **Força Máxima de aderência**, o veículo irá patinar.
Portanto é função do fator de aderência ($f$) e do **Peso aderente**
($T_{d}$).

> \[!CAUTION\]  
> EM CAMINHÕES, O PESO ADERENTE É FUNÇÃO DA QUANTIDADE DE EIXOS
> MOTRIZES. VERIFIQUE SE O CAMINHÃO É DO TIPO: 4X2, 6X2, 6X4 OU OUTRA
> CONFIGURAÇÃO. DIFERENTE DAS LOCOMOTIVAS, **EM CAMINHÕES APENAS OS
> EIXOS MOTRIZES SÃO COMPUTADOS NO `PESO ADERENTE` ($T_{d}$)**.

![cv-trucks](_img/cv-trucks.jpg)

A seguir, a tabela [^3] com fatores de aderência para diferentes tipos
de pavimentos.

| ***Superfície***         | ***Aderência*** |
|:-------------------------|----------------:|
| Asfalto ou concreto seco |     0,80 – 0,90 |
| Concreto molhado         |            0,80 |
| Asfalto molhado          |     0,50 – 0,70 |
| Pedrisco                 |            0,60 |
| Terra firme seca         |            0,70 |
| Terra solta seca         |            0,45 |
| Terra firma úmida        |            0,55 |
| Areia seca               |            0,20 |
| Areia úmida              |            0,40 |
| Neve                     |            0,20 |
| Gelo                     |            0,10 |

*Fatores de aderência para pavimentos rodoviários*

### Velocidade em caminhões

As diferenças no equacionamento de veículos ferroviários estão em:

- Potência não constante, em função da rotação do motor;
- Caixa de câmbio, o que proporciona diferentes forças para cada marcha.

Assim, é necessário calcular a velocidade que o motor consegue entregar,
em função da marcha, da rotação do motor, do diferencial e do diâmetro
do pneu:

$$
V = \frac{60 \cdot N}{g_{t} \cdot g_{d}} \cdot \frac{\pi \cdot D}{1000}
$$

Em que:

- $V$ : a velocidade do veículo \[km/h\]

- $N$ : a rotação do motor por minuto \[rpm\]

- $g_{t}$ : fator de redução da caixa de câmbio (um valor para cada
  marcha)

- $g_{d}$ : fator de redução do diferencial

- $D$ : diâmetro do pneu

> [**ATIVIDADE 4**](_atividades/ATV04.pdf)

## Resistências em Veículos Rodoviários

A força resistiva ao movimento de um veículo rodoviário é composta de
três parcelas a saber:

$$
R_t = R_r + R_a + R_g
$$

Sendo,

- $R_t$ : resistência total \[kN\]

- $R_r$ : resistência ao rolamento \[kN\]

- $R_a$ : resistência aerodinâmica \[kN\]

- $R_g$ : resistência de rampa \[kN\]

Dentre as parcelas, as resistências **ao rolamento e aerodinâmica**
sempre existirão, portanto é denominada de ***Resistência Básica*** ou
***Resistência Inerente***.

### Resistência ao Rolamento

A resistência de rolamento para veículos rodoviários pode ser estimada
pela seguinte equação:

$$
R_r = \left( c_1 + c_2 \cdot V \right) \cdot \frac{G}{1000}
$$

Em que,

- $R_r$ : resistência ao rolamento \[kN\]

- $G$ : peso do veículo \[kN\]

- $V$ : velocidade do veículo \[km/h\]

- $c_1$ : constante que incorpora o efeito da deformação do pneu no
  pavimento (rodovias pavimentadas – asfalto ou concreto) $\approx 7,6$

- $c_2$ : constante que reflete o efeito de outros fatores na
  resistência ($\approx 0,056$)

### Resistência Aerodinâmica

O modelo simplificado de resitência aerodinâmica é:

$$
R_a = \frac{c_a \cdot A \cdot V^2}{1000}
$$

Tal que,

- $R_a$ : resistência aerodinâmica \[kN\]

- $c_a$ : coeficiente de penetração aerodinâmico [^4]

- $A$ : área frontal do veículo \[m²\]

| **Veículo** | **Área frontal (m²)** |     **$c_a$** |
|:------------|:----------------------|--------------:|
| Automóveis  | 2,5 – 3,5             | 0,020 a 0,025 |
| Ônibus      | 7,0 – 9,0             | 0,035 a 0,040 |
| Caminhões   | 6,0 – 9,0             | 0,028 a 0,040 |

*Coeficientes aerodinâmicos para veículos rodoviários*

### Resistência de Rampa

$$
R_g = G \cdot i
$$

Em que,

- $R_g$ : resistência de rampa em \[kN\]

- $G$ : peso do veículo \[kN\]

- $i$ : declividade da rampa \[% – em decimal\]

> [**ATIVIDADE 5**](_atividades/ATV05.pdf)

[^1]: Hay, W. (1982) *Railroad Engineering*. Wiley & Sons, New York, 2ª
    edição.

[^2]: Setti, J.R. (2002) *Tecnologia de Transportes*. Notas de aula,
    USP-EESC.

[^3]: Setti, J.R. (2002) *Tecnologia de Transportes*. Notas de aula,
    USP-EESC.

[^4]: Setti, J.R. (2002) *Tecnologia de Transportes*. Notas de aula,
    USP-EESC.
