# Portais 3D

Protótipo de exploração em primeira pessoa com dois portais conectados, renderização de perspectiva através das aberturas e reposicionamento por mira.

## Executar
Abra `index.html` em um servidor estático ou publique o repositório pelo GitHub Pages. O Three.js é carregado por CDN, então é necessária conexão com a internet.

## Controles
- **WASD:** mover
- **Mouse:** olhar
- **Espaço:** pular
- **1 / 2:** selecionar portal azul ou laranja
- **Clique esquerdo:** disparar/reposicionar o portal selecionado
- **Esc:** liberar o mouse; clique na cena para retomar

## Estado do protótipo
Esta é uma primeira versão experimental. A renderização usa câmeras auxiliares para mostrar o cenário através dos portais. A movimentação e a travessia são implementações iniciais; colisão precisa com geometria arbitrária, conservação rigorosa de velocidade e recorte perfeito das superfícies ainda exigem refinamento.
