## Projeto de Consulta de Cidades e Previsão do Tempo

Este projeto é uma aplicação web desenvolvida em Next.js 13 que possibilita buscar informações sobre cidades brasileiras e exibir as condições meteorológicas de cada local nos próximos 6 dias. O projeto também conta com um sistema de login utilizando JWT para autenticação de usuários.

- **📋 Funcionalidades**

  - Busca por cidade: Pesquisa informações de cidades por CEP, utilizando a API brasilapi.com.br.

  - Exibição do clima: Mostra os dados climáticos (temperatura mínima e máxima) para a cidade consultada.

  - Sistema de login: Login utilizando autenticação com JWT. Após o login, o nome do usuário é mostrado na página de perfil.

- **🛠️ Tecnologias Empregadas**

  - Next.js 13 (React).

  - Context API para gestão de estado global.

  - API Externa: brasilapi.com.br para consulta de cidades e informações meteorológicas.

  - API Fake: Servidor Hapi.js funcionando localmente para simular o login e gerar tokens JWT.

## Como Executar o Projeto

**Pré-requisitos**

- Node.js (versão >= 16.0.0)

- npm

- Next.js 13

## 🔑 Login
Utilize as seguintes credenciais para autenticar no sistema:

Email: jorge@abreu.com.br

Senha: abobrinha

## Como rodar o projeto localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/LuannZeiro/CP5-Frontend-main

2. **Instale as dependecias:**
   ```bash
   cd CP5-Frontend
   npm install

3. **Instale as dependências do projeto:**
   ```bash
   npm install

4.  **Execute o projeto:**
    ```bash
     npm run dev
