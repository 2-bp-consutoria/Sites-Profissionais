# Capítulo 08: Frota de tutores — uma universidade, muitos professores

## Ideia central
Um tutor é uma pasta; por isso a escala é trivial — você cria dezenas de tutores especializados, cada um com seu currículo, seu histórico e seu progresso, em vez de um agente genérico que tenta ensinar tudo.

## Frameworks introduzidos
- **Uma pasta = um tutor**: a unidade de organização de toda a sua universidade de bolso.
  - Quando usar: sempre que um novo domínio entrar na sua vida de estudo.
  - Como: duplique a estrutura, renomeie o tutor para o tópico (ex.: um tutor de cibersegurança, um de alemão, um de qualquer outro tema), rode o setup e siga. Renomear o título do tutor deixa claro qual agente você está abrindo.
  - Por que funciona: isolamento de contexto e de histórico. O progresso em alemão não polui a detecção de ponto fraco em cibersegurança.
- **Amplitude vs. profundidade**: dois tipos legítimos de tutor.
  - Quando usar: ao definir o recorte de um tutor novo (liga com o Cap. 04).
  - Como: **tutor de amplitude** cobre os fundamentos de um domínio inteiro; **tutor de profundidade** ataca um único subtópico de um domínio, sem nenhuma pretensão de abrangência. Escolha um dos dois por pasta — misturar os dois na mesma pasta produz o currículo raso do Cap. 04.
- **Progresso cumulativo**: cada exercício feito dentro de um agente empurra aquele domínio adiante.
  - Quando usar: como critério de escolha entre estudar dentro do tutor ou fora dele.
  - Como: estudo feito fora do tutor não entra no histórico e, portanto, não gera revisão nem detecção de ponto fraco. Conduza o estudo *através* dos tutores para que o progresso seja mantido na ponta do lápis.

## Conceitos-chave
- **Frota de tutores** — o conjunto dos seus agentes especializados, um por domínio.
- **Tutor especializado** — agente cujo currículo, histórico e materiais tratam de um único tópico.
- **Tutor de amplitude** — cobre os fundamentos de um domínio inteiro.
- **Tutor de profundidade** — cobre um recorte estreito com profundidade alta.
- **Base de conhecimento por domínio** — o acúmulo, dentro de cada pasta, do que você já domina.
- **Universidade de bolso** — a frota inteira, funcionando como uma grade curricular própria.

## Modelos mentais
- Pense em cada pasta como um professor com caderneta própria: ele só sabe da sua matéria, e é por isso que ele é bom nela.
- Você não está montando um assistente; está montando um corpo docente. A pergunta de organização não é "como faço meu agente aprender mais um assunto?", é "qual professor eu contrato para isso?".
- Estudo que não passa pelo tutor é estudo que não deixa rastro — e sem rastro não há revisão.

## Exemplo trabalhado
Como uma frota cresce na prática:

| Tutor (pasta) | Tipo | Recorte |
|---|---|---|
| `tutor-cibersegurança` | Amplitude | Fundamentos amplos, do zero |
| `tutor-alemão` | Amplitude | Idioma, do zero, 1 h/dia |
| `tutor-criptografia-aplicada` | Profundidade | Um subtópico só, sem pretensão de abranger a área |

Cada pasta tem seu próprio currículo, roadmap, exercícios resolvidos, flashcards e histórico de progresso. Abrir a pasta no agente é escolher com qual professor você vai estudar hoje.

O ganho aparece com o tempo: depois de algumas semanas, cada tutor sabe o que você esqueceu, o que você nunca articulou bem, e o que precisa voltar na próxima sessão — e essa memória é específica daquele domínio. Um agente único tentando manter isso para cinco assuntos ao mesmo tempo perde a resolução exatamente onde ela importa.

## Anti-padrões
- **Um agente genérico para todos os assuntos**: o histórico se mistura e a detecção de ponto fraco perde precisão.
- **Misturar amplitude e profundidade na mesma pasta**: produz um currículo que não é nem panorâmico nem profundo.
- **Estudar por fora e voltar ao tutor só para tirar dúvida**: você volta a ser o copiloto do Cap. 01.
- **Criar tutores demais de uma vez**: cada um exige sessões recorrentes para valer alguma coisa; a frota deve crescer conforme o tempo de dedicação real.

## Principais aprendizados
1. Tutor é pasta — criar um novo é trivial e não custa nada ao existente.
2. Isolamento por domínio é o que mantém o rastreamento de progresso preciso.
3. Escolha por pasta: amplitude ou profundidade, nunca os dois.
4. Cada exercício feito dentro do agente contribui para a base daquele domínio.
5. O valor real do tutor aparece ao longo de semanas, na revisão do que você esqueceu — não na primeira sessão.
6. A frota inteira é a sua universidade de bolso: currículos próprios, corpo docente próprio, ritmo próprio.

## Conecta com
- **Cap. 04**: o setup que cada tutor novo executa.
- **Cap. 03**: os componentes que vivem dentro de cada pasta.
- **Cap. 02**: a frota é a resposta prática ao problema econômico da tutoria individual.
