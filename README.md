# App de Organização de Finanças Pessoais com Vibe Coding


## 🪄 Etapas do Desafio

### 1. Prompts Final


```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas de todas as idades que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes. Abrangendo desde jovens que recebem suas mesadas até idosos, já recebendo aposentadoria.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
Como entrada inicial será solicitado o valor aproximado de rendimentos recebidos, com check box para selecionar em uma lista com faixas de valores
Depois o usuário irá selecionar, em um check box geral, quais são os gastos que fazem parte da sua realidade, para haver um refinamento personalizado para cada usuário.
Também será pedido para que ele informe se têm algum tipo de planejamento futuro, seja a curto ou a longo prazo, como uma viagem, troca de carro, compra de imóvel, reforma...
2. Classificar automaticamente as transações em categorias como gastos fixos (água, luz, internet, escola, cursos livres, condomínio, gás, planos de saúde etc), custos extras anuais (IPVA, IPTU, seguros, materiais escolares, apostilas, etc), gastos variáveis (vestuário, lazer, alimentação, empréstimos, financiamentos, co-participação em planos de saúde, remédios, etc) .
Os gastos fixos deverão ser alimentos anualmente, ou alterado somente quando tiverem reajustes, evitando ter que preenchê-los mensalmente  
3. Definir e acompanhar metas financeiras, fazer planejamento de projetos futuros a curto e a longo prazo, metas de investimentos e amortização/quitação de dívidas.  
4. Receber dicas de economia do “Agente Financeiro”, como:
- se identificar a possibilidade de economizar em alguma categoria, retornar em tela com dicas simples. Retornando a dica após a entrada de algum gasto considerado desnecessário
- identificando sobra de valores naquele mês, sugerir valores a serem guardados a fim de realizar algum dos planejamentos futuros
5. A solução deverá ser construída com base em Design Universal, garantindo que o aplicativo ofereça uma experiência acessível, intuitiva e inclusiva para o maior número possível de pessoas, independente da idade, nível de alfabetização digital, limitações físicas ou cognitivas. Isso inclui:
- interface clara e legível
- navegação simples e sem sobrecarga de informações
- compatibilidade com leitores de tela e comandos por voz
- opções de feedbacks visuais e auditivos para facilitar o uso
6. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

## Resposta do Copilot para "Quero o PRD ideal para colar no Lovable":


## PRD – Aplicativo Conversacional de Organização de Finanças Pessoais

## Visão do Produto
Aplicativo de organização de finanças pessoais que funciona por meio de conversas com o usuário.  
O objetivo é ajudar pessoas iniciantes a controlar gastos, planejar objetivos e economizar dinheiro de forma simples, natural e sem burocracia.

O aplicativo atua como um "Agente Financeiro", conversando com o usuário, entendendo frases naturais e oferecendo orientações claras e personalizadas.

---

## Problema
Muitas pessoas desistem de organizar suas finanças porque os aplicativos existentes exigem:
- Muito preenchimento manual
- Linguagem técnica difícil
- Planilhas e cadastros complexos
- Pouca orientação prática

Esse produto resolve isso ao permitir que tudo seja feito por conversa, com auxílio ativo da IA.

---

## Público-Alvo
- Pessoas que nunca organizaram suas finanças
- Usuários que querem simplicidade e praticidade
- Pessoas com baixa ou média familiaridade com tecnologia
- Pessoas de diferentes idades e com possíveis limitações físicas ou cognitivas

---

## Objetivo Principal
Ajudar o usuário a:
- Entender para onde vai o seu dinheiro
- Criar o hábito de registrar gastos
- Planejar metas e sonhos
- Receber orientações simples para economizar

---

## Funcionamento Geral
O usuário conversa com o aplicativo, digitando ou falando frases comuns do dia a dia.  
O Agente Financeiro interpreta a mensagem, organiza as informações e responde de forma clara e acolhedora.

---

## Onboarding (Primeiro Acesso)

No início, o Agente Financeiro conduz uma conversa guiada para entender a realidade do usuário.

### 1. Faixa de renda mensal
O usuário escolhe uma faixa aproximada:
- Até R$ 2.000
- De R$ 2.000 a R$ 4.000
- De R$ 4.000 a R$ 8.000
- Acima de R$ 8.000

Não é necessário informar valores exatos.

### 2. Gastos fixos da realidade do usuário
O usuário seleciona quais despesas fazem parte do seu mês:
- Aluguel
- Condomínio
- Água, luz, internet, gás
- Escola ou cursos
- Plano de saúde
- Transporte recorrente
- Outros

Esses gastos não precisam ser informados todo mês.  
Eles só serão revisados uma vez por ano ou quando houver reajuste.

### 3. Planejamentos e sonhos
O usuário informa se possui planos futuros:
- Curto prazo (ex: viagem, pequena reforma)
- Médio prazo (ex: trocar de carro, estudar)
- Longo prazo (ex: imóvel, aposentadoria)

---

## Registro de Gastos por Conversa

O usuário registra gastos com frases simples, como:
- "Gastei 45 reais no mercado"
- "Paguei a conta de luz hoje"
- "Comprei um tênis por 280"

O Agente Financeiro:
- Identifica o tipo de gasto
- Organiza automaticamente
- Só faz perguntas adicionais se algo não estiver claro

---

## Tipos de Gastos

### 1. Gastos Fixos
São gastos recorrentes que mudam pouco ao longo do tempo:
- Água, luz, internet, gás
- Condomínio
- Escola e cursos
- Plano de saúde

Esses gastos:
- São registrados uma vez
- São revisados apenas anualmente ou quando houver reajuste

### 2. Custos Extras Anuais
São gastos que acontecem poucas vezes por ano:
- IPVA
- IPTU
- Seguros
- Material escolar

O Agente Financeiro:
- Lembra o usuário quando chega a época
- Sugere a divisão do valor ao longo dos meses

### 3. Gastos Variáveis (mensais)
São gastos que acontecem todo mês e variam de valor:
- Alimentação
- Lazer
- Vestuário
- Remédios
- Coparticipações
- Empréstimos e financiamentos

Esses gastos:
- São registrados mensalmente
- Fazem parte da rotina de conversa com o app

---

## Metas e Planejamento Financeiro

O usuário pode criar metas como:
- Guardar dinheiro para uma viagem
- Quitar ou amortizar dívidas
- Reservar dinheiro para um objetivo específico

O Agente Financeiro:
- Ajuda a definir valores mensais
- Mostra o progresso de forma simples
- Ajusta sugestões conforme a realidade do mês

---

## Dicas do Agente Financeiro

O aplicativo oferece recomendações quando identifica oportunidades, sempre com tom educativo.

Exemplos:
- Sugerir economia ao perceber gastos excessivos em uma categoria
- Incentivar a guardar dinheiro quando sobra valor no mês
- Ajudar o usuário a manter foco nos objetivos

Nunca usar tom punitivo ou julgador.

---

## Relatórios Simples
O usuário pode visualizar:
- Resumo do mês (quanto entrou e quanto saiu)
- Principais categorias de gasto
- Progresso das metas

Relatórios com pouco texto, visual claro e fácil entendimento.

---

## Acessibilidade e Inclusão
O aplicativo deve:
- Ter interface clara e legível
- Evitar excesso de informações
- Ser compatível com leitores de tela
- Permitir uso por voz
- Oferecer feedbacks simples e objetivos

---

## Fora do Escopo Inicial
- Integração com bancos
- Open Finance
- Investimentos automáticos
- Funcionalidades avançadas de relatórios

---

## Tom e Personalidade do Agente Financeiro
- Educativo
- Acolhedor
- Claro e paciente
- Linguagem simples
- Sem termos técnicos
- Focado em ajudar, não em julgar


### 2. Explorando o Lovable na Prática

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).


### 3. Entregando o Desafio na DIO

## Algumas fases da interação com a IA;
<img width="690" height="328" alt="image" src="https://github.com/user-attachments/assets/73b7ef98-e481-4008-8021-31f331610153" />

## Questionei o Lovable nesta etapa, pois minha ideia é que ele iniciasse pedindo os gastos fixos mensais, para armazenamento
Retorno:
"Para armazenar os gastos fixos de forma persistente, preciso habilitar o Lovable Cloud (backend com banco de dados). Posso fazer
Também quero confirmar: você quer que o onboarding peça os valores"

<img width="356" height="329" alt="image" src="https://github.com/user-attachments/assets/3b8ffede-2cf5-4843-872e-719366de058d" />

## Optei por Valores exatos:

<img width="368" height="400" alt="image" src="https://github.com/user-attachments/assets/c4509244-6722-4655-a9cb-6f89e4affc99" />

<img width="356" height="167" alt="image" src="https://github.com/user-attachments/assets/32d28cbb-2bc3-4908-a9b3-c8ff3c1b0fda" />

## Lovable fez as alterações e retornou com o início desejado, porém me alertou quanto a segurança:

<img width="522" height="454" alt="image" src="https://github.com/user-attachments/assets/60056941-b7a9-46f3-84ac-0f6043db67b9" />

---

### Inseri os dados, porém coloquei que recebi um valor extra e ele não entendeu como entrada, pedi a correção e também que me gerasse uma página com o extrato, detalhando entradas e saídas. Também foi solicitado que corrigisse o problema da segurança, iniciando com login e senha para o app

O login e senha foram criados, porém os ganhos extras o app não entendeu:
<img width="803" height="521" alt="image" src="https://github.com/user-attachments/assets/735d72e2-36ec-40f1-b62b-bbe71a5ca862" />

Também não conseguiu gerar o extrato, dando erro. Os créditos do dia acabaram novamente, somente com essa interação

### Optei por retornar ao Copilot e solicitar a correção do PRD inicial, com os erros encontrados no Lovable. Também iniciei a criação do App no próprio Copilot, por ser totalmente gratuito



# Resumo das funcionalidades do **App de Finanças Pessoais**:

  
**Reflexão sobre o processo**:
  - O que funcionou bem?

O Copilot foi a ferramenta preferida neste projeto, pois as interações ilimitadas permitiu o refinamento do prompt de maneira eficaz e rápida

  - O que não funcionou como o esperado?

Por questões de segurança, não sei se indicar o valor exato das receitas no App é viável, o que torna um pouco mais complicado para os iniciantes fazerem a correta gestão de seus rendimentos.

O Lovable, com a versão gratuita, possui poucas iterações diárias, o que acaba atrasando a geração do App, e causando a perda de raciocínio lógico na criação.

  - O que aprendeu sobre conversar com IAs?

Conversar com a IA é extremamente divertido, basta saber exatamente o que você quer e expor as ideias completas, de maneira clara, que se obtém o resultado esperado. Por mais que ouça falar sobre as "alucuinações", nessa experiência não tive esse problema.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
