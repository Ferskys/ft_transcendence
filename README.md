# 🎮 ft_transcendence  
**Um jogo Pong multiplayer** com autenticação segura, backend em Django, infraestrutura Docker e deploy automatizado.

---

## 📋 Descrição  
Bem-vindo ao projeto **ft_transcendence**! Nossa missão é criar uma **Single Page Application (SPA)** que permita partidas emocionantes de Pong com torneios, chat em tempo real, **autenticação 2FA e JWT**, e uma infraestrutura pronta para produção.

---

## 🚀 Tecnologias e Ferramentas  

### 1. 🐋 Docker e Docker Compose  
- **O que é:** Plataforma para empacotar e executar aplicações em containers.  
- **Por que usar:** Facilita o deploy e garante consistência entre ambientes.  
- **Uso:** Gerenciamento do backend Django, banco de dados PostgreSQL e frontend isolados em containers.  
- **Tarefas:**
  - [ ] Configuração de Contêineres com Docker
  - [ ] Setup de Servidores

---

### 2. 🎯 GitHub Projects (Kanban)  
- **O que é:** Ferramenta integrada para gerenciamento de tarefas e organização.  
- **Por que usar:** Permite acompanhar o progresso de cada atividade com um Kanban.  
- **Uso:** Organize tarefas em **Backlog, In Progress, Testing e Done**.

---

### 3. 🐍 Django (Backend)  
- **O que é:** Framework de alto nível para desenvolvimento web em **Python**.  
- **Por que usar:** Facilita a criação de APIs robustas e seguras.  
- **Uso:** Implementação das APIs do jogo, autenticação e chat.  
- **Tarefas:**
  - [@Vinicius Pereira] Web Framework Backend (Django)
  - [ ] Banco de Dados (PostgreSQL)
  - [ ] Microservices Architecture
  - [ ] API para o Jogo de Pong (game logic)
  - [ ] Integração do Pong via CLI com a API

---

### 4. ✨ Vanilla JavaScript (Frontend)  
- **O que é:** JavaScript puro para a interface do usuário.  
- **Por que usar:** Permite maior controle e simplicidade no frontend.  
- **Uso:** Implementar o jogo Pong e manter a SPA funcional e responsiva.  
- **Tarefas:**
  - [ ] Bootstrap para Frontend
  - [ ] Single-Page Application (Vanilla JS/Bootstrap)
  - [ ] Customização do Jogo (opções de mapas, power-ups)
  - [ ] Gráficos Avançados em 3D (Three.js/WebGL)

---

### 5. 🔑 JWT (JSON Web Tokens)  
- **O que é:** Padrão aberto para **autenticação baseada em tokens**.  
- **Por que usar:** Garante segurança e elimina sessões persistentes no servidor.  
- **Uso:** Autenticar usuários durante o login e proteger as rotas da API.  
- **Tarefas:**
  - [@Aline | Cejrie | aqueiroz] 2FA e JWT
  - [ ] WAF/ModSecurity e Vault
  - [ ] Compliance com GDPR (anonimização e gestão de dados)

---

### 6. 🔒 2FA (Autenticação de Dois Fatores)  
- **O que é:** Camada extra de segurança no login.  
- **Por que usar:** Protege os usuários contra acessos não autorizados.  
- **Uso:** Implementação via **Google Authenticator** ou e-mail.

---

### 7. 🛢️ PostgreSQL (Banco de Dados)  
- **O que é:** Banco de dados relacional robusto.  
- **Por que usar:** Suporta operações complexas e garante integridade dos dados.  
- **Uso:** Armazenar usuários, partidas, torneios e mensagens.  

---

### 8. ⚙️ GitHub Actions (CI/CD)  
- **O que é:** Plataforma de automação para integração e deploy contínuos.  
- **Por que usar:** Automatiza testes e builds para garantir qualidade.  
- **Uso:** Rodar pipelines de CI/CD para verificar commits e realizar deploys.  
- **Tarefas:**
  - [ ] Configuração do Pipeline CI/CD
  - [ ] Automação de Testes com CI/CD
  - [ ] Deploy Automático
  - [ ] Integração de Qualidade de Código no Pipeline (Linting/Code Analysis)

---

### 9. 📊 Prometheus e Grafana (Monitoramento)  
- **O que são:** Ferramentas de coleta e visualização de métricas.  
- **Uso:** Monitorar desempenho e alertar sobre problemas em tempo real.  
- **Tarefas:**
  - [ ] Setup do Sistema de Monitoring (Prometheus, Grafana)

---

### 10. 🕵️ ELK Stack (Logs e Análise)  
- **O que é:** Conjunto para gerenciamento de logs: Elasticsearch, Logstash e Kibana.  
- **Uso:** Monitorar logs e diagnosticar problemas no sistema.  
- **Tarefas:**
  - [ ] Gestão de Logs com ELK Stack
  - [ ] Implementação de Alertas Automáticos (monitoramento de falhas)

---

## 📦 Como Rodar o Projeto Localmente  
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/ft_transcendence.git
   cd ft_transcendence
