Jogo do Número Secreto 🎮

Um jogo web interativo e divertido onde o objetivo é adivinhar o número secreto gerado aleatoriamente pelo sistema. O jogo fornece dicas visuais e em áudio para ajudar o jogador a encontrar a resposta correta.

📝 Sobre o Projeto

Este projeto é uma aplicação web simples desenvolvida para praticar lógicas de programação em JavaScript, manipulação do DOM e integração com APIs externas (neste caso, a ResponsiveVoice para acessibilidade em áudio). O sistema escolhe um número de 1 a 10, e o usuário deve inserir palpites até acertar.

✨ Funcionalidades

Sorteio Aleatório: Geração de um número secreto único a cada rodada.

Lógica de Não-Repetição: O sistema garante que os números não se repitam em partidas consecutivas até que todos os números possíveis (1 a 10) tenham sido sorteados.

Feedback Interativo: Dicas na tela informando se o número secreto é "maior" ou "menor" que o palpite atual.

Contador de Tentativas: Registra e exibe quantas tentativas foram necessárias para acertar.

Acessibilidade em Áudio: Integração com a API ResponsiveVoice para ler em voz alta os textos da tela (em Português do Brasil).

Interface Responsiva: Layout que se adapta a diferentes tamanhos de tela.

🚀 Tecnologias Utilizadas

HTML5: Estruturação semântica da página.

CSS3: Estilização, layout Flexbox e design responsivo.

JavaScript: Lógica de programação, manipulação do DOM e eventos.

ResponsiveVoice API: Para a funcionalidade de Text-to-Speech (leitura de texto).

Google Fonts: Utilização das fontes Chakra Petch e Inter.

📂 Estrutura de Arquivos

index.html: Contém a estrutura principal da página e a importação de scripts e estilos.

style.css: Contém toda a estilização visual do projeto.

app.js: Contém toda a lógica do jogo e funções de interatividade.

💻 Como Executar o Projeto

Faça o download ou clone este repositório para o seu computador.

Certifique-se de estar conectado à internet (necessário para carregar as fontes do Google e a API do ResponsiveVoice).

Dê um duplo clique no arquivo index.html para abri-lo em seu navegador web padrão.

Digite um palpite no campo de texto e clique em "Chutar"!

💡 Próximos Passos (Sugestões de Melhoria)

Adicionar níveis de dificuldade (ex: Fácil de 1 a 10, Médio de 1 a 100).

Implementar um limite máximo de tentativas.

Adicionar efeitos sonoros para os momentos de acerto e erro.
