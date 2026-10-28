# Exercício 8: Product Backlog, Sprint Backlog e Increment

## Distinção por finalidade e responsável

O **Product Backlog** é a lista ordenada de tudo o que pode ser feito no produto; é a fonte única de trabalho e sua finalidade é orientar o que gera valor, sendo mantido pelo **Product Owner**. O **Sprint Backlog** é o subconjunto do Product Backlog selecionado para a Sprint mais o plano de como entregá-lo; sua finalidade é orientar o trabalho diário do time rumo à meta da Sprint, e é mantido pelos **Developers**. O **Increment** é a soma do que foi entregue na Sprint e nas anteriores, em estado utilizável e atendendo à Definition of Done; sua finalidade é ser o resultado concreto e potencialmente entregável, e é construído pelos **Developers**, com o PO responsável por aceitá-lo (Guia Scrum 2020, seção "Artefatos Scrum").

## Por que a ausência de critério compartilhado de "pronto" gera confusão

No episódio da funcionalidade recusada, o Developer considerou o item pronto porque, para ele, "funcionar" bastava; o PO recusou porque faltava teste automatizado. O problema não foi má-fé de nenhum dos dois: foi a ausência de uma Definition of Done compartilhada, que é o critério objetivo de "pronto" acordado pelo time (Guia Scrum 2020, seção "Definition of Done"). Sem esse critério, cada um usa sua própria régua, o Developer mede por funcionalidade visível, o PO mede por qualidade percebida, e a divergência só aparece no fim, gerando retrabalho e desgaste. Com uma Definition of Done explícita, o teste automatizado estaria no critério desde o início, e o Developer saberia que o item não está pronto antes de apresentá-lo ao PO.

## Quadro: artefato, responsável e momento de consulta

| Artefato | Papel responsável por mantê-lo | Momento do Sprint em que é mais consultado |
|---|---|---|
| Product Backlog | Product Owner | No refinamento e na Sprint Planning (para escolher o que entra) e na Sprint Review (para adaptar prioridades) |
| Sprint Backlog | Developers | Diariamente, na Daily Scrum, para inspecionar progresso rumo à meta e ajustar o plano |
| Increment | Developers (construção) / PO (aceite) | Ao final da Sprint, na Sprint Review, para inspeção com os stakeholders; e sempre que um item atinge a Definition of Done |
