# Exercício 7: Daily Scrum orientada a impedimentos e meta

## Roteiro da Daily Scrum para o RotaViva

A Daily é uma reunião de 15 minutos, no mesmo horário e lugar, para os Developers inspecionarem o progresso rumo à meta da Sprint e adaptarem o Sprint Backlog (Guia Scrum 2020, seção "Daily Scrum"). O roteiro é: (1) o facilitador abre lembrando a meta da Sprint; (2) cada Developer responde, em no máximo 2 minutos, a três perguntas orientadas a impedimento e meta, "o que fiz ontem que aproximou o time da meta?", "o que farei hoje para aproximar o time da meta?" e "há algum impedimento que me bloqueia ou bloqueia outra pessoa?"; (3) o facilitador anota impedimentos em um quadro visível; (4) ao final, os impedimentos são atribuídos a quem vai resolvê-los, com prazo, e o time confirma se o progresso está compatível com a meta; (5) se um impedimento exigir ação fora da Daily, o responsável o leva para fora da reunião e reporta na próxima. O foco é sincronizar e destravar, não narrar tarefas.

## Transcrição da Daily simulada

**SM (facilitador):** "Bom dia. Meta da Sprint: permitir que o gestor cadastre rota com janela de entrega e veja custo estimado. Vamos direto: o que aproximou da meta ontem, o que farei hoje e o que está travando."

**Developer 1:** "Ontem terminei o schema de parâmetros de rota do PB-01, o que destrava o cálculo. Hoje integro o cadastro com o schema e começo os testes. Sem impedimento."

**Developer 2:** "Ontem modelei o cálculo de rota do PB-02 usando o schema provisório. Hoje integro com o schema final do Developer 1 e valido o tempo por trecho. **Tenho um impedimento:** a API externa de mapas que uso para distância está retornando erro 429 (limite de requisições), e isso bloqueia a validação do cálculo. Preciso que alguém fale com o fornecedor ou libere uma chave adicional."

**Developer 3:** "Ontem preparei a tela de simulação de custo do PB-03, mas ela depende do cálculo do PB-02. Hoje adianto os testes de contrato da simulação e espero a integração. Sem impedimento próprio, mas fico bloqueado se o PB-02 atrasar."

**SM:** "Impedimento do Developer 2: erro 429 na API de mapas. Vou acionar o fornecedor hoje e pedir a chave adicional; levo para fora da Daily e reporto amanhã. Developer 3, você consegue avançar nos testes de contrato enquanto o PB-02 não integra? Se sim, seguimos dentro da meta. Alguém mais travado?"

**Developer 1:** "Não. Se o schema está fechado, consigo entregar o PB-01 até amanhã."

**SM:** "Fechado: impedimento da API comigo, Developer 3 nos testes de contrato, Developer 1 no PB-01. Progresso compatível com a meta. Encerramos em 12 minutos."

## O que muda em relação ao formato antigo

No formato antigo (vinte minutos, cada um narrando tudo o que fez), a Daily virava relatório individual, sem foco em impedimento nem em meta, e o tempo estourava. No roteiro novo, a reunião começa e termina ancorada na meta da Sprint, cada fala é filtrada por "isso aproxima da meta?", os impedimentos são explicitados, registrados e atribuídos com responsável e prazo, e o que exige ação externa sai da reunião com dono — não fica só na narrativa. O tempo cai para até 15 minutos porque o relato detalhado de tarefas é substituído por sincronização e destravamento.
