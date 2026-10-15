---
theme: slidev-theme-fasm
title: "Reabilitação neuropsicológica: técnicas"
info: Técnicas de aprendizagem para memória, auxílios externos, treino de
  atenção, treino de metas e resolução de problemas, autoconsciência, manejo de
  comportamento, treino computadorizado e trabalho com a família
date: "2027-05-18"
author: FASM · Neuropsicologia II
# Gera o PDF no build (via playwright-chromium) e liga o botão de download no deck.
download: true
exportFilename: aula-15-reabilitacao-tecnicas
themeConfig:
  lang: pt-BR
layout: lead
index: "15"
kicker: Neuropsicologia II · FASM
subtitle: A caixa de ferramentas.
---

<!--
- Estrutura do encontro: 1 h 30 de técnicas, 30 min de intervalo, 30 min de evidência e família, 30 min de estações práticas em grupo.
- **GMT** — *Goal Management Training*, treino de gerenciamento de metas.
- **APT** — aqui, *Attention Process Training*, treino de processos atencionais (não confundir com amnésia pós-traumática, da aula 05).
-->

---
layout: agenda
kicker: Aula 15 · o caminho de hoje
title: Caminho da aula
items:
  - {
      topic: "Memória",
      desc: "como ensinar a quem não lembra"
    }
  - {
      topic: "Atenção e funções executivas",
      desc: "treino por níveis e metas"
    }
  - {
      topic: "Consciência, emoção e comportamento",
      desc: "o que vem antes do treino"
    }
  - {
      topic: "Computador e família",
      desc: "o que funciona e o que vende"
    }
---

---
layout: section
index: "01"
kicker: Parte um
title: Memória
subtitle: Ensinar a quem não lembra.
---

---
layout: define
kicker: Técnica 1
term: Aprendizagem sem erro
definition: Ensinar de forma que a pessoa <em>não erre</em> durante a
  aprendizagem, dando a resposta certa antes que ela tente adivinhar.
points:
  - "Quem tem amnésia não lembra que errou"
  - "O erro se repete porque a memória implícita guarda o que foi feito"
  - "Funciona melhor para informação específica"
---

<!--
- Baddeley e Wilson (1994) mostraram a vantagem da aprendizagem sem erro sobre a aprendizagem por ensaio e erro em pacientes amnésicos.
- Na prática: "o nome da nova cuidadora é Rosa. Repita: Rosa". Nunca "adivinhe o nome dela".
-->

---
layout: columns
kicker: Técnicas 2 e 3
title: Recuperação espaçada e pistas que somem
columns:
  - {
      title: "Recuperação espaçada",
      items: [
        "Evocar a informação em intervalos crescentes",
        "30 s, 1 min, 2 min, 4 min…",
        "Se errar, volta ao intervalo anterior"
      ]
    }
  - {
      title: "Desvanecimento de pistas",
      items: [
        "Começa com a pista completa",
        "Retira uma parte a cada acerto",
        "Ro__, R___, sem pista"
      ]
    }
---

<!--
- As duas combinam com a aprendizagem sem erro e funcionam até em demência leve a moderada (Clare e Woods, 2004).
- O que se aprende assim é específico: a pessoa aprende o nome da cuidadora, não "melhora a memória".
-->

---
layout: feature
kicker: Técnica 4
title: Auxílios externos de memória
columns: 3
features:
  - {
      icon: "lucide:notebook-pen",
      title: "Agenda e diário",
      desc: "o que fazer e o que já foi feito"
    }
  - {
      icon: "lucide:smartphone",
      title: "Celular",
      desc: "alarmes, lembretes, fotos"
    }
  - {
      icon: "lucide:pill",
      title: "Caixa de remédios",
      desc: "com divisórias e alarme"
    }
  - {
      icon: "lucide:clipboard-check",
      title: "Listas e quadros",
      desc: "rotina na geladeira, checklist na porta"
    }
  - {
      icon: "lucide:tag",
      title: "Rótulos",
      desc: "gavetas e armários identificados"
    }
  - {
      icon: "lucide:map",
      title: "Pistas no ambiente",
      desc: "setas, cores, objetos sempre no mesmo lugar"
    }
---

<!--
- O auxílio externo é a intervenção de memória com mais evidência em lesão adquirida (Cicerone et al., 2019).
- O problema: usar a agenda é, em si, uma tarefa de memória. O uso precisa ser treinado em etapas (aquisição, aplicação, adaptação), como fizeram Sohlberg e Mateer com o "memory book".
-->

---
layout: default
kicker: Fixação · pergunta 1
title: O nome do neto
---

Dona Célia, 79 anos, com TNC maior por Alzheimer, não lembra o nome do neto que nasceu há
três meses e fica envergonhada. A família quer "exercícios de memória". O que propor?

<v-clicks>

- **A.** Jogos de memória no tablet, uma hora por dia
- **B.** Perguntar o nome várias vezes ao dia até ela acertar sozinha
- **C.** Aprendizagem sem erro com recuperação espaçada e uma foto com o nome
- **D.** Nada: no Alzheimer não há aprendizagem possível

</v-clicks>

---
layout: default
kicker: Fixação · resposta 1
title: A resposta é <span class="accent2">C</span>
---

<Grid head highlight="row:4" :data="[
  ['', 'Alternativa', 'Por que erra — ou por que acerta'],
  ['A', 'Jogos no tablet', 'treino genérico não transfere para o nome do neto'],
  ['B', 'Perguntar até acertar', 'é ensaio e erro: ela vai repetir os nomes errados'],
  ['C', 'Sem erro e espaçada', '<b>correta</b> — meta específica, relevante, com técnica que funciona na demência'],
  ['D', 'Nada', 'a memória implícita e o aprendizado com pista estão relativamente preservados'],
]" />

---
layout: section
index: "02"
kicker: Parte dois
title: Atenção e funções executivas
subtitle: Treino por níveis e metas.
---

---
layout: steps
kicker: Sohlberg e Mateer
title: Treino de processos atencionais
steps:
  - {
      icon: "lucide:timer",
      title: "Sustentada",
      desc: "manter o foco em tarefa longa e monótona"
    }
  - {
      icon: "lucide:filter",
      title: "Seletiva",
      desc: "a mesma tarefa com ruído e distratores"
    }
  - {
      icon: "lucide:repeat",
      title: "Alternada",
      desc: "trocar de regra a cada sinal"
    }
  - {
      icon: "lucide:split",
      title: "Dividida",
      desc: "duas tarefas ao mesmo tempo"
    }
---

<!--
- O modelo hierárquico da aula 02 virando treino: só se passa ao nível seguinte quando o anterior está estável.
- A evidência é melhor quando o treino se combina com estratégias metacognitivas e com tarefas da vida real (Cicerone et al., 2019).
-->

---
layout: steps
kicker: Levine e Robertson
title: Goal Management Training
steps:
  - {
      icon: "lucide:pause",
      title: "Pare",
      desc: "o que estou fazendo?"
    }
  - {
      icon: "lucide:target",
      title: "Defina a meta",
      desc: "qual é a tarefa principal?"
    }
  - {
      icon: "lucide:list-ordered",
      title: "Divida em passos",
      desc: "quais etapas, em que ordem?"
    }
  - {
      icon: "lucide:brain",
      title: "Aprenda os passos",
      desc: "eu sei o que fazer?"
    }
  - {
      icon: "lucide:check-check",
      title: "Confira",
      desc: "estou fazendo o que planejei?"
    }
---

<!--
- Levine et al. (2000) e Stamenova e Levine (2019): o GMT tem evidência em TCE, AVC, EM e envelhecimento.
- O "pare" é o coração da técnica: interrompe o piloto automático e chama o controle executivo. Pode-se usar um alarme aleatório no celular como sinal de "pare".
- Ponte com a aula 03: cada passo exercita um componente do planejamento.
-->

---
layout: vs
kicker: Escolhendo a técnica
title: Restaurar ou compensar a atenção
left:
  title: "Treino da função"
  items:
    - "Déficit leve a moderado"
    - "Fase subaguda"
    - "Boa consciência do déficit"
right:
  title: "Estratégia e ambiente"
  items:
    - "Déficit grave ou progressivo"
    - "Fase crônica"
    - "Pouca consciência do déficit"
---

---
layout: section
index: "03"
kicker: Parte três
title: Consciência, emoção e comportamento
subtitle: O que vem antes do treino.
---

---
layout: panels
kicker: Autoconsciência
title: Três níveis de consciência
panels:
  - {
      icon: "lucide:brain",
      title: "Intelectual",
      body: "Sabe que tem a dificuldade."
    }
  - {
      icon: "lucide:eye",
      title: "Emergente",
      body: "Percebe a dificuldade quando ela acontece."
    }
  - {
      icon: "lucide:shield",
      title: "Antecipatória",
      body: "Prevê a dificuldade e se prepara antes."
    }
---

<!--
- Modelo da pirâmide de Crosson et al. (1989). Só a consciência antecipatória permite usar compensação de forma espontânea.
- Técnicas: previsão e comparação (o paciente prevê o desempenho, faz a tarefa e compara), feedback em vídeo, comparação com o informante.
- Volta ao TCE (aula 05): a anosognosia era o obstáculo do retorno ao trabalho.
-->

---
layout: columns
kicker: Emoção e comportamento
title: Intervenções que acompanham a cognição
columns:
  - {
      title: "Emoção",
      items: [
        "Psicoeducação sobre a lesão",
        "Terapia cognitivo-comportamental adaptada",
        "Luto pela identidade anterior"
      ]
    }
  - {
      title: "Comportamento",
      items: [
        "Análise funcional: antecedente, comportamento, consequência",
        "Mudança do ambiente que dispara a crise",
        "Reforço do comportamento alternativo"
      ]
    }
---

<!--
- TCC adaptada: sessões mais curtas, material escrito, mais repetição, uso de agenda e resumo no fim.
- No manejo comportamental, o alvo frequente é o cuidador: ele aprende a identificar o gatilho e a responder sem escalar. Volta no trabalho do filme — as crises de Anthony muitas vezes nascem da confusão e da correção insistente.
-->

---
layout: section
index: "04"
kicker: Parte quatro
title: Computador e família
subtitle: O que funciona e o que vende.
---

---
layout: vs
kicker: Treino cognitivo computadorizado
title: O que a evidência diz
left:
  title: "Melhora"
  items:
    - "O desempenho na tarefa treinada"
    - "Tarefas muito parecidas"
    - "Mais quando há terapeuta junto"
right:
  title: "Pouco transfere"
  items:
    - "Para a vida diária"
    - "Para outros domínios"
    - "Quando é feito sozinho, sem meta"
---

<!--
- Simons et al. (2016) revisaram a literatura dos "brain games": melhora na tarefa treinada, pouca transferência distante.
- O computador é útil como ferramenta dentro de um plano com meta funcional — por exemplo, treino de atenção com estratégias, ou o próprio celular como auxílio externo.
-->

---
layout: panels
kicker: A família
title: O cuidador também é paciente
panels:
  - {
      icon: "lucide:book-open",
      title: "Psicoeducação",
      body: "Entender o quadro muda a leitura do comportamento."
    }
  - {
      icon: "lucide:messages-square",
      title: "Comunicação",
      body: "Frases curtas, uma ideia por vez, sem corrigir à toa."
    }
  - {
      icon: "lucide:battery-low",
      title: "Sobrecarga",
      body: "Rastrear o cuidador e oferecer suporte e pausa."
    }
---

<!--
- Escala de sobrecarga de Zarit, com versão brasileira, para medir a carga do cuidador.
- Nas demências, intervenções com o cuidador reduzem sintomas comportamentais e adiam institucionalização.
-->

---
layout: statement
kicker: Estações em grupo
title: Cada grupo ensina à turma <em>uma técnica</em>, com um caso do semestre.
---

<!--
- Cinco estações de 6 minutos: aprendizagem sem erro (nome da cuidadora), recuperação espaçada (o PIN do banco), GMT (fazer o almoço), previsão e comparação (o motoboy do TCE), análise funcional (a crise no banho).
- Os grupos são os mesmos do trabalho do filme: a técnica treinada hoje pode entrar no plano.
-->

---
layout: panels
kicker: Para levar
title: Três coisas que ficam
panels:
  - {
      icon: "lucide:shield-check",
      title: "Sem erro",
      body: "Quem não lembra que errou aprende o erro. Ensine a resposta certa."
    }
  - {
      icon: "lucide:notebook-pen",
      title: "Auxílio se treina",
      body: "A agenda é a intervenção com mais evidência, <strong>se o uso for
        treinado</strong>."
    }
  - {
      icon: "lucide:users",
      title: "Antes do treino",
      body: "Consciência, emoção e família decidem a adesão."
    }
---

---
layout: reference
kicker: Referências
title: Base desta aula
items:
  - {
      term: "Cicerone et al., 2019",
      desc: "Evidence-based cognitive rehabilitation: systematic review of the
        literature from 2009 through 2014. <em>Archives of Physical Medicine and
        Rehabilitation</em>, 100(8), 1515-1533."
    }
  - {
      term: "Baddeley e Wilson, 1994",
      desc: "When implicit learning fails: amnesia and the problem of error
        elimination. <em>Neuropsychologia</em>, 32(1), 53-68."
    }
  - {
      term: "Levine et al., 2000",
      desc: "Rehabilitation of executive functioning: an experimental-clinical
        validation of Goal Management Training. <em>Journal of the International
        Neuropsychological Society</em>, 6(3), 299-312."
    }
  - {
      term: "Sohlberg e Mateer, 2001",
      desc: "<em>Cognitive rehabilitation: an integrative neuropsychological
        approach</em>. New York: Guilford."
    }
  - {
      term: "Simons et al., 2016",
      desc: "Do “brain-training” programs work? <em>Psychological Science in the
        Public Interest</em>, 17(3), 103-186."
    }
---
