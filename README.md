## Contador de Dedos Usando OpenCV e MediaPipe

### Descrição
Este projeto utiliza OpenCV e MediaPipe para capturar a imagem de uma mão através da webcam e contar quantos dedos estão levantados. O programa identifica os pontos de articulação da mão em tempo real e exibe na tela a quantidade de dedos levantados.

### Funcionalidades
- Captura de vídeo em tempo real via webcam.
- Detecção da mão e suas articulações.
- Contagem de dedos levantados (polegar e outros dedos).
- Exibição do número de dedos levantados sobre a imagem capturada.

### Tecnologias Utilizadas
- **OpenCV**: Biblioteca para captura e manipulação de imagens.
- **MediaPipe**: Framework para rastreamento de mãos e outros pontos de referência.
- **Python**: Linguagem de programação usada para implementar o projeto.

### Requisitos
- Python 3.x
- OpenCV: `pip install opencv-python`
- MediaPipe: `pip install mediapipe`

## Funcionamento
- O programa acessa a webcam do dispositivo e, usando o MediaPipe, detecta uma mão e suas articulações.
- O código então verifica se os dedos estão levantados, baseando-se na posição das articulações dos dedos.
- O número de dedos levantados é exibido em tempo real sobre a imagem capturada.
- O programa continua rodando até que a tecla 'r' seja pressionada, o que interrompe a execução.

## Estrutura do Código
- Captura de vídeo: O código utiliza OpenCV para acessar a webcam.
- Detecção de mãos: MediaPipe é usado para detectar os pontos de referência da mão.
- Contagem de dedos: O programa compara as articulações dos dedos para determinar quais estão levantados.
- Exibição de resultados: O número de dedos levantados é exibido na tela.
- Encerramento: O programa é finalizado quando a tecla 'r' é pressionada.

## Como Utilizar

- O programa é executado com a webcam ativada.
- Ele detecta a mão e exibe o número de dedos levantados em tempo real na janela de visualização.
- Para encerrar o programa, pressione a tecla 'r'.

## Observações

- O código foi configurado para detectar apenas a mão esquerda.
- Certifique-se de que sua webcam esteja conectada e funcionando corretamente.
