 Projeto: Sistema de Reconhecimento Facial do Zero
   Descrição
   
Este projeto implementa um sistema básico de reconhecimento facial utilizando Python e as bibliotecas face_recognition e OpenCV. Ele permite carregar uma imagem, detectar rostos presentes nela e desenhar caixas ao redor das faces detectadas.

 Estrutura do Código
1 Instalação das Bibliotecas Necessárias

Instala as bibliotecas opencv-python-headless, face_recognition e matplotlib.
2 Importação das Bibliotecas

Importa face_recognition, cv2 e matplotlib.pyplot.
3 Carregamento da Imagem

Permite o upload de uma imagem diretamente no Google Colab.
4 Processamento da Imagem

Lê a imagem e detecta a localização de rostos nela.
5 Desenho das Caixas

Adiciona caixas verdes ao redor das faces detectadas.
6 Exibição do Resultado

Mostra a imagem processada com as caixas ao redor das faces.
7 Coordenadas das Faces

Exibe as coordenadas das faces detectadas no console.
   Tecnologias Utilizadas
Python 
OpenCV 
Face Recognition 
Matplotlib 

   Como Executar
1 Requisitos
Certifique-se de ter o Google Colab ou um ambiente Python configurado com as bibliotecas necessárias.

2 Instale as Dependências
Execute o seguinte comando para instalar as bibliotecas:

pip install opencv-python-headless face_recognition matplotlib
3 Rode o Código
Copie e cole o código em um notebook do Google Colab ou em um script Python e execute cada célula.

   Exemplo de Uso
 Upload de uma Imagem
Após carregar uma imagem, o sistema processará a imagem e desenhará caixas ao redor dos rostos detectados.

   Exibição do Resultado
A imagem com os rostos detectados será exibida com caixas verdes ao redor das faces.

   Saída no Console
O programa imprimirá a quantidade de rostos detectados e suas coordenadas.

   Melhorias Futuras
   
 Melhorar a precisão da detecção
 Implementar reconhecimento facial com banco de dados
 Integrar com uma API para detecção em tempo real

 Autor
 Sidney Pereira Santos – Data Analyst & Machine Learning Enthusiast

 Contato: sidneysantosdatascientist@gmail.com
 https://www.linkedin.com/in/sidney-santos-analista-de-dados/
