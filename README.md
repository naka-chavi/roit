# Case da Roit

NN indentificador de numeros

Esse repositório contém o arquivo .ipynb para criar, treinar, hospedar e armazenar uma NN indetificadora de números. Para utilizar acesse [Notebook hospedado no google collab](https://colab.research.google.com/drive/12H0Hl1Bk5W57QxNSi5tC7Bq7XKQwYao4?usp=sharing)

Notas:
 * O código não foi testado para rodar localmente e só é garantido de funcinar via o notebook hospedado.
 
 * Para não precisar treinar a rede neural na hora, é preciso colocar o [.h5](https://github.com/naka-chavi/roit/raw/main/my_model.h5) deste repositório na pasta do collab

 * Envie o request do tipo POST para o segundo link gerado quando rodar a célula 8(Ela muda para toda execução de código e portanto não é destacada aqui).

Formato da requisição:

{"text":"*payload*"}

onde payload é a imagem codificada em base64
