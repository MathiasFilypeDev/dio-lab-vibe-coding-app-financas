# 💸 Fluxo — Gestão Financeira por Conversa

> **Projeto desenvolvido como desafio da DIO (Digital Innovation One) explorando os conceitos de Vibe Coding, Engenharia de Prompt, UI/UX Apple e desenvolvimento de MVP com IA.**

---

## 📌 Sobre o Projeto & Problemas Resolvidos

O **Fluxo** nasce para eliminar a principal barreira da organização financeira pessoal: **o atrito e a burocracia da entrada manual de dados**. A grande maioria das pessoas abandona o controle de gastos nas primeiras semanas porque preencher planilhas ou categorizar compras em formulários tradicionais é uma tarefa tediosa, cansativa e sem engajamento.

O **Fluxo** transforma essa experiência ao substituir formulários rígidos por uma **interface conversacional contínua, simples e inteligente**, combinando o conceito de **Vibe Coding** com diretrizes visuais modernas inspiradas no ecossistema Apple (iOS/macOS).

### 🎯 Problemas Resolvidos

1. **Abandono do Controle Financeiro por Cansaço Operacional**: Elimina a necessidade de abrir múltiplos menus e formulários para registrar uma despesa.
2. **Falta de Personalização nos Insights**: O Agente Financeiro analisa os gastos no contexto do usuário e fornece recomendações preventivas em tempo real.
3. **Complexidade Visual em Gráficos Tradicionais**: Substitui painéis poluídos por cartões e widgets minimalistas dentro do próprio feed de conversa.
4. **Resistência de Usuários Iniciantes**: Utiliza linguagem natural e amigável, permitindo que qualquer pessoa interaja como se estivesse conversando com um consultor pelo chat.

---

## 💪 Pontos Fortes do Projeto

* **Interface Conversacional Inteligente (Mobile First)**: Centraliza toda a jornada do usuário em um feed de chat limpo e intuitivo.
* **UI/UX Inspirada na Apple**: Utilização de componentes minimalistas, cantos arredondados (*squircles*), sombras suaves, tipografia refinada e forte legibilidade visual.
* **Processamento de Linguagem Natural**: O usuário registra transações com frases simples do dia a dia, como *"Almoço R$ 45 no cartão"*.
* **Feedback Contextual Ativo**: O Agente Financeiro cruza novos registros com as metas ativas do usuário instantaneamente.
* **Arquitetura de MVP Enxuta**: Foco estrito em resolver a dor principal sem adicionar funcionalidades desnecessárias.

---

## 📸 Imagens Descritivas do Projeto

*(Substitua os links abaixo pelas imagens reais do seu projeto publicadas na pasta `/assets` do repositório)*

### 1. Onboarding Conversacional & Apresentação do Agente
> Tela de boas-vindas do aplicativo simulando o início da interação conversacional com o Agente Financeiro.

![Onboarding e Apresentação do Agente](/assets/agente-registro.png)

---

### 2. Fluxo Principal de Chat & Registro de Gastos
> Feed de conversa exibindo o envio de mensagens em linguagem natural e a geração automática do cartão de confirmação da transação.

![Fluxo de Chat e Cartão de Transação](/assets/painel-comando.png)

---

### 3. Painel de Metas & Relatório Visual em Widgets
> Visualização de cartões minimalistas contendo o progresso de metas financeiras e gráficos de gastos gerados diretamente no feed.

![Painel de Metas e Relatórios](/assets/metas.png)

---

## 🛣️ Passo a Passo: Do Prompt à Publicação no Lovable

Todo o processo de desenvolvimento do **Fluxo** seguiu a metodologia de **Vibe Coding**, priorizando clareza de intenção, estruturação de contexto e iterações estratégicas com IA.

```text
┌─────────────────┐     ┌──────────────────┐     ┌──────────────────┐     ┌──────────────────┐
│  1. Elaboração  │ ──> │  2. Refinamento  │ ──> │  3. Construção   │ ──> │ 4. Publicação &  │
│     do PRD      │     │  no Copilot Web  │     │    no Lovable    │     │   Validação MVP  │
└─────────────────┘     └──────────────────┘     └──────────────────┘     └──────────────────┘
```

### 🛠️ Passo 1: Estruturação do PRD Inicial
Antes de enviar comandos diretos para ferramentas de geração de código, criei um documento de requisitos simplificado (PRD) definindo o problema, o público-alvo e as 5 funcionalidades indispensáveis do MVP.

### 🔍 Passo 2: Lapidação e Refinamento do Prompt no Copilot
Enviei o PRD inicial para o **Copilot Web** com o objetivo de testar a clareza da instrução e adicionar diretrizes específicas de UI/UX baseadas nas convenções de design da Apple (layout clean, cartões flutuantes, conversação nativa e microinterações intuitivas).

#### 📄 Prompt Final Utilizado (PRD Enriquecido)

> **Contexto**  
> Quero criar o conceito do aplicativo "Fluxo", focado em Organização de Finanças Pessoais com navegação mobile, altamente interativa e no estilo Apple (UI/UX clean, cantos arredondados, tipografia refinada e animações suaves). O aplicativo deve operar prioritariamente por meio de conversas em linguagem natural com um Agente Financeiro alimentado por IA.  
>  
> **Problema**  
> Muitas pessoas abandonam o controle de gastos pela fricção da entrada manual em formulários tradicionais ou planilhas. Falta personalização e um acompanhamento dinâmico e amigável.  
>  
> **Público-Alvo**  
> Iniciantes na organização financeira e pessoas que buscam uma solução prática, rápida e conversacional para o dia a dia.  
>  
> **Funcionalidades-Chave**  
> 1. Registro de receitas e despesas via Chat em linguagem natural.  
> 2. Classificação e categorização automática de transações via IA.  
> 3. Definição, acompanhamento e visualização progressiva de metas financeiras.  
> 4. Agente Financeiro Inteligente ("Fluxo Bot") com tom educativo, empático e consultivo.  
> 5. Dashboards e relatórios visuais gerados diretamente na conversa via widgets minimalistas.  
>  
> **Diretrizes de UI/UX (Estilo Apple)**  
> - Design Mobile-First limpo, foco em clareza e espaçamento equilibrado.  
> - Respostas da IA formatadas em cartões (cards) dinâmicos no próprio feed de conversa.  
> - Sem poluição visual, formulários extensos ou excesso de botões.  
>  
> **Entregável Esperado no Lovable**  
> 1. Plano do MVP (Produto Mínimo Viável) com escopo enxuto e critérios de validação.  
> 2. Definição do Agente Financeiro (Tom de voz, persona e regras de resposta).  
> 3. Fluxo conceitual de telas cobrindo o onboarding, chat principal, registro de despesas e visualização de metas.

### 🚀 Passo 3: Execução e Geração no Lovable
Com o prompt revisado, acessei a plataforma **Lovable** e executei o comando estratégico em etapas para otimizar os limites de interações:

1. **Primeiro Prompt**: Envio do PRD completo solicitando a estrutura geral do app e o fluxo de telas.
2. **Segundo Prompt**: Refinamento da interface conversacional, solicitando a criação dos cartões de transação e dos widgets no estilo iOS.
3. **Terceiro Prompt**: Validação da persona e tom de voz do Agente Financeiro.

### 🌐 Passo 4: Publicação do Projeto e Documentação
Após a validação da estrutura gerada pela IA, criei o repositório no GitHub, organizei os ativos visuais na pasta `/assets`, documentei a experiência no `README.md` e publiquei o projeto para compartilhamento na plataforma da DIO.

---

## 🏗️ Estrutura do Repositório

```text
Fluxo-App/
├── 📄 README.md                 # Documentação completa do projeto e desafio
├── 📱 docs/
│   ├── PRD-Prompt.md            # Prompt e especificações detalhadas do app
│   ├── Agente-Financeiro.md     # Persona, tom de voz e regras do Bot
│   └── Fluxo-de-Telas.md        # Detalhamento da jornada conversacional de telas
└── 🖼️ assets/
    ├── mockup-onboarding.png    # Imagem descritiva da tela de entrada
    ├── mockup-chat-registro.png # Imagem descritiva do registro conversacional
    └── mockup-dashboard-widgets.png # Imagem descritiva dos widgets do app
```

---

## 🤖 Arquitetura do Agente Financeiro ("Fluxo Bot")

* **Papel**: Consultor e parceiro de finanças pessoais focado em educação e hábitos positivos.
* **Tom de Voz**: Didático, acolhedor, transparente e direto, livre de jargões técnicos do mercado financeiro.
* **Exemplo de Comportamento**:
  > **Usuário**: *"Gastei R$ 120 num jantar ontem à noite."*
  > 
  > **Fluxo Bot**: *"Anotado! R$ 120 categorizado em Alimentação/Lazer. Lembre-se que você já atingiu 80% do seu limite semanal para essa categoria. Deseja reajustar suas metas?"*

---

## 💭 Reflexão & Experiência com Vibe Coding

A construção do **Fluxo** aplicando **Vibe Coding** consolidou a importância de atuar como um diretor de produto ao lado da Inteligência Artificial.

### 💪 Pontos Fortes do Processo
* **Velocidade de Ideação**: Transformação de uma ideia abstrata em um conceito funcional de MVP em poucos minutos.
* **Clareza de Requisitos**: A necessidade de fornecer um briefing preciso organizou as ideias antes de focar nos detalhes estéticos.
* **Design Guiado por Restrições**: A definição explícita do padrão Apple forçou a IA a manter consistência e simplicidade visual.

### ⚠️ Desafios Encontrados
* **Gestão de Prompts no Plano Gratuito**: A limitação de chamadas diárias exige que cada prompt seja revisado minuciosamente para evitar desperdício de tentativas.
* **Tendência a Formulários Tradicionais**: A IA inicialmente tendia a sugerir botões e formulários padrão; foi necessário reforçar a restrição da interface conversacional.

### 💡 Aprendizados Principais
1. **Intenção Importa Mais que Código**: Saber explicar o problema e o comportamento esperado da aplicação é a habilidade central na era da IA generativa.
2. **Qualidade de Contexto é Tudo**: Quanto melhor estruturado for o PRD (problema, público, regras e estilo), mais refinado será o resultado entregue pelas ferramentas.

---
### Conclusão
 - O Uso de Vibe Coding, quando aplicado com conhecimento prévio, é uma ferramenta poderosa e nos dá inúmeras possibilidades de melhorar o desempenho, estudar de forma mais estratégica e nos mostra que utilizando as ferramentas corretas (dependendo do contexto) reduz o tempo de produção, aumenta a produtividade e nos mostra que, com o tempo nos tornamos profissionais ainda mais qualificados e que aos invés de algo que vai "roubar nosso emprego" temos um aliado poderosos que nos ajuda, até mesmo de forma grátis, basta o conhecimento correto, organização progressiva e gradual e sempre a iniciativa de melhorar. Chegamos em uma nova era da tecnologia, você escolhe adaptar-se ou perder tempo e produtividade.
---
## 🔗 Links e Referências

- **Plataforma Educacional**: [DIO - Digital Innovation One](https://www.dio.me/)
- **Ferramentas Utilizadas**: Lovable, Copilot Web, GitHub.

---
