# Gala Tríade 2026 — Avaliação de Funcionários CLTs

Formulário web anônimo (celular-first) para avaliação interna dos funcionários CLTs da
Triade Espaço Terapêutico — **sistema separado da avaliação entre terapeutas PJ**
(repositório `gala-triade-avaliacao`).

- **Página:** https://paulocentroga-ship-it.github.io/gala-triade-avaliacao-clt/
- **Link personalizado:** adicione `?avaliado=Nome%20Completo` à URL — o nome fica
  pré-preenchido e travado (avaliação direcionada).
- **Período avaliado:** 01/01/2026 a 30/11/2026.
- **Escala:** 1 (insuficiente) a 5 (excelente) + NA (peso redistribuído no bloco).
- **Nota final 0–100** = Σ(média do bloco × 20 × peso do bloco).
  A = 40% · B = 30% · C = 20% · D = 10%.
- **Cortes:** ≥85 = Indicado à Gala · 70–84,9 = Desempenho Adequado · <70 = PDI.

Blocos e critérios (16):
- **A — Qualidade Técnica e Entrega (40%)**: A1 Rigor e Conformidade Técnica ·
  A2 Cumprimento de Prazos · A3 Consistência da Documentação ·
  A4 Precisão e Acurácia Operacional.
- **B — Colaboração e Interdisciplinaridade (30%)**: B1 Cooperação Multidisciplinar ·
  B2 Comunicação Intersetorial · B3 Participação Técnica ·
  B4 Clima Organizacional e Suporte Mútuo.
- **C — Acolhimento e Relacionamento (20%)**: C1 Conduta Ética e Sigilo ·
  C2 Vínculo e Acolhimento · C3 Empatia e Manejo de Crises ·
  C4 Clareza e Transparência na Comunicação.
- **D — Comprometimento e Conduta Funcional (10%)**: D1 Assiduidade e Pontualidade ·
  D2 Observância aos Procedimentos Internos · D3 Proatividade e Responsabilidade ·
  D4 Estabilidade e Profissionalismo.

As respostas vão para o webhook do assistente e são consolidadas na planilha
"**Gala Tríade 2026 — Respostas CLT**" (Google Sheets).
