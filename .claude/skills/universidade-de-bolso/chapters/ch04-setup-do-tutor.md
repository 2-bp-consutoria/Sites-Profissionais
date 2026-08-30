# Capítulo 04: Setup — montando seu tutor do zero

## Ideia central
O setup não é burocracia: as respostas que você dá nele (objetivo, nível, tempo disponível) são os parâmetros que determinam o currículo inteiro — e as integrações que você aceita determinam de quais mídias o tutor será capaz.

## Frameworks introduzidos
- **As quatro perguntas do setup**: o que o agente precisa saber antes de gerar qualquer aula.
  - Quando usar: na criação de todo tutor novo.
  - Como:
    1. **O que você quer aprender** — o domínio.
    2. **Recorte do objetivo** — domínios amplos precisam de foco (ex.: "cibersegurança" → "fundamentos amplos primeiro" vs. um subtema específico).
    3. **Nivelamento** — o que você já sabe e o que nunca estudou; declarar "começando do zero" é uma resposta legítima e faz o agente começar pelo fundamento.
    4. **Tempo de dedicação** — 1 h/dia, 10 h/dia ou 1 h/semana. Define o quão longe você chega, em quanto tempo, e como o programa é fatiado.
- **Recorte antes de currículo**: um tema amplo demais não gera um bom plano.
  - Quando usar: sempre que o domínio pedido couber em uma prateleira inteira de livraria.
  - Como: o agente devolve opções de recorte; você escolhe a pertinente ou digita a sua. Opções diferentes podem aparecer para a mesma entrada — isso é comportamento esperado do modelo, não erro.
  - Modo de falha: aceitar um currículo genérico de um tema gigante produz superficialidade em tudo e domínio em nada.
- **Agente que se instala sozinho**: o setup também cuida das ferramentas.
  - Quando usar: na primeira execução.
  - Como: o agente instala o que precisa e conecta as integrações (ex.: NotebookLM, autenticado com sua conta). Sem essas integrações ele funciona, mas com limitação de recursos — perde geração de vídeo, imagem e podcast.

## Conceitos-chave
- **Nivelamento** — diagnóstico inicial do que o aluno já domina, que define onde o currículo começa.
- **Recorte de objetivo** — estreitamento de um domínio amplo até algo que cabe em um currículo.
- **Tempo de dedicação** — orçamento declarado de horas, que define profundidade e ritmo.
- **Integração de mídia** — ferramenta externa conectada ao agente para gerar áudio, imagem e vídeo.
- **Pasta do tutor** — o diretório que *é* o tutor: currículo, aulas, exercícios, flashcards e progresso vivem nele.

## Modelos mentais
- Pense no setup como configuração de compilador: as mesmas fontes geram programas diferentes conforme os parâmetros. Objetivo, nível e tempo não são formalidade — são os parâmetros.
- Pense em cada pasta como um tutor: criar um tutor novo é criar uma pasta nova, não reconfigurar o antigo (ver Cap. 08).
- Declarar menos conhecimento do que você tem é barato; declarar mais é caro. Na dúvida, comece mais embaixo — o currículo acelera sozinho quando você acerta tudo.

## Exemplo trabalhado
Setup completo, do zero, para cibersegurança:

1. **Abrir a pasta do tutor no agente.** Qualquer ambiente serve — Claude Code no terminal ou no desktop, VS Code, Cursor, outros agentes. O que importa é que o agente esteja apontado para a pasta certa.
2. **Rodar `/setup`.** O agente conduz o passo a passo e instala/conecta o que falta.
3. **Aceitar as integrações de mídia.** Login e autenticação de dois fatores na conta a ser usada; o agente detecta a confirmação e segue. Pular isso limita o tutor a texto.
4. **"O que você quer aprender?"** → *cibersegurança*.
5. **Recorte.** O agente aponta que o tema é abrangente demais e oferece caminhos; escolha: *fundamentos amplos primeiro*.
6. **Nivelamento.** → *começando do zero*.
7. **Tempo.** → *1 hora por dia*.
8. **Geração.** O agente busca fontes confiáveis, monta o roadmap e começa a produzir as aulas em sequência (Aula 00, 01, 02...) até fechar o currículo.

Resultado observável na pasta: currículo, roadmap, aulas, e — conforme o estudo avança — exercícios resolvidos, flashcards e revisões.

## Anti-padrões
- **Pular as integrações "para agilizar"**: o tutor perde justamente as mídias que aceleram a compreensão (Cap. 07).
- **Responder o tema amplo e aceitar o primeiro currículo**: gera um plano raso; o recorte é a etapa que mais muda a qualidade do resultado.
- **Inflar o nivelamento**: pular fundamentos por vaidade cria a dívida conceitual que o Cap. 03 descreve.
- **Declarar um tempo de dedicação irreal**: o programa é dimensionado por esse número; superestimar produz um plano que você abandona na segunda semana.

## Principais aprendizados
1. Objetivo, recorte, nível e tempo são os quatro parâmetros que geram o currículo — trate-os com cuidado.
2. Tema amplo exige recorte antes de virar plano.
3. Começar do zero é uma escolha estratégica, não uma confissão.
4. As integrações de mídia fazem parte da qualidade final do agente, não são enfeite.
5. O tutor é a pasta: abrir a pasta certa no agente é o passo zero de toda sessão.

## Conecta com
- **Cap. 03**: os artefatos que o setup passa a gerar.
- **Cap. 06**: como alimentar o currículo com fontes universitárias antes ou depois do setup.
- **Cap. 08**: por que cada tutor merece a própria pasta.
