# Pac-man-Simples
Como funciona : 
Mapa: O jogo utiliza uma matriz (initialMap) para representar o labirinto. 1 são paredes, 0 são pontinhos de pontuação e 2 são espaços vazios.
Movimento: O Pac-Man segue a grade do labirinto e só muda de direção quando está alinhado com ela. As paredes bloqueiam o movimento.
Fantasmas: Os fantasmas verificam os caminhos disponíveis nos cruzamentos e escolhem aleatoriamente uma direção, evitando paredes e o caminho anterior.
Colisões: O jogo calcula a distância entre o Pac-Man e os fantasmas usando Math.hypot(). Se houver contato, o jogo termina.
Mobile: O jogo também funciona em celulares através de gestos de swipe, permitindo controlar o Pac-Man deslizando o dedo pela tela.