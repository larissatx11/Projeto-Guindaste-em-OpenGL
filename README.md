# Simulador de Guindaste em OpenGL

## Descrição
Este projeto representa um guindaste composto por um caminhão com uma carroceria amarela e uma cabine vermelha, equipado com quatro rodas azuis. O cenário permite movimentos complexos, proporcionando aos espectadores diferentes perspectivas do caminhão. O elemento central é o braço mecânico conectado à parte traseira do caminhão, composto por diversas partes manipuláveis.

## Controle de Movimentos
1. **Mover Caminhão:** Teclas '8' e '9' (esquerda e direita, respectivamente).
2. **Girar Base do Braço:** Teclas '+' e '-' (esquerda e direita, respectivamente).
3. **Estender e Recolher Corda:** Teclas 'W' e 'S' (respectivamente).
4. **Abrir e Fechar Garra Mecânica:** Teclas 'Q' e 'E' (respectivamente).
5. **Rotacionar Garra Mecânica:** Teclas 'Z' e 'X' (esquerda e direita, respectivamente).

## Transformações Utilizadas
- **Translação (glTranslatef):** Movimento lateral do caminhão e posicionamento de partes do braço mecânico e rodas.
- **Rotação (glRotatef):** Controle da orientação do braço mecânico e ajuste da direção e rotação da garra mecânica.
- **Escala (glScalef):** Ajuste do tamanho da corda e definição das dimensões do cubo representando partes do caminhão.

Este projeto utiliza OpenGL para simular um guindaste, proporcionando uma experiência visual interativa.
