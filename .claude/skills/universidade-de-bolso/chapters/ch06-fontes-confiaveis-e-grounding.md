# Capítulo 06: Ancorando o tutor em fontes confiáveis

## Ideia central
MIT, Harvard, Oxford e Stanford publicam semestres inteiros de aula de graça na internet — e você pode baixar a transcrição dessas aulas e usá-la como base do currículo do seu tutor, o que resolve na prática o medo de alucinação.

## Frameworks introduzidos
- **Grounding por transcrição**: alimentar o agente com o material da fonte antes de pedir o currículo.
  - Quando usar: quando a exatidão importa (certificação, concurso, prova específica) ou quando você não confia no conhecimento paramétrico do modelo sobre o tema.
  - Como: (1) localize o curso aberto da universidade; (2) baixe a transcrição de cada aula (arquivos `.txt` ou legendas `.srt`); (3) coloque os arquivos dentro da pasta do tutor; (4) peça explicitamente que a grade seja montada **com base nessas aulas**.
  - Por que funciona: o currículo passa a ser derivado de um material verificável, e as respostas do tutor ficam ancoradas em texto presente na pasta, não só na memória do modelo.
- **Assistir ≠ reter**: a razão de usar a aula *dentro* do tutor em vez de só assistir.
  - Quando usar: sempre que você tiver acesso a uma aula gravada boa.
  - Como: assista se quiser — mas coloque a transcrição no tutor para que alguém garanta que você vai lembrar do que foi dito. A aula entrega conteúdo; o tutor entrega retenção.
- **Curadoria de fonte pelo agente**: mesmo sem material seu, o agente busca fontes de qualidade.
  - Quando usar: no início da geração do currículo.
  - Como: o agente procura fontes reconhecidas (universidades, material acadêmico) antes de escrever a primeira aula. Você pode e deve conferir quais foram.

## Conceitos-chave
- **OCW / material aberto** — cursos completos publicados gratuitamente por grandes universidades.
- **Transcrição (.txt)** — o texto integral da aula, insumo ideal para o agente.
- **Legenda (.srt)** — mesma informação com marcação de tempo; serve igualmente como fonte.
- **Grounding** — ancorar as respostas do agente em material fornecido, em vez da memória do modelo.
- **Alucinação** — resposta inventada com aparência de correta; o risco que o grounding mitiga.
- **Biblioteca infinita** — o conjunto de material aberto disponível para montar qualquer currículo.

## Modelos mentais
- Pense na transcrição como o livro-texto da disciplina e no tutor como o professor que o conduz: o material dá autoridade, o tutor dá acompanhamento.
- Se o medo é alucinação, a resposta não é abandonar a IA — é dar a ela a fonte. O medo aponta para uma solução técnica, não para um veto.
- Uma aula gravada de uma hora é conteúdo; a mesma aula dentro de um tutor é currículo com verificação.

## Exemplo trabalhado
Montando um tutor de cibersegurança ancorado em Harvard:

1. Localize o curso aberto de cibersegurança da universidade (há vários; qualquer um serve como exemplo).
2. Em cada aula (tipicamente ~1 hora), baixe a transcrição em `.txt` — e, se disponível, a legenda `.srt`. Muitas oferecem legenda em português.
3. Salve os arquivos dentro da pasta do seu tutor.
4. Peça: *"monte a grade com base nas informações destas aulas"*.
5. O agente deriva o roadmap do material real do curso, e não de uma ideia genérica de "o que costuma ter em um curso de cibersegurança".
6. Estude com o tutor normalmente. A diferença: quando ele pergunta, a resposta esperada está ancorada em um curso que você pode auditar; quando você duvida, a fonte está na pasta.

Isso é especialmente relevante quando o objetivo é uma prova ou certificação específica: a grade precisa refletir *aquele* conteúdo, não uma média do tema.

## Anti-padrões
- **Desistir da IA por medo de alucinação**: o medo é razoável, mas a resposta é grounding, não abstinência.
- **Só assistir à aula gravada**: entrega conteúdo, não retenção — é o problema do Cap. 01 em vídeo.
- **Aceitar o currículo sem olhar as fontes**: pergunte quais fontes o agente usou; é informação disponível.
- **Misturar fontes contraditórias sem hierarquia**: se você trouxer material, deixe claro qual é a fonte canônica para prova ou certificação.

## Principais aprendizados
1. Semestres inteiros de universidades de elite estão abertos e gratuitos — use-os.
2. Transcrição `.txt` e legenda `.srt` são o formato de entrada ideal para o tutor.
3. Peça explicitamente que a grade seja montada com base no material que você forneceu.
4. Grounding é a resposta técnica ao medo de alucinação.
5. Fonte externa é obrigatória quando o alvo é uma prova ou certificação específica.
6. Isso funciona com qualquer universidade e qualquer tema, não só com o exemplo citado.

## Conecta com
- **Cap. 00**: a "biblioteca infinita" mencionada como oportunidade.
- **Cap. 04**: onde no setup entra o material trazido por você.
- **Cap. 08**: um tutor por curso/fonte quando os materiais são muito diferentes.
