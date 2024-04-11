<div align="center" style="display: inline_block">
  <img align="center" alt="VS" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
  <img align="center" alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img align="center" alt="Markdown" src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" />
</div>

<br>
<div align="center">
  
<table>
<thead>
  <tr>
    <td rowspan="2"><img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Logo_CEFET-MG.png" alt="Image" width="200" height="200"></td>
    <td>Professor: Diego Ascanio</td>
    <td>Disciplina: Lab. de Micro</td>
  </tr>Contador de Interrupções Externas:

Objetivo: Crie um programa que use uma interrupção externa para contar o número de vezes que um botão é pressionado.
Detalhes: O contador deve ser incrementado a cada pressionamento de botão e o valor atual deve ser exibido no Serial Monitor. Utilize o pino 2 do Arduino UNO para a interrupção.

  <tr>
    <td>Aluno: <code>Celso Vinícius Sudário</code></td>
    <td>Matrícula: <code>20203003611</code></td>
  </tr>
</thead>
</table>

</div>

## Exercício 1

<div align="justify">

Contador de Interrupções Externas:

Objetivo: Crie um programa que use uma interrupção externa para contar o número de vezes que um botão é pressionado.
Detalhes: O contador deve ser incrementado a cada pressionamento de botão e o valor atual deve ser exibido no Serial Monitor. Utilize o pino 2 do Arduino UNO para a interrupção.

</div>

```C++
...
```

<p align="center">
<img src="imgs/" width="600"/> 
</p>
<p align="center">
<em>Figura 1: Captura de tela do exercicio 1 implementado.</em>
</p>

<div align=center>
Link do projeto: 
</div>
  
## Exercício 2

<div align="justify">

Medidor de Tempo de Interrupção:

Objetivo: Desenvolva um programa que meça o tempo entre duas interrupções externas em milissegundos.
Detalhes: O início e o fim do tempo devem ser disparados por dois botões diferentes, cada um conectado a seu próprio pino de interrupção (pino 2 e pino 3, por exemplo). Mostre o tempo decorrido no Serial Monitor.

</div>

```C++
...
```

<p align="center">
<img src="imgs/" width="600"/> 
</p>
<p align="center">
<em>Figura 2: Captura de tela do exercicio 2 implementado.</em>
</p>

<div align=center>
Link do projeto: 
</div>

## Exercício 3

<div align="justify">

Alarme de Interrupção com Cancelamento:

Objetivo: Faça um sistema de alarme onde uma interrupção externa ativada por um sensor de movimento (pushbutton, conectado ao pino 2) ligue um LED e emita um som através de um buzzer e mantenha o alarme ligado.
Detalhes: Adicione uma funcionalidade para desligar o alarme pressionando um botão, que também deve funcionar através de uma interrupção externa (conectado ao pino 3).

</div>

```C++
...
```

<p align="center">
<img src="imgs/aula2-03.png" width="600"/> 
</p>
<p align="center">
<em>Figura 3: Captura de tela do exercicio 3 implementado.</em>
</p>

<div align=center>
Link do projeto: 
</div>

## Exercício 4

<div align="justify">

Alarme com Função Soneca:

Objetivo: Faça um alarme que, ao ser disparado, emite um som e, se a função soneca for ativada, silencia por um período de tempo antes de soar novamente.
Detalhes: Utilize um buzzer para o som do alarme e botões para disparar (desligar) o alarme a ativar a função soneca. Se o alarme não for desligado pelo botão, ele deve desligar sozinho após 30 segundos de funcionamento.

</div>

```C++
...
```

<p align="center">
<img src="imgs/" width="600"/> 
</p>
<p align="center">
<em>Figura 4: GIF do exercicio 4 implementado.</em>
</p>

<div align=center>
Link do projeto: 
</div>
