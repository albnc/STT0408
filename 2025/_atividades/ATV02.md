---
output: pdf_document
latex-engine: lualatex
documentclass: article
papersize: a4
geometry: margin=10mm
fontsize: 11pt
colorlinks: true
---

| **UNIVERSIDADE DE SÃO PAULO** | **ESCOLA DE ENGENHARIA DE SÃO CARLOS** | 
|:--------------------------------|---------------------------------:|
| **STT0408** Fundamentos de Engenharia de Transportes  |   **1º semestre de 2025**  |
| **Atividade 2** : Resistência ao movimento e velocidade de cruzeiro | **Entrega**: Classroom |


# INSTRUÇÕES:

Considere as características da Locomotiva [**EMD GT46AC**](https://www.progressrail.com/en/Segments/Locomotive/Locomotives/FreightLocomotives/GT46AC.html) [^1].

[^1]: <https://www.progressrail.com/en/Segments/Locomotive/Locomotives/FreightLocomotives/GT46AC.html>

a. Monte uma planilha eletrônica com os dados da locomotiva, considerando as características do motor (potência e eficiência) e seus limites de aderência máxima (peso aderente do veículo) e tração máxima pela corrente elétrica (VMOC - *Velocidade Mínima em Operação Constante*), assim como do número de eixos e peso da locomotiva.

b. Calcule a **Força Motriz** da locomotiva em função da **Velocidade**. Na ausência de dados, adote valores para a eficiência do motor ($\eta$) e coeficiente de aderência ($f$).

c. Plote o gráfico **Velocidade vs. Força Tratora** para a locomotiva dada. O gráfico deve indicar as forças disponíveis para operações de 20\%, 40\%, 60\%, 80\% e 100\% da potência máxima. O gráfico deve ser o mais limpo possível: 
    
    - remova as casas decimais nos valores dos eixos; 
    - valores muito grandes devem ser apresentados em unidades milhar ($k \Rightarrow 10^3$) ou milhão ($M \Rightarrow 10^6$);
    - os eixos devem ter a identificação da *Variável* representada e sua respetiva **unidade de medida**, por exemplo "Peso [kg]";
    - defina uma escala para o intervalo de valores dos eixos do gráfico -- preferência a valores inteiros.


---

# QUESTÕES:

Adote: $\eta = 0,82$.

Submeta um arquivo PDF com os gráficos e a resposta das seguintes questões, 

1. Qual a **Velocidade Mínima de Operação Contínua** (VMOC) desta locomotiva?

2. Qual o **Peso Aderente** ($Td$), em kN, desta locomotiva? Quantos eixos motrizes?

3. Qual a **máxima força tratora** produzida pela locomotiva na **velocidade máxima**?

4. Considere a locomotiva operando na VMOC. Quais as **máximas forças tratoras** disponíveis nas condições de piso totalmente seco ($f_{1} = 0,33$) e úmido/sujo ($f_{2} = 0,11$)?

5. Considere a locomotiva operando no limite das **Forças de Aderência** das condições do item anterior. Quais as maiores velocidades possíveis para essas forças?