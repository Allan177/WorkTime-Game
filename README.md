# WordTime - Jogo de Palavras Multiplayer

![alt text](https'://i.imgur.com/your-logo-image-url.png')
<!-- Sugestão: Faça upload da sua logo para um site como o Imgur e cole o link aqui -->

WordTime é um jogo de palavras multiplayer vibrante e rápido para Android, onde dois jogadores competem para encontrar palavras que começam e terminam com letras específicas antes que o tempo acabe. Desenvolvido em Java nativo e utilizando o poder do Firebase Firestore para funcionalidades em tempo real.

🌟 Funcionalidades

Multiplayer em Tempo Real: Crie salas online e desafie seus amigos em partidas rápidas e dinâmicas.

Três Modos de Jogo:

🎲 Aleatório: As letras são sorteadas pelo sistema. A primeira é sempre uma consoante e a última uma vogal para maximizar a diversão!

👑 Clássico: Um jogador escolhe a letra inicial e o outro a letra final, criando um desafio estratégico.

⚡ Rápido (Melhor de 3): O primeiro jogador a vencer 2 rodadas é o campeão.

🏅 Normal (Melhor de 5): Uma partida mais longa para testar quem é o verdadeiro mestre das palavras.

Validação de Palavras: O jogo utiliza um dicionário local embutido para garantir que apenas palavras válidas (Português-BR) sejam aceitas.

Interface Intuitiva: Design limpo, com efeitos sonoros e um seletor de letras moderno para uma experiência de usuário agradável.

📱 Telas do Jogo
Tela Inicial	Seleção de Modo	Lobby
		
Tela de Jogo	Seleção de Letra (Clássico)	Tela de Vitória
		

🛠️ Tecnologias Utilizadas

Linguagem: Java

IDE: Android Studio

Banco de Dados: Firebase Firestore (para gerenciamento de salas, jogadores e estado do jogo em tempo real).

Arquitetura: Estrutura de Activities com listeners do Firestore para atualizações de UI.

Dicionário: Dicionário de palavras em Português-BR incluído como um recurso raw para validação offline e instantânea.

⚙️ Como Compilar e Executar

Para compilar e executar o projeto localmente, siga estes passos:

Clone o Repositório:

code
Bash
download
content_copy
expand_less

git clone https://github.com/Allan177/WorkTime-Game.git

Abra o Android Studio.

Clique em File > Open e selecione a pasta do projeto clonado.

Configure o Firebase:

Vá para o Console do Firebase.

Crie um novo projeto.

Adicione um novo aplicativo Android ao projeto, usando o nome do pacote com.example.palavraexpress (ou o seu nome de pacote customizado).

Siga as instruções para baixar o arquivo google-services.json.

Coloque o arquivo google-services.json na pasta app/ do seu projeto no Android Studio.

No console do Firebase, vá para a seção Firestore Database, clique em "Criar banco de dados" e inicie-o em modo de teste.

Adicione o Dicionário e os Sons:

Obtenha um arquivo .txt com uma lista de palavras em Português-BR. Renomeie para dicionario_pt.txt.

Coloque este arquivo na pasta app/src/main/res/raw.

Coloque seus arquivos de som (timer_tick.mp3, round_win.mp3, game_over.mp3) na mesma pasta res/raw.

Compile o Projeto:

Clique em Build > Rebuild Project.

Execute o aplicativo em um emulador ou dispositivo físico clicando no botão de Play (▶️).

🚀 Possíveis Melhorias Futuras

Adicionar suporte a múltiplos idiomas (Inglês).

Implementar um ranking global de jogadores.

Adicionar power-ups durante as rodadas (tempo extra, dica de letra, etc.).

Animações de transição entre telas e eventos.

Login de usuários com Firebase Auth para salvar o progresso.





