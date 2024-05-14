## Quiz de Fatos Históricos

Esse projeto foi desenvolvido em JavaScript e é executado no Node JS. Ele seleciona 10 perguntas aleatórias de História de uma base de dados com 30 questões. 

Foi utilizado um plugin denominado ‘’readline-sync” para que haja interação com o usuário. 
O projeto apresenta além da base de dados citada acima, cinco funções: 
- iniciaQuiz(): Faz a saudação inicial e chama as demais funções para o funcionamento da aplicação.
- selecionarPerguntasAleatorias(): Recebe a base dados, embaralha essa base e seleciona 10 perguntas.
- exibePerguntas(): Recebe as 10 perguntas, salva a resposta do usuário para cada uma delas e dá um feedback para acerto ou erro do usuário com auxílio da próxima função. 
- confereResposta(): Confere a resposta do usuário.
- finalizaQuiz(): Retorna a quantidade de acertos que o jogador teve.
