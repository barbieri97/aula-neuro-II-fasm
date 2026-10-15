---
theme: slidev-theme-fasm
title: "Funções cognitivas I"
info: Atenção, velocidade de processamento, memória e linguagem — conceito,
  modelos, como falham e com que instrumentos brasileiros se avaliam; como ler um
  escore normatizado
date: "2027-02-16"
author: FASM · Neuropsicologia II
# Gera o PDF no build (via playwright-chromium) e liga o botão de download no deck.
download: true
exportFilename: aula-02-funcoes-cognitivas-i
themeConfig:
  lang: pt-BR
layout: lead
index: "02"
kicker: Neuropsicologia II · FASM
subtitle: Conceito e avaliação.
---

<!--
- Estrutura do encontro: 1 h 20 de exposição (atenção, velocidade, memória, linguagem), 30 min de intervalo, 40 min sobre escore normatizado, 30 min de exercício em dupla convertendo escores.
- **RAVLT** — *Rey Auditory Verbal Learning Test*, Teste de Aprendizagem Auditivo-Verbal de Rey.
- **TMT** — *Trail Making Test*, Teste de Trilhas.
- **NEUPSILIN** — Instrumento de Avaliação Neuropsicológica Breve.
-->

---
layout: agenda
kicker: Aula 02 · o caminho de hoje
title: Caminho da aula
items:
  - {
      topic: "Atenção e velocidade",
      desc: "a porta de entrada de toda a cognição"
    }
  - {
      topic: "Memória",
      desc: "sistemas, processos e o que cada teste mede"
    }
  - {
      topic: "Linguagem",
      desc: "compreender, nomear, produzir"
    }
  - {
      topic: "O escore normatizado",
      desc: "da nota bruta à classificação"
    }
---

<!--
- A aula 03 continua com funções executivas, praxias, gnosias, visuoconstrução e cognição social, e com a avaliação computadorizada.
- O critério de recorte é o da prova: conceito de cada função, como falha, um ou dois instrumentos de referência.
-->

---
layout: statement
title: Nenhum teste mede uma função <em>pura</em>.
---

<!--
- Copiar uma figura exige atenção, percepção visual, planejamento, motricidade. Lembrar uma história exige atenção, compreensão verbal, memória.
- Por isso a avaliação é sempre um perfil: a função se infere do padrão entre tarefas, não de um escore isolado.
-->

---
layout: section
index: "01"
kicker: Parte um
title: Atenção e velocidade
subtitle: A porta de entrada.
---

---
layout: define
kicker: A definição
term: Atenção
definition: Capacidade de <em>selecionar</em> a informação relevante, de
  <em>manter</em> o foco nela e de <em>distribuir</em> recursos entre tarefas.
points:
  - "Recurso limitado"
  - "Base de todas as outras funções"
  - "A queixa chega como “esquecimento” ou “distração”"
---

<!--
- Quem não registrou não pode lembrar: boa parte das queixas de memória em adultos é queixa de atenção.
- Modelo clínico de referência: Sohlberg e Mateer, hierárquico, usado também na reabilitação (aula 15).
-->

---
layout: columns
kicker: Sohlberg e Mateer
title: Os tipos de atenção
columns:
  - {
      title: "Sustentada",
      items: [
        "Manter o foco ao longo do tempo",
        "Falha: perde o fio na tarefa longa"
      ]
    }
  - {
      title: "Seletiva",
      items: [
        "Focar no relevante e ignorar o resto",
        "Falha: qualquer ruído distrai"
      ]
    }
  - {
      title: "Alternada e dividida",
      items: [
        "Trocar de foco ou dividir entre duas tarefas",
        "Falha: não cozinha e conversa ao mesmo tempo"
      ]
    }
---

<!--
- O modelo completo tem cinco níveis: focada (alerta), sustentada, seletiva, alternada e dividida. A focada é a do paciente agudo, no leito.
- A ordem é hierárquica: a dividida depende das anteriores. É a lógica do treino em reabilitação — começa-se de baixo.
-->

---
layout: define
kicker: A função que atravessa todas
term: Velocidade de processamento
definition: Rapidez com que a pessoa recebe, processa e responde a uma informação
  simples.
points:
  - "Lentificação rebaixa quase todos os testes cronometrados"
  - "É o marcador mais sensível da lesão difusa"
  - "Aparece em TCE, esclerose múltipla, depressão e envelhecimento"
---

<!--
- Antes de concluir déficit executivo num teste de tempo, pergunte se não é só lentidão. O TMT B menos o TMT A é a forma clássica de separar as duas coisas.
- Volta em quase todas as aulas de quadro — especialmente TCE (05) e esclerose múltipla (13).
-->

---
layout: default
kicker: Instrumentos
title: Avaliar atenção e velocidade
---

<Grid head :data="[
  ['Instrumento', 'O que mede', 'Norma brasileira'],
  ['Teste de Trilhas (TMT A e B)', 'velocidade visuomotora; alternância', 'adultos e idosos'],
  ['Teste d2-R', 'atenção concentrada e seletiva', 'SATEPSI'],
  ['TAVIS-4', 'seletiva, alternada e sustentada, computadorizado', 'SATEPSI'],
  ['Códigos e Símbolos (WAIS-III)', 'velocidade de processamento', 'SATEPSI'],
  ['Dígitos ordem direta', 'span atencional', 'SATEPSI (WAIS-III)'],
]" />

<!--
- Confira sempre no site do SATEPSI a situação do instrumento antes de usar: os pareceres têm validade e são revistos.
- O TAVIS é um exemplo de avaliação computadorizada brasileira, que retomamos na aula 03.
-->

---
layout: section
index: "02"
kicker: Parte dois
title: Memória
subtitle: Sistemas e processos.
---

---
layout: diagram
kicker: Os sistemas
title: Taxonomia da memória
---

<Figure src="/taxonomia-memoria.svg" alt="A memória de longo prazo dividida em declarativa (episódica e semântica) e não declarativa (procedimental, priming, condicionamento e aprendizagem não associativa), cada ramo com a estrutura cerebral que o sustenta" />

<!--
- O que mais cai em lesão adquirida é a episódica — a memória datada, com contexto. Semântica e de procedimentos costumam resistir mais.
- Essa dissociação é a que torna possível a reabilitação por aprendizagem de procedimentos (aula 15): o paciente amnésico aprende a usar a agenda sem lembrar que aprendeu.
-->

---
layout: define
kicker: O sistema mais avaliado
term: Memória episódica
definition: Lembrança de acontecimentos <em>situados</em> no tempo e no espaço —
  o quê, onde e quando.
points:
  - "Depende do hipocampo e do lobo temporal medial"
  - "É a primeira a cair no Alzheimer"
  - "Avalia-se com listas de palavras, histórias e figuras"
---

<!--
- Semântica é o conhecimento sem data: saber que Paris é a capital da França. Episódica é lembrar a viagem a Paris.
- Na anamnese: "o que jantou ontem", "quem visitou no domingo" — perguntas episódicas, conferidas com o informante.
-->

---
layout: diagram
kicker: Memória operacional
title: O modelo de Baddeley
---

<Figure src="/modelo-baddeley.svg" alt="O modelo multicomponente de Baddeley: a central executiva no alto ligada por setas de mão dupla ao esboço visuoespacial, ao buffer episódico e à alça fonológica; abaixo, como sistemas cristalizados, a semântica visual, a memória episódica de longo prazo e a linguagem" />

<!--
- Manter sete dígitos é alça fonológica; repeti-los de trás para frente exige a central executiva.
- A central executiva é a ponte com a aula 03: é ali que memória e funções executivas se encontram.
-->

---
layout: diagram
kicker: Os processos
title: Codificar, armazenar, evocar
---

<Figure src="/processos-memoria.svg" alt="As três fases do processamento da memória em cadeia — codificação, armazenamento e recuperação — e sob cada uma o sinal clínico de que a falha aconteceu ali" />

<!--
- Cada etapa falha de um jeito e tem um sinal no teste:
- Codificação: aprende pouco já na curva de aprendizagem (atenção, frontal).
- Armazenamento: aprende, mas esquece rápido e pistas não ajudam (hipocampo).
- Evocação: aprende, não evoca sozinho, mas reconhece ou melhora com pista (frontal-subcortical).
-->

---
layout: compare
kicker: O sinal no teste
title: Onde a memória falhou
columns: ["Padrão", "Aprendizagem", "Evocação tardia", "Reconhecimento"]
rows:
  - { metric: "Codificação", before: "baixa", after: "baixa", delta: "baixo" }
  - { metric: "Armazenamento", before: "razoável", after: "muito baixa", delta: "não ajuda" }
  - { metric: "Evocação", before: "razoável", after: "baixa", delta: "melhora" }
---

<!--
- Esta tabela é a ferramenta mais útil do semestre para os quadros: o armazenamento é a assinatura do Alzheimer e da epilepsia do lobo temporal; a evocação, das lesões frontais-subcorticais, da esclerose múltipla e da depressão.
- O RAVLT entrega as três colunas numa só aplicação.
-->

---
layout: diagram
kicker: Onde a memória mora
title: Cinco estruturas, cinco memórias
---

<Figure src="/neuroanatomia-memoria.svg" alt="Corte esquemático do encéfalo em vista lateral, com cinco estruturas numeradas — hipocampo, amígdala, estriado, cerebelo e córtex pré-frontal — e a lista do tipo de memória que cada uma sustenta" />

<!--
- É o mapa que liga a aula aos quadros do semestre: hipocampo na epilepsia do lobo temporal e no Alzheimer; pré-frontal no TCE e na esclerose múltipla.
-->

---
layout: default
kicker: Instrumentos
title: Avaliar memória
---

<Grid head :data="[
  ['Instrumento', 'O que mede', 'Observação'],
  ['RAVLT', 'aprendizagem, evocação e reconhecimento verbal', 'normas brasileiras por idade'],
  ['Memória Lógica (WMS)', 'memória de histórias, imediata e tardia', 'normas por escolaridade'],
  ['Figura de Rey, reprodução', 'memória visual', 'SATEPSI'],
  ['Dígitos e Sequência de Letras e Números', 'memória operacional', 'SATEPSI (WAIS-III)'],
  ['Teste de Memória Visual de Rostos', 'memória visual de longo prazo', 'computadorizado'],
]" />

<!--
- A memória lógica tem dados normativos brasileiros de Oliveira et al. (2017), cujo PDF está na pasta da aula.
- Versões alternativas: para reavaliar o mesmo paciente sem efeito de prática, use forma paralela (Bolognani et al., 2015).
-->

---
layout: default
kicker: Fixação · pergunta 1
title: Aprende, mas não guarda
---

Um paciente de 50 anos aprende 11 de 15 palavras no RAVLT, evoca 2 depois de 20 minutos e,
no reconhecimento, acerta tão pouco quanto erra. Que etapa falhou?

<v-clicks>

- **A.** Atenção, porque a lista é longa
- **B.** Codificação, porque não aprendeu
- **C.** Armazenamento
- **D.** Evocação, porque reconheceria com pistas

</v-clicks>

---
layout: default
kicker: Fixação · resposta 1
title: A resposta é <span class="accent2">C</span>
---

<Grid head highlight="row:4" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'Atenção', 'aprender 11 de 15 mostra que a informação entrou'],
  ['B', 'Codificação', 'a curva de aprendizagem foi boa'],
  ['C', 'Armazenamento', '<b>correta</b> — esquece rápido e o reconhecimento não ajuda'],
  ['D', 'Evocação', 'na falha de evocação o reconhecimento melhora; aqui ele não melhora'],
]" />

---
layout: section
index: "03"
kicker: Parte três
title: Linguagem
subtitle: Compreender, nomear, produzir.
---

---
layout: panels
kicker: Os componentes
title: O que se avalia na linguagem
panels:
  - {
      icon: "lucide:ear",
      title: "Compreensão",
      body: "Entender a palavra, a frase e o texto, oral e escrito."
    }
  - {
      icon: "lucide:tag",
      title: "Nomeação",
      body: "Achar a palavra para o objeto. A falha é a <strong>anomia</strong>."
    }
  - {
      icon: "lucide:message-circle",
      title: "Expressão",
      body: "Fluência, gramática, repetição e discurso."
    }
  - {
      icon: "lucide:pen-line",
      title: "Leitura e escrita",
      body: "Alexia e agrafia acompanham muitas afasias."
    }
---

<!--
- A anomia é o sintoma mais comum e menos específico: aparece em afasia, Alzheimer, TCE e até na fadiga.
- Afasia é alteração de linguagem adquirida por lesão. As síndromes afásicas são detalhadas na aula 04 (AVC).
-->

---
layout: vs
kicker: Fluência verbal
title: Duas tarefas, dois sistemas
left:
  title: "Fonêmica (F, A, S)"
  items:
    - "Palavras que começam com uma letra"
    - "Exige estratégia de busca"
    - "Mais sensível ao lobo frontal"
right:
  title: "Semântica (animais)"
  items:
    - "Palavras de uma categoria"
    - "Exige o estoque de conceitos"
    - "Mais sensível ao lobo temporal"
---

<!--
- Padrão útil: semântica muito pior que fonêmica sugere perda do estoque (Alzheimer, demência semântica); o inverso sugere falha de busca (frontal, subcortical).
- Normas brasileiras por escolaridade — escolaridade pesa mais que idade nessas tarefas.
-->

---
layout: default
kicker: Instrumentos
title: Avaliar linguagem
---

<Grid head :data="[
  ['Instrumento', 'O que mede'],
  ['Teste de Nomeação de Boston', 'nomeação por confronto visual'],
  ['Fluência verbal fonêmica e semântica', 'busca lexical e estoque semântico'],
  ['Token Test', 'compreensão de ordens'],
  ['Bateria MTL-Brasil', 'linguagem em adultos com lesão'],
  ['NEUPSILIN, subtestes de linguagem', 'rastreio dentro de bateria breve'],
]" />

<!--
- A avaliação detalhada da afasia é, em geral, feita em conjunto com a fonoaudiologia. O neuropsicólogo descreve o impacto da linguagem nos outros testes — um paciente que não compreende instruções vai mal em tudo.
-->

---
layout: section
index: "04"
kicker: Parte quatro
title: O escore normatizado
subtitle: Da nota bruta à classificação.
---

---
layout: define
kicker: A comparação
term: Norma
definition: Desempenho de um grupo de referência <em>semelhante</em> à pessoa
  avaliada, contra o qual o seu escore bruto ganha sentido.
points:
  - "Idade e escolaridade são as variáveis mais importantes"
  - "Norma estrangeira não serve para população brasileira"
  - "A norma diz o que é raro, não o que é patológico"
---

<!--
- 18 pontos no MEEM é baixo para quem tem doutorado e esperado para quem não frequentou a escola. O número só significa algo diante da norma.
- Raro não é sinônimo de patológico: 2% da população saudável fica abaixo de −2 DP por definição.
-->

---
layout: chart
kicker: A curva normal
title: Onde fica cada pessoa
note: Quanto mais longe da média, mais rara a pontuação. Abaixo de −1,5 desvio
  costuma-se falar em déficit.
chart:
  type: bar
  height: "260px"
  unit: "%"
  categories: ["< −2 DP", "−2 a −1", "−1 a 0", "0 a +1", "+1 a +2", "> +2 DP"]
  series:
    - { name: "Proporção da população", data: [2.3, 13.6, 34.1, 34.1, 13.6, 2.3] }
---

<!--
- Escore-z = (escore bruto − média da norma) ÷ desvio-padrão da norma.
- Correspondências úteis: z = −1 ≈ percentil 16; z = −1,5 ≈ percentil 7; z = −2 ≈ percentil 2.
- O ponto de corte varia entre manuais (−1,5 ou −2 DP; percentil 5 ou 10). Diga no laudo qual critério usou.
-->

---
layout: reference
kicker: Converter e classificar
title: As três réguas
items:
  - {
      term: "Escore-z",
      desc: "distância da média em desvios-padrão; média 0, DP 1"
    }
  - {
      term: "Escore padrão",
      desc: "média 100, DP 15; o QI usa esta régua"
    }
  - {
      term: "Escore ponderado",
      desc: "média 10, DP 3; os subtestes das Escalas Wechsler usam esta"
    }
  - {
      term: "Percentil",
      desc: "porcentagem da norma que pontua igual ou abaixo"
    }
---

<!--
- Exemplo para a lousa: média da norma 40, DP 8, paciente fez 28. z = (28 − 40) ÷ 8 = −1,5 → percentil ≈ 7 → escore padrão ≈ 77,5.
-->

---
layout: default
kicker: Fixação · pergunta 2
title: Dois pacientes, um escore
---

Dois homens de 60 anos fazem 22 pontos na mesma tarefa. Um tem 4 anos de estudo; o
outro, 16. A norma do grupo de 4 anos tem média 20 e DP 4; a do grupo de 16 anos, média 30 e
DP 4. O que dizer?

<v-clicks>

- **A.** Os dois tiveram o mesmo desempenho
- **B.** O de 4 anos está na média; o de 16 está 2 DP abaixo
- **C.** Os dois estão abaixo do esperado
- **D.** Não dá para comparar sem o percentil

</v-clicks>

---
layout: default
kicker: Fixação · resposta 2
title: A resposta é <span class="accent2">B</span>
---

<Grid head highlight="row:3" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'Mesmo desempenho', 'mesmo escore bruto, normas diferentes'],
  ['B', 'Na média e −2 DP', '<b>correta</b> — z = +0,5 para um e z = −2,0 para o outro'],
  ['C', 'Ambos abaixo', 'o de 4 anos está acima da média do seu grupo'],
  ['D', 'Falta o percentil', 'o escore-z já permite a comparação'],
]" />

---
layout: statement
kicker: Exercício em dupla
title: Converta os escores da ficha, classifique e escreva <em>uma frase de laudo</em> para cada um.
---

<!--
- Ficha em papel: seis escores brutos com média e DP de norma (RAVLT, TMT A e B, fluência, Boston, Dígitos).
- Peça a frase no formato da aula 01: função, comparação com norma, descrição do erro.
-->

---
layout: panels
kicker: Para levar
title: Três coisas que ficam
panels:
  - {
      icon: "lucide:focus",
      title: "Atenção primeiro",
      body: "Sem atenção e velocidade, todo o resto cai. Descarte-as antes de concluir
        outro déficit."
    }
  - {
      icon: "lucide:database",
      title: "Memória em três etapas",
      body: "Codificar, armazenar, evocar. O <strong>reconhecimento</strong> separa
        armazenamento de evocação."
    }
  - {
      icon: "lucide:ruler",
      title: "Escore pede norma",
      body: "Idade e escolaridade adequadas; diga no laudo qual norma e qual corte."
    }
---

---
layout: reference
kicker: Referências
title: Base desta aula
items:
  - {
      term: "Malloy-Diniz et al., 2016",
      desc: "<em>Avaliação neuropsicológica</em>. 2ª ed. Porto Alegre: Artmed. Caps.
        sobre atenção, memória, linguagem e psicometria."
    }
  - {
      term: "Sohlberg e Mateer, 2001",
      desc: "<em>Cognitive rehabilitation: an integrative neuropsychological
        approach</em>. New York: Guilford."
    }
  - {
      term: "Baddeley, 2000",
      desc: "The episodic buffer: a new component of working memory? <em>Trends in
        Cognitive Sciences</em>, 4(11), 417-423."
    }
  - {
      term: "Oliveira et al., 2017",
      desc: "Dados normativos da Memória Lógica (WMS-R) em adultos brasileiros. PDF na
        pasta da aula."
    }
  - {
      term: "Strauss, Sherman e Spreen, 2006",
      desc: "<em>A compendium of neuropsychological tests</em>. 3rd ed. New York:
        Oxford University Press."
    }
---
