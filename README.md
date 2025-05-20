# FastChat — Comunicação em tempo real para conectar pessoas

Aplicação web que permite a comunicação instantânea entre múltiplos usuários por meio de mensagens enviadas e recebidas em tempo real, ideal para bate-papo rápido e interações ao vivo.

---

## 📌 Visão Geral

FastChat é uma plataforma feita para facilitar conversas instantâneas entre pessoas em tempo real, criando um ambiente dinâmico e interativo, ideal para:

- Usuários que querem trocar mensagens rápidas e manter contato  
- Comunidades que buscam um espaço para bate-papo durante eventos ao vivo  
- Streamers e espectadores interagindo de forma fluida e imediata  

---

## 🔍 Funcionalidades

✅ Chat em tempo real com múltiplos usuários conectados simultaneamente

✅ Interface simples e intuitiva para envio e recebimento instantâneo de mensagens

✅ Suporte a múltiplas salas ou canais de conversa (opcional para futuras versões)

✅ Notificações visuais para novas mensagens

✅ Conexão via WebSocket para comunicação eficiente e em tempo real

✅ Arquitetura leve, sem necessidade obrigatória de banco de dados para chat simples

✅ Possibilidade de expansão para histórico e autenticação de usuários (futuro)

---

## 🧱 Tecnologias Utilizadas

### 🖥️ Backend

- Python  
- FastAPI  
- WebSocket  

### 💻 Frontend (em desenvolvimento)

- HTML  
- CSS  
- JavaScript

---

## 🧠 Arquitetura do Projeto

```
fastchat/
├── server.py               # Código principal do servidor FastAPI + WebSocket
├── templates/              # Arquivos HTML (frontend)
│   └── index.html          # Página principal do chat
├── static/                 # Arquivos estáticos (CSS, JS, imagens)
│   └── ...
├── requirements.txt        # Dependências do Python
└── README.md               # Documentação do projeto
```

---

## 🚀 Como Rodar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/Aleckenzo/fastchat-live.git
cd fastchat-live
```

2. Crie e ative um ambiente virtual:

- No Linux/Mac:

```bash
python3 -m venv venv
source venv/bin/activate
```

- No Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Inicie o servidor:

```bash
uvicorn server:app --reload
```

5. Abra o navegador no endereço:

[http://localhost:8000](http://localhost:8000)

---

Feito com ❤️ por desenvolvedores que acreditam em conexões reais no universo tech.
