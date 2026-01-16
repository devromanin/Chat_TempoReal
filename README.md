# 🗨️ Chat em Tempo Real com Flask + SocketIO

Aplicação simples de chat em tempo real desenvolvida com Flask e Flask-SocketIO. Permite que vários usuários troquem mensagens instantaneamente através do navegador.

Projeto criado com foco em aprendizado de comunicação em tempo real utilizando WebSockets.

---

## 🚀 Funcionalidades

- Comunicação em tempo real
- Backend em Flask
- Uso de Socket.IO
- Interface web simples
- Envio de mensagens sem recarregar a página

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Flask
- Flask-SocketIO
- Eventlet
- HTML
- JavaScript

---

## ▶️ Como executar o projeto

1. Clonar o repositório  
git clone https://github.com/devromanin/Chat_TempoReal.git  

2. Acessar a pasta do projeto  
cd Chat_TempoReal  

3. Instalar as dependências  
pip install -r requirements.txt  

4. Executar a aplicação  
python app.py  

5. Acessar no navegador  
http://localhost:5000  

---

## 🧪 Como testar o chat

- Abra o endereço da aplicação em duas abas do navegador
- Envie uma mensagem em uma aba
- A mensagem aparecerá instantaneamente na outra

---

## 🧠 Funcionamento da aplicação

- O Flask é responsável por servir a página HTML
- O Flask-SocketIO gerencia a comunicação em tempo real
- As mensagens enviadas são transmitidas para todos os usuários conectados

