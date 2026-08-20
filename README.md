# 🌐 ConectaIdiomas
![Requisitos](https://img.shields.io/badge/Engenharia%20de-Requisitos-green)
![UML](https://img.shields.io/badge/Modelagem-UML-blue)
![Figma/Wireframes](https://img.shields.io/badge/UI%2FUX-Protótipos-orange)

Sistema proposto para facilitar a conexão entre estudantes interessados em praticar idiomas dentro do ambiente acadêmico.

> **Projeto acadêmico de Requisitos e Modelagem de Sistemas**

---
## 📌 Sobre o projeto

O **ConectaIdiomas** é uma solução projetada para conectar estudantes locais e internacionais interessados em praticar idiomas, permitindo encontrar parceiros com interesses compatíveis, organizar interações e agendar encontros.

O projeto surgiu a partir da identificação de uma dificuldade no ambiente acadêmico: encontrar parceiros adequados para a prática de idiomas e organizar esses encontros de maneira estruturada.

A proposta busca promover o desenvolvimento linguístico, a integração cultural e uma experiência acadêmica mais colaborativa.

---

## 🎯 Objetivo

Especificar uma plataforma capaz de:

- conectar estudantes interessados em troca de idiomas;
- permitir a busca e filtragem de parceiros;
- possibilitar o agendamento de encontros;
- organizar os encontros entre os usuários;
- permitir avaliações após as sessões;
- disponibilizar notificações sobre encontros e atividades;
- oferecer mecanismos de denúncia e moderação;
- disponibilizar funcionalidades administrativas para gerenciamento da plataforma.

---

## 👥 Público-alvo

O sistema foi pensado principalmente para estudantes universitários, incluindo:

- estudantes locais interessados em praticar idiomas estrangeiros;
- estudantes internacionais interessados em praticar português e integrar-se à comunidade acadêmica;
- administradores responsáveis pelo gerenciamento da plataforma.

A documentação define a Universidade de Fortaleza (UNIFOR) como cliente do projeto e considera estudantes locais e internacionais como público principal.

---

## ⚙️ Principais funcionalidades

### 👤 Usuário

- Cadastro e login;
- Recuperação de senha;
- Gerenciamento de perfil;
- Seleção de idiomas;
- Busca de parceiros;
- Filtros por idioma;
- Visualização de perfis;
- Agendamento de encontros;
- Gerenciamento de agendamentos;
- Confirmação ou recusa de encontros;
- Cancelamento de encontros;
- Avaliação das sessões;
- Notificações;
- Denúncia de usuários.

### 🛡️ Administrador

- Login administrativo;
- Recuperação de senha;
- Painel administrativo;
- Visualização de métricas;
- Gerenciamento de usuários;
- Gerenciamento de encontros;
- Gerenciamento de denúncias e alertas;
- Suspensão de usuários;
- Envio de avisos;
- Consulta de informações e históricos da plataforma.

---

## 📋 Requisitos

Os requisitos foram organizados utilizando identificadores para requisitos funcionais (**RF**) e requisitos não funcionais (**RNF**), além de prioridades classificadas como:

- **Essencial**
- **Importante**
- **Desejável**

Essa organização foi utilizada para facilitar a identificação, priorização e gerenciamento dos requisitos do sistema.

---

## 🔧 Requisitos não funcionais

Entre os requisitos definidos estão aspectos relacionados a:

### Usabilidade

- Interface responsiva;
- Navegação intuitiva;
- Feedback visual;
- Consistência visual;
- Acessibilidade.

### Confiabilidade

- Disponibilidade mínima de 99%;
- Validação de dados;
- Integridade dos dados;
- Recuperação de falhas.

### Desempenho

- Tempo de resposta de até 3 segundos em condições normais;
- Carregamento das principais telas em até 5 segundos em redes 4G;
- Envio de notificações em até 1 minuto;
- Suporte a pelo menos 500 usuários simultâneos.

### Segurança

- Autenticação;
- Armazenamento seguro de senhas;
- Proteção de dados pessoais;
- Controle de acesso por perfil;
- Comunicação utilizando HTTPS;
- Expiração de sessão.

---

## 🧩 Modelagem do sistema

O projeto contempla diferentes artefatos de análise e modelagem:

- Protótipo de baixa fidelidade;
- Diagrama de Caso de Uso;
- Especificação de Casos de Uso;
- Diagrama de Atividades;
- Diagrama de Transição de Estado;
- Diagramas de Sequência;
- Diagrama de Classes;
- Protótipo da solução.

Entre os fluxos representados nos diagramas de sequência estão:

- Login de usuário;
- Agendamento de encontro;
- Suspensão de usuário.

---

## 🎨 Protótipos

Foram especificadas interfaces para diferentes etapas da experiência do usuário, incluindo:

- Cadastro/Login;
- Mural de estudantes;
- Perfil;
- Agendamento;
- Notificações.

Os protótipos foram planejados como wireframes para validação da solução antes do desenvolvimento.

---

## 🚫 Escopo negativo

Para manter o foco na proposta principal, algumas funcionalidades foram explicitamente excluídas do escopo, como:

- Chat em tempo real;
- Tradução automática;
- Correção linguística;
- Gestão de cursos e conteúdos educacionais;
- Integração direta com sistemas acadêmicos institucionais;
- Geolocalização em tempo real.

Essas decisões mantêm o foco do sistema na conexão e organização dos encontros entre estudantes.

---

## 📚 Documentação

A documentação completa do projeto está disponível em:

📄 [`docs/ConectaIdiomas-Requisitos.pdf`](docs/ConectaIdiomas-Requisitos.pdf)

---

## 👥 Integrantes da Equipe

- **Arthur Viana de Assis Lima**
- **Samuel Batista Oliveira**
- **Vítor Apolônio Tourinho Costa**

---


## 📁 Estrutura do projeto

```text
conectaidiomas-requisitos/
│
├── README.md
│
├── docs/
│   └── ConectaIdiomas-Requisitos.pdf
│
├── diagramas/
│   ├── diagrama-caso-de-uso.png
│   ├── diagrama-atividades.png
│   ├── diagrama-transicao-estado.png
│   ├── diagrama-sequencia-login.png
│   ├── diagrama-sequencia-agendamento.png
│   ├── diagrama-sequencia-suspensao.png
│   └── diagrama-classes.png
│
└── prototipos/
    └── baixa-fidelidade/
