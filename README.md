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
10. [Licença](#licença)

---

## 📖 Descrição do Projeto

**EasyMoney** é um aplicativo de controle financeiro pessoal desenvolvido pela **Easydata360**, que combina simplicidade, inteligência artificial e tecnologia mobile para ajudar usuários a dominar suas finanças. Ele permite gerenciar receitas, despesas, contas bancárias, despesas fixas, investimentos e metas financeiras de forma intuitiva e centralizada.

Utilizando **React Native** na construção do app, **SQLite** para armazenamento local e **D3.js** para visualizações interativas, o EasyMoney oferece uma experiência fluida, responsiva e analítica. A plataforma permite acompanhar a saúde financeira em tempo real, identificar padrões de consumo e tomar decisões mais assertivas com apoio de relatórios, gráficos e recomendações personalizadas por IA.

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
* **Banco de Dados Local:** SQLite
* **Visualização de Dados:** D3.js
* **Inteligência Artificial:** OpenAI API / Google Gemini (via integração com backend)
* **Arquitetura planejada:** Mobile-first com migração posterior para Web (React)

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

## 📜 Licença

Este projeto está licenciado sob a Licença MIT.
