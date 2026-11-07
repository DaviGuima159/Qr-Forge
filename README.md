<h1 align="center">🔳 QR Forge</h1>

<p align="center">
  Gerador de QR Codes personalizáveis com pré-visualização em tempo real, estilos avançados e cofre de QR Codes salvos na nuvem.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
</p>

---

## 📌 Sobre o projeto

O **QR Forge** é uma aplicação web para criar QR Codes com identidade visual própria. O usuário altera cores, estilos, logotipo e outras opções e vê o resultado na hora. Com login, é possível salvar os QR Codes e modelos personalizados na nuvem para reutilizar depois.

O projeto foi criado para praticar desenvolvimento front-end moderno, componentização com React, gerenciamento de estado e integração com serviços em nuvem (Firebase).

## ✨ Funcionalidades

- ⚡ **Pré-visualização em tempo real** enquanto as opções são ajustadas
- 🎨 **Personalização avançada:** cores, estilos dos pontos e cantos, upload de logotipo
- 🧩 **Modelos prontos (presets)** e **modelos personalizados** criados pelo usuário
- 🔍 **Painel de análise** do QR Code gerado
- 🔐 **Login com conta Google** e **cofre** para salvar QR Codes (Firebase Authentication + Firestore)
- 🛡️ **Regras de segurança do Firestore** para proteger os dados de cada usuário
- 📥 Download do QR Code gerado

## 🛠️ Tecnologias

| Camada | Ferramentas |
|---|---|
| Front-end | React, TypeScript, Vite |
| Estilo e UI | Tailwind CSS, Motion (animações), Lucide Icons |
| QR Code | `qr-code-styling` |
| Back-end / Nuvem | Firebase (Authentication com Google e Firestore) |

## 📁 Estrutura

```
src/
├── components/
│   ├── layout/      # Sidebar e área de pré-visualização
│   ├── qr/          # Canvas, painel de configurações, cofre, modelos e análise
│   └── ui/          # Componentes reutilizáveis (Button, Input, Card, Select...)
├── constants/       # Presets de estilos
├── context/         # Estado global do QR Code (QRContext)
├── services/        # Integração com o Firebase
├── types/           # Tipagens TypeScript
└── utils/           # Funções auxiliares e tratamento de erros
```

## ▶️ Como executar

**Pré-requisito:** [Node.js](https://nodejs.org/) instalado.

```bash
# 1. Clone o repositório
git clone https://github.com/DaviGuima159/Qr-Forge.git
cd Qr-Forge

# 2. Instale as dependências
npm install

# 3. Crie o arquivo .env.local com base no .env.example
#    e informe sua chave GEMINI_API_KEY

# 4. Rode o projeto
npm run dev
```

## 📚 Aprendizados

- Organização de um projeto React em componentes reutilizáveis
- Gerenciamento de estado global com Context API
- Autenticação e banco de dados na nuvem com Firebase
- Escrita de regras de segurança para proteger dados de usuários
- Estilização rápida e responsiva com Tailwind CSS

## 👤 Autor

**Davi Guimarães** · Estudante de Engenharia de Software (UNICID)

[![GitHub](https://img.shields.io/badge/GitHub-DaviGuima159-181717?style=flat-square&logo=github)](https://github.com/DaviGuima159)
