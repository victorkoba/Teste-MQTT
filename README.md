# Teste-MQTT
Projeto criado durante a aula do SENAI, com intuito de adquirir conhecimento sobre protocolo MQTT.

# MQTT Teste - Publicador e Assinante
Este projeto contém um exemplo de comunicação MQTT utilizando a biblioteca `paho-mqtt` em Python.

## **Pré-requisitos**
- Python 3 instalado
- Biblioteca `paho-mqtt` instalada

## **Instalação**
Para instalar a biblioteca necessária, execute este comando no terminal:
pip install paho-mqtt

## **Como testar**
### **1. Clonar o repositório**
É necessário clonar este repositório para a máquina local e acessar o diretório do projeto.

### **2. Executar os arquivos**
Abrir dois terminais ou duas janelas do prompt de comando e seguir os passos:

- No primeiro terminal, executar o subscriber para receber mensagens.  
- No segundo terminal, executar o publisher para enviar mensagens.  

### **3. Enviar mensagens**
Após iniciar o publicador, será solicitado que uma mensagem seja digitada. Ao digitar e confirmar, a mensagem será enviada para o broker MQTT e o assinante irá recebê-la e exibir no terminal.  

### **4. Verificar o funcionamento**
Se a mensagem enviada pelo publicador aparecer no terminal do assinante, a comunicação MQTT está funcionando corretamente.  

Para testar novamente, basta enviar novas mensagens pelo publicador e acompanhar a recepção no assinante.

## **Sobre o MQTT e este projeto**
Este projeto utiliza um **broker MQTT público** (`broker.hivemq.com`), permitindo testes sem a necessidade de um broker local.
