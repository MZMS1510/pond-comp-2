# Ponderada de Computação #2

## Marcos Vinicius Marcondes Silva

## Descrição

Nesta ponderada, utilizamos um citcuito RC para realizar o deboucing de um botão, abaixo podemos observar dois sistemas que utilizam botões, um que não utiliza capacitores e outro que utiliza

![Circuito criado no TinkerCAD](./ponderada2.png)

O segundo circuito (o que utiliza capacitores), contém o script presente em [`pond-comp-2.ino`](./pond-comp-2.ino), que printa no console o tempo de execução do programa, a tensão do capacitor e a tensão do resistor.

## Análise de dados

Para observar a transferêcia da tensão entre o resistor e o capacitor, pegamos as informações impressas no console e colocamos ela como input no notebook [`graph.ipynb`](./graph.ipynb). A partir disso, podemos obter o seguinte gráfico:

![Gráfico de transferência de tensão](./graph.png)

## Referências

UNIVESP. **Eletromagnetismo - Aula 28 - Circuitos RC, RL e LC**. Disponível em: https://youtu.be/xjI9Ju2RHOg?si=sLxEbpnSH0gvNg9H
