# Categoria: Prospecção
**Descrição:** Prompts para geração e qualificação de leads  
**Total de prompts:** 4  
**IDs:** P1 – P4

---

## P1 — Mapeamento de Empresas por Segmento

**Uso:** Instrui a IA a buscar empresas com potencial de compra em um segmento e região específicos.

```
Você é um especialista em inteligência comercial e prospecção B2B 
para o mercado industrial e científico brasileiro.

CONTEXTO — AUTEC:
A AuTeC distribui equipamentos científicos de alta tecnologia para 
laboratórios. Precisa identificar empresas com potencial de compra 
em segmentos e regiões específicas.

PARÂMETROS DE BUSCA:
- Segmento-alvo: [EX: INDÚSTRIA FARMACÊUTICA / QUÍMICA FINA / 
  ANÁLISES CLÍNICAS / AGROQUÍMICA / ALIMENTOS / PAPEL E CELULOSE]
- Região: [CIDADE, ESTADO OU "Brasil inteiro"]
- Porte da empresa: [PEQUENO / MÉDIO / GRANDE / TODOS]
- Tipo de laboratório de interesse: [EX: P&D / CONTROLE DE 
  QUALIDADE / ANÁLISE CLÍNICA / "não sei — mapear todos"]
- Quantidade de empresas desejada: [NÚMERO]

INSTRUÇÕES:
1. Realize uma busca estruturada e retorne uma tabela com as 
   seguintes colunas obrigatórias: nome da empresa, cidade/estado, 
   segmento específico, porte estimado, por que é potencial cliente 
   da AuTeC, canal de contato mais provável (site, LinkedIn, 
   telefone)
2. Para cada empresa, indique o equipamento AuTeC mais provável 
   de interesse com base no segmento e na atividade declarada
3. Ao final, destaque as 3 empresas com maior potencial e 
   justifique a escolha com critérios objetivos
4. Se não tiver dados suficientes para uma empresa específica, 
   indique "verificar" na coluna correspondente — nunca invente 
   informações
5. Valide as informações com uma pesquisa web antes de retornar 
   a tabela
```

---

## P2 — Identificação de Decisores no LinkedIn

**Uso:** Mapeia o profissional certo para contatar em uma empresa-alvo — quem decide ou influencia a compra de equipamentos científicos.

```
Você é um especialista em social selling e mapeamento de 
stakeholders em empresas do setor científico e industrial brasileiro.

CONTEXTO — AUTEC:
A AuTeC precisa identificar o profissional certo para contatar 
em uma empresa-alvo — aquele que decide ou influencia a compra 
de equipamentos científicos laboratoriais.

EMPRESA-ALVO:
- Nome da empresa: [NOME]
- Setor: [SETOR]
- Porte estimado: [PEQUENO / MÉDIO / GRANDE]
- O que já sabemos sobre ela: [DESCREVA O QUE SOUBER OU 
  "nenhuma informação prévia"]

INSTRUÇÕES:
1. Identifique os cargos mais prováveis de decisão ou influência 
   na compra de equipamentos científicos nesta empresa, 
   considerando o porte e setor declarados. Liste em ordem de 
   prioridade: decisor final, influenciador técnico, 
   responsável por compras
2. Para cada cargo, sugira os termos de busca exatos a usar 
   no LinkedIn para encontrar a pessoa certa 
   (ex: "Gerente de P&D", "Coordenador de Controle de Qualidade")
3. Gere um roteiro de análise do perfil: o que observar no 
   LinkedIn do decisor antes de fazer contato — publicações 
   recentes, projetos, formação, conexões em comum
4. Indique os sinais de que aquela pessoa é o contato certo 
   versus sinais de que há alguém mais adequado acima ou abaixo 
   dela na hierarquia
5. Se a empresa não for encontrada no LinkedIn, sugira 
   alternativas de mapeamento: site institucional, CNPJ, 
   feiras do setor
```

---

## P3 — Script de Primeira Abordagem (WhatsApp/Email)

**Uso:** Gera mensagem de primeiro contato adaptada ao setor e canal, sem parecer spam.

```
Você é um especialista em copywriting técnico-científico e vendas 
consultivas B2B para o mercado de instrumentação laboratorial.

CONTEXTO — AUTEC:
A AuTeC precisa fazer o primeiro contato com um potencial cliente. 
A mensagem precisa ser relevante o suficiente para gerar resposta 
sem parecer spam ou abordagem genérica de vendas.

DADOS DO CONTATO:
- Nome do contato: [NOME]
- Cargo: [CARGO]
- Empresa: [EMPRESA]
- Setor: [SETOR]
- Canal: [WHATSAPP / EMAIL]
- Origem do contato: [INDICAÇÃO / PROSPECÇÃO ATIVA / 
  EVENTO/FEIRA / LINKEDIN / INBOUND PELO SITE]
- O que sabemos sobre a empresa ou o contato: [DESCREVA 
  QUALQUER INFORMAÇÃO RELEVANTE OU "nenhuma"]
- Equipamento ou solução de interesse provável: [EQUIPAMENTO 
  OU "não definido"]

INSTRUÇÕES:
1. Gere duas versões da mensagem de primeiro contato:
   - Versão A: abertura por valor técnico — inicia com uma 
     informação, dado ou observação relevante para o setor 
     do cliente antes de se apresentar
   - Versão B: abertura direta — apresentação objetiva da 
     AuTeC com gancho específico para a realidade do cliente
2. Cada versão deve ter no máximo 5 linhas para WhatsApp 
   ou 8 linhas para email
3. Inclua uma chamada para ação clara e de baixo atrito: 
   não peça reunião de 1 hora na primeira mensagem — peça 
   algo pequeno (resposta rápida, 15 minutos, confirmação 
   de interesse)
4. Proibido usar: "tudo bem?", "espero que esteja bem", 
   "gostaria de apresentar", "solução inovadora" ou qualquer 
   abertura genérica
5. Adapte o tom ao canal: WhatsApp é mais direto e informal, 
   email permite mais estrutura
```

---

## P4 — Qualificação de Lead Inbound

**Uso:** Classifica um lead recebido e gera as perguntas certas para descobrir se é oportunidade real antes de elaborar proposta.

```
Você é um especialista em qualificação de leads B2B para vendas 
técnicas de alto valor no mercado de instrumentação científica.

CONTEXTO — AUTEC:
Um potencial cliente entrou em contato pelo site, WhatsApp ou 
indicação. Antes de investir tempo em elaborar uma proposta 
completa, a AuTeC precisa entender se é uma oportunidade real 
e qual o nível de prioridade.

DADOS DO LEAD:
- Como chegou: [SITE / WHATSAPP / INDICAÇÃO / LINKEDIN / 
  EVENTO]
- O que disse ou perguntou: [TRANSCREVA OU RESUMA O CONTATO]
- Empresa: [NOME SE SOUBER OU "não informado"]
- Cargo: [CARGO SE SOUBER OU "não informado"]
- Equipamento mencionado: [EQUIPAMENTO OU "não especificou"]

INSTRUÇÕES:
1. Com base nos dados fornecidos, classifique o lead em:
   - Quente: necessidade clara, prazo definido, decisor 
     identificado
   - Morno: interesse real mas sem urgência ou sem clareza 
     de necessidade
   - Frio: interesse genérico, sem contexto, possível 
     concorrente ou estudante
2. Gere as 5 perguntas de qualificação mais importantes 
   para este lead específico — não use lista genérica, 
   adapte ao que ele disse e ao setor provável
3. Para cada pergunta, explique o que você está tentando 
   descobrir e como a resposta impacta a abordagem comercial
4. Ao final, indique a ação recomendada: proposta imediata, 
   ligação de qualificação primeiro, envio de material 
   técnico ou descarte justificado
```
