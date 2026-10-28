# Exercício 6: Primeira Sprint Planning do RotaViva

## Propósito e duração recomendada de cada evento

A **Sprint Planning** define o que pode ser entregue na Sprint e como o trabalho será feito; é o evento que abre a Sprint. Duração recomendada: até 8 horas para uma Sprint de um mês; para Sprints de duas semanas, proporcionalmente menor (cerca de 4 horas). O **Daily Scrum** sincroniza o time e inspeciona o progresso rumo à meta, ajustando o Sprint Backlog; duração fixa de 15 minutos, todos os dias. A **Sprint Review** inspeciona o Increment com os stakeholders e adapta o Product Backlog; duração de até 4 horas para Sprint de um mês (proporcionalmente menor para duas semanas). A **Sprint Retrospective** inspeciona o processo e o time, identificando melhorias; duração de até 3 horas para Sprint de um mês (proporcionalmente menor para duas semanas). (Guia Scrum 2020, seção "Eventos Scrum".)

## Itens hipotéticos do Product Backlog

1. **PB-01**: Cadastro de transportadora com parâmetros de rota (origem, destino, janela de entrega).
2. **PB-02**: Cálculo de rota otimizada com base em distância e tempo.
3. **PB-03**: Simulação de custo da rota antes da confirmação.
4. **PB-04**: Painel de acompanhamento de entregas do dia.
5. **PB-05**: Exportação de relatório de rotas em PDF.

## Meta de Sprint

**Meta:** "Permitir que o gestor da transportadora cadastre uma rota com janela de entrega e veja o custo estimado antes de confirmar." A meta dá sentido ao conjunto: o cliente consegue, ao fim da Sprint, fazer o fluxo mínimo de cadastrar e simular uma rota com custo.

## Itens selecionados e justificativa

Entram na Sprint: **PB-01, PB-02 e PB-03**. O PB-01 é pré-requisito de tudo (sem transportadora cadastrada não há rota). O PB-02 é o núcleo da meta (cálculo da rota). O PB-03 é o que fecha a meta (custo estimado antes de confirmar). Ficam de fora o **PB-04** e o **PB-05**, porque não contribuem para a meta desta Sprint: o painel de acompanhamento e a exportação em PDF são valor para depois que o fluxo de cadastro e simulação estiver funcionando. A seleção segue a meta, não a ordem do backlog.

## Transcrição da Sprint Planning simulada

**PO:** "A meta desta Sprint é permitir que o gestor cadastre uma rota com janela de entrega e veja o custo estimado antes de confirmar. Temos cinco itens no backlog; o que cabe em duas semanas?"

**Developer 1:** "O PB-01 é pré-requisito. Sem cadastro de transportadora, nada funciona. Eu pego."

**Developer 2:** "O PB-02 depende do PB-01. Posso começar a modelar o cálculo de rota enquanto o PB-01 não está pronto, mas só integro depois."

**Developer 3:** "O PB-03 depende do PB-02. Se o cálculo estiver pronto até a metade da Sprint, consigo entregar a simulação de custo."

**SM:** "E o PB-04 e o PB-05? Alguém vê relação com a meta?"

**PO:** "Não. O PB-04 é painel de acompanhamento e o PB-05 é exportação; nenhum dos dois é necessário para cadastrar e simular. Deixamos para a próxima Sprint."

**Developer 1:** "Concordo. Se sobrar tempo, a gente puxa o PB-04, mas a meta é PB-01, PB-02 e PB-03."

**SM:** "Então a Sprint tem PB-01, PB-02 e PB-03, com a meta de cadastrar e simular rota com custo. Alguém vê impedimento para começar?"

**Developer 2:** "Preciso do schema de parâmetros de rota definido antes de modelar o cálculo; se o PB-01 definir isso na primeira metade, consigo."

**PO:** "Combinado: o PB-01 define o schema até a metade da Sprint e o PB-02 integra depois. Fechado."
