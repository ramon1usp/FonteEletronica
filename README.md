# Projeto da Fonte

## Sumário
[Integrantes](#Integrantes) <br />
[Objetivo](#objetivo) <br />
[Função de cada Componente](#funcao) <br />
[Componentes](#Componentes) <br />
[Imagens](#imagens) <br />
[Links](#Links)

## Integrantes
<h4> Ramon Moreira Machado - Nº USP 12543179 <br />
Victor Lucas de Almeida Fernandes - Nº USP 12675399 </h4>

<a name="objetivo"> </a>
## Objetivo do trabalho
Partindo de uma tomada com corrente alternada de 127V (pico de 179,6V)
e frequência de 60 Hz, construir uma fonte retificadora que consiga deixar 
a corrente contínua e ajustar a tensão para valores entre 3V e 12V.


<a name="funcao"> </a>
## Função de cada Componente

* **Transformador:** 
responsável pela redução da tensão que chega da tomada. O transformador
escolhido é capaz de modificar a ddp de 127V para 15V. Como a tensão máxima 
da fonte é de 12V, escolhemos um valor superior para garantir que esse resultado
consiga ser obtido.

* **Ponte de diodos:** 
responsável pela retificação do circuito, ou seja, por inverter o 
semiciclo negativo da corrente alternada. Assim, o circuito é abastecido com a corrente 
em ambos os semiciclos da corrente. No entanto, ainda existe variação na tensão, decorrente
da troca entre os semiciclos.


* **Capacitor:** 
responsável pela etapa de filtragem, que reduz a variação da tensão existente.
O capacitor é carregado durante a parte de crescimento da onda de corrente e descarregado
na parte de decrescimento. 

Um filtro capacitivo é um arranjo de circuito elétrico que tem a finalidade de reduzir variações de tensão e corrente de altas frequências. Basicamente os filtros capacitivos usados em fontes servem para eliminar uma tensão alternada pulsativa e transformá-la em uma (tensão contínua) que varia menos. Essa variação é chamada de tensão de ondulação ou ripple.

Usando um filtro capacitivo em um circuito retificador, obtém-se uma tensão de ripple resultante do descarregamento lento do capacitor em relação à fonte.[1] O dimensionamento do capacitor utilizado no filtro pode ser feito para gerar uma tensão de ripple controlada para ser posteriormente eliminada através de regulador zener, regulador linear ou outros tipos de regulagem. Para efetuar o dimensionamento, levamos em consideração que a capacitância de um capacitor é definida como:


* **Resistores:**


* **Potenciômetro:**


* **Diodo Zener:**


* **Transistor NPN**:

## Componentes

| Componente | Especificação | Valor |
| --- | --- | --- |
| Transformador | | |`R$ x`|
| Ponte de Diodos | | | |
| Capacitor | | | |
| Resistor | | | |
| Diodo Zener | | | |
| Potenciômetro | | | |
| Transistor | | | |

<a name="imagens"> </a>
## Imagens do circuito

## Links
