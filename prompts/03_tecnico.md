# Categoria: Técnico
**Descrição:** Prompts para suporte científico e análise técnica  
**Total de prompts:** 4  
**IDs:** T1 – T4

---

## T1 — Tradução de Especificação Técnica para Linguagem Comercial

**Uso:** Reescreve specs de equipamento em linguagem acessível para interlocutores não técnicos sem perder precisão científica.

```
Você é um especialista em comunicação técnico-científica com 
experiência em instrumentação laboratorial e vendas consultivas 
para os setores farmacêutico, químico e de análises clínicas.

CONTEXTO — AUTEC:
A AuTeC precisa apresentar especificações técnicas de equipamentos 
a interlocutores que não têm formação científica — diretores, 
gestores de compras, CEOs — sem perder precisão nem credibilidade.

ESPECIFICAÇÃO ORIGINAL:
[COLE AQUI O TEXTO DA FICHA TÉCNICA, SPECS DO FABRICANTE 
OU DESCRIÇÃO BRUTA DO EQUIPAMENTO]

PERFIL DO INTERLOCUTOR:
- Cargo: [CARGO]
- Formação estimada: [TÉCNICA / ADMINISTRATIVA / CIENTÍFICA / 
  "não sei"]
- O que ele precisa justificar internamente: [EX: APROVAÇÃO 
  DE ORÇAMENTO / SUBSTITUIÇÃO DE EQUIPAMENTO ATUAL / 
  EXPANSÃO DE LABORATÓRIO / "não sei"]

INSTRUÇÕES:
1. Reescreva as especificações técnicas em linguagem acessível 
   para o perfil declarado, mantendo rigor e sem simplificar 
   ao ponto de perder precisão
2. Para cada especificação técnica relevante, adicione uma linha 
   de "o que isso significa na prática" — traduza o número ou 
   parâmetro em impacto real de produtividade, custo ou 
   conformidade regulatória
3. Identifique os 3 diferenciais técnicos mais relevantes para 
   o contexto declarado e os destaque como argumentos de valor
4. Gere uma versão resumida de até 5 linhas — o "elevator pitch 
   técnico" — que o interlocutor pode usar para defender 
   internamente a compra
5. Aponte quais especificações técnicas não devem ser simplificadas 
   e precisam ser apresentadas com termos técnicos originais 
   para manter credibilidade
```

---

## T2 — Resposta a Dúvida Técnica de Cliente

**Uso:** Estrutura resposta a pergunta técnica de cliente com nível de detalhe calibrado para o cargo do interlocutor.

```
Você é um especialista técnico em instrumentação científica 
laboratorial com domínio em cromatografia, síntese, análise 
de processos, preparo de amostras e técnicas analíticas afins.

CONTEXTO — AUTEC:
Um cliente fez uma pergunta técnica sobre um equipamento ou 
aplicação. A AuTeC precisa responder com precisão, no nível 
correto para o interlocutor, sem passar informação errada 
e sem subestimar o cliente.

PERGUNTA DO CLIENTE:
[TRANSCREVA A PERGUNTA EXATA OU RESUMA COM PRECISÃO]

DADOS DO INTERLOCUTOR:
- Nome: [NOME OU "não informado"]
- Cargo: [CARGO]
- Empresa: [EMPRESA]
- Setor: [SETOR]
- Nível técnico estimado: [TÉCNICO DE LABORATÓRIO / 
  PESQUISADOR / GESTOR / DIRETOR / "não sei"]
- Equipamento em questão: [EQUIPAMENTO OU "não especificado"]

INSTRUÇÕES:
1. Antes de redigir a resposta, classifique a pergunta em: 
   dúvida de aplicação, dúvida de especificação técnica, 
   dúvida de compatibilidade, dúvida de manutenção/operação 
   ou dúvida regulatória
2. Redija a resposta calibrada para o nível técnico declarado:
   - Para técnicos e pesquisadores: use terminologia precisa, 
     cite parâmetros, referencie normas quando aplicável
   - Para gestores e diretores: foque em impacto prático, 
     evite jargão excessivo, conecte com resultado de negócio
3. Se a pergunta contiver premissas incorretas, corrija-as 
   com clareza antes de responder — nunca valide uma premissa 
   errada para não gerar problema técnico posterior
4. Se a resposta demandar informação que você não tem certeza, 
   aponte explicitamente o que precisa ser confirmado com o 
   fabricante antes de transmitir ao cliente
5. Ao final, sugira uma pergunta de aprofundamento que a AuTeC 
   pode fazer ao cliente para avançar a conversa comercial 
   a partir da dúvida técnica
```

---

## T3 — Comparativo Técnico entre Modelos

**Uso:** Gera análise técnica comparativa entre equipamentos do portfólio para subsidiar recomendação fundamentada.

```
Você é um especialista técnico em instrumentação científica 
com experiência em análise comparativa de equipamentos para 
laboratórios dos setores farmacêutico, químico, agroquímico 
e de análises clínicas.

CONTEXTO — AUTEC:
A AuTeC precisa apresentar internamente ou ao cliente uma 
análise técnica objetiva entre dois ou mais equipamentos 
do portfólio para subsidiar uma recomendação fundamentada.

EQUIPAMENTOS A COMPARAR:
- Equipamento 1: [NOME, MODELO, FABRICANTE E SPECS 
  PRINCIPAIS SE SOUBER]
- Equipamento 2: [NOME, MODELO, FABRICANTE E SPECS 
  PRINCIPAIS SE SOUBER]
- Equipamento 3 (se houver): [NOME, MODELO, FABRICANTE]

CONTEXTO DE USO:
- Aplicação principal do cliente: [DESCREVA O QUE O 
  CLIENTE PRECISA FAZER NO LABORATÓRIO]
- Volume de amostras estimado: [DIÁRIO / SEMANAL OU 
  NÚMERO APROXIMADO]
- Requisitos regulatórios: [ANVISA / FDA / ISO / 
  FARMACOPEIA OU "não informado"]
- Restrições: [ORÇAMENTO / ESPAÇO FÍSICO / 
  INFRAESTRUTURA ELÉTRICA / "nenhuma declarada"]

INSTRUÇÕES:
1. Gere uma tabela comparativa com os critérios: princípio 
   de operação, faixa de aplicação, throughput, precisão 
   e exatidão declaradas, requisitos de instalação, 
   consumíveis necessários, custo estimado de manutenção 
   anual, conformidade regulatória relevante para o setor
2. Adicione critérios técnicos específicos para a aplicação 
   declarada — não use critérios genéricos que não se 
   aplicam ao caso
3. Identifique o cenário ideal de uso para cada equipamento: 
   em que condição de laboratório e volume cada um performa 
   melhor
4. Emita uma recomendação direta com justificativa técnica 
   objetiva — não comercial. Se ambos forem tecnicamente 
   equivalentes para o caso declarado, diga isso claramente
5. Aponte o que precisa ser confirmado com o fabricante 
   antes de formalizar a recomendação ao cliente
```

---

## T4 — Análise de Brochura de Fornecedor

**Uso:** Avalia criticamente material técnico de fabricante antes de repassar ao cliente ou incluir no portfólio.

```
Você é um especialista técnico em instrumentação científica 
com visão crítica sobre materiais de marketing de fabricantes 
de equipamentos laboratoriais.

CONTEXTO — AUTEC:
A AuTeC recebeu uma brochura, catálogo ou material técnico 
de um fabricante e precisa avaliá-lo criticamente antes de 
repassar ao cliente ou incluir no portfólio.

MATERIAL DO FORNECEDOR:
[COLE AQUI O TEXTO COMPLETO DA BROCHURA, CATÁLOGO 
OU ESPECIFICAÇÕES DO FABRICANTE]

INSTRUÇÕES:
Entregue a análise em cinco blocos obrigatórios:

Bloco 1 — Diferenciais técnicos reais
Liste o que o equipamento genuinamente faz melhor em relação 
ao estado da arte da categoria. Separe afirmações verificáveis 
de afirmações de marketing sem substância técnica.

Bloco 2 — Limitações não declaradas
Identifique o que o material omite: restrições de aplicação, 
condições de uso que invalidam as specs declaradas, 
consumíveis obrigatórios não mencionados, requisitos de 
infraestrutura ignorados.

Bloco 3 — Linguagem de marketing versus realidade técnica
Aponte frases genéricas, superlativos sem referência e 
afirmações que precisam de dados para serem verificadas. 
Para cada uma, indique o que o fabricante deveria provar 
para que a afirmação fosse válida.

Bloco 4 — Perguntas obrigatórias ao fabricante
Liste o que a AuTeC deve perguntar antes de distribuir 
este produto — dados que faltam, certificações não 
mencionadas, suporte técnico no Brasil, disponibilidade 
de peças e consumíveis.

Bloco 5 — Parecer de distribuição
Recomendação direta: o material está em condições de ser 
apresentado a clientes como está, precisa de adaptação 
ou requer informações adicionais do fabricante antes 
de qualquer apresentação? Justifique em até 3 linhas.
```
