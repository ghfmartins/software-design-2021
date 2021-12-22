Desafio 4x4

Para resolver este problema proponho a seguinte solução:

App: MagicSquarePro
- Elaboraremos um jogo para celular e navegadores web utilizando o modelo de PWA(Progressive Web App) e será construído utilizando front-end em React e back-end em NodeJs.

- O jogo seguirá as regras do jogo quadrado mágico 4x4.

- O Usuário poderá se cadastrar usando seu email e utilizará um nickname para login assim manterá uma conta com todos os seus resultados e pontuações e será identificado por um apelido.

- Nesta aplicação os usuários tentarão resolver o desafio e aqueles que conseguirem receberam uma pontuação.

- A pontuação será escalonada de acordo com o tempo que o usuário gastou para encontrar uma resposta válida (quanto menor, maior a pontuação) e se está é uma resposta única.

- Sempre que o usuário encontrar uma resposta válida esta será comparada com um banco de dados com todas as respostas únicas já encontradas anteriormente.

- Assim, validaremos se aquela é a primeira ocorrencia da resposta e daremos uma pontuação maior aquele jogador e salvaremos a resposta no nosso banco de dados.

- Para incentivar o usuário, teremos diferentes sistemas de rankings para que este possa competir com amigos e os demais usuários do jogo: 
	I - O primeiro ranking será de pontuação geral, adquiridos sempre que encontrar uma reposta válida para os desafios (quanto maior, melhor ranqueado).
	II - O segundo será um ranking de respostas únicas de um quadrado com n linhas encontradas por usuário(quanto maior, melhor ranqueado).
	III - O terceiro será o por número de respostas válidas encontradas (quanto maior, melhor ranqueado).
  
- O jogador terá acesso a um histórico com todas as respostas válidas que encontrou e também conhecerá a quantidade de respostas únicas já encontradas em toda a aplicação para que possa tentar encontrá-las também.

- Como padrão, o jogo utiliza o quadrado mágico 4x4, contudo o usuário poderá tentar resolver quadrados maiores, limitado ao máximo de 10x10, ou menor de 3x3.

- Ao final de um período de 6 meses os usuários mais ativos serão premiados.
