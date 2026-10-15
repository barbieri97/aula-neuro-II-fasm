---
theme: slidev-theme-fasm
title: "Acidente vascular cerebral"
info: Tipos, territórios arteriais e as síndromes que deles resultam; curso da
  recuperação, comorbidades e avaliação neuropsicológica no AVC — do quadro ao
  laudo
date: "2027-03-02"
author: FASM · Neuropsicologia II
# Gera o PDF no build (via playwright-chromium) e liga o botão de download no deck.
download: true
exportFilename: aula-04-acidente-vascular-cerebral
themeConfig:
  lang: pt-BR
layout: lead
index: "04"
kicker: Neuropsicologia II · FASM
subtitle: Quando o sangue para de chegar.
---

<!--
- Estrutura do encontro: 1 h 30 de quadro (tipos, territórios, síndromes, curso), 30 min de intervalo, 30 min de avaliação, 30 min de vinheta e conclusão de laudo em grupo.
- **AVC** — acidente vascular cerebral. **AIT** — ataque isquêmico transitório.
- **ACM, ACA, ACP** — artérias cerebrais média, anterior e posterior.
- **NIHSS** — *National Institutes of Health Stroke Scale*, escala neurológica de gravidade.
-->

---
layout: agenda
kicker: Aula 04 · o caminho de hoje
title: Caminho da aula
items:
  - {
      topic: "O que é o AVC",
      desc: "tipos, causas e números"
    }
  - {
      topic: "Território e síndrome",
      desc: "a artéria decide o que se perde"
    }
  - {
      topic: "Curso e recuperação",
      desc: "do agudo ao crônico, e o que acompanha"
    }
  - {
      topic: "A avaliação neuropsicológica",
      desc: "quando, o quê e como adaptar"
    }
  - {
      topic: "Do quadro ao laudo",
      desc: "vinheta e conclusão em grupo"
    }
---

---
layout: section
index: "01"
kicker: Parte um
title: O que é o AVC
subtitle: Tipos, causas e números.
---

---
layout: define
kicker: A definição
term: Acidente vascular cerebral
definition: Déficit neurológico <em>súbito</em> causado por interrupção do fluxo
  sanguíneo ou por sangramento no encéfalo.
points:
  - "Começa de repente, com sinal focal"
  - "O sintoma depende do território afetado"
  - "Tempo é cérebro: o tratamento agudo tem janela de horas"
---

<!--
- Sinais de alerta da campanha SAMU: sorriso torto, abraço fraco (fraqueza de um lado), música (fala alterada) — e ligar 192.
- O psicólogo raramente está na fase hiperaguda, mas reconhecer os sinais é obrigação de qualquer profissional de saúde.
-->

---
layout: vs
kicker: Os dois tipos
title: Isquêmico e hemorrágico
left:
  title: "Isquêmico · cerca de 85%"
  items:
    - "Uma artéria é obstruída"
    - "Trombose local ou êmbolo vindo do coração"
    - "Lesão no território da artéria"
right:
  title: "Hemorrágico · cerca de 15%"
  items:
    - "Um vaso se rompe"
    - "Intraparenquimatoso ou subaracnóideo"
    - "Efeito de massa e pressão intracraniana"
---

<!--
- AIT: déficit isquêmico que regride, sem lesão na imagem. É um aviso — risco alto de AVC nos dias seguintes.
- Hemorragia subaracnóidea por aneurisma rompido: déficits de memória e executivos difusos, mesmo sem lesão focal grande. Muito frequente em adultos jovens.
-->

---
layout: stats
kicker: A dimensão do problema
title: Por que o AVC está no programa
stats:
  - { value: 1, unit: " em 4", label: "adultos terá um AVC ao longo da vida", tone: warn }
  - { value: "2ª", label: "causa de morte no mundo", tone: bad }
  - { value: 1, unit: "/3", label: "dos sobreviventes desenvolve depressão", tone: info }
---

<!--
- Dados globais da World Stroke Organization e do Global Burden of Disease (Feigin et al., 2022).
- No Brasil, o AVC é uma das principais causas de morte e a principal causa de incapacidade em adultos.
- Depressão pós-AVC: Hackett e Pickles (2014), cerca de um terço dos sobreviventes.
-->

---
layout: feature
kicker: Fatores de risco
title: O que aumenta o risco
columns: 3
features:
  - {
      icon: "lucide:heart-pulse",
      title: "Hipertensão",
      desc: "o fator mais importante e mais tratável"
    }
  - {
      icon: "lucide:activity",
      title: "Fibrilação atrial",
      desc: "forma coágulos que viajam até o cérebro"
    }
  - {
      icon: "lucide:droplet",
      title: "Diabetes e colesterol",
      desc: "aterosclerose das artérias grandes e pequenas"
    }
  - {
      icon: "lucide:cigarette",
      title: "Tabagismo e álcool",
      desc: "risco dobrado nos fumantes"
    }
  - {
      icon: "lucide:armchair",
      title: "Sedentarismo",
      desc: "obesidade e síndrome metabólica"
    }
  - {
      icon: "lucide:brain",
      title: "AVC prévio",
      desc: "quem teve um tem risco maior de outro"
    }
---

<!--
- A prevenção secundária entra no plano de reabilitação: adesão à medicação é tarefa de memória prospectiva — e é aí que o neuropsicólogo ajuda.
-->

---
layout: section
index: "02"
kicker: Parte dois
title: Território e síndrome
subtitle: A artéria decide o que se perde.
---

---
layout: default
kicker: Os três territórios
title: Artéria e síndrome
---

<Grid head :data="[
  ['Artéria', 'Irriga', 'Sinais típicos'],
  ['Cerebral média', 'face lateral dos lobos frontal, parietal e temporal', 'hemiparesia de face e braço; afasia à esquerda; negligência à direita'],
  ['Cerebral anterior', 'face medial do frontal', 'paresia da perna; apatia, abulia, desinibição'],
  ['Cerebral posterior', 'occipital, temporal medial e tálamo', 'hemianopsia; agnosia visual; amnésia'],
]" highlight="row:2" />

<!--
- A cerebral média responde pela maioria dos AVC isquêmicos e pelas síndromes que mais aparecem no consultório.
- Infartos lacunares (pequenas artérias perfurantes) e AVC talâmico podem produzir quadro cognitivo desproporcional ao tamanho da lesão: o tálamo é estação dos circuitos frontais-subcorticais.
-->

---
layout: vs
kicker: Os dois hemisférios
title: Esquerdo e direito
left:
  title: "Hemisfério esquerdo"
  items:
    - "Afasias"
    - "Apraxias"
    - "Alexia, agrafia, acalculia"
    - "Memória verbal"
right:
  title: "Hemisfério direito"
  items:
    - "Negligência espacial"
    - "Anosognosia"
    - "Déficit visuoconstrutivo"
    - "Prosódia e pragmática"
---

<!--
- A regra vale para destros e para a maioria dos canhotos (linguagem à esquerda em cerca de 95% dos destros e 70% dos canhotos).
- O paciente com lesão direita parece "melhor" porque fala bem — e por isso o déficit é subestimado pela família e pela equipe.
-->

---
layout: columns
kicker: Afasias
title: As síndromes clássicas
columns:
  - {
      title: "Broca",
      items: [
        "Fala não fluente, esforçada",
        "Compreensão relativamente preservada",
        "Frontal inferior esquerdo"
      ]
    }
  - {
      title: "Wernicke",
      items: [
        "Fala fluente, sem sentido",
        "Compreensão comprometida",
        "Temporal superior esquerdo"
      ]
    }
  - {
      title: "Condução e global",
      items: [
        "Condução: a repetição é que falha",
        "Global: expressão e compreensão",
        "Fascículo arqueado; ACM inteira"
      ]
    }
---

<!--
- Classificação de Boston: fluência, compreensão e repetição são os três eixos. As transcorticais preservam a repetição.
- O paciente com Wernicke muitas vezes não percebe o próprio erro (anosognosia da afasia) e se irrita com quem não o entende.
-->

---
layout: diagram
kicker: Linguagem
title: Broca, Wernicke e o fascículo arqueado
---

<Figure src="/ling-areas-hemisferio.svg" alt="Vista lateral do hemisfério esquerdo, sobre o atlas de Brodmann, com a frente do cérebro à esquerda. Em azul, a área de Broca (áreas 44 e 45, giro frontal inferior), ligada à produção. Em ocre, a área de Wernicke (porção posterior da área 22, giro temporal superior), ligada à compreensão. Uma linha tracejada contorna o fim da fissura lateral e liga as duas: o fascículo arqueado" />

<!--
- As duas áreas e o feixe que as liga ficam no território da artéria cerebral média esquerda. Oclusão do ramo superior tende a dar Broca; do inferior, Wernicke; do tronco, afasia global.
-->

---
layout: define
kicker: Hemisfério direito
term: Negligência espacial unilateral
definition: Falha em <em>perceber</em>, <em>orientar-se</em> ou <em>responder</em>
  ao lado do espaço oposto à lesão, sem perda sensorial que a explique.
points:
  - "Quase sempre o lado esquerdo"
  - "Come só metade do prato e barbeia metade do rosto"
  - "Frequentemente acompanhada de anosognosia"
---

<!--
- Testes: cancelamento de linhas ou estrelas, bissecção de linhas, cópia de figura, desenho do relógio com números amontoados à direita.
- É um dos maiores preditores de mau prognóstico funcional: aumenta quedas e dependência.
-->

---
layout: default
kicker: Fixação · pergunta 1
title: Ele diz que está bem
---

Um senhor de 64 anos, uma semana após AVC, fala fluentemente e diz que "está ótimo, só
cansado". Bate a cadeira de rodas na porta do lado esquerdo e deixa a comida desse lado do
prato. Qual o território mais provável?

<v-clicks>

- **A.** Artéria cerebral média esquerda
- **B.** Artéria cerebral média direita
- **C.** Artéria cerebral anterior esquerda
- **D.** Artéria cerebral posterior esquerda

</v-clicks>

---
layout: default
kicker: Fixação · resposta 1
title: A resposta é <span class="accent2">B</span>
---

<Grid head highlight="row:3" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'ACM esquerda', 'produziria afasia; ele fala fluentemente'],
  ['B', 'ACM direita', '<b>correta</b> — negligência à esquerda e anosognosia são sinais parietais direitos'],
  ['C', 'ACA esquerda', 'daria paresia da perna e quadro frontal medial'],
  ['D', 'ACP esquerda', 'hemianopsia direita e alexia, não negligência à esquerda'],
]" />

---
layout: define
kicker: O efeito somado
term: Comprometimento cognitivo vascular
definition: Declínio cognitivo atribuído a doença cerebrovascular — um grande
  infarto, vários pequenos ou lesão difusa de substância branca.
points:
  - "Lentificação e disfunção executiva predominam"
  - "Memória com falha de evocação"
  - "Curso em degraus ou progressivo"
---

<!--
- A ponte para a aula 11: TNC vascular é a segunda causa de demência. A forma de pequenos vasos é silenciosa e progressiva — não há "o dia do AVC".
- Critérios VASCOG (Sachdev et al., 2014).
-->

---
layout: section
index: "03"
kicker: Parte três
title: Curso e recuperação
subtitle: Do agudo ao crônico.
---

---
layout: timeline
kicker: O curso
title: As fases depois do AVC
events:
  - { date: "Dias", title: "Aguda", desc: "estabilização clínica, rastreio à beira do leito" }
  - { date: "1–3 meses", title: "Subaguda inicial", desc: "a maior parte da recuperação espontânea" }
  - { date: "3–6 meses", title: "Subaguda tardia", desc: "ganhos mais lentos; avaliação abrangente" }
  - { date: "> 6 meses", title: "Crônica", desc: "adaptação, compensação e retorno à vida" }
---

<!--
- A janela de recuperação espontânea mais intensa é nos três primeiros meses (Bernhardt et al., 2017, consenso de recuperação do AVC).
- Avaliação completa muito cedo subestima o potencial; muito tarde perde a janela de intervenção. Na fase aguda, rastreio; aos 3 meses, avaliação abrangente.
-->

---
layout: columns
kicker: Prognóstico
title: O que pesa na recuperação
columns:
  - {
      title: "Da lesão",
      items: [
        "Tamanho e local",
        "Gravidade inicial",
        "AVC prévios e substância branca"
      ]
    }
  - {
      title: "Da pessoa",
      items: [
        "Idade",
        "Reserva cognitiva e escolaridade",
        "Consciência do déficit"
      ]
    }
  - {
      title: "Do contexto",
      items: [
        "Reabilitação precoce",
        "Suporte familiar",
        "Acesso ao serviço"
      ]
    }
---

---
layout: panels
kicker: O que acompanha o AVC
title: Além da cognição
panels:
  - {
      icon: "lucide:cloud-rain",
      title: "Depressão pós-AVC",
      body: "Cerca de um terço dos sobreviventes. Piora a reabilitação e a cognição."
    }
  - {
      icon: "lucide:battery-low",
      title: "Fadiga",
      body: "Desproporcional ao esforço. Limita sessões e tarefas."
    }
  - {
      icon: "lucide:pause",
      title: "Apatia",
      body: "Falta de iniciativa. Confunde-se com depressão."
    }
  - {
      icon: "lucide:heart-crack",
      title: "Labilidade emocional",
      body: "Choro ou riso súbitos, desproporcionais ao que a pessoa sente."
    }
---

<!--
- Apatia e depressão: na apatia falta motivação sem tristeza; na depressão há humor deprimido. Separar as duas muda o tratamento.
- Rastrear humor é parte da avaliação neuropsicológica no AVC — e com afasia, use escalas visuais ou relato do cuidador.
-->

---
layout: section
index: "04"
kicker: Parte quatro
title: A avaliação neuropsicológica
subtitle: Quando, o quê e como adaptar.
---

---
layout: steps
kicker: O protocolo
title: Avaliar no AVC
steps:
  - {
      icon: "lucide:stethoscope",
      title: "Leia o prontuário",
      desc: "tipo, território, data, NIHSS e imagem"
    }
  - {
      icon: "lucide:eye",
      title: "Cheque o canal",
      desc: "visão, audição, braço dominante, compreensão"
    }
  - {
      icon: "lucide:clipboard-list",
      title: "Escolha pelo território",
      desc: "linguagem à esquerda; negligência e visuoespacial à direita"
    }
  - {
      icon: "lucide:heart",
      title: "Rastreie humor e fadiga",
      desc: "escalas adaptadas e relato do cuidador"
    }
  - {
      icon: "lucide:home",
      title: "Meça a funcionalidade",
      desc: "o que mudou nas atividades de vida diária"
    }
---

<!--
- Hemiparesia do braço dominante: testes com resposta motora precisam de adaptação ou substituição (resposta verbal, apontar com a mão não dominante — e registrar no laudo).
- Afasia de compreensão invalida testes verbais: um escore baixo de memória verbal não significa amnésia se o paciente não entendeu a lista.
-->

---
layout: default
kicker: Instrumentos
title: Uma bateria para o AVC
---

<Grid head :data="[
  ['Domínio', 'Instrumento'],
  ['Rastreio', 'MoCA'],
  ['Linguagem', 'Boston, fluência, Token Test'],
  ['Negligência', 'cancelamento, bissecção de linhas'],
  ['Atenção e velocidade', 'Trilhas A e B, Códigos'],
  ['Memória', 'RAVLT, Figura de Rey'],
  ['Humor', 'escalas de depressão adaptadas'],
]" />

<!--
- A MoCA é mais sensível que o MEEM ao comprometimento vascular, por conter tarefas executivas.
-->

---
layout: section
index: "05"
kicker: Parte cinco
title: Do quadro ao laudo
subtitle: A vinheta.
---

---
layout: default
kicker: Vinheta clínica
aside: "vinheta clínica"
title: Dona Marta, 61 anos
---

Professora aposentada. AVC isquêmico da artéria cerebral média direita há quatro meses.
Mora com a filha, que a trouxe à avaliação.

<Callout icon="lucide:message-square">A neurologista pergunta: <strong>ela pode voltar a cuidar das finanças da casa?</strong></Callout>

<!--
- A ficha completa está em `referencias/aula-04/vinheta-dona-marta.docx`: história, escores com norma e relato da filha.
-->

---
layout: compare
kicker: Vinheta clínica
title: Os achados de Dona Marta
columns: ["Domínio", "Resultado", "Norma", "Leitura"]
rows:
  - { metric: "Linguagem", before: "Boston 56/60", after: "média", delta: "preservada" }
  - { metric: "Memória verbal", before: "RAVLT tardia 9", after: "média", delta: "preservada" }
  - { metric: "Atenção", before: "Trilhas A 98 s", after: "z −2,1", delta: "lentificada" }
  - { metric: "Negligência", before: "omite 9 de 20 à esquerda", after: "—", delta: "presente" }
  - { metric: "Visuoconstrução", before: "Rey cópia 18/36", after: "z −2,8", delta: "rebaixada" }
---

<!--
- Relato da filha: "erra contas, pula linhas no extrato, diz que está tudo certo".
- O ponto da vinheta: os testes verbais preservados escondem o déficit; a pergunta (finanças) depende justamente do que está alterado.
-->

---
layout: steps
kicker: Levando para o laudo
title: Como escrever a conclusão
steps:
  - {
      icon: "lucide:message-square",
      title: "Retome a pergunta",
      desc: "a neurologista quer saber sobre as finanças"
    }
  - {
      icon: "lucide:list",
      title: "Descreva o perfil",
      desc: "o que está preservado e o que está alterado, por função"
    }
  - {
      icon: "lucide:link",
      title: "Ligue ao quadro",
      desc: "compatível com lesão hemisférica direita"
    }
  - {
      icon: "lucide:home",
      title: "Traduza para a rotina",
      desc: "negligência e anosognosia explicam os erros no extrato"
    }
  - {
      icon: "lucide:route",
      title: "Recomende",
      desc: "supervisão nas finanças, reabilitação, reavaliação em 6 meses"
    }
---

<!--
- Exemplo de conclusão (ler depois que os grupos escreverem a sua): "A avaliação evidenciou linguagem e memória verbal preservadas, com lentificação, déficit visuoconstrutivo e negligência espacial à esquerda, associados a pouca consciência das dificuldades. O perfil é compatível com lesão hemisférica direita. No momento, recomenda-se que a gestão financeira seja feita com supervisão, além de reabilitação neuropsicológica com foco em varredura visual e reavaliação em seis meses."
-->

---
layout: statement
kicker: Dinâmica em grupo
title: Leiam a ficha de Dona Marta e escrevam a <em>conclusão</em> do laudo.
---

<!--
- 25 minutos de escrita, 15 de leitura em voz alta de dois grupos. Corrija pelo roteiro do slide anterior: pergunta, perfil, quadro, rotina, recomendação.
-->

---
layout: panels
kicker: Para levar
title: Três coisas que ficam
panels:
  - {
      icon: "lucide:map",
      title: "Território decide",
      body: "Esquerdo: linguagem e praxia. Direito: <strong>negligência</strong> e
        anosognosia."
    }
  - {
      icon: "lucide:clock",
      title: "O tempo importa",
      body: "Rastreio no agudo; avaliação abrangente por volta dos três meses."
    }
  - {
      icon: "lucide:file-text",
      title: "O laudo responde",
      body: "Perfil, ligação com o quadro e tradução para a <strong>vida
        diária</strong>."
    }
---

---
layout: reference
kicker: Referências
title: Base desta aula
items:
  - {
      term: "Feigin et al., 2022",
      desc: "World Stroke Organization: Global Stroke Fact Sheet 2022.
        <em>International Journal of Stroke</em>, 17(1), 18-29.
        doi:10.1177/17474930211065917"
    }
  - {
      term: "Hackett e Pickles, 2014",
      desc: "Part I: frequency of depression after stroke: an updated systematic review
        and meta-analysis. <em>International Journal of Stroke</em>, 9(8),
        1017-1025. doi:10.1111/ijs.12357"
    }
  - {
      term: "Bernhardt et al., 2017",
      desc: "Agreed definitions and a shared vision for new standards in stroke
        recovery research. <em>International Journal of Stroke</em>, 12(5),
        444-450. doi:10.1177/1747493017711816"
    }
  - {
      term: "Sachdev et al., 2014",
      desc: "Diagnostic criteria for vascular cognitive disorders: a VASCOG statement.
        <em>Alzheimer Disease &amp; Associated Disorders</em>, 28(3), 206-218."
    }
  - {
      term: "Malloy-Diniz et al., 2016",
      desc: "<em>Avaliação neuropsicológica</em>. 2ª ed. Porto Alegre: Artmed. Capítulo
        sobre doenças cerebrovasculares."
    }
---
