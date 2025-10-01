Eco Runner ♻️ 

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/f59aed9a-79f2-4857-b6fc-1dd45f359d7b" />



Um jogo 2D de corrida infinita (infinite runner) com tema de reciclagem, desenvolvido em C++ e OpenGL. Este projeto serve como um estudo prático de computação gráfica, gerenciamento de estados de jogo e interação com o usuário.

📜 Sobre o Jogo

O conceito do "Eco Runner" é simples e educativo: o jogador controla um personagem que corre por um cenário, precisando desviar de obstáculos e coletar lixos para arremessá-los nas lixeiras corretas. O objetivo é marcar o máximo de pontos possível, combinando agilidade e atenção.

Esta versão do projeto foi estruturada para ser compilada em um ambiente Windows com MinGW, utilizando a biblioteca freeGLUT para a criação de janelas e gerenciamento de eventos.

✨ Funcionalidades

Renderização 2D: Utiliza OpenGL para desenhar todos os elementos em cena, incluindo o personagem, cenário, obstáculos e itens.

Lógica de Jogo: A lógica principal do jogo, como movimento, pontuação e estados, é encapsulada nos arquivos GameLogic.h/cpp.

Gerenciamento de Input: O input do teclado e mouse é gerenciado através dos callbacks do freeGLUT, com a lógica centralizada em Input.h/cpp.

Física Simples: O personagem possui mecânicas de pulo com gravidade e corrida automática.

Texturas e Sprites: Carregamento de imagens .png para texturas através da biblioteca stb_image.h.

Estrutura Modular: O código é organizado em diferentes módulos para lógica, renderização, input e dados globais.

🛠️ Tecnologias Utilizadas

Linguagem: C++

API Gráfica: OpenGL

Biblioteca de Janelas/Eventos: freeGLUT (para criar a janela, o contexto OpenGL e gerenciar o loop principal e o input).

Biblioteca de Imagens: stb_image.h (para carregar os arquivos de textura).

Compilador: MinGW (g++) para Windows.

Ambiente de Desenvolvimento: Visual Studio Code, com compilação gerenciada por tarefas (tasks.json).

👥 Créditos e Agradecimentos

Este projeto foi desenvolvido em colaboração por:

Carlos Eduardo Batista Diniz (https://github.com/CaduBD)

Raimundo Ferreira do Nascimento Junior (https://github.com/Raijunior05)

Uma parceria para aprofundar nossos estudos em desenvolvimento de jogos e computação gráfica.

Projeto desenvolvido como parte de um estudo em C++ e Computação Gráfica.
