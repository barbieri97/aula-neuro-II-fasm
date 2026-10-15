---
theme: slidev-theme-fasm
title: "Funções cognitivas II"
info: Funções executivas, praxias, gnosias, visuoconstrução e cognição social;
  baterias breves, avaliação computadorizada, SATEPSI e normas brasileiras
date: "2027-02-23"
author: FASM · Neuropsicologia II
# Gera o PDF no build (via playwright-chromium) e liga o botão de download no deck.
download: true
exportFilename: aula-03-funcoes-cognitivas-ii
themeConfig:
  lang: pt-BR
layout: lead
index: "03"
kicker: Neuropsicologia II · FASM
subtitle: Funções complexas e instrumentos atuais.
---

<!--
- Estrutura do encontro: 1 h 20 de exposição (executivas, praxias, gnosias, visuoconstrução, cognição social), 30 min de intervalo, 40 min sobre baterias, avaliação computadorizada e normas, 30 min de montagem de protocolo em grupo.
- **FE** — funções executivas. **FAB** — Bateria de Avaliação Frontal. **MoCA** — *Montreal Cognitive Assessment*.
- **CANTAB** — *Cambridge Neuropsychological Test Automated Battery*. **CPT** — *Continuous Performance Test*.
-->

---
layout: agenda
kicker: Aula 03 · o caminho de hoje
title: Caminho da aula
items:
  - {
      topic: "Funções executivas",
      desc: "a tríade, as funções complexas e o lobo frontal"
    }
  - {
      topic: "Praxias, gnosias e visuoconstrução",
      desc: "fazer, reconhecer e montar no espaço"
    }
  - {
      topic: "Cognição social",
      desc: "entender o outro"
    }
  - {
      topic: "Os instrumentos de hoje",
      desc: "baterias, avaliação computadorizada e normas brasileiras"
    }
---

---
layout: section
index: "01"
kicker: Parte um
title: Funções executivas
subtitle: O gerente do cérebro.
---

---
layout: define
kicker: A definição
term: Funções executivas
definition: Processos que <em>controlam outros processos</em> a serviço de um
  comportamento dirigido a uma meta.
points:
  - "Aparecem quando a resposta automática não serve"
  - "Gerenciam e organizam os demais processos cognitivos"
---

<!--
- Diamond (2013) é a referência de definição.
- Contraste com a aula 02: memória e linguagem são conteúdo; executiva é controle sobre o conteúdo.
-->

---
layout: diagram
kicker: Diamond, 2013
title: A tríade
---

<Figure src="/fe-triade.svg" alt="Três núcleos executivos lado a lado — controle inibitório, memória operacional e flexibilidade cognitiva — sustentando, acima, a faixa das funções executivas complexas" />

<!--
- Unidade e diversidade (Friedman e Miyake, 2017): correlacionados, mas separáveis.
- Um teste "de função executiva" mede na prática um desses núcleos, mais o que a tarefa carrega de linguagem, motricidade e velocidade.
-->

---
layout: panels
kicker: A tríade num quadro só
title: O que cada núcleo faz e como falha
panels:
  - {
      title: "Controle inibitório",
      icon: "lucide:hand",
      items: [
        "<strong>Faz:</strong> segura a resposta dominante",
        "<strong>Falha:</strong> impulsividade, desinibição",
        "<strong>Teste:</strong> Stroop, Go/No-Go"
      ]
    }
  - {
      title: "Memória operacional",
      icon: "lucide:layers",
      items: [
        "<strong>Faz:</strong> mantém e opera ao mesmo tempo",
        "<strong>Falha:</strong> perde o fio, refaz do começo",
        "<strong>Teste:</strong> Dígitos inversos, Sequência de Letras e Números"
      ]
    }
  - {
      title: "Flexibilidade cognitiva",
      icon: "lucide:repeat",
      items: [
        "<strong>Faz:</strong> troca de regra e de estratégia",
        "<strong>Falha:</strong> rigidez, perseveração",
        "<strong>Teste:</strong> Wisconsin, Trilhas B"
      ]
    }
---

<!--
- Peça exemplos de vida diária da turma para cada falha antes de mostrar o slide.
-->

---
layout: diagram
kicker: As funções complexas
title: A base sustenta o conjunto
---

<Figure src="/fe-complexas-dependencia.svg" alt="Uma fundação larga e única, com as três funções executivas básicas lado a lado, sustenta por baixo um bloco mais estreito com as três funções complexas — as divisões dos dois blocos não se alinham, porque a base sustenta o conjunto, não uma função de cada vez" />

<!--
- Planejamento, raciocínio e resolução de problemas são os três núcleos trabalhando juntos.
- Quando o planejamento falha, a pergunta seguinte é sempre: por causa de qual núcleo?
- Testes: Torre de Londres (planejamento), Matrizes (raciocínio), Figura de Rey cópia (organização).
-->

---
layout: diagram
kicker: Neuroanatomia
title: Três circuitos pré-frontais
---

<Figure src="/fe-neuroanatomia.svg" alt="Áreas de Brodmann em vistas lateral e medial do encéfalo, com três circuitos pré-frontais numerados — dorsolateral, orbitofrontal e cingulado anterior — e, ao lado, a síndrome característica de cada um" />

<!--
- Dorsolateral: síndrome disexecutiva (planejamento, flexibilidade).
- Orbitofrontal: desinibição, impulsividade, alteração de conduta social.
- Cingulado anterior: apatia, abulia, pouca iniciativa.
- Os circuitos passam por núcleos da base e tálamo: lesão subcortical produz síndrome frontal (Bonelli e Cummings, 2007). É a ponte para AVC, TCE e esclerose múltipla.
-->

---
layout: default
kicker: Fixação · pergunta 1
title: Ele começa tudo e não termina nada
---

Após um TCE, um engenheiro de 42 anos começa a montar uma estante, larga para regar as
plantas, volta, recomeça do zero. Nos testes, vai bem em Dígitos e mal na Torre de Londres e no
Trilhas B. Qual o achado central?

<v-clicks>

- **A.** Déficit de memória operacional
- **B.** Déficit de planejamento e flexibilidade
- **C.** Apraxia construtiva
- **D.** Déficit de memória episódica

</v-clicks>

---
layout: default
kicker: Fixação · resposta 1
title: A resposta é <span class="accent2">B</span>
---

<Grid head highlight="row:3" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'Memória operacional', 'Dígitos preservado afasta a memória operacional como causa principal'],
  ['B', 'Planejamento e flexibilidade', '<b>correta</b> — Torre e Trilhas B rebaixados, com a vida diária desorganizada'],
  ['C', 'Apraxia construtiva', 'ele monta, mas não sustenta a sequência; o problema é de organização'],
  ['D', 'Memória episódica', 'nada indica que esquece o que fez; ele abandona a tarefa'],
]" />

---
layout: section
index: "02"
kicker: Parte dois
title: Praxias, gnosias e visuoconstrução
subtitle: Fazer, reconhecer e montar.
---

---
layout: define
kicker: Fazer
term: Apraxia
definition: Incapacidade de executar um gesto aprendido <em>sem</em> paralisia,
  falta de coordenação ou falta de compreensão que a explique.
points:
  - "Ideomotora: sabe o gesto, não o executa sob comando"
  - "Ideatória: perde a sequência e o uso dos objetos"
  - "Lesões parietais e frontais, geralmente à esquerda"
---

<!--
- Exemplo da ideomotora: pede-se "mostre como escova os dentes" e o paciente usa o dedo como escova; com a escova na mão, faz certo.
- Exemplo da ideatória: põe o café no filtro depois de passar a água.
- Teste à beira do leito: gestos simbólicos (dar tchau), uso de objeto imaginado, sequência punho-borda-palma de Luria.
-->

---
layout: define
kicker: Reconhecer
term: Agnosia
definition: Falha em <em>reconhecer</em> um estímulo apesar de a sensação estar
  preservada.
points:
  - "Visual de objetos: vê, descreve, não sabe o que é"
  - "Prosopagnosia: não reconhece rostos conhecidos"
  - "Anosognosia: não reconhece o próprio déficit"
---

<!--
- Agnosias visuais vêm da via ventral, occipitotemporal.
- A anosognosia é a mais importante para a reabilitação: quem não reconhece o déficit não adere ao treino. Volta no AVC (negligência) e no TCE.
-->

---
layout: vs
kicker: Visuoconstrução
title: Copiar e desenhar
left:
  title: "Figura Complexa de Rey"
  items:
    - "Cópia: organização e planejamento visuoespacial"
    - "Reprodução tardia: memória visual"
    - "O tipo de cópia diz mais que o escore"
right:
  title: "Teste do Relógio"
  items:
    - "Planejamento, visuoconstrução e conceito de tempo"
    - "Rápido, sensível, pouco específico"
    - "Bom rastreio em idosos"
---

<!--
- Lesão direita: perde a configuração geral, os detalhes ficam soltos.
- Lesão esquerda: mantém o contorno, simplifica e omite detalhes.
- Lesão frontal: cópia fragmentada, sem plano, por partes.
-->

---
layout: diagram
kicker: O que o desenho mostra
title: O relógio planejado e o desorganizado
---

<Figure src="/teste-do-relogio.svg" alt="Dois desenhos do teste do relógio: um planejado e um com prejuízo de organização espacial" />

<!--
- Mesmo escore pode esconder erros diferentes: números fora do círculo (planejamento), ponteiros iguais (conceitual), metade dos números (negligência).
-->

---
layout: section
index: "03"
kicker: Parte três
title: Cognição social
subtitle: Entender o outro.
---

---
layout: define
kicker: A definição
term: Cognição social
definition: Processos que permitem <em>perceber</em>, <em>interpretar</em> e
  <em>responder</em> às intenções e emoções dos outros.
points:
  - "Reconhecimento de emoções em faces"
  - "Teoria da mente: atribuir estados mentais"
  - "Empatia e julgamento social"
---

<!--
- Circuitos orbitofrontal, amígdala, junção temporoparietal.
- É o domínio que mais pesa no retorno ao trabalho e nas relações depois do TCE, e central em esquizofrenia e DFT variante comportamental.
-->

---
layout: columns
kicker: Como se avalia
title: Três tarefas de referência
columns:
  - {
      title: "Emoções",
      items: [
        "Reconhecimento de expressões faciais",
        "Escolher a emoção entre seis básicas"
      ]
    }
  - {
      title: "Teoria da mente",
      items: [
        "Leitura da mente nos olhos",
        "Histórias de falso crença e de gafe"
      ]
    }
  - {
      title: "Conduta",
      items: [
        "Entrevista com informante",
        "Escalas de comportamento"
      ]
    }
---

<!--
- Poucos instrumentos de cognição social têm parecer do SATEPSI; muitos são tarefas de pesquisa. No laudo, cite como recurso complementar.
- A entrevista com o informante é o dado mais robusto: "ele perdeu o tato", "não percebe que magoa".
-->

---
layout: section
index: "04"
kicker: Parte quatro
title: Os instrumentos de hoje
subtitle: Baterias, computador e normas.
---

---
layout: compare
kicker: Rastreio e bateria
title: O que cada nível entrega
columns: ["Nível", "Exemplos", "Tempo", "Uso"]
rows:
  - { metric: "Rastreio", before: "MEEM, MoCA, FAB", after: "10–15 min", delta: "há algo a investigar?" }
  - { metric: "Bateria breve", before: "NEUPSILIN, ACE-III", after: "40–60 min", delta: "quais domínios?" }
  - { metric: "Avaliação abrangente", before: "testes por domínio", after: "3–6 sessões", delta: "qual perfil e qual hipótese?" }
---

<!--
- A MoCA é mais sensível que o MEEM para comprometimento leve e para funções executivas.
- A FAB tem normas brasileiras por escolaridade (Beato et al., 2012); os PDFs estão na pasta da aula.
- NEUPSILIN: bateria brasileira (Fonseca, Salles e Parente), avalia nove funções em cerca de 40 minutos.
-->

---
layout: define
kicker: A avaliação computadorizada
term: Testagem informatizada
definition: Aplicação, registro e correção de tarefas cognitivas por
  <em>computador</em> ou <em>tablet</em>.
points:
  - "Mede tempo de reação em milissegundos"
  - "Padroniza a aplicação"
  - "Gera formas paralelas para reteste"
---

<!--
- Exemplos: CANTAB (internacional), CPT (atenção sustentada), TAVIS-4 (brasileiro, com parecer favorável).
- Também entram aqui as plataformas de avaliação remota, que ganharam espaço desde 2020.
-->

---
layout: vs
kicker: Avaliação computadorizada
title: O que ganha e o que perde
left:
  title: "Ganha"
  items:
    - "Precisão de tempo"
    - "Correção automática"
    - "Menos efeito do examinador"
    - "Reteste com formas paralelas"
right:
  title: "Perde"
  items:
    - "Familiaridade com a tela pesa no idoso"
    - "Pouca observação qualitativa"
    - "Poucas normas brasileiras"
    - "Teleavaliação exige ambiente controlado"
---

<!--
- A Resolução CFP 11/2018 regulamenta serviços psicológicos por meios de tecnologia; a aplicação remota de teste exige que o manual preveja essa forma.
- Regra prática: o computador mede melhor o tempo; o examinador observa melhor o erro.
-->

---
layout: panels
kicker: Normas brasileiras
title: Três perguntas antes de usar um teste
panels:
  - {
      icon: "lucide:shield-check",
      title: "Tem parecer favorável?",
      body: "Confira no site do SATEPSI. Os pareceres vencem e são revistos."
    }
  - {
      icon: "lucide:users",
      title: "A norma é para esta pessoa?",
      body: "Idade, escolaridade e região próximas das do paciente."
    }
  - {
      icon: "lucide:calendar",
      title: "A norma é recente?",
      body: "O efeito Flynn e a mudança de escolaridade envelhecem as tabelas."
    }
---

<!--
- Testes sem parecer (tarefas neuropsicológicas de pesquisa) podem compor a avaliação como recurso complementar, desde que com fundamentação e citados como tal no laudo.
-->

---
layout: default
kicker: Fixação · pergunta 2
title: O teste no tablet
---

Uma clínica quer substituir toda a avaliação por uma bateria em tablet, de 30 minutos, com
normas americanas e relatório automático. O que responder?

<v-clicks>

- **A.** É melhor: mais precisa e sem viés de examinador
- **B.** Pode complementar, mas norma estrangeira e relatório automático não substituem o raciocínio clínico
- **C.** Só serve para crianças
- **D.** É proibido usar computador em avaliação psicológica

</v-clicks>

---
layout: default
kicker: Fixação · resposta 2
title: A resposta é <span class="accent2">B</span>
---

<Grid head highlight="row:3" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'É melhor', 'precisão de tempo não compensa a norma inadequada nem a falta de observação'],
  ['B', 'Complementa', '<b>correta</b> — instrumento precisa de norma da população e o laudo, de integração'],
  ['C', 'Só crianças', 'há baterias computadorizadas para todas as idades'],
  ['D', 'Proibido', 'é permitido, com instrumento adequado e regulamentado'],
]" />

---
layout: statement
kicker: Dinâmica em grupo
title: Montem um protocolo para a <em>pergunta</em> do cartão sorteado.
---

<!--
- Cartões: (1) "Perdeu a memória depois do AVC?" (2) "Pode voltar a dirigir após TCE?" (3) "É depressão ou demência?" (4) "Esclerose múltipla com queixa de lentidão".
- Cada grupo escolhe de 5 a 7 instrumentos, justifica cada um pela função e diz qual norma usaria. 20 min de montagem, 10 min de discussão.
-->

---
layout: panels
kicker: Para levar
title: Três coisas que ficam
panels:
  - {
      icon: "lucide:workflow",
      title: "Controle sobre conteúdo",
      body: "As executivas são <strong>três núcleos</strong>; as complexas são eles
        combinados."
    }
  - {
      icon: "lucide:shapes",
      title: "Fazer, reconhecer, montar",
      body: "Apraxia, agnosia e visuoconstrução falham sem perda motora ou sensorial."
    }
  - {
      icon: "lucide:monitor",
      title: "Instrumento com critério",
      body: "Rastreio, bateria e computador servem a perguntas diferentes. A norma é
        sempre a da pessoa avaliada."
    }
---

---
layout: reference
kicker: Referências
title: Base desta aula
items:
  - {
      term: "Diamond, 2013",
      desc: "Executive functions. <em>Annual Review of Psychology</em>, 64, 135-168.
        doi:10.1146/annurev-psych-113011-143750"
    }
  - {
      term: "Bonelli e Cummings, 2007",
      desc: "Frontal-subcortical circuitry and behavior. <em>Dialogues in Clinical
        Neuroscience</em>, 9(2), 141-151. PDF na pasta da aula."
    }
  - {
      term: "Beato et al., 2012",
      desc: "Frontal Assessment Battery in a Brazilian sample of healthy controls:
        normative data. <em>Arquivos de Neuro-Psiquiatria</em>, 70(4), 278-280."
    }
  - {
      term: "Fonseca, Salles e Parente, 2009",
      desc: "<em>NEUPSILIN: Instrumento de Avaliação Neuropsicológica Breve</em>. São
        Paulo: Vetor."
    }
  - {
      term: "CFP, 2018",
      desc: "Resolução n. 11/2018. Regulamenta a prestação de serviços psicológicos
        realizados por meios de tecnologias da informação e da comunicação."
    }
---
