---
name: universidade-de-bolso
description: "Base de conhecimento extraída do conteúdo \"Universidade de bolso: como criar seu tutor de IA\" (transcrição de vídeo, Maestros da IA). Use ao montar ou operar tutores de IA personalizados, planejar estudo com curva do esquecimento, efeito 2-Sigma de Bloom, técnica Feynman, flashcards, rastreamento de progresso e grounding em aulas universitárias abertas."
---

<!-- argument-hint: [tópico, nome do framework ou número do capítulo] -->

# Universidade de bolso — como criar seu tutor de IA
**Fonte**: transcrição de vídeo (Maestros da IA) | **Idioma**: PT-BR | **Capítulos**: 9 | **Gerado**: 2026-08-30

## Como usar esta skill

- **Sem argumento** — carrega os frameworks centrais para consulta
- **Com um tópico** — pergunte por `curva do esquecimento`, `nivelamento`, `grounding`, `flashcards`; eu localizo e leio o capítulo certo
- **Com capítulo** — peça `ch05`; carrego aquele capítulo específico
- **Navegar** — pergunte "quais capítulos você tem?" para ver o índice completo

Quando você perguntar sobre algo que não está nos Frameworks Centrais abaixo, eu leio o capítulo correspondente antes de responder.

---

## Frameworks centrais e modelos mentais

### O problema
- **Curva do esquecimento** — o que foi perfeitamente compreendido hoje tem alta chance de não ser reproduzível em uma semana. Trate todo "entendi" como hipótese, nunca como resultado.
- **Copiloto vs. sistema** — usar IA para tirar dúvidas pontuais resolve o bloqueio do momento e não deixa rastro. Sistema é o arranjo que *lembra de você*: guarda o que você viu, seu nível e onde você erra. Falta às pessoas sistema, não informação.
- **Custo de oportunidade da atenção** — 3h32/dia de redes ≈ 3.000 h em ~2,5 anos ≈ a carga horária de uma graduação. O tempo já existe; o trabalho é realocar.

### A evidência
- **Efeito 2-Sigma (Bloom, 1984)** — alunos com tutoria individual superaram as notas de 98% dos alunos de sala de aula tradicional. O que impediu aplicar isso por 40 anos foi custo, não pedagogia — e é o custo que a IA derruba.
- **Tutor como técnico esportivo** — o técnico não dá uma aula e vai embora; fica na beira da piscina todo dia, cronometrando cada braçada, vendo a evolução e apontando o que fortalecer. Exija acompanhamento longitudinal, não aulas avulsas.
- **Garantir aprendizado ≠ transmitir conteúdo** — a entrega da aula é o começo do trabalho do tutor, não o fim.

### A construção do tutor
- **Os sete componentes** — currículo/roadmap, aulas (objetivos + checklist, não texto corrido), exercícios com variação, flashcards, rastreamento de progresso, detecção de ponto fraco, revisões. O diferencial está nos componentes de memória, não na qualidade da explicação.
- **Empilhar blocos** — todo bloco novo se apoia em blocos já dominados. Ao travar em um conceito, pergunte qual bloco de baixo está faltando.
- **As quatro perguntas do setup** — o que aprender → recorte do objetivo → nivelamento → tempo de dedicação. São os parâmetros que geram o currículo inteiro.
- **Recorte antes de currículo** — tema amplo demais ("cibersegurança") produz plano raso. Estreite antes de gerar.
- **Nivelamento pelo piso** — na dúvida, declare "começando do zero". Fundamento a mais custa dias; buraco na base custa meses.
- **Uma pasta = um tutor** — a frota escala trivialmente: um tutor de cibersegurança, um de alemão, um de qualquer subtópico. Isolamento de histórico é o que mantém a detecção de ponto fraco precisa. Por pasta: amplitude **ou** profundidade, nunca os dois.

### As regras de conduta do agente
- **Nada é assumido como sabido** — o agente nunca usa um conceito ou termo que ele ainda não ensinou. É a regra que impede o aluno de se perder no meio do processo.
- **Concreto antes do abstrato** — cena e metáfora primeiro, nome depois, generalização por último.
- **Articular de volta (Feynman)** — ele ensinou, você leu, você entendeu: isso não conta. O que conta é quão bem você devolve o conceito com suas palavras. E mesmo articulando bem, o conceito volta em revisão futura.
- **Avaliação de profundidade** — respostas são julgadas por solidez conceitual, não só por acerto, e ficam registradas.
- **Uma pergunta por vez** — nunca listas gigantes; cada pergunta se adapta à resposta anterior.
- **Loop de ponto fraco** — respostas ruins recorrentes sobre um tema marcam uma fraqueza, e as próximas sessões concentram nela até a profundidade melhorar.

### Fontes e mídias
- **Grounding por transcrição** — MIT, Harvard, Oxford e Stanford publicam semestres inteiros de graça. Baixe `.txt`/`.srt` das aulas, coloque na pasta do tutor e peça a grade **com base nesse material**. É a resposta técnica ao medo de alucinação — não abandonar a IA, mas dar a ela a fonte.
- **Assistir ≠ reter** — a aula gravada entrega conteúdo; o tutor entrega retenção. Assista se quiser, mas coloque a transcrição no tutor.
- **Geração de mídia por aula** — peça nomeando a aula ("gere um podcast e uma imagem para a Aula 00"). Imagem para estrutura, áudio para narrativa e revisão em deslocamento, texto para consulta, vídeo para processos.
- **Saída personalizável** — formato, estilo, linguagem e público são ajustáveis, inclusive registro infantil. O HTML das aulas é simples de propósito, para você redesenhar.

---

## Índice de capítulos

| # | Título | Frameworks principais |
|---|--------|----------------------|
| [ch00](chapters/ch00-custo-de-oportunidade-da-atencao.md) | O custo de oportunidade da atenção | Conta do diploma perdido, janela de vantagem competitiva |
| [ch01](chapters/ch01-curva-do-esquecimento.md) | A curva do esquecimento | Curva do esquecimento, copiloto vs. sistema |
| [ch02](chapters/ch02-efeito-2-sigma-de-bloom.md) | O efeito 2-Sigma de Bloom | Efeito 2-Sigma, barreira econômica dissolvida, tutor como técnico |
| [ch03](chapters/ch03-anatomia-do-tutor-ia.md) | Anatomia de um tutor de IA | Os sete componentes, empilhar blocos, loop de ponto fraco |
| [ch04](chapters/ch04-setup-do-tutor.md) | Setup — montando seu tutor do zero | As quatro perguntas do setup, recorte antes de currículo |
| [ch05](chapters/ch05-principios-pedagogicos.md) | Os princípios pedagógicos do agente | Nada assumido como sabido, Feynman, uma pergunta por vez |
| [ch06](chapters/ch06-fontes-confiaveis-e-grounding.md) | Ancorando em fontes confiáveis | Grounding por transcrição, assistir ≠ reter |
| [ch07](chapters/ch07-materiais-multimodais.md) | Materiais multimodais | Geração sob demanda, cena primeiro conceito depois |
| [ch08](chapters/ch08-frota-de-tutores.md) | Frota de tutores | Uma pasta = um tutor, amplitude vs. profundidade |

## Índice de tópicos

- **Alucinação / confiabilidade** → ch06
- **Articular de volta / Feynman** → ch05
- **Aula (formato)** → ch03, ch07
- **Bloom / 2-Sigma** → ch02
- **Currículo / roadmap** → ch03, ch04
- **Curva do esquecimento** → ch01
- **Detecção de ponto fraco** → ch03, ch05
- **Exercícios com variação** → ch03
- **Flashcards** → ch03
- **Fontes universitárias abertas** → ch06, ch00
- **Grounding / transcrições** → ch06
- **Imagens e metáforas visuais** → ch07, ch05
- **Integrações de mídia** → ch04, ch07
- **Multimodalidade / podcast** → ch07
- **Nivelamento** → ch04
- **Pasta = tutor** → ch04, ch08
- **Personalização de linguagem** → ch07
- **Progresso / histórico** → ch03, ch08
- **Recorte de objetivo** → ch04, ch08
- **Revisões** → ch03, ch05
- **Setup** → ch04
- **Tempo de dedicação** → ch04, ch00
- **Tempo de tela / custo de oportunidade** → ch00
- **Tutoria individual** → ch02
- **Uma pergunta por vez** → ch05

## Arquivos de apoio

- [glossary.md](glossary.md) — todos os termos-chave com definição e capítulo
- [patterns.md](patterns.md) — técnicas e padrões com quando usar, como e trade-offs
- [cheatsheet.md](cheatsheet.md) — regras de decisão, escolha de mídia, números de referência e sinais de sistema quebrado

---

## Escopo e limites

Esta skill cobre o método descrito na fonte — como estruturar, configurar e operar tutores de IA para estudo. Ela **não** é o agente tutor em si: não gera currículos, não guarda seu progresso e não aplica revisões. Para isso, monte a pasta do tutor conforme o ch04.

A fonte é a transcrição de um vídeo promocional de uma comunidade paga; a extração deliberadamente ignora a parte comercial e mantém apenas o método pedagógico e operacional. Como transcrição falada, ela não traz citações formais: o dado de Bloom (1984) e as estatísticas de tempo de tela aparecem aqui como declarados na fonte — confira-os antes de usá-los em material público. Detalhes de interface de ferramentas específicas mudam rápido; os princípios (ch01–ch03, ch05) envelhecem melhor que os passos de setup (ch04).
