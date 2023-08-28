## Desafio Concluído: Controle de Fluxo em Java

Olá, pessoal! Neste desafio, desenvolvi uma solução em Java para realizar a contagem e impressão de números inteiros de acordo com os parâmetros fornecidos via terminal. A solução abordou cenários onde a quantidade de interações é definida pelo intervalo entre os números fornecidos.

**Funcionamento da Solução:**

- A classe `Contador.java` é responsável por implementar a lógica do programa. Ela recebe dois números inteiros como parâmetros via terminal.
- A quantidade de interações (for) é calculada a partir da diferença entre os dois números fornecidos.
- Durante cada interação, o programa imprime a mensagem "Imprimindo o número X", onde X é o número atual da interação.
- Caso o primeiro parâmetro seja maior que o segundo, a exceção customizada `ParametrosInvalidosException` é lançada com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

Este desafio foi proposto pelo professor Gleyson Sampaio através da plataforma Digital Innovation One (DIO) durante um bootcamp em back-end em Java.
