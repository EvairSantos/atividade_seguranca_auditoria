<!DOCTYPE html>
<html>
<head>
<style>
  /* Estilize o título em azul claro */
  .titulo {
    color: #00aaff; /* Cor azul claro */
    font-size: 24px;
    font-weight: bold;
  }
  /* Estilize os botões */
  .botao {
    background-color: #00aaff; /* Cor de fundo azul claro */
    color: white; /* Cor do texto branco */
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
  }
</style>
</head>
<body>
  <!-- Título em azul claro -->
  <h1 class="titulo">Trabalho Prático com Wireshark</h1>

  <!-- Botão para o LinkedIn -->
  <a href="https://www.linkedin.com/seuperfil" class="botao" target="_blank">LinkedIn</a>

  <!-- Botão para o site -->
  <a href="https://www.seusite.com" class="botao" target="_blank">Site</a>
</body>
</html>

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

- Determinar a versão do HTTP usada pelo navegador e pelo servidor.
![Captura de Tela Parte 1](Screenshots/parte1_1.png)
- Identificar os idiomas que o navegador pode aceitar.
![Captura de Tela Parte 1](Screenshots/parte1_2.png)
- Encontrar os endereços IP do seu computador e do servidor.
![Captura de Tela Parte 1](Screenshots/parte1_3.png)
- Identificar a aplicação e versão usadas pelo servidor web.
![Captura de Tela Parte 1](Screenshots/parte1_4.png)

### Parte 2 - Análise do Protocolo TCP

- Encontrar as portas TCP usadas pelo cliente e pelo servidor.
![Captura de Tela Parte 2](Screenshots/parte2_1.png)
- Identificar o pacote de segmento TCP SYN para iniciar a conexão.
![Captura de Tela Parte 2](Screenshots/parte2_2.png)
- Identificar o tamanho da janela de controle de fluxo.
![Captura de Tela Parte 2](Screenshots/parte2_3.png)
- Identificar o pacote de segmento TCP que encerra a conexão.
![Captura de Tela Parte 2](Screenshots/parte2_4.png)


### Parte 3 - Análise do Protocolo DNS

- Identificar a mensagem de consulta DNS para obter o IP do host.

![Captura de Tela Parte 3](Screenshots/parte3_1.png)

- Encontrar a porta destino usada para a consulta DNS.

![Captura de Tela Parte 3](Screenshots/parte3_2.png)

- Identificar o endereço IP do servidor DNS usado para a resolução do endereço IP.

![Captura de Tela Parte 3](Screenshots/parte3_3.png)

### Parte 4 - Análise do Protocolo Ethernet

- Encontrar o endereço MAC do seu computador.

![Captura de Tela Parte 4](Screenshots/parte4_1.png)

- Identificar o endereço MAC do host `gaia.cs.umass.edu`.

![Captura de Tela Parte 4](Screenshots/parte4_2.png)

## Conclusão

*Este trabalho prático utiliza o Wireshark para explorar diferentes protocolos de rede em várias camadas.*

--- 

