#🚀 Quiz Interativo de Matemática
Bem-vindo ao Quiz Interativo de Matemática! Um jogo dinâmico e divertido, criado para testar seus conhecimentos matemáticos de uma forma moderna e engajante. O projeto foi desenvolvido com tecnologias web de ponta, focado em uma experiência de usuário rica e interativa.

✨ Features Principais
Este não é um quiz comum! Ele foi turbinado com diversas funcionalidades para torná-lo mais divertido e desafiador:

🧠 Níveis de Dificuldade: Escolha entre os modos Fácil e Difícil para adaptar o desafio ao seu nível.

📚 Banco de 100 Perguntas: Uma vasta coleção de perguntas de matemática para o 5º ano, cada uma categorizada por dificuldade.

🎲 Seleção Aleatória: A cada partida, 7 perguntas são sorteadas aleatoriamente, garantindo que o jogo seja sempre uma nova experiência.

⏱️ Pontuação por Tempo: Responda rápido! Quanto mais rápido você acertar, mais pontos ganha.

🏆 Sistema de Recordes: O jogo salva sua maior pontuação (High Score) no navegador, incentivando você a se superar.

💥 Animações e Micro-interações: Respostas corretas "pulam" e incorretas "tremem". A pontuação sobe com uma animação suave.

🔊 Efeitos Sonoros: Feedback sonoro para acertos, erros e um "tique-taque" de tensão nos segundos finais do cronômetro.

📊 Barra de Progresso: Acompanhe seu avanço visualmente durante a partida.

📱 Design Responsivo: Jogue confortavelmente em qualquer dispositivo, seja no computador, tablet ou celular.

🎉 Efeitos de Confete: Celebre um novo recorde ou uma resposta correta com uma chuva de confetes!

🛠️ Tecnologias Utilizadas
Este projeto foi construído inteiramente com tecnologias front-end, em um único arquivo para simplicidade e portabilidade.

HTML5: Para a estrutura semântica do conteúdo.

Tailwind CSS: Um framework CSS utilitário para criar um design moderno e responsivo rapidamente.

JavaScript (ES6+): O cérebro do jogo, controlando toda a lógica, interatividade, animações e efeitos sonoros.

🚀 Como Executar
É muito simples! Como o projeto não depende de nenhum servidor ou compilação, basta seguir os passos:

Faça o download do arquivo quiz.html.

Certifique-se de que a imagem logofiapcsohol.png esteja na mesma pasta que o arquivo HTML.

Abra o arquivo quiz.html em qualquer navegador de internet moderno (Chrome, Firefox, Edge, etc.).

Pronto! Comece a jogar.

📂 Estrutura do Código
Todo o código está contido no arquivo quiz.html. A seção <script> é organizada da seguinte forma:

quizData: Um array de objetos que funciona como o banco de dados, contendo todas as 100 perguntas, suas alternativas e o nível de dificuldade.

Variáveis Globais: Seletores de elementos do DOM e variáveis para controlar o estado do jogo (pontuação, pergunta atual, etc.).

Funções de Áudio: Lógica para gerar os efeitos sonoros de acerto, erro e do cronômetro usando a Web Audio API.

Funções do Jogo:

startQuiz(): Inicia o jogo, filtra as perguntas pela dificuldade escolhida e embaralha a seleção.

setNextQuestion(): Prepara e exibe a próxima pergunta.

selectAnswer(): Processa a resposta do jogador, calcula a pontuação e dá o feedback visual e sonoro.

showResults(): Exibe a tela final com a pontuação e verifica se um novo recorde foi estabelecido.

Funções de High Score: Funções get e set que utilizam o localStorage do navegador para persistir a maior pontuação.

Funções do Timer: Controlam a lógica do cronômetro regressivo, a animação do círculo e a mudança de cores.

Funções de Efeitos Visuais: Como o triggerConfetti(), que cria as animações de celebração.

Inicialização: Adiciona os event listeners aos botões para dar início ao jogo.

Este projeto foi criado como uma demonstração de desenvolvimento web front-end interativo.
