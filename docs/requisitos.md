Requisitos do Projeto

1. Objetivo

   Criar um site rápido para realização de simulados de legislação de trânsito, utilizando questões focadas nos tópicos que o usuário precisa estudar.

2. Público-alvo

   Estudante candidato à cnh

3. Escopo do MVP

- Apresentar uma tela inicial para seleção do tópico do simulado.
- Disponibilizar os tópicos Placas, Pontuação e PPD como opções selecionáveis.
- Ao selecionar um tópico, o sistema deverá iniciar o simulado correspondente.
- Iniciar o simulado.
- Apresentar as 10 questões, uma por vez, com quatro alternativas e apenas uma resposta correta.
- Permitir a seleção de uma alternativa antes de avançar para a próxima questão.
- Apresentar o botão "Próxima" nas questões iniciais.
- Na última questão, apresentar o botão "Finalizar Simulado".
- Apresentar o resultado ao finalizar, com número de acertos e porcentagem.
- Permitir visualizar as respostas corretas após a finalização.

4. Fluxo do

-1. O usuário acessa a tela inicial.
-2. O sistema apresenta os tópicos Placas, Pontuação e PPD.
-3. O usuário seleciona um tópico.
-4. O sistema inicia o simulado correspondente.
-5. O sistema apresenta a primeira questão.
-6. O usuário seleciona uma alternativa.
-7. O usuário avança para a próxima questão.
-8. O processo se repete até a décima questão.
-9. Na décima questão, o usuário seleciona uma alternativa e finaliza o simulado.
-10.O sistema apresenta o resultado.
-11.O usuário pode visualizar as respostas corretas.

5. Regras de negócio

- O simulado terá 10 questões.
- Cada questão terá 4 alternativas e apenas 1 resposta correta.
- Cada questão valerá 1 ponto.
- O usuário deverá selecionar uma alternativa antes de avançar.
- Caso tente avançar sem selecionar uma alternativa, o sistema deverá impedir o avanço e informar que é necessário selecionar uma resposta para continuar.
- O usuário não poderá voltar para questões anteriores.
- O usuário não poderá alterar uma resposta depois de avançar.
- A resposta correta não será informada durante o simulado.
- O resultado será apresentado somente após a finalização.
- A pontuação será calculada com base no número de respostas corretas.
- A porcentagem de acertos será calculada considerando as 10 questões.

6. Critérios de conclusão
   O MVP será considerado concluído quando:

- O usuário conseguir iniciar o simulado.
- As 10 questões forem apresentadas corretamente, uma por vez.
- O usuário conseguir selecionar uma alternativa em cada questão.
- O sistema impedir o avanço quando nenhuma alternativa estiver selecionada e apresentar uma mensagem explicativa.
- O sistema registrar a resposta selecionada ao avançar.
- O usuário não conseguir retornar às questões anteriores.
- O usuário não conseguir alterar uma resposta já registrada.
- O botão "Finalizar Simulado" aparecer na última questão.
- O sistema calcular corretamente o número de acertos e a porcentagem.
- O sistema apresentar o resultado após a finalização.
- O usuário conseguir visualizar suas respostas e as respostas corretas após finalizar.
- O usuário conseguir iniciar um novo simulado.
- O sistema funcionar adequadamente em computadores e dispositivos móveis.

7. Melhorias futuras

- 30 questões.
- Banco maior de questões.
- Sorteio das questões.
- Filtro por tópico.
- Explicação das respostas.
- Indicador de progresso.
- Histórico de resultados.
- Estatísticas de desempenho.
- Acessibilidade aprimorada.
- Opção de imprimir ou salvar o simulado para consulta física.
