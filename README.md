# Microsoft-DIO-Car
Construção de uma Aplicação de Aluguel de Carros totalmente Cloud-Native 
# 🚗 Sistema de Aluguel de Carros na Nuvem 🚀

Este repositório contém um sistema completo de aluguel de carros, desenvolvido com foco em escalabilidade e hospedagem na nuvem. A solução abrange tanto o back-end quanto o front-end, permitindo o gerenciamento eficiente de clientes, veículos e reservas.

## 🛠 Tecnologias Utilizadas
### Back-end
- Node.js com Express.js
- Banco de dados MongoDB
- Autenticação JWT para segurança

### Front-end
- React.js
- Biblioteca Axios para consumo da API
- CSS para estilização

### Hospedagem
- Microsoft Azure (App Service para API e React App)
- Banco de Dados hospedado no Azure CosmosDB

---

## 📂 Estrutura do Projeto
```bash
📁 backend
├── app.js                # Arquivo principal do servidor
├── 📂 models             # Definições de esquemas (clientes, carros, reservas)
├── 📂 routes             # Arquivos de rotas da API RESTful
└── 📂 config             # Configurações (conexão com banco de dados)

📁 frontend
├── 📂 src                # Código-fonte do React App
│   ├── 📂 components     # Componentes reutilizáveis
│   ├── 📂 pages          # Páginas principais da aplicação
│   ├── App.js            # Arquivo principal do React
│   ├── index.js          # Ponto de entrada
└── 📂 public             # Arquivos públicos (favicon, index.html)
