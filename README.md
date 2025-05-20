# EasyMoney - Sistema de Controle Financeiro com Inteligência Artificial

![Badge](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

## 📌 Índice

1. [Descrição do Projeto](#descrição-do-projeto)
2. [Status do Projeto](#status-do-projeto)
3. [Funcionalidades e Telas do Sistema](#funcionalidades-e-telas-do-sistema)
4. [Inteligência Artificial para Finanças Pessoais](#inteligência-artificial-para-finanças-pessoais)
5. [Acesso ao Projeto](#acesso-ao-projeto)
6. [Tecnologias Utilizadas](#tecnologias-utilizadas)
7. [Pessoas Contribuidoras](#pessoas-contribuidoras)
8. [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras-do-projeto)
9. [Outros Produtos Easydata360](#outros-produtos-easydata360)
10. [Estrutura de Arquivos](#estrutura-de-arquivos)
11. [Estrutura do Banco de Dados](#estrutura-do-banco-de-dados)
12. [Licença](#licença)

---

## 📖 Descrição do Projeto

**EasyMoney** é uma solução de controle financeiro pessoal desenvolvida pela **Easydata360**, pensada para oferecer muito mais do que simples registros de entradas e saídas. Combinando **interface amigável**, **tecnologia de ponta** e **inteligência artificial aplicada às finanças**, o aplicativo ajuda usuários a organizarem sua vida financeira, tomarem melhores decisões e planejarem o futuro com clareza e segurança.

O sistema é construído com foco mobile-first utilizando **React Native**, **PostgreSQL** como banco de dados robusto e escalável, e conteinerização com **Docker** para facilitar a distribuição e implantação em diferentes ambientes. Além disso, conta com dashboards visuais interativos desenvolvidos com **D3.js**, oferecendo análises dinâmicas e personalizadas da saúde financeira do usuário.

Com o apoio de modelos de linguagem (LLMs) como **OpenAI** ou **Gemini**, o EasyMoney transforma-se em um verdadeiro **consultor financeiro digital**. Ele analisa dados em tempo real, simula cenários, propõe metas e oferece sugestões de economia, investimento e controle de dívidas de forma contextualizada e pessoal.

Seja para quem quer sair do vermelho, se planejar para grandes conquistas ou simplesmente entender melhor o próprio dinheiro, o EasyMoney entrega autonomia, clareza e inteligência — tudo na palma da mão.

---

## 🚀 Status do Projeto

O projeto está em desenvolvimento ativo. A versão inicial será lançada como aplicativo mobile, e posteriormente migrada para versão web com React.

---

## ✨ Funcionalidades e Telas do Sistema

O EasyMoney é composto por diversas telas integradas, que permitem ao usuário realizar a gestão completa de suas finanças pessoais de maneira simples, intuitiva e eficiente:

### 🏠 Tela de Dashboard (Home)

Apresenta uma visão geral e interativa da saúde financeira do usuário. Traz gráficos com:

* Evolução do saldo ao longo do tempo;
* Distribuição de gastos por categoria;
* Comparação entre contas bancárias;
* Rentabilidade dos investimentos.
  Utiliza D3.js para visualizações dinâmicas e responsivas.

### 💸 Tela de Lançamentos

Permite registrar todas as movimentações financeiras:

* Entradas e saídas de dinheiro;
* Campos para data, descrição, valor, tipo (entrada/saída), categoria, conta bancária e parcelas;
* Exibição de lançamentos recentes em tabela dinâmica;
* Cálculo automático do saldo acumulado.

### 📂 Tela de Categorias

Facilita a organização das transações:

* Cadastro, edição e exclusão de categorias de receita e despesa;
* Exemplo: "Alimentação", "Lazer", "Salário", "Investimentos" etc.;
* As categorias alimentam diretamente a tela de lançamentos e os gráficos do dashboard.

### 🏦 Tela de Contas Bancárias

Controle total sobre os recursos distribuídos em diferentes instituições:

* Cadastro de contas correntes, poupança e carteiras digitais;
* Visualização de saldo inicial e saldo atual com base nas movimentações relacionadas;
* Útil para saber onde está o dinheiro em tempo real.

### 📅 Agenda Financeira / Calendário de Pagamentos

Organização visual das obrigações financeiras:

* Mostra despesas fixas, parcelas futuras e lançamentos agendados;
* Visualização mensal ou semanal;
* Ajuda a evitar atrasos e facilita o planejamento por datas.

### 💳 Tela de Despesas Fixas

Gerencia gastos recorrentes mensais:

* Cadastro de despesas como aluguel, internet, plano de saúde;
* Definição de valores, vencimentos e conta vinculada;
* Automatiza os lançamentos mensais e evita esquecimentos.

### 📈 Tela de Investimentos

Acompanhamento completo dos ativos financeiros:

* Cadastro de tipo de investimento (ações, criptomoedas, renda fixa etc.);
* Informações sobre item investido, valor de compra, preço atual e rentabilidade;
* Registro da frequência de pagamento e rendimentos recebidos;
* Gráficos para acompanhar crescimento e rentabilidade real.

### 📊 Relatórios Personalizados

Análises detalhadas sob demanda:

* Filtros por período, tipo de transação, categoria e conta bancária;
* Geração de relatórios analíticos com gráficos comparativos;
* Exportação em PDF ou Excel para uso externo e tomada de decisão.

---

## 🤖 Inteligência Artificial para Finanças Pessoais

EasyMoney contará com um **módulo de IA integrado com LLMs** (como ChatGPT ou Gemini), que funcionará como um **consultor financeiro pessoal acessível**. Essa funcionalidade permitirá:

* Análise da situação financeira do usuário com base nos seus dados reais (renda, despesas, saldo, investimentos, dívidas).
* Sugestões personalizadas sobre quanto poupar, como investir e onde economizar.
* Recomendações sobre organização de dívidas e estratégias tributárias.
* Respostas em linguagem natural para perguntas como:

  * "Quanto posso gastar este mês?"
  * "Como melhorar meu rendimento mensal?"
  * "Quais categorias mais afetaram meu orçamento?"
* Simulação de metas e projeção de saldo futuro com base em cenários e objetivos.
* Acompanhamento de metas e desempenho financeiro com alertas inteligentes.

> A IA terá acesso controlado e seguro aos dados do usuário, com foco em **privacidade, transparência e personalização real.**

---

## 🔗 Acesso ao Projeto

Para acessar o código-fonte, clone o repositório:

```sh
git clone https://github.com/seuusuario/EasyMoney.git
cd EasyMoney
```

---

## 🛠 Tecnologias Utilizadas

* **Frontend/App Mobile:** React Native
* **Backend e API:** Python (Flask ou FastAPI com arquitetura MVC)
* **Banco de Dados:** PostgreSQL (alta performance, integridade relacional, multiusuário)
* **Containerização:** Docker (Docker Compose para orquestração de serviços)
* **Visualização de Dados:** D3.js (para gráficos e relatórios interativos)
* **Inteligência Artificial:** Google Gemini (via Google Cloud AI APIs)
* **Infraestrutura em Nuvem:** Google Cloud Platform (GCP), com escalabilidade e deploy contínuo
* **Arquitetura planejada:** Mobile-first, escalável, com futura versão Web em React\*\* Mobile-first, escalável, com futura versão Web em React

---

## 👥 Pessoas Contribuidoras

Caso queira contribuir para o projeto, abra um pull request ou entre em contato.

---

## 👨‍💻 Pessoas Desenvolvedoras do Projeto

* [Nome do Desenvolvedor 1](https://github.com/usuario1)
* [Nome do Desenvolvedor 2](https://github.com/usuario2)

---

## 🚀 Outros Produtos Easydata360

A Easydata360 desenvolve soluções inteligentes e ágeis. Todos os produtos começam com **"Easy"**:

* **EasyChat:** Chat de atendimento ao cliente com inteligência artificial e integração à base de dados.
* **EasyGym:** Sistema de gestão para academias, com controle de alunos, planos e pagamentos.
* **EasyBlog:** Plataforma para geração e publicação automatizada de conteúdo em blogs e redes sociais.
* **EasyInsight:** Microserviço de análise de dados sob demanda, que transforma arquivos em gráficos, relatórios e insights inteligentes.

Saiba mais em nosso site: [Easydata360](https://easydata360.com)

---

## 🗂️ Estrutura de Arquivos

A estrutura de diretórios do EasyMoney segue boas práticas de desenvolvimento e o padrão arquitetural MVC (Model-View-Controller), implementado tanto no aplicativo React Native quanto no backend em Python (Flask/FastAPI). Essa organização garante escalabilidade, modularidade e facilidade de manutenção para times de desenvolvimento.

```plaintext
EasyMoney/
├── app/                         # Aplicativo React Native (camada de visualização)
│   ├── assets/			 # Logos, ícones, fontes
│   │   ├── logo.png
│   │   ├── icons/
│   ├── components/		 # Componentes reutilizáveis de interface
│   │   ├── Header.js
│   │   ├── CardBalance.js
│   │   ├── TransactionItem.js
│   ├── screens/		 # Telas principais do app (Dashboard, Lançamentos, etc.)
│   │   ├── DashboardScreen.js
│   │   ├── TransactionsScreen.js
│   │   ├── AccountsScreen.js
│   │   ├── FixedExpensesScreen.js
│   │   ├── InvestmentsScreen.js
│   │   ├── CalendarScreen.js
│   ├── navigation/		# Definição de rotas e navegação entre telas
│   │   ├── AppNavigator.js
│   ├── services/		# Integração com APIs do backend
│   │   ├── api.js
│   ├── context/		# Contextos globais (usuário, autenticação, tema)
│   │   ├── AuthContext.js
│   │   ├── ThemeContext.js
│   ├── hooks/			# Hooks personalizados
│   │   ├── useFetch.js
│   │   ├── useAuth.js
│   ├── styles/			# Estilos globais e variáveis de tema
│   │   ├── colors.js
│   │   ├── global.js
│   └── App.js			 # Entrada principal do app
│
├── backend/			# Backend Python (Flask/FastAPI com padrão MVC)
│   ├── app/			# Aplicação principal
│   │   ├── controllers/	# Controladores: tratam requisições e respostas
│   │   │   ├── user_controller.py
│   │   │   ├── transaction_controller.py
│   │   │   ├── account_controller.py
│   │   │   ├── investment_controller.py
│   │   │   ├── fixed_expense_controller.py
│   │   │   ├── calendar_controller.py
│   │   ├── models/		# Definições das tabelas e ORM com SQLAlchemy
│   │   │   ├── user.py
│   │   │   ├── transaction.py
│   │   │   ├── account.py
│   │   │   ├── investment.py
│   │   │   ├── fixed_expense.py
│   │   ├── routes/		 # Módulos de rotas organizadas
│   │   │   ├── user_routes.py
│   │   │   ├── transaction_routes.py
│   │   │   ├── account_routes.py
│   │   ├── services/		# Regras de negócio, integrações com IA e lógica complexa	
│   │   │   ├── auth_service.py
│   │   │   ├── investment_service.py
│   │   │   ├── ai_advisor_service.py  # Integração com IA Gemini
│   │   ├── middlewares/	# Middlewares (autenticação, validações, erros)
│   │   │   ├── auth_middleware.py
│   │   ├── schemas/		# Validação de entrada/saída com Pydantic (se FastAPI)
│   │   │   ├── transaction_schema.py
│   │   │   ├── investment_schema.py
│   │   ├── __init__.py		# Inicialização da aplicação
│   ├── config/			# Arquivos de configuração do ambiente, banco etc.
│   │   ├── database.py
│   │   ├── settings.py
│   ├── main.py                 # Ponto de entrada da aplicação Flask/FastAPI
│   ├── requirements.txt	# Dependências do backend
│
├── database/ 			# Scripts e versionamento do banco PostgreSQL
│   ├── migrations/ 		# Scripts de migração (via Alembic ou Flask-Migrate)
│   │   ├── 001_create_tables.sql
│   │   ├── 002_add_investments.sql
│   ├── seeders/		# Dados para popular ambiente de dev
│   │   ├── sample_users.sql
│   │   ├── sample_transactions.sql
│   └── init.sql		# Estrutura inicial para criação do banco
│
├── docker/			# Containerização
│   ├── Dockerfile.backend	# Build do container do backend
│   ├── Dockerfile.react	# Build do app mobile (usado em CI/CD ou PWA opcional)
│   └── docker-compose.yml	# Orquestração de backend, db e serviços auxiliares
│
├── scripts/			# Scripts auxiliares (deploy, backup, restore)
│   ├── start.sh		# Inicialização customizada do containe
│   ├── reset_db.sh
│
├── .env			# Variáveis de ambiente (não versionado)
├── .gitignore			# Ignora arquivos sensíveis e cache
├── README.md			# Documentação principal do projeto
├── Makefile			# Comandos simplificados para devops/test/build
└── LICENSE

```

Essa estrutura promove:

* Separação de responsabilidades (MVC);
* Flexibilidade para escalar ou trocar camadas do sistema;
* Facilidade de testes e manutenção;
* Integração facilitada com ferramentas de CI/CD e DevOps.

## 🧩 Estrutura do Banco de Dados

O banco de dados do EasyMoney utiliza **PostgreSQL** e é modelado com foco em integridade relacional, performance e extensibilidade. A seguir, está o detalhamento das principais tabelas e seus relacionamentos:

### 🔹 Tabela: `usuarios`

Armazena os dados dos usuários da aplicação.

```sql
id SERIAL PRIMARY KEY,
nome TEXT NOT NULL,
email TEXT UNIQUE NOT NULL,
senha TEXT NOT NULL,
criado_em TIMESTAMP DEFAULT NOW()
```

### 🔹 Tabela: `contas_bancarias`

Contas utilizadas para movimentações e investimentos.

```sql
id SERIAL PRIMARY KEY,
usuario_id INTEGER REFERENCES usuarios(id),
nome TEXT NOT NULL,
tipo TEXT NOT NULL, -- ex: corrente, poupança
saldo_inicial NUMERIC(10,2) DEFAULT 0
```

### 🔹 Tabela: `categorias`

Categorias de transações financeiras.

```sql
id SERIAL PRIMARY KEY,
nome TEXT NOT NULL,
tipo TEXT CHECK (tipo IN ('entrada', 'saida')),
usuario_id INTEGER REFERENCES usuarios(id)
```

### 🔹 Tabela: `lancamentos`

Movimentações financeiras de entrada e saída.

```sql
id SERIAL PRIMARY KEY,
data DATE NOT NULL,
descricao TEXT,
valor NUMERIC(10,2) NOT NULL,
tipo TEXT CHECK (tipo IN ('entrada', 'saida')),
categoria_id INTEGER REFERENCES categorias(id),
conta_id INTEGER REFERENCES contas_bancarias(id),
usuario_id INTEGER REFERENCES usuarios(id),
parcela TEXT
```

### 🔹 Tabela: `despesas_fixas`

Despesas mensais recorrentes.

```sql
id SERIAL PRIMARY KEY,
nome TEXT NOT NULL,
valor NUMERIC(10,2) NOT NULL,
vencimento INTEGER CHECK (vencimento BETWEEN 1 AND 31),
conta_id INTEGER REFERENCES contas_bancarias(id),
usuario_id INTEGER REFERENCES usuarios(id)
```

### 🔹 Tabela: `investimentos`

Investimentos realizados pelos usuários.

```sql
id SERIAL PRIMARY KEY,
data DATE NOT NULL,
tipo TEXT NOT NULL, -- ex: ações, cripto
item TEXT NOT NULL, -- ex: PETR4, Bitcoin
valor_compra NUMERIC(10,2) NOT NULL,
preco_atual NUMERIC(10,2),
frequencia_pagamento TEXT, -- mensal, trimestral, etc.
valor_recebido NUMERIC(10,2),
conta_id INTEGER REFERENCES contas_bancarias(id),
usuario_id INTEGER REFERENCES usuarios(id)
```

Essa estrutura permite:

* Relacionar todas as informações financeiras por usuário;
* Garantir segurança e isolamento de dados multiusuário;
* Integrar facilmente com análises preditivas e inteligência artificial;
* Facilitar geração de relatórios complexos e dashboards.

## 📜 Licença

Este projeto está licenciado sob a Licença MIT.
