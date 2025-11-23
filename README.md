# Desafio DIO – QA Manual Funcional  
## Projeto: SwagLabs Shopping (Loja Virtual)

Este repositório contém a documentação produzida para o desafio de projeto **“O dia a dia de um QA: A prática de testes manuais funcionais”** da DIO, aplicada ao contexto de uma loja virtual chamada **SwagLabs Shopping**.

---

## 1. Contexto do Projeto

O SwagLabs Shopping é uma loja virtual fictícia utilizada como base para estudo de:

- Levantamento e análise de requisitos
- Configuração e fluxo de trabalho em metodologias ágeis (Scrum)
- Atividades de QA com foco em **testes manuais funcionais**, caixa-preta, em nível de sistema e aceite
- Uso de ferramentas como Jira e Confluence para gestão do trabalho e documentação

---

## 2. Documentos Entregues (PDFs)

Todos os documentos foram gerados em **PDF**, conforme orientações da DIO, e estão na pasta `docs/` deste repositório.

### 2.1. Fluxo de Trabalho e Ciclo de Vida do Bug

**Arquivo:** `fluxo_trabalho_swaglabs.pdf`  

Conteúdo:

- Descrição do **fluxo de trabalho de desenvolvimento** no contexto do SwagLabs Shopping (Scrum, backlog, sprint, desenvolvimento, QA, homologação e produção).
- Fluxograma textual dos **status de trabalho** de uma User Story:
  - Backlog → To Do → In Progress → In Review → In Test (QA) → Done
- Descrição detalhada do **ciclo de vida do bug**:
  - New → Assigned → Open → Fixed → Pending Retest → Retest → Verified → Closed  
  - Estados alternativos: Rejected, Duplicate, Deferred, Reopened.
- Papel do QA em todo o fluxo.

---

### 2.2. User Stories

**Arquivo:** `user_stories_swaglabs.pdf`  

Conteúdo:

- Mínimo de **2 User Stories** criadas para o contexto da loja virtual SwagLabs:
  1. **Login do Cliente**
     - Como cliente da loja virtual, desejo fazer login com e-mail e senha para acessar minha conta e finalizar compras com segurança.
  2. **Adicionar Produto ao Carrinho**
     - Como cliente logado, desejo adicionar produtos ao carrinho para selecionar o que vou comprar antes de finalizar o pedido.
- Para cada User Story:
  - Épico associado (ex.: Autenticação, Carrinho)
  - Critérios de aceite claros e testáveis (podendo usar Given/When/Then)

---

### 2.3. Mind Map de User Story

**Arquivo:** `mind_map_user_story.pdf`  

Conteúdo:

- **Mind-map** produzido para uma das User Stories (por exemplo, “Adicionar Produto ao Carrinho”).
- Estrutura visual contemplando:
  - Entradas (estado logado, catálogo de produtos, botão “Adicionar ao carrinho”)
  - Regras (produto disponível, preço, quantidade padrão)
  - Comportamento esperado (atualização do carrinho, exibição de itens)
  - Mensagens/feedback ao usuário
  - Variações de cenários e riscos

O mind-map foi criado em ferramenta visual (como XMind / Miro / MindMup) e exportado para PDF.

---

### 2.4. Casos de Teste – Step-by-step

**Arquivo:** `casos_teste_step_by_step_swaglabs.pdf`  

Conteúdo (exemplos):

- **CT-001 – Login com credenciais válidas**
  - Pré-condições, dados de teste, passos detalhados e resultado esperado para um login bem-sucedido.
- **CT-002 – Adicionar produto válido ao carrinho**
  - Passos para adicionar um produto disponível ao carrinho e validar o comportamento do contador, a listagem e o total.

Os casos seguem o formato step-by-step, com foco em clareza e reprodutibilidade.

---

### 2.5. Casos de Teste – BDD (Gherkin)

**Arquivo:** `casos_teste_bdd_swaglabs.pdf`  

Conteúdo (exemplos):

- **BDD-001 – Login bem-sucedido**
  - Funcionalidade: Login na loja virtual SwagLabs  
  - Cenário: Login com credenciais válidas  
  - Formato Given/When/Then (Dado/Quando/Então).
- **BDD-002 – Adicionar produto ao carrinho com sucesso**
  - Funcionalidade: Carrinho de compras  
  - Cenário: Adicionar produto disponível ao carrinho  
  - Também descrito em Gherkin.

---

## 3. Ferramentas e Metodologia

- **Metodologia:** Scrum
- **Ferramentas sugeridas:**
  - Jira (gestão de backlog, fluxo de trabalho e bugs)
  - Confluence (documentação)
  - Ferramenta de mind-map (XMind, MindMup, Miro, etc.)
- **Tipo de teste:** Manual, funcional, caixa-preta
- **Nível de teste:** Sistema e aceite (UAT)

---

## 4. Como Este Repositório se Relaciona ao Desafio da DIO

Este repositório foi estruturado para atender aos itens exigidos no slide:

- Plano de fluxo de trabalho de desenvolvimento e ciclo de vida do bug (PDF)
- Documento com no mínimo 2 User Stories (PDF)
- Documentos de teste:
  - Mind-map de pelo menos 1 User Story (PDF)
  - 2 casos de teste step-by-step (PDF)
  - 2 casos de teste em BDD (PDF)

Toda a documentação está organizada para facilitar a leitura, o rastreamento e a avaliação.

---

## 5. Autor

- Nome: **Rafael Pereira Galhardo**
- Desafio: **O dia a dia de um QA: A prática de testes manuais funcionais – DIO**
- Contato (opcional): [www.linkedin.com/in/rpg2011]
