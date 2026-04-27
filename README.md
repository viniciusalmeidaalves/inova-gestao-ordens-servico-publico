
# 🚀 Inova Gestão de Ordens de Serviço
Observação: Este repositório foi criado para fins de visualização. O repositório original é restrito, contendo o histórico completo de desenvolvimento e versões do projeto.

**Solução simples para organizar e controlar ordens de serviço para serralheria Inova.**

O Inova é um micro ERP web desenvolvido para facilita o registro, acompanhamento e histórico de de ordem de serviço para serralheria Inova de Ibaté-SP.

---

## 🎯 Objetivo do Projeto

O **Inova Gestão de Ordens de Serviço** foi criado com o objetivo de resolver problemas comuns do dia a dia:

- Falta de controle sobre atendimentos
- Dificuldade de rastrear histórico de clientes
- Processos manuais (papel / planilhas)
- Falta de indicadores operacionais

O sistema centraliza e organiza todas as informações em um único ambiente digital.

---

## 🖼️ Imagens do Sistema

Veja abaixo algumas telas do Innova e entenda o que cada módulo faz:

### Login
<img width="1354" height="629" alt="login-inicial" src="https://github.com/user-attachments/assets/b5f66c05-3473-4c81-a7ad-42f5bb0f6af2" />
Permite que usuários autorizados acessem o sistema de forma segura.

### Dashboard
<img width="1350" height="628" alt="Dashboard" src="https://github.com/user-attachments/assets/31cba389-ba55-46d5-be80-36c8c6ecc47d" />
Visão geral dos atendimentos, indicadores e atalhos para as principais funções.

### Kanban de Ordens de Serviço
<img width="1352" height="631" alt="Kamban" src="https://github.com/user-attachments/assets/c2eb8579-ab0c-4d5c-a279-de16be97747b" />
Visualize e mova as ordens de serviço entre os diferentes status (Aberta, Em andamento, Finalizada) de forma intuitiva, como em um quadro Kanban. Facilita o acompanhamento do fluxo de trabalho e a priorização dos atendimentos.

### Cadastro de Clientes
<img width="1352" height="630" alt="Clientes" src="https://github.com/user-attachments/assets/88d5cc16-c40a-4f79-8037-ede64f0abaf4" />
Gerencie todos os clientes da empresa, com histórico de ordens e dados de contato.

### Ordens de Serviço
<img width="1349" height="629" alt="Ordens" src="https://github.com/user-attachments/assets/6bd3c3be-533c-4dfa-b32b-6c27fb84ffc7" />
Crie, acompanhe e atualize ordens de serviço, registrando status e detalhes de cada atendimento.

### Impressão da erdem de Serviço
<img width="1343" height="543" alt="image" src="https://github.com/user-attachments/assets/552a8a6d-dcd1-473b-8a3e-c504adeb015d" />
Gerar PDF da Ordem de Serviço

---

- PHP 8+
- Laravel 12
- MySQL
- Blade
- Vite
- Git & GitHub

---

## 📦 Funcionalidades Planejadas (MVP)

- [ ] Cadastro de clientes
- [ ] Cadastro de técnicos
- [ ] Abertura de Ordem de Serviço
- [ ] Atualização de status (Aberta, Em andamento, Finalizada)
- [ ] Histórico por cliente
- [ ] Autenticação de usuários
- [ ] Controle de permissões (Admin / Técnico)

---

## 🧠 Arquitetura

O projeto segue o padrão MVC do Laravel:

- **Models** → Representação das entidades do sistema
- **Controllers** → Regras de negócio
- **Views (Blade)** → Interface do usuário
- **Migrations** → Controle de versionamento do banco de dados


