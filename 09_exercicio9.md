# Exercício 9: Definition of Done do RotaViva

## Proposta de Definition of Done

Um item do RotaViva só é considerado pronto quando atende a todos os critérios abaixo: (1) o código foi revisado por pelo menos outro Developer (code review aprovado); (2) há testes automatizados cobrindo o comportamento principal e os casos de erro do item, e eles passam na esteira de integração; (3) o item foi validado em ambiente de homologação com dados representativos de uma transportadora real; (4) a documentação mínima da funcionalidade (contrato de API e regra de negócio) foi atualizada; (5) não há defeito conhecido de severidade alta ou média em aberto no item; (6) o Product Owner validou o comportamento do item contra o critério de aceite acordado na Sprint Planning.

## Justificativa de cada critério

O critério (1) é necessário porque, sem revisão, o código entra sem segunda opinião e o retrabalho aparece depois, foi o tipo de falha que contribuiu para a funcionalidade recusada. O critério (2) é o coração do episódio: o Developer considerou pronto sem teste automatizado e o PO recusou; com o critério explícito, o teste deixa de ser opcional. O critério (3) evita o "funciona na minha máquina": validar em homologação com dados reais garante que a funcionalidade atende ao cenário do cliente. O critério (4) evita que a regra de negócio se perca e que o próximo Developer a reimplemente errado. O critério (5) impede que um item seja declarado pronto carregando defeito conhecido, o que gera retrabalho e desgaste com o cliente. O critério (6) garante que "pronto" não é só uma visão técnica: o PO confirma que o comportamento atende ao que foi acordado, fechando a lacuna que gerou a recusa.

## Como usar a Definition of Done durante a Sprint

A Definition of Done não é checklist de fim de Sprint: ela deve ser consultada na Sprint Planning, para o time só selecionar itens que consegue levar até o "pronto" completo; durante a Sprint, em cada item, para o Developer saber quando pode considerar o trabalho encerrado e para o PO saber quando pode aceitar; na Daily, para checar se algum item está perto de cumprir todos os critérios; e na Sprint Review, como régua de aceite. Assim, o "pronto" é verificado continuamente, e não descoberto na hora da recusa.
