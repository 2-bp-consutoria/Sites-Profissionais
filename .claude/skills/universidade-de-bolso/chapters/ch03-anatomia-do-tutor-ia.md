# Capítulo 03: Anatomia de um tutor de IA

## Ideia central
Um tutor de IA não é um chat que explica bem — é um conjunto de componentes que trabalham juntos: currículo, aulas, exercícios, flashcards, rastreamento de progresso, detecção de pontos fracos e revisões programadas.

## Frameworks introduzidos
- **Os sete componentes do tutor**: o inventário mínimo de um agente que ensina de verdade.
  - Quando usar: ao montar, avaliar ou depurar um tutor — se algum componente falta, você sabe qual sintoma esperar.
  - Como:
    1. **Currículo / roadmap** — a sequência ordenada de aulas, do zero ao objetivo.
    2. **Aulas** — não texto corrido: objetivos + checklist de tópicos que você precisa dominar para fechar a aula.
    3. **Exercícios com variação** — sempre reformulados, para que nenhum conceito fique para trás.
    4. **Flashcards** — resgate espaçado do que já foi ensinado.
    5. **Rastreamento de progresso** — registro do que você estudou, quando, e como respondeu.
    6. **Detecção de ponto fraco** — leitura do histórico para descobrir onde suas respostas são recorrentemente ruins.
    7. **Revisões** — sessões que devolvem o conteúdo na ordem certa, uma pergunta por vez.
- **Empilhar blocos**: a regra de construção do currículo.
  - Quando usar: ao ordenar qualquer conteúdo novo.
  - Como: cada bloco só entra apoiado em blocos já dominados; nada de conceito solto no ar. A consequência prática é que você nunca deixa um conceito para trás — ele volta como pré-requisito do próximo.
  - Por que funciona: dívida conceitual é cumulativa; um buraco na base derruba tudo que vem depois.
- **Loop de ponto fraco**: como o tutor decide o que fazer amanhã.
  - Quando usar: automaticamente, a cada sessão.
  - Como: respostas ruins recorrentes sobre um tema → o tema é marcado como fraqueza → as próximas sessões focam especificamente nele, com exercícios variados, até a resposta melhorar.

## Conceitos-chave
- **Currículo** — o plano completo de aulas gerado para o seu objetivo e o seu nível.
- **Roadmap** — a visão das etapas e da ordem em que elas serão percorridas.
- **Aula como programa** — a aula é uma lista de objetivos e tópicos a dominar, não um texto para ler passivamente.
- **Exercício com variação** — mesma competência cobrada de ângulos diferentes, para impedir memorização da forma da pergunta.
- **Flashcard** — unidade mínima de resgate: uma pergunta, uma resposta, repetida no tempo.
- **Rastreamento de progresso** — histórico persistente do estudo, base de toda adaptação.
- **Ponto fraco** — tema em que suas respostas são recorrentemente insuficientes, sinalizado pelo histórico.

## Modelos mentais
- Pense na aula como *checklist de domínio*, não como texto: você fecha a aula quando consegue responder pelos tópicos dela, não quando termina de ler.
- Pense no currículo como uma pilha: você não coloca um bloco onde não há apoio. Ao encontrar um conceito difícil, a pergunta certa é "qual bloco de baixo está faltando?".
- Trate cada resposta sua como dado, não como conversa: ela alimenta a decisão do que virá na próxima sessão.

## Exemplo trabalhado
Um currículo de cibersegurança pedido por alguém que declarou saber "absolutamente nada" não começa por cibersegurança:

- **Aula 00 — Como um computador funciona.** Objetivos + checklist de tópicos. Nada de firewall, nada de criptografia.
- **Aula 01 — Diferença entre CPU, RAM e disco.** Construída com metáfora concreta (a CPU é o cozinheiro, a RAM é a bancada de ingredientes, o disco é a despensa que sobrevive ao desligamento).
- **Aula 02 —** próximo bloco, apoiado nos dois anteriores.
- ... o agente segue gerando até fechar o currículo inteiro até o objetivo declarado.

Por que isso importa: sem entender o que é memória volátil e o que é armazenamento persistente, não há como entender por que um ataque que vive só na RAM é difícil de detectar. O bloco de baixo não é enfeite — ele é pré-requisito do bloco de cima. O agente que pula a Aula 00 produz um aluno que repete termos sem sustentação.

## Anti-padrões
- **Tutor sem memória**: sem rastreamento, não há detecção de ponto fraco nem revisão — vira copiloto (Cap. 01).
- **Aula como parede de texto**: entrega conteúdo, não verifica domínio; o aluno confunde leitura com aprendizado.
- **Exercício sempre idêntico**: o aluno memoriza a forma da pergunta, não o conceito.
- **Currículo montado por assunto interessante em vez de pré-requisito**: gera buracos que só aparecem lá na frente, quando é caro voltar.

## Principais aprendizados
1. O diferencial do tutor está nos componentes de memória (progresso, ponto fraco, revisão), não na qualidade da explicação.
2. Aula é checklist de domínio; a leitura é meio, não fim.
3. Todo conceito novo se apoia em conceito já dominado — currículo é pilha, não lista.
4. Exercícios precisam variar para medir conceito, não forma.
5. Respostas ruins recorrentes não são fracasso: são o sinal que direciona as próximas sessões.

## Conecta com
- **Cap. 02**: os componentes são a implementação das propriedades da tutoria.
- **Cap. 04**: como esses artefatos são criados na prática (pastas de currículo, exercícios, flashcards).
- **Cap. 05**: as regras de conduta que o agente segue ao usar esses componentes.
