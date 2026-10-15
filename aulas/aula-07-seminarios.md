---
theme: slidev-theme-fasm
title: "Seminários"
info: Neuropsicologia nos transtornos psiquiátricos — ordem das apresentações,
  roteiro de cada grupo, rubrica e combinados das semanas 7 e 8
date: "2027-03-23"
author: FASM · Neuropsicologia II
# Gera o PDF no build (via playwright-chromium) e liga o botão de download no deck.
download: true
exportFilename: aula-07-seminarios
themeConfig:
  lang: pt-BR
layout: lead
index: "07"
kicker: Neuropsicologia II · FASM
subtitle: Neuropsicologia nos transtornos psiquiátricos.
---

<!--
- Deck de abertura das duas noites de seminário (S7 e S8). Projeta-se a ordem da noite, os combinados e, entre os grupos, o slide de perguntas.
- Proposta completa, rubrica e bibliografia de partida em `referencias/atividades/`.
-->

---
layout: columns
kicker: Semana 7
title: Seminários I
columns:
  - {
      title: "Humor e psicose",
      items: [
        "1 · Transtorno depressivo maior",
        "2 · Transtorno bipolar",
        "3 · Esquizofrenia"
      ]
    }
  - {
      title: "Ansiedade e trauma",
      items: [
        "4 · Transtorno obsessivo-compulsivo",
        "5 · Transtorno de estresse pós-traumático"
      ]
    }
---

---
layout: columns
kicker: Semana 8
title: Seminários II
columns:
  - {
      title: "Ansiedade e neurodesenvolvimento",
      items: [
        "6 · Transtorno de ansiedade generalizada",
        "7 · TDAH no adulto"
      ]
    }
  - {
      title: "Outros quadros",
      items: [
        "8 · Transtorno por uso de álcool",
        "9 · Anorexia nervosa",
        "10 · Transtorno da personalidade borderline"
      ]
    }
---

---
layout: steps
kicker: O roteiro de cada grupo
title: O que a apresentação precisa ter
steps:
  - {
      icon: "lucide:book-open",
      title: "O quadro",
      desc: "critérios, curso e epidemiologia em poucos slides"
    }
  - {
      icon: "lucide:brain",
      title: "O perfil cognitivo",
      desc: "domínios alterados e preservados, com estado e traço"
    }
  - {
      icon: "lucide:clipboard-list",
      title: "A avaliação",
      desc: "instrumentos, normas brasileiras e confundidores"
    }
  - {
      icon: "lucide:file-text",
      title: "Caso e laudo",
      desc: "uma vinheta e a conclusão do laudo escrita pelo grupo"
    }
  - {
      icon: "lucide:target",
      title: "Intervenção",
      desc: "o que a reabilitação ou a remediação oferecem"
    }
---

<!--
- O caso pode ser fictício ou adaptado de artigo; sem dados identificáveis de paciente real.
- A conclusão do laudo segue o roteiro das aulas 04 a 06: pergunta, perfil, quadro, rotina, recomendação.
-->

---
layout: panels
kicker: Combinados
title: Como funciona a noite
panels:
  - {
      icon: "lucide:timer",
      title: "25 minutos",
      body: "20 de apresentação e 5 de perguntas. O tempo é cronometrado."
    }
  - {
      icon: "lucide:users",
      title: "Todos falam",
      body: "Cada integrante apresenta uma parte e responde a perguntas."
    }
  - {
      icon: "lucide:upload",
      title: "Entrega",
      body: "Slides e referências enviados até o dia anterior à apresentação."
    }
  - {
      icon: "lucide:message-circle-question",
      title: "Plateia",
      body: "Cada grupo prepara uma pergunta para o grupo seguinte."
    }
---

---
layout: default
kicker: Avaliação
title: A rubrica
---

<Grid head :data="[
  ['Critério', 'Pontos', 'O que se observa'],
  ['Domínio do conteúdo', '3,0', 'quadro e perfil cognitivo corretos, com fonte'],
  ['Avaliação', '2,0', 'instrumentos adequados e normas brasileiras'],
  ['Caso e laudo', '2,5', 'conclusão que responde à pergunta do caso'],
  ['Comunicação', '1,5', 'clareza, tempo e slides legíveis'],
  ['Perguntas', '1,0', 'respostas e pergunta ao outro grupo'],
]" />

<!--
- Nota de 0 a 10. O peso do seminário na média do bimestre está no plano de ensino.
- Parte da nota é individual: quem não apresenta ou não responde perde os pontos de comunicação e perguntas.
-->

---
layout: statement
kicker: Entre os grupos
title: Qual achado deste transtorno mudaria a <em>conclusão</em> de um laudo?
---

<!--
- Pergunta para a plateia depois de cada grupo, enquanto o próximo se prepara.
-->

---
layout: end
title: Bons seminários
subtitle: As apresentações caem na prova 1.
---
