# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);
  ''''
  # PRD: FinanceChat — MVP de Finanças Pessoais Conversacional

## 1. Visão Geral do Produto
* **Nome do Projeto:** FinanceChat
* **Objetivo:** Criar um aplicativo web intuitivo e acessível para gerenciamento de finanças pessoais, no qual o usuário registra e acompanha gastos conversando com um agente inteligente em linguagem natural.
* **Problema Resolvido:** Eliminar o atrito do preenchimento manual em planilhas ou formulários burocráticos que levam iniciantes e pessoas com diferentes níveis de habilidade a desistir do controle financeiro.
* **Público-Alvo:** Iniciantes na organização financeira, idosos ou pessoas com pouca afinidade tecnológica que buscam uma experiência simples, humana e inclusiva.

---

## 2. Diretrizes de Design Universal & Acessibilidade (a11y)
* **Contraste e Cores (WCAG AA):** Taxa de contraste elevada entre texto e fundo. Suporte claro a modo Claro/Escuro ajustável pelo usuário.
* **Informação Perceptível (Dupla Codificação):** Indicadores de saldo, ganhos e perdas **nunca** dependem apenas da cor (verde/vermelho). Devem sempre estar acompanhados de ícones explícitos (+ / -, setas para cima/baixo, sinalizadores de texto).
* **Uso Flexível e Múltiplas Entradas:** A barra de chat deve suportar entrada via **texto** e simulação de **comando de voz** (*Speech-to-Text* via microfone).
* **Navegação por Teclado e Semântica:** Utilização de componentes semânticos (`<main>`, `<nav>`, `<button>`) com atributos `aria-label` para compatibilidade total com leitores de tela.
* **Ergonomia e Área de Clique:** Botões e elementos clicáveis com área mínima de $44 \times 44\text{px}$ para telas sensíveis ao toque. Tipografia legível (mínimo $16\text{px}$ para texto base).
* **Tolerância ao Erro e Prevenção:** O agente sempre confirma dados extraídos antes de salvar e oferece opções diretas de "Editar" ou "Desfazer" transações.

---

## 3. Arquitetura e Stack Tecnológica (Padrão Lovable)
* **Frontend:** React + Vite + Tailwind CSS
* **Componentes de UI:** Shadcn UI + Lucide Icons (design acessível e responsivo)
* **Gerenciamento de Estado:** React Hooks / Context API (Estado global unificado de transações e metas)
* **Gráficos:** Recharts / Shadcn Chart (com legendas e padrões de fácil leitura)
* **Backend & Banco de Dados:** PostgreSQL / Supabase (ou Mock local expansível)

---

## 4. Modelo de Dados (Database Schema)

### Tabela `transactions` (Transações)
| Campo | Tipo | Descrição |
| :--- | :--- | :--- |
| `id` | UUID | Identificador único da transação |
| `amount` | Decimal | Valor numérico da transação |
| `description` | String | Descrição textual (ex: "Compras no mercado") |
| `category` | String | Categoria (ex: Alimentação, Transporte, Moradia, Lazer, Saúde) |
| `type` | Enum | `INCOME` (Receita) ou `EXPENSE` (Despesa) |
| `date` | Timestamp | Data e hora do registro |

### Tabela `goals` (Metas Financeiras)
| Campo | Tipo | Descrição |
| :--- | :--- | :--- |
| `id` | UUID | Identificador único |
| `title` | String | Nome da meta (ex: "Reserva de Emergência") |
| `target_amount` | Decimal | Valor objetivo final |
| `current_amount` | Decimal | Valor acumulado até o momento |
| `deadline` | Date | Data limite pretendida |

---

## 5. Telas e Interface do Usuário (UI/UX)

Navegação principal via **Sidebar** (Desktop) e **Barra Inferior / Bottom Nav** (Mobile).

### 1. Tela de Chat Conversacional (Aba Principal)
* **Header Acessível:** Nome do app, indicador visual + texto do status ("Agente On-line") e leitor rápido de Saldo Atual.
* **Histórico da Conversa:**
  * Balões de mensagem diferenciados por alinhamento e alto contraste.
  * Respostas do Agente em linguagem simples, pedagógica e sem jargões técnicos.
  * **Card de Confirmação Visível:** Cada gasto/receita detectado exibe um mini-card com ícone, categoria, valor e botões "Confirmar" e "Editar".
* **Barra de Entrada:**
  * Campo de texto amplo.
  * Botão de envio e botão de microfone (Simulação de voz).

### 2. Tela de Dashboard & Relatórios
* **Cards Resumo:** Saldo Total, Entradas do Mês e Saídas do Mês (cada um com ícones + texto + cor).
* **Gráficos Inclusivos:**
  * Gráfico de Pizza/Rosca para categorias com legenda textual clara.
  * Gráfico de Barras com comparação de receitas vs. despesas.
* **Tabela de Transações:** Lista detalhada com busca, filtro de categorias e opção de exclusão/edição com confirmação.

### 3. Tela de Metas Financeiras
* **Cards de Progresso:** Barras de progresso com porcentagem em texto e cores de alto contraste.
* **Modal / Formulário:** Interface simplificada para criação de novas metas com validação amigável de erros.

---

## 6. Regras de Negócio e Agente Financeiro

1. **Parsing Conversacional Inteligente:**
   * Frase: *"Gastei 45 reais na farmácia hoje"*
   * Extração: Valor (`45.00`), Tipo (`Despesa`), Categoria (`Saúde`), Descrição (`Farmácia`).
2. **Dicas Pedagógicas Preventivas:**
   * Se os gastos de uma categoria superarem 30% da receita do mês, o Agente gera uma dica educativa em tom amigável.

---

## 7. Prompt Mestre para o Lovable

```text
Crie o aplicativo web "FinanceChat", um gerenciador de finanças pessoais conversacional focado em extrema facilidade de uso e Princípios de Design Universal (Acessibilidade a11y, WCAG AA).

STACK TECNOLÓGICA & ESTILO:
- React, Tailwind CSS, Shadcn UI, Lucide Icons e Recharts.
- Design limpo, acolhedor e intuitivo com palette de alto contraste (verde/azul financeiro) e suporte nativo a modo Claro/Escuro.
- Layout responsivo com navegação por abas: Chat Conversacional, Dashboard e Metas.
- Padrões de Acessibilidade: Todos os indicadores de ganhos e perdas devem usar cor + ícone (ex: verde com seta para cima (+) para receitas, vermelho com seta para baixo (-) para despesas). Botões com área de clique confortável (mínimo 44px) e fontes legíveis.

Aba 1: CHAT CONVERSACIONAL (Principal)
- Header com status do Agente ("Agente Financeiro On-line") e um resumo em card do Saldo Atual.
- Histórico de mensagens no formato de conversa com rolagem automática.
- Crie um simulador de IA em linguagem natural em português. Ao digitar frases como "Gastei 50 reais no mercado" ou "Recebi 2000 de salário", o agente deve responder educadamente e gerar um Card de Transação estruturado com Valor, Categoria, Tipo e botões de ação ("Confirmar" e "Editar").
- Barra de entrada de mensagem com campo de texto flexível, botão de Enviar e um botão de Microfone (simulação de gravação por voz).

Aba 2: DASHBOARD & RELATÓRIOS
- 3 Cards Principais: Saldo Total, Total de Entradas e Total de Saídas (todos combinando ícones, texto e cores).
- Gráfico de pizza/rosca interativo mostrando a distribuição de gastos por categoria (Alimentação, Transporte, Moradia, Lazer, Saúde, Outros) com legenda visível.
- Gráfico de barras simples comparando Entradas vs Saídas do mês.
- Tabela de transações recentes conectada ao estado global, com opção de excluir uma transação com aviso de confirmação.

Aba 3: METAS FINANCEIRAS
- Lista de metas com barras de progresso dinâmicas (ex: "Reserva de Emergência", "Viagem das Férias") exibindo porcentagem concluída, valor atual e valor objetivo em texto claro.
- Botão "Nova Meta" que abre um modal simples com validação amigável de formulário.

ESTADO GLOBAL & DADOS INICIAIS:
- Adicione dados fictícios (mocks) iniciais para transações e metas para que a dashboard e o chat já venham populados e prontos para demonstração.
- Garanta que qualquer nova transação adicionada pelo chat atualize instantaneamente o saldo, os gráficos do Dashboard e o histórico.
```
  
- Prints ou pequenos vídeos das interações com a IA;
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/258a07cd-6035-47dc-92d8-f70c6825b5d7" />

  
- Um resumo do que o seu **App de Finanças Pessoais** faz;
Visão Geral do Produto
* **Nome do Projeto:** FinanceChat
* **Objetivo:** Criar um aplicativo web intuitivo e acessível para gerenciamento de finanças pessoais, no qual o usuário registra e acompanha gastos conversando com um agente inteligente em linguagem natural.
- 
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
     Todos testes de interação como inclusão e exclusão de dados

  - O que aprendeu sobre conversar com IAs?
    Muita praticidade em transformar a ideia em um produto

> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.
> Visite a página criada
https://personal-cents-pal.lovable.app

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
