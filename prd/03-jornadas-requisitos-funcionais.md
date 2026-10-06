# Jornadas e requisitos funcionais do FootFanatics

> **Status:** rascunho para validação das jornadas.
> **Base:** [Visão Geral](01-visao-geral.md) e [Personas](02-personas.md).
> **Escopo:** comportamento do produto, sem definir tecnologias ou arquitetura.

## 1. Objetivo

Descrever como cada persona busca atender seus objetivos no FootFanatics, distinguindo as responsabilidades conceituais da interface (front-end) e dos serviços e dados da aplicação (back-end). Os requisitos funcionais serão derivados após a validação destas jornadas.

## 2. Jornadas propostas

As jornadas abaixo são preliminares. Elas descrevem apenas o resultado desejado e o papel geral do front-end e do back-end; não definem telas, mecanismos de acesso, fontes de dados ou regras de negócio ainda não confirmadas.

### 2.1 Torcedor acompanha o próprio time

**Objetivo:** consultar o desempenho, os dados, os resultados e a posição/classificação do próprio time no campeonato.

1. O torcedor acessa no FootFanatics as informações relacionadas ao time que acompanha.
2. O front-end apresenta os dados do time, seu desempenho, os resultados de partidas e sua posição/classificação na tabela.
3. O back-end disponibiliza os dados do time e do campeonato necessários para essa consulta.

**Resultado esperado:** o torcedor consegue acompanhar a situação do próprio time no Brasileirão.

**Ponto em aberto:** como o aplicativo identifica ou permite informar o time acompanhado.

### 2.2 Investidor analisa um time

**Objetivo:** analisar o desempenho de um time no campeonato e a quantidade de acessos/interesse associada a cada time na aplicação.

1. O investidor consulta as informações de um time que considera para investimento.
2. O front-end apresenta informações de desempenho do time e a quantidade de acessos/interesse disponível para análise.
3. O back-end disponibiliza os dados de desempenho e os dados de acessos/interesse associados ao time.

**Resultado esperado:** o investidor encontra informações para analisar o time no contexto do campeonato e do interesse registrado na aplicação.

**Pontos em aberto:** definição de acesso/interesse, forma de contabilização, período considerado e indicadores de desempenho.

### 2.3 Administrador acessa recursos administrativos

**Objetivo:** acessar as funções administrativas da aplicação e o banco de dados, conforme escopo ainda a definir.

1. O administrador acessa os recursos administrativos disponíveis no FootFanatics.
2. A aplicação disponibiliza ao administrador o acesso administrativo e ao banco de dados previsto para seu papel.

**Resultado esperado:** o administrador consegue exercer as responsabilidades que forem definidas para esse perfil.

**Pontos em aberto:** funções administrativas, permissões, operações permitidas e escopo do acesso ao banco de dados. A jornada não presume acesso irrestrito nem define como a autorização será feita.

## 3. Revisão das jornadas

Esta seção deve ser validada antes da elaboração dos requisitos funcionais, para que os FRs reflitam as jornadas acordadas e não transformem pontos em aberto em decisões.

## 4. Próximos passos propostos

1. Validar ou ajustar as jornadas das três personas.
2. Derivar requisitos funcionais rastreáveis às jornadas validadas.
3. Manter como pontos em aberto as regras de negócio que ainda não foram definidas.