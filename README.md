# 💸 App de Finanças Pessoais com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto de Vibe Coding utilizando o Lovable  e o Copilot Web. Com foco em criar um aplicativo de organização financeiro pessoal baseado em interações em linguaguem natural.

---

## 📝 PRD Refinado no Copilot Web

```markdown
# PRD: App de Finanças com Conversa Natural

## Contexto
Muitas pessoas enfrentam dificuldades para organizar suas finanças pessoais devido à complexidade dos aplicativos existentes, que exigem preenchimento manual de dados e conhecimento prévio de finanças. A proposta é criar um aplicativo que funcione como um assistente financeiro conversacional, permitindo que o usuário registre e acompanhe seus gastos por meio de uma interface de chat em linguagem natural.

## Problema
A maioria dos apps de finanças exige esforço excessivo do usuário: preenchimento de planilhas, categorização manual e pouca personalização. Isso desmotiva especialmente quem está começando. Queremos resolver isso com uma experiência fluida, conversacional e inteligente, que incentive o hábito de controle financeiro com o mínimo de fricção.

## Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática, intuitiva e sem complicações — especialmente iniciantes ou pessoas que nunca usaram apps financeiros antes.

## Proposta de Valor
Um app que conversa com você como um “Agente Financeiro Pessoal”, entendendo sua linguagem e ajudando a registrar gastos, definir metas e economizar — tudo de forma leve, educativa e personalizada.

## Funcionalidades-Chave (MVP)
1. Registro de gastos via chat: O usuário descreve o gasto em linguagem natural (ex: “gastei 50 reais no mercado”) e o app interpreta automaticamente.
2. Classificação automática de transações: O app identifica a categoria do gasto (ex: alimentação, transporte).
3. Definição e acompanhamento de metas financeiras: O usuário pode criar metas (ex: “quero economizar R$ 500 este mês”) e acompanhar o progresso.
4. Dicas personalizadas de economia: O “Agente Financeiro” envia sugestões com base nos hábitos do usuário.
5. Relatórios simples e visuais: Gráficos e resumos que mostram para onde o dinheiro está indo, com linguagem acessível.
6. Design Universal: A interface será desenvolvida com base em princípios de acessibilidade e usabilidade, garantindo que pessoas com diferentes perfis — incluindo idosos, pessoas com deficiência visual, baixa alfabetização digital ou limitações motoras — possam utilizar o app com conforto e autonomia.

## Entregável da IA
- Um plano de MVP com:
  - Principais telas (wireframes conceituais)
  - Recursos técnicos necessários (ex: NLP, categorização automática, motor de metas)
  - Estratégia de validação inicial (ex: testes com 5 usuários reais, análise de engajamento no chat)
  - Linguagem acessível e tom educativo, em português.
```

---

## 📸 Interações com o Lovable

> Crie um App de Finanças com o seguinte PRD (Product Requirements Document): {PRD}

> Tentei criar uma meta chamada "Reserva" e um registro de gastos via chat em linguagem natural. Meu app "Assistente Financeiro" precisa ser validado para garantir que as funcionalidades principais estão funcionando corretamente.

> Aqui estão os pontos que não estão atualizando como esperado:
- Ao enviar "gastei 50 reais no mercado" no chat, o gasto não aparece no dashboard.
- Ao criar uma meta de R$ 1000, ela não é registrada nem exibida na aba de metas.
- O dashboard não atualiza com os dados inseridos via chat ou metas criadas.

> Quero que o Lovable verifique:
- Se os dados estão sendo corretamente salvos no Supabase
- Se os componentes Dashboard e Goals estão escutando e renderizando os dados atualizados
- Se há falhas na lógica de sincronização entre o chat e o dashboard/metas
- Se os hooks ou chamadas de API estão funcionando corretamente

---

## ✅ Resultado Final no Lovable

[Visualizar App](https://chat-financeiro-facil.lovable.app)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/440bdda6-33c4-4ce6-a25e-f1006ecaed2e" />

---

## 📌 Resumo do App

**Assistente Financeiro** é um aplicativo de organização de finanças pessoais com interface conversacional em linguagem natural. Desenvolvido para facilitar o controle financeiro de forma acessível, intuitiva e inclusiva.

### Funcionalidades Principais

#### 1. Registro de Gastos via Chat
O usuário pode registrar despesas usando linguagem natural, como:
- "Gastei 50 reais no mercado"

Essas mensagens são interpretadas automaticamente e transformadas em registros financeiros.

#### 2. Classificação Automática de Transações
Os gastos são categorizados com base no conteúdo da mensagem. Exemplo:
- Alimentação: R$ 50,00
- Outros: R$ 3200,00

#### 3. Criação e Acompanhamento de Metas Financeiras
O usuário pode definir metas como:
- "Quero criar uma meta de R$ 1000"

O app registra a meta e acompanha seu progresso. No dashboard, é possível visualizar o número de metas ativas.

#### 4. Visualização de Relatórios Simples
O dashboard exibe:
- Total gasto acumulado
- Gastos do mês atual
- Metas ativas
- Gráfico de gastos por categoria

Essas informações ajudam o usuário a entender para onde está indo seu dinheiro.

#### 5. Interface Conversacional e Educativa
A interação é feita por meio de um chat acessível, com linguagem simples e educativa, facilitando o uso por iniciantes.

#### 6. Design Universal
A interface é desenvolvida com base em princípios de acessibilidade e usabilidade, garantindo que pessoas com diferentes perfis — incluindo idosos, pessoas com deficiência visual, baixa alfabetização digital ou limitações motoras — possam utilizar o app com conforto e autonomia.

---

## 💬 Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações quando bem pensadas já são de grande ajuda para aprender mais sobre o Vibe Coding.

### O que aprendi sobre conversar com IAs?
Aprendi que é basicamente como conversar com uma pessoa. Quanto mais detalhes e clareza você dá, melhor é a interação.

---

Se quiser, posso te ajudar a criar uma seção de instalação ou instruções de uso para complementar o projeto.
