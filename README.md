# Separador de Lixo: Um Passo Rumo à Reciclagem Inteligente


## A Ideia
Este projeto nasceu com a ambição de revolucionar a maneira como reciclamos. Imaginamos um futuro onde a separação de lixo é totalmente automatizada, tornando o processo mais eficiente e eficaz. A visão original incluia uma inteligência artificial (IA) conectada a uma câmera posicionada sobre uma esteira de lixo. Esta IA, então, identificaria cada objeto e o separaria automaticamente.

## Desafios e Adaptação
Devido a limitações de tempo e conhecimento técnico, o escopo do projeto precisou ser adaptado. No momento, o modelo se concentra na identificação de imagens e classificação dos objetos como recicláveis ou não recicláveis.

## Aplicações Práticas
Apesar da mudança de escopo, o projeto ainda possui grande potencial para facilitar a reciclagem! O modelo pode ser utilizado em conjunto com lixeiras inteligentes. Uma câmera acoplada à lixeira capturaria a imagem do objeto sendo descartado, enviando-a para o modelo de IA. O modelo, então, classificaria o objeto e indicaria se ele deve ser direcionado para o compartimento de recicláveis ou não.

## Como visualizar o modelo
Como o projeto foi todo feito no colab é necessario que faça o upload do arquivo para seu colab, assim como subir juntamente as imagens e adicionar novas (se quiser).
Apos realizar a ação voce precisa trocar o Token de acesso no codigo, na qual esta explicado no notebook o local em que deve colocar seu token de acesso

## Usando o modelo
o modelo é bem simples , assim que subir as imagens para o google colab so rodar os codigos , quando chegar na parte de rodar o codigo que ira reconhecer se o lixo é reciclavel ira abrir um poup-up.
esse poup-up usei como modo de interação do usuario com o codigo, uma vez que o mesmo nao esta conectado a uma camera, e o usuario ira digitar o nome da imagem e o formato que ela esta.

por exemplo: (imagem.png)

apos isso o codigo ira identificar qual seria a imagem e retoranr a resposta, lembre-se que como se trata de um ambiente vitual a imagem precisa estar no colab e precisa estar com mesmo nome de arquivo na qual ira colocar no poup-up
