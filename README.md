# 🤖 Chatbot IA para Vendas de Carros
## Sistema Integrado Telegram + RAG + LLM Local (OLLAMA)

Este projeto implementa um chatbot inteligente para vendas de carros usando Telegram como interface, RAG (Retrieval Augmented Generation) para contexto e LLM local para processamento de linguagem natural.

### 📋 Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Uso](#uso)
- [Contato](#contato)

### 🎯 Sobre o Projeto
O projeto visa automatizar e melhorar o processo de vendas de carros através de um chatbot inteligente que pode:
- Responder perguntas sobre veículos
- Mostrar fotos do carro
- Fornecer informações técnicas
- Conectar com vendedor humano quando necessário

### ✨ Funcionalidades
- Interface via Telegram
- Respostas contextualizadas usando RAG
- Processamento de linguagem natural local
- Galeria de fotos integrada
- Sistema de chat intuitivo
- Integração com WhatsApp para vendas

### 🛠️ Tecnologias Utilizadas
- Python
- Telegram Bot API
- OLLAMA (LLM Local)
- RAG (Retrieval Augmented Generation)
- LlamaIndex
- pyTelegramBotAPI

### 📁 Estrutura do Projeto
```
projeto/
├── data/
│   └── [arquivos de dados]
├── imagens_estética/
│   └── [fotos dos carros]
├── notebook.ipynb
└── README.md
```

### 🚀 Instalação
1. Clone o repositório
```bash
git clone [URL_DO_REPOSITÓRIO]
```

2. Instale as dependências
```bash
pip install pyTelegramBotAPI
pip install llama-index
pip install python-telegram-bot --upgrade
```

### ⚙️ Configuração
1. Configure o token do bot Telegram
2. Prepare a base de dados na pasta `data/`
3. Adicione as fotos na pasta `imagens_estética/`
4. Configure as variáveis de ambiente necessárias

### 📖 Uso
1. Inicie o OLLAMA localmente
2. Execute o notebook ou script Python
3. Interaja com o bot via Telegram
4. Use os comandos disponíveis:
   - `/start` - Iniciar bot
   - `/help` - Obter ajuda
   - `/Fotos` - Ver fotos
   - `/chat` - Iniciar conversa
   - `/menu` - Menu principal

### 📞 Contato
Para mais informações ou dúvidas sobre o projeto:

- **LinkedIn**: [Erickson Santos](www.linkedin.com/in/erickson-santos-36a607318)
- **Email**: erickson1.dev@gmail.com
- **WhatsApp**: (47) 997246705

---

### 🔒 Notas de Segurança
- Mantenha seu token do bot seguro
- Use variáveis de ambiente para dados sensíveis
- Faça backup regular da base de dados

### 🛠️ Troubleshooting
Em caso de problemas:
1. Verifique a conexão com OLLAMA
2. Confirme o token do Telegram
3. Verifique os logs de erro
4. Certifique-se que todas as dependências estão instaladas
