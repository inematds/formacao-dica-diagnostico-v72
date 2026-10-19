# ATUALIZACAO — DICA 1 · Diagnóstico (o que muda em relação ao mapacliente)

Conferência feita em **19/10/2026**, antes de escrever o conteúdo, como pede a regra do Nei. Fonte antiga: `~/projetos/mapacliente` (commit `8fad8f5`, intacto), módulos 1.1, 2.3 e 3.1–3.5. Pesquisa externa só em páginas públicas (Meta, ANPD, Planalto e reportagens com data). Nenhuma API de modelo.

## Fontes externas consultadas (19/10/2026)

| # | Fato | URL | O que a página diz |
|---|---|---|---|
| F1 | Cobrança do WhatsApp Business por mensagem | https://developers.facebook.com/docs/whatsapp/pricing (atualizada pela Meta em 30/09/2026) | "Los precios basados en conversaciones quedaron obsoletos. Los reemplazaron con los precios por mensaje el 1 de julio de 2025." Cobra por mensagem entregue; tarifa varia por mercado e categoria (marketing, utilidade, autenticação, serviço). |
| F2 | Janela de atendimento de 24 h e opt-in | mesma URL (seção "Intervalo de servicio de atención al cliente") | Mensagem livre só dentro de 24 h depois que o cliente escreve; fora disso, só modelo aprovado. "Solo puedes enviar mensajes a los usuarios de WhatsApp que aceptaron recibir tus mensajes." Conversas de serviço gratuitas desde 01/11/2024. |
| F3 | Chatbot de IA de uso geral proibido na API a partir de 15/01/2026 | https://respond.io/blog/whatsapp-general-purpose-chatbots-ban | Proibido: assistente aberto tipo ChatGPT como função principal. Permitido: bots para atendimento, agendamento, pedidos, avisos e vendas do próprio negócio. Novos usuários já sob a regra desde 15/10/2025. |
| F4 | Mesma regra, reportagem com data e trecho dos termos | https://9to5mac.com/2025/10/20/whatsapp-bans-ai-chatbots-from-using-its-business-api/ (20/10/2025) | Cita os termos: proibido "when such technologies are the primary (…) functionality"; "as determined by Meta in its sole discretion". Atendimento com IA dentro do fluxo do negócio não é afetado. |
| F5 | LGPD: dado de saúde é dado sensível; consentimento específico e destacado | https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm (art. 5º, II; art. 11, I) | "dado pessoal sensível: … dado referente à saúde …"; tratamento só "quando o titular … consentir, de forma específica e destacada, para finalidades específicas" ou nas hipóteses do inciso II. |
| F6 | LGPD: revisão humana de decisão automatizada | mesma URL (art. 20) | O titular pode pedir revisão de decisão tomada só com tratamento automatizado. |
| F7 | ANPD: regras para agente de pequeno porte | https://www.gov.br/anpd/pt-br/acesso-a-informacao/institucional/atos-normativos/regulamentacoes_anpd/resolucao-cd-anpd-no-2-de-27-de-janeiro-de-2022 (Resolução CD/ANPD nº 2/2022; página modificada em 16/09/2026) | Microempresa e EPP são "agentes de tratamento de pequeno porte" (art. 2º); registro de operações pode ser simplificado (art. 9º); prazo em dobro (art. 14). Alto risco = 1 critério geral (larga escala ou afetar direitos) + 1 específico, entre eles "tecnologias emergentes" e "dados pessoais sensíveis" (art. 4º). A ANPD pode exigir as obrigações dispensadas conforme o risco (art. 16). |

## Módulo a módulo

### 1.1 Por que PME, por que agora → aula 1
- **O módulo diz:** PME vive paradoxo de tempo; "estudos relatam abandono em até 70% dos casos em 90 dias"; janela de adoção de 2–3 anos; "milhões de PMEs, 0,001% é carteira"; "conta plausível" com ticket em R$.
- **O que mudou / sem fonte:** os 70%, a janela de 2–3 anos, o 0,001% e os tickets não têm estudo, data nem amostra. Venda e preço já são da Vendas com IA.
- **O que entra:** o retrato operacional do pequeno negócio (dono decide sozinho, sem TI, WhatsApp no centro, informação na cabeça do dono) como observação de campo do mapacliente, sem número; o método DICA dentro do papel Consultor do Profissional 2030 (https://eventos.inema.pro/prof2030/, 200 em 19/10/2026); "o que você não é" fica em link (prof2030-base a7).
- **Cortado:** 70%, 0,001%, "conta plausível", janela de 2–3 anos.

### 2.3 Explicar IA sem assustar → aula 8 (linguagem do relatório)
- **O módulo diz:** tabela jargão → língua do dono, analogias de gente, teste do avô, 5 limites, reset em 3 frases; "R$ 800/mês contra CLT de R$ 3–5 mil"; "~10% das respostas precisam de ajuste".
- **Sem fonte:** os R$ e os ~10%.
- **O que entra:** tabela de tradução, teste do avô e os limites ditos antes (sem percentual: "nas primeiras semanas uma parte das respostas vai precisar de ajuste, e é por isso que começa com aprovação").
- **Cortado:** comparação de custo com salário; ~10%.

### 3.1 Entrevista com o dono → aula 2
- **O módulo diz:** 20 min de preparação ("à frente de 90% dos consultores"), 15 perguntas em 5 blocos, fala 20/80, 3 segundos de silêncio ("70% das vezes ele continua"), dor real × falsa, gravação "95% dizem sim", ferramentas Otter.ai/Fireflies, devolutiva em 5–7 dias, "diagnóstico de R$ 500 × R$ 2.500".
- **O que mudou:** gravar e transcrever com IA é tratamento de dado pessoal; numa clínica, a conversa pode citar paciente e saúde, que é dado sensível (F5). O consentimento precisa dizer **para que** grava, **onde** fica, **se uma ferramenta de IA vai transcrever** e **quando apaga**. A entrevista aqui é a de **entrega** (diagnóstico já combinado); a call de venda é da Vendas com IA 2 · a2.
- **O que entra:** as 15 perguntas (mantidas); preparação de 20 min; 20/80 e 3 segundos como **regra prática do consultor**; teste das 3 perguntas para dor falsa; script de consentimento novo com finalidade, ferramenta, prazo de apagar e "não diga nome de paciente"; link para prof2030-auditor a6 (Data guard) e prof2030-base a5.
- **Cortado:** 90%, 70%, 95%, R$ 500/2.500, nomes de ferramenta de transcrição.

### 3.2 Mapeamento das 5 áreas → aula 3
- **O módulo diz:** 3 perguntas por área, sintomas, assistente sugerido; matriz dor × urgência × prontidão 0–3; "conversão cai 60%", "50% dos fechamentos após 5+ contatos", "economiza 2h/dia", "triplicou", "responde 90% das dúvidas".
- **Sem fonte:** todos os números dos exemplos.
- **O que entra:** as 5 áreas, as 3 perguntas e os sintomas (mantidos); matriz 0–3 com **critério escrito para cada nota** (novo); exemplos da clínica e da imobiliária como fictícios e sem número de resultado; financeiro sempre com aprovação humana (mantido).
- **Cortado:** 60%, 50%, 2h/dia, "triplicou", 90%.

### 3.3 Conhecimento implícito → aulas 4 e 5
- **O módulo diz:** "dono opera 80% no automático", "me conta um caso recente", regra do 3 ("3 casos é padrão, 5 é regra"), template de caso de 6 campos, SE/ENTÃO, validar com 3 casos novos, "estrutura ideal de prompt" em 6 blocos, "50% das vezes ele ajusta".
- **O que mudou:** o "prompt em 6 blocos" envelheceu como peça isolada; hoje o lugar das regras é o **pacote de contexto da empresa**, com dono e data (gestao-ia-recursos-v72 a3, https://inematds.github.io/gestao-ia-recursos-v72/, 200 em 19/10/2026). O exemplo "convênio Bradesco não cobre cirurgia" cita operadora real: vira convênio fictício.
- **O que entra:** caso recente, regra do 3 como regra prática, template de caso, SE/ENTÃO, validação com 3 casos novos, arquivo de regras com dono, data e versão.
- **Cortado:** 80%, 50%, nome de operadora real, "few-shot" como jargão sem explicação.

### 3.4 Mapa de oportunidades → aulas 6 e 7
- **O módulo diz:** 6 eixos 0–3 ("cobrem 95% das decisões"), score = (impacto + facilidade + urgência + venda) − (risco + dependência humana), 4 quadrantes, 3 níveis de automação, "bot resolve 80%, escala 20%", impacto "< R$ 1k/mês > R$ 5k/mês", "não recomendar" e devolutiva de 10 min que termina em "posso mandar contrato?".
- **O que mudou:** o conceito-dono de priorização é valor × viabilidade + "quando não usar IA" (prof2030-consultor a3, https://inematds.github.io/prof2030-consultor/aulas/valor-viabilidade/, 200 em 19/10/2026). Os 6 eixos ficam como a versão de pequeno negócio, com a pergunta "precisa de IA mesmo?" antes de pontuar. Fechamento de contrato é da Vendas com IA.
- **O que entra:** 6 eixos com fórmula (mantida), impacto em horas da semana ou clientes perdidos **contados pelo próprio dono**, sem R$; 4 quadrantes; 1 recomendada + 1 "não precisa de IA"; 3 níveis de automação (aula 7); devolutiva termina em próximo passo, não em contrato.
- **Cortado:** 95%, 80/20, faixas em R$, "posso te mandar contrato".

### Risco e plataforma (novo) → aula 7
- **O módulo diz:** risco = eixo da matriz; nada de LGPD; WhatsApp tratado em outros módulos com API não oficial e custo fixo.
- **O que entra:** checklist antes de recomendar: nível de automação 1–3; que dado pessoal passa (F5: saúde = sensível); quem responde se errar (F6: revisão humana); canal oficial ou não (F1–F4): cobrança por mensagem desde **01/07/2025**, janela de 24 h e opt-in, chatbot de uso geral proibido desde **15/01/2026** (atendimento do próprio negócio continua permitido, e quem decide o que é "principal" é a Meta). Pequena empresa tem regras simplificadas da ANPD, mas IA + dado de saúde pode cair nos critérios de alto risco (F7, art. 4º) — dizer "confira com um especialista" e linkar prof2030-auditor a6.
- **Cortado:** qualquer recomendação de API não oficial (Z-API, Evolution); custo fixo de mensagem.

### 3.5 Relatório e plano de 30 dias → aula 8
- **O módulo diz:** 1 página em 5 blocos (situação, oportunidades, recomendação, plano 30 dias, investimento), linguagem de dono, plano S1–S4, investimento em faixas de R$, parcelas 30/30/40, call de 30 min, contrato, "90% dos conflitos vêm de escopo".
- **O que mudou:** preço e contrato saem (Vendas com IA 2 · a3, Vendas com IA 4 · a4). O piloto de 30 dias com critério de parar é do prof2030-consultor a5.
- **O que entra:** 1 página com 3 achados, 1 recomendação, "o que fica de fora", plano de 4 semanas com marco visível; checklist de linguagem; **escopo** (inclui / não inclui) sem valor; gerador do plano.
- **Cortado:** faixas de investimento, parcelas, 90%, roteiro de fechamento.

## Resumo para o retorno
- Atualizado: WhatsApp por mensagem desde 01/07/2025 (F1), janela de 24 h e opt-in (F2), chatbot de uso geral proibido desde 15/01/2026 (F3, F4), dado de saúde sensível e consentimento destacado (F5), revisão humana (F6), regras ANPD para pequeno porte e critério de alto risco (F7); "prompt em 6 blocos" → pacote de contexto com dono e data.
- Cortado por falta de fonte: 70% de abandono, 0,001%, 90%/70%/95% da entrevista, 60%/50%/2h/"triplicou"/90% das 5 áreas, 80% automático, 50% de ajuste, 95% dos 6 eixos, 80/20 do bot, ~10% de erro, todas as faixas em R$ e parcelas.
