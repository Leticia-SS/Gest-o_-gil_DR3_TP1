# Exercício 5: Composição da Squad: Uma Grande x Duas Menores

## Impacto de cada composição na entrega frequente e previsível

Uma squad única de oito desenvolvedores generalistas tem mais gente, mas perde em frequência e previsibilidade: com oito pessoas em um só fluxo, a coordenação cresce, as decisões ficam mais lentas e o trabalho em qualquer parte do sistema tende a gerar dependências cruzadas e retrabalho, o que atrasa entregas pequenas. Duas squads de quatro focadas em módulos (roteirização e faturamento) tendem a entregar com mais frequência porque cada time tem escopo mais estreito, menos dependências internas e decisões mais rápidas, mas exigem coordenação entre as duas squads para não duplicar esforço nem criar interfaces conflitantes.

## Risco concreto de cada composição

Na squad grande de oito generalistas, o risco concreto para o RotaViva é o **gargalo de coordenação**: todos mexem em qualquer parte do sistema, o que aumenta o risco de conflito de código e de decisões inconsistentes entre roteirização e faturamento, justamente quando o produto precisa lançar semanalmente. Nas duas squads de quatro, o risco concreto é o **desalinhamento entre módulos**: roteirização e faturamento podem evoluir em ritmos diferentes e criar integrações quebradas (ex.: uma funcionalidade de rota que depende de um cálculo de faturamento que a outra squad ainda não entregou), o que exige sincronização explícita entre as squads.

## Recomendação

Recomendo as **duas squads menores de quatro**, focadas em roteirização e faturamento. Justificativa técnica: os princípios do Scrum Team apontam para times pequenos e autogerenciados, com escopo claro e capacidade de entregar Increment a cada Sprint (Guia Scrum 2020, seção "Scrum Team"). Times menores tomam decisões mais rápido, têm menos dependências internas e conseguem manter cadência semanal; a coordenação entre as duas squads é um custo gerenciável (ex.: sincronização de interfaces e um PO que priorize os dois backlogs de forma coerente), enquanto o gargalo de coordenação de oito generalistas é estrutural e tende a piorar com o crescimento.
