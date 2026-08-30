# Apostila de Concursos — Psicólogo (Método Reverso)

Gerada com a skill `apostila-concursos-reverso`. Estado: **Etapas 1 e 2 concluídas** (extração de editais + plano pedagógico). Etapas 3–6 (teoria, questões, montagem final) ainda não iniciadas.

## Editais mapeados (8 de 9 recebidos — Bariri/SP pendente)

| Edital | Cargo(s) | Banca | UF |
|---|---|---|---|
| `edital-agsus-98-2026.md` | Psicólogo | Cebraspe | DF |
| `edital-anhembi-001-2026.md` | Psicólogo | INEPAM | SP |
| `edital-embu-das-artes-001-2026.md` | Psicólogo | INEPAM | SP |
| `edital-unesp-301-2026.md` | Psicólogo (Saúde) | própria | SP |
| `edital-sao-roque-008-2026.md` | Psicólogo Adulto, Psicólogo Infantil | não informada | SP |
| `edital-sao-pedro-do-turvo-01-2026.md` | Psicólogo 20h, Psicólogo Educacional | UNIQUE | SP |
| `edital-antonio-prado-de-minas-01-2026.md` | Psicólogo | IBGP | MG |
| `edital-paiva-mg-001-2026.md` | Psicólogo da Educação | JCM Concursos | MG |

**10 cargos de psicólogo no total.** Ver `plano_pedagogico.json` para o mapa completo (matérias comuns, módulos de psicologia reaproveitáveis, distribuição de questões por edital).

## Pendências
- Bariri/SP — Edital nº 01/2026 (retificações): recebido só como link; PCI Concursos bloqueado pela política de egresso da sessão que gerou este material. Precisa reenviar o PDF.

## Próximos passos (retomar a skill a partir daqui)
1. Confirmar com o usuário: profundidade da amostra (`amostras/AMOSTRA-calibracao.md`), formato de questão por banca (nativo vs. banco único renderizado), se inclui módulo de preparação para a prova dissertativa da UNESP.
2. Gerar os módulos de maior reuso primeiro (Ética Profissional — 9 cargos; Psicopatologia, Avaliação/Psicodiagnóstico, Teorias da Personalidade, Desenvolvimento — 6+ cargos cada).
3. Seguir Etapas 3–6 do skill `apostila-concursos-reverso` normalmente.

## Nota de extração
Os editais de Anhembi, Embu das Artes, São Roque, São Pedro do Turvo e Antônio Prado de Minas foram extraídos com `pdftotext -layout` (poppler-utils). O da AgSUS usou `pypdf`. O da UNESP tinha a camada de texto corrompida (fontes Type 3 malformadas) e foi lido por renderização visual das páginas.
