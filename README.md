# Gestão & Projeção Orçamentária de TI (DRE & Fluxo de Caixa)
Aplicação completa construída com **React 18 (Vite)** no Frontend e **Node.js (Express)** no Backend.

---

## 🚀 Como Executar Localmente na sua Máquina

### 1. Pré-requisito
Tenha o [Node.js](https://nodejs.org/) instalado (versão 18 ou superior).

### 2. Instalação das Dependências
Abra o terminal (Prompt de Comando ou VS Code) na pasta do projeto e execute:
```bash
npm install
```

### 3. Rodar em Modo de Desenvolvimento
Para rodar o Backend e o Frontend:
* **Terminal 1 (Backend Node.js):**
  ```bash
  npm run server
  ```
  *(O servidor iniciará em `http://localhost:5000`)*

* **Terminal 2 (Frontend React):**
  ```bash
  npm run dev
  ```
  *(O frontend abrirá em `http://localhost:3000` com hot-reload)*

---

## 🌐 Como Postar / Hospedar Gratuitamente na Web

Você pode hospedar esta aplicação em poucos minutos de forma 100% gratuita em plataformas como **Render**, **Railway** ou **Vercel**.

### Opção 1: Hospedagem no Render.com (Recomendado - Frontend + Backend juntos)
1. Crie uma conta gratuita em [render.com](https://render.com/).
2. Suba a pasta deste projeto para um repositório no seu GitHub (ex.: `gestao-custos-ti`).
3. No painel do Render, clique em **New +** e selecione **Web Service**.
4. Conecte com o seu repositório do GitHub.
5. Configure os seguintes campos:
   * **Name:** `gestao-custos-ti`
   * **Environment:** `Node`
   * **Build Command:** `npm install && npm run build`
   * **Start Command:** `npm run start`
   * **Plan Type:** `Free`
6. Clique em **Create Web Service**.
7. Pronto! Em 2 minutos você terá uma URL pública (ex.: `https://gestao-custos-ti.onrender.com`) para compartilhar com a equipe.

### Opção 2: Hospedagem no Vercel (Somente Frontend)
1. Execute `npm run build` na sua máquina (será gerada a pasta `dist`).
2. Conecte o repositório na [Vercel](https://vercel.com/) e aponte para a pasta raiz.
