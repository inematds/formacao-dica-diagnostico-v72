# REVISÃO — DICA 1 · Diagnóstico: o Mapa do Cliente (v7.2)

- **Revisor:** revisor independente (não é o autor do curso)
- **Data:** 19/10/2026
- **O que foi lido:** `conteudo/pt/curso.json` e `conteudo/pt/aulas/01..08-*.json` (todos os campos); `ATUALIZACAO.md` e `PLANO.md`; `BRIEF-CURSO.md`, `CURRICULO.md` e `AUDITORIA-LOCAL.md` do longrun; fonte antiga `mapacliente/curso/trilha3/modulo-3-1`, `3-2` e `3-4` (conferência do que foi mantido).
- **Conferência externa:** Resolução CD/ANPD nº 2/2022, página da ANPD (gov.br), consultada em 19/10/2026: art. 4º (alto risco = **1 critério geral E 1 específico, cumulativamente**), art. 9º (registro simplificado), art. 14 (prazo em dobro), art. 16 (ANPD pode exigir o dispensado), art. 5º e art. 8º (que remetem ao art. 3º, exclusão de quem faz tratamento de alto risco). Datas do WhatsApp (01/07/2025 e 15/01/2026) conferidas contra as fontes F1–F4 do ATUALIZACAO.md.
- Nenhum arquivo do curso foi alterado além deste.

---

## 1. Fidelidade à fonte atualizada — 8/10

**O que está bom**
- O que é do mapacliente veio certo. As 15 perguntas da aula 2 batem com o módulo 3.1, na mesma ordem e nos mesmos 5 blocos. As adaptações são boas: a P5 ganhou "quantas mensagens chegam num dia normal?" e a P11 trocou "10 horas" por "algumas horas". Na aula 3, as 5 áreas, as 3 perguntas por área e os critérios de dor batem com o 3.2 ("3 = cita exemplo recente e quantifica prejuízo"). Na aula 6, os 6 eixos, a fórmula e os 4 quadrantes batem com o 3.4.
- WhatsApp com data e fonte, nas aulas 7 e 1:
  - cobrança "por mensagem entregue" desde 01/07/2025;
  - janela de 24 h e opt-in;
  - "Desde 15/01/2026 os termos da API proíbem chatbot de IA de uso geral… IA de atendimento, agendamento, pedido e venda do próprio negócio continua permitida. Quem decide o que é 'principal' é a Meta."
  
  Está correto e bem dito. O quiz 7·Q3 cobra justamente a diferença entre os dois casos.
- LGPD: aparece o art. 5º, II (dado de saúde é sensível) na aula 2 (aba "Por que tanto cuidado com a gravação") e na aula 7. O art. 11 (consentimento específico e destacado) e o art. 20 (revisão humana) estão na aula 7, e o modelo do checklist tem uma linha para revisão humana.
- O "prompt em 6 blocos" virou o arquivo de regras com dono, data e versão, apontando para o pacote de contexto (aula 5). O convênio real (Bradesco) saiu do texto.

**O que falta**
- **ANPD (aula 7, passo "Pequeno porte") está incompleto num ponto que muda a conclusão.** O texto diz que "o art. 4º lista critérios de alto risco, entre eles tecnologia nova e dado sensível; a ANPD pode exigir mais conforme o risco (art. 16)". Faltam duas coisas:
  - o art. 4º exige **um critério geral (larga escala ou afetar significativamente direitos) e um específico, ao mesmo tempo**;
  - quem faz tratamento de alto risco **não se beneficia** do regime simplificado (art. 3º; o art. 8º diz "inclusive àqueles que realizem tratamento de alto risco", o que confirma a exclusão).
  
  Do jeito que está, o dono lê "tenho regime simplificado; no máximo a ANPD pede mais". O correto é: "se cair em alto risco, as simplificações podem não valer". Ver o grave G1.
- **Canal não oficial (aula 7, exemplo "Canal oficial ou não").** A frase "pode ter o número bloqueado e **fica fora das regras acima**" dá margem a ler que a via não oficial escapa da cobrança e da proibição, como se fosse vantagem. Na verdade, ela viola os termos do WhatsApp e não tem garantia nenhuma. Ver o grave G2.
- Aula 6: o eixo "Venda" da fonte ("cliente quer pagar por isso? 'tá legal' × 'preciso resolver'") virou "vontade do dono" sem registro no ATUALIZACAO.md. A troca é boa, mas precisa ser registrada.
- Aula 7, passo "WhatsApp: custo": "conversas de atendimento iniciadas pelo cliente seguem regras próprias de gratuidade" ficou vago. A F2 permite ser preciso: mensagens de serviço dentro da janela de 24 h são gratuitas desde 01/11/2024, segundo a Meta.

## 2. Número com fonte — 9/10

- Nenhum número da lista da AUDITORIA §a aparece. Procurei por `%`, `R$`, "reais", 70/90/95/80/60/50, faixas de preço e parcelas: só aparecem em frases que **proíbem** R$, como "Nenhuma nota de impacto está em reais" (aula 6) e "Valor em reais no diagnóstico: preço e proposta seguem a Vendas com IA" (aula 8).
- Os números que aparecem são estruturais: 15 perguntas, 20 min, escala 0–3, 3 casos, 10 min de devolutiva, 4 semanas. Ou são exemplos rotulados: "apago o áudio em 30 dias" na fala simulada; "cirurgia nos últimos 6 meses" na R02 fictícia. "Regra do 3" e "ele fala a maior parte do tempo" estão marcados como **"Regra prática do consultor"**, como pede o brief.
- O caso de "quando ele não sabe o número" (combinar uma contagem de uma semana) é o melhor acréscimo do curso. Ele aparece de forma coerente na aula 2, na simconversa, no quiz 2·Q3, no checklist da aula 8 ("Nenhum número sem origem") e no plano de 30 dias (linha de base na semana 1).
- Nenhuma promessa de renda. Nenhuma API não oficial recomendada. Nenhum nome de modelo ou de ferramenta como recomendação: Otter, Fireflies, n8n, Z-API, Evolution, Claude e ChatGPT dão zero ocorrências.
- O ponto que tira nota: a frase do canal não oficial (G2) é a única brecha nesse critério.

## 3. Tom de dono — 9/10

- Frases curtas e exemplos de balcão: "às vezes um sobrinho" (aula 1), "um papel na recepção, uma marca por mensagem perdida" (aula 2), "Você diria essa frase no balcão da padaria?" (aula 8). A tabela "tradução para o dono" da aula 8 é ótima.
- O jargão é quase todo explicado: "conhecimento tácito" (aula 4, legenda), SE/ENTÃO com exemplo (aula 5), níveis 1–3 (aula 7).
- Termos que ainda escapam sem explicação:
  - "linha de base" (aula 2, comentário da simconversa; aula 8, plano);
  - "escopo" (aulas 7 e 8);
  - "mapa de 12 meses" (aula 3, "dor sem urgência entra no mapa de 12 meses"), um conceito do curso 2 que aparece aqui sem explicação nem link;
  - "provedor oficial" (aula 7).

## 4. Prática verificável — 8/10

- Todo exercício termina em "pronto quando", e a maioria dá para o aluno conferir sozinho:
  - aula 3 E1: "as 5 áreas com nota 0–3… e o critério de cada nota escrito ao lado";
  - aula 5 E3: "uma busca por nome ou telefone não acha nada";
  - aula 7 E2: duas fontes com a data de hoje;
  - aula 8 E2: "a pessoa que ouviu consegue dizer, com as palavras dela, o que você recomendou".
- Todos os modelos estão em blocos `codigo`, com botão de copiar e placeholders `< >`. Cada aula tem "Como conferir" e "Erros comuns".
- Pontos fracos:
  - **Aula 6, os 6 eixos não têm critério por nota.** A aula 3 insiste em "critério antes da nota", mas na aula 6 a única orientação é "Impacto (horas por semana ou clientes perdidos…), facilidade (dado pronto…)", sem âncora de 0 e de 3. A fonte (3.4) tinha uma tabela com pergunta-guia e "nota baixa / nota alta". Sem isso, o E1 da aula 6 só confere se a matriz está preenchida, não se as notas têm critério.
  - **Aula 5, E2, validação circular.** Com empresa fictícia, o aluno escreve a regra, inventa os 3 casos novos e decide se "o dono faria igual". O "pronto quando" ("resultado madura") passa sempre. Falta exigir pelo menos 1 caso de borda feito para quebrar a regra, ou a ajuda de outra pessoa no papel da dona.
  - Aula 8, `mapa`: "10 exercícios" conta só as aulas 2, 3, 5 e 6. Os degraus "Regras" e "Recomendação" citam "aulas 4 e 5" e "aulas 6 e 7", mas apontam para uma aula só, então os exercícios das aulas 4 e 7 ficam fora do mapa.
  - Aula 7, o exemplo preenchido não tem a linha "Base para tratar". O modelo pede essa linha e o "Como conferir" exige "quem confirma a base para tratar". O exemplo deveria mostrar.

## 5. Sem repetir irmão — 9/10

- O curso respeita a tabela "dono de cada assunto":
  - aula 2: a legenda diz "Esta é a entrevista de entrega. A call que vende o diagnóstico é outra", com link para a Vendas com IA 2 · call-descoberta;
  - aula 6: a devolutiva termina em "próximo passo", e "Fechar a devolutiva com contrato" aparece em Erros comuns;
  - aula 8: "Escopo sem preço: preço é conversa da Vendas com IA", com link para a Vendas com IA 4;
  - "O que ficou na Vendas com IA" aparece no início, e os 4 papéis ficam em link (aula 1);
  - valor × viabilidade fica em link para o prof2030-consultor a3 (aula 6); pacote de contexto, para a gestao-ia-recursos a3 (aulas 4 e 5); processo a fundo, para a gestao-ia-processos (aula 3); LGPD, para o prof2030-auditor a6 e o prof2030-base a5.
- Vazamento leve para o curso 2, no plano de 30 dias da aula 8: "Semana 2: assistente montado em teste, conferido contra 15 casos escritos" e "Semana 4: recepção e dona treinadas". É conteúdo do DICA 2 (a4 e a5) sem aviso de que é lá. Basta um "(curso 2)".

## Conferências pedidas

- **Vila Serena e Ponto Firme rotuladas como fictícias:** sim. Toda aparição tem "(fictícia)" na própria linha ou no rótulo do bloco ("Exemplo preenchido (fictício)", "Comparação (fictícia)"), ou o subtítulo da seção avisa ("A Clínica Vila Serena é fictícia…", "Use a Vila Serena (fictícia)…"). A aula 8 E1 pede "Marque no topo que a empresa é fictícia". OK.
- **Simconversa (aula 2):**
  - O roteiro é coerente: "uns quarenta minutos, às três chega paciente" combina com "Já são quase três horas".
  - O caso da paciente das sete da noite leva a "respondo de noite, quando lembro", que vira a contagem depois das 18 h e depois o plano da aula 8.
  - Notas 0/1/2 bem graduadas, com comentário para cada opção. O caminho máximo dá 12 pontos (abre, dor, caso, silêncio, número, encerra).
  - Os 4 fins são distintos e didáticos: receita antes do exame, número de palpite, sem próximo passo, diagnóstico com chão.
  - Dois deslizes pequenos:
    - quem responde "Quantas vezes isso acontece por semana?" (no nó `caso`) cai em `numero`, que abre com "Já pus mensagem automática de ausência…", resposta a uma pergunta ("já tentou?") que não foi feita;
    - "Vou colocar 'muitas mensagens perdidas'" (nota 0) segue para `encerra` normalmente, enquanto o palpite numérico vai para um fim ruim. É coerente pela nota, mas o comentário poderia dizer que a conversa segue, só que sem número.
- **Quizzes:** 3 a 4 perguntas por aula, a certa em posições variadas (0 a 3 em todas as aulas), com explicação defensável e coerente com o texto. Opções erradas longas foram usadas de propósito para não entregar a resposta pelo tamanho. Algumas erradas são implausíveis demais e não ensinam nada:
  - "Porque é a pergunta mais curta do roteiro" (2·Q1);
  - "O que o dono achar mais bonito" (6·Q1);
  - "Porque a fórmula fica mais curta" (6·Q3);
  - "Quando fizer sentido" (5·Q1).
- **LGPD onde há dado pessoal:**
  - gravação (aula 2): consentimento com finalidade, ferramenta, local, prazo e pedido de não citar paciente, mais o link para o Data guard;
  - conversas reais (aula 4): "não copie nome, telefone nem dado de saúde";
  - arquivo de regras (aula 5): "Não guarde aqui nome, telefone ou dado de saúde";
  - canal e dado (aula 7): checklist completo.
  
  Boa cobertura. Inconsistência leve na aula 4: o mesmo passo sugere registrar "uma paciente de 50 anos, com dor lombar" e, logo depois, proíbe "dado de saúde" no arquivo (o quiz 4·Q3 também). Ver menor M5.

---

## Problemas graves (bloqueiam publicação)

**G1 · Aula 7, passo "Pequeno porte": regime simplificado da ANPD descrito pela metade.**
Correção proposta para o `texto[1]`: "Mas o regime simplificado não vale para quem faz tratamento de **alto risco** (art. 3º). Pelo art. 4º, alto risco é ter, ao mesmo tempo, um critério geral (larga escala ou afetar de forma significativa os direitos das pessoas) e um específico (entre eles, tecnologia nova ou inovadora e dado sensível). IA lendo mensagem de paciente pode cair aí: confira com um especialista antes de contar com as simplificações." Ajustar também o resumo ("pequeno porte tem regras simplificadas, mas…") e registrar o art. 3º na F7 do ATUALIZACAO.md.

**G2 · Aula 7, exemplo "Canal oficial ou não": "fica fora das regras acima".**
Trocar por: "Ferramenta que conecta ao WhatsApp sem ser a API oficial da Meta (ou um provedor oficial dela) **viola os termos do WhatsApp**: o número pode ser bloqueado a qualquer momento, sem aviso nem recurso. Não recomende. No diagnóstico, marque o canal como oficial ou não oficial e escreva o risco."

## Problemas menores (sugestões)

1. **Aula 6, 6 eixos sem critério por nota.** Incluir um bloco (passos ou tabela) com a pergunta-guia e as âncoras 0 e 3 de cada eixo, adaptadas da fonte 3.4 e **sem R$**. Exemplo para impacto: "0 = o dono não sente na semana; 3 = horas ou clientes perdidos contados por ele". Pôr no "pronto quando" do E1: "cada nota com critério de 1 linha".
2. **Aula 5, E2, validação circular.** Exigir que, dos 3 casos novos de cada regra, pelo menos 1 seja de borda (feito para quebrar a regra), ou que outra pessoa faça o papel da dona. "Pronto quando": "…e pelo menos 1 regra precisou de ajuste, ou o caso de borda está registrado como 'bate'".
3. **Aula 2, consentimento: "Quem ouve: só eu" contradiz "Ferramenta: … vai transformar o áudio em texto".** Trocar por "Quem tem acesso: eu e a ferramenta de transcrição <nome>, que <guarda / não guarda> o áudio".
4. **Aula 7, exemplo da Vila Serena sem "Base para tratar".** Acrescentar algo como "Base: a confirmar com especialista; candidatas: consentimento destacado no primeiro contato ou tutela da saúde (LGPD art. 11, II, f)". Assim o exemplo bate com o modelo e com o "Como conferir".
5. **Aula 4, "uma paciente de 50 anos, com dor lombar" contra "não copie dado de saúde" e quiz 4·Q3.** Deixar claro que o proibido é o dado de saúde **ligado a quem é a pessoa** (nome, telefone, foto). Ou trocar o exemplo por "uma paciente nova, com dor nas costas", e ajustar a explicação do quiz.
6. **Aula 8, plano de 30 dias com trechos do curso 2.** Marcar "(curso 2)" em "15 casos escritos" e "treinadas", ou linkar o DICA 2.
7. **Aula 8, `mapa` "10 exercícios" ignora as aulas 4 e 7.** Acrescentar degraus para essas aulas, ou ajustar o total e o texto dos degraus.
8. **Jargão sem explicação:** "linha de base" (aulas 2 e 8), "escopo" (aulas 7 e 8), "mapa de 12 meses" (aula 3), "provedor oficial" (aula 7). Uma explicação curta na primeira aparição de cada.
9. **Aula 7, gratuidade do atendimento vaga.** Trocar por "mensagens de serviço, respondidas dentro de 24 h depois que o cliente escreve, são gratuitas desde 01/11/2024 (Meta, página de preços)".
10. **Simconversa, nó `numero`.** A fala de abertura responde "já tentou?" mesmo quando o aluno perguntou "quantas vezes por semana?". Criar um nó separado ou neutralizar a fala ("Número eu não sei: ninguém conta…" primeiro; "já pus mensagem automática" só no caminho do "já tentou").
11. **Quizzes, erradas fracas.** Trocar por erros que o aluno comete de verdade:
    - 2·Q1: "Porque é a pergunta mais curta" → "Porque o medo é resolvido pela demonstração do assistente";
    - 6·Q1: "O que o dono achar mais bonito" → "O de maior impacto, mesmo difícil";
    - 6·Q3: "a fórmula fica mais curta" → "porque são notas dadas pelo dono e não pelo consultor".
12. **Aula 2, passos "Os 5 blocos de perguntas" com 4 itens** (blocos fundidos e um item "dor real ou falsa"). Renomear para "Os blocos de perguntas e o teste da dor", para não confundir com o diagrama.
13. **ATUALIZACAO.md:** registrar a troca do eixo "Venda" por "Vontade do dono" (aula 6) e o art. 3º da Res. 2/2022.

---

## Amostra EN/ES

pendente: tradução em andamento

---

Leitura final: curso sólido, fiel ao miolo do mapacliente, limpo de números sem fonte e com a LGPD e o WhatsApp atualizados. G1 e G2 são correções de uma ou duas frases na aula 7 e precisam entrar antes de publicar. Corrigidos os dois e o menor 1, a nota sobe para 9.

Nota PT: 8/10
