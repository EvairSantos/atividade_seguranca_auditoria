# Trabalho Prático com Wireshark

Este repositório contém um trabalho prático que envolve a utilização do software Wireshark para analisar protocolos de rede em diferentes camadas. O trabalho está dividido em quatro partes, e para cada parte, você encontrará instruções e questões específicas que precisam ser respondidas com base na captura de pacotes.

## Pré-requisitos

Certifique-se de ter o Wireshark instalado no seu computador. Você pode fazer o download do Wireshark em [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html).

## Instruções Gerais

- Cada parte do trabalho inclui um conjunto de questões que requerem análise das capturas de pacotes.
- Para cada questão, será necessário incluir capturas de tela relevantes que demonstrem sua análise.
- As capturas de tela devem ser inseridas diretamente no documento, indicando claramente a parte relevante da captura.
- Certifique-se de nomear adequadamente as capturas de tela para referenciá-las no documento.
- Siga as instruções fornecidas em cada parte do trabalho para realizar a análise apropriada.

## Conteúdo do Trabalho

### Parte 1 - Análise do Protocolo HTTP

-  O seu navegador executa a versão 1.0 ou 1.1 do HTTP? Qual a versão do HTTP que está rodando no
servidor?
![Captura de Tela Parte 1](Screenshots/parte1_1.png)
- Quais linguagens (idiomas) o seu navegador indica que pode aceitar do servidor?
![Captura de Tela Parte 1](Screenshots/parte1_2.png)
- Qual o endereço IP do seu computador? E do servidor gaia.cs.umass.edu?
![Captura de Tela Parte 1](Screenshots/parte1_3.png)
- Qual aplicação (e versão) é utilizada pelo servidor web gaia.cs.umass.edu?
![Captura de Tela Parte 1](Screenshots/parte1_4.png)

### Parte 2 - Análise do Protocolo TCP

- Qual é o número da porta TCP usada pelo seu computador cliente (source) para requisitar o arquivo
html para gaia.cs.umass.edu? E qual o número de porta TCP que o servidor gaia está usando para receber e enviar
essas respostas?
![Captura de Tela Parte 2](Screenshots/parte2_1.png)
- Mostre e comente o pacote que contém o segmento TCP SYN que caracteriza o início de uma
conexão TCP (estabelecimento inicial de conexão - three way handshake) entre o computador cliente e o
gaia.cs.umass.edu?
![Captura de Tela Parte 2](Screenshots/parte2_2.png)
- Após responder à questão 2.2 mostre e comente o campo do segmento TCP que contém o tamanho
da janela utilizada pelo TCP para o controle de fluxo? Qual é o tamanho da janela em bytes?
![Captura de Tela Parte 2](Screenshots/parte2_3.png)
-  Identifique, abra e mostre o pacote do segmento TCP responsável pelo término da conexão. Qual é
a flag que o TCP usa para encerrar a conexão? 
![Captura de Tela Parte 2](Screenshots/parte2_4.png)


### Parte 3 - Análise do Protocolo DNS

- Identifique e comente a mensagem de consulta ao DNS para descobrir o IP do host
‘gaia.cs.umass.edu’. Qual foi o protocolo da camada de transporte utilizado?
![Captura de Tela Parte 3](Screenshots/parte3_1.png)

-  Após responder à questão 3.1 identifique e comente a porta destino usada para a consulta DNS?

![Captura de Tela Parte 3](Screenshots/parte3_2.png)

- Qual é o endereço IP do servidor de DNS que foi usado para a resolução do endereço IP do host
‘gaia.cs.umass.edu’?
![Captura de Tela Parte 3](Screenshots/parte3_3.png)

### Parte 4 - Análise do Protocolo Ethernet

- Após responder à questão 3.3, identifique e comente sobre o endereço MAC do seu computador?
![Captura de Tela Parte 4](Screenshots/parte4_1.png)

- Qual é o endereço MAC do host `gaia.cs.umass.edu`? Justifique e fundamente a sua resposta.

![Captura de Tela Parte 4](Screenshots/parte4_2.png)

## Conclusão

*Este trabalho prático utiliza o Wireshark para explorar diferentes protocolos de rede em várias camadas.*

--- 

