Repositório com as documentações OMS
====================================

Sobre
-----

Este repositório contém a documentação do OMS

-   [OVERVIEW OMS](snippets/overview/index.md)
-   [CONFIGURAÇÕES AVANÇADAS OMS](snippets/avancado/index.md)
-   [START para começar o DEV, VM local, códigos,
    etc.](snippets/prepare-env-dev/README.md)
-   [EXPOSED API's](snippets/exposed-apis/index.md)
-   [CONSOLES WEBLOGIC](snippets/consoles-weblogic/index.md)
-   [CONFIGURAÇÕES DE AMBIENTES](snippets/confg-envs/index.md)
-   [2 - OMS Interface Details](snippets/data-model/index.md)
-   [3 - OMS Data Model](snippets/data-model/index.md)
-   [4 - OMS Order Data Model
    Mapping](snippets/order-data-model-mapping/index.md)
-   [5 - OMS Negotiation](snippets/negotiation/index.md)
-   [6 - OMS Decomposition](snippets/decomposition/index.md)
-   [7 - OMS Negotiation Siebel Pre](snippets/negotiation-pre/index.md)
-   [8 - OMS EPC Data Model](snippets/data-model/index.md)
-   [9 - OMS OFP Engine Overview](snippets/ofp-engine/index.md)
-   [10 - OMS SCA](snippets/sca/index.md)
-   [11 - OMS GUI](snippets/gui/index.md)
-   [PROVISIONAMENTO](snippets/aprovisionamento/aprovisionamento.md)
-   [LINKS UTEIS](snippets/links/links.md)
-   [TABELAS OMS](snippets/tables/tables.md)
-   [ARQUITETURA
    OMS](snippets/downloads/OMS%20Architecture%20Diagram%20AS-IS.pdf)
-   [FLUXO DE TRABALHO](snippets/fluxo-trabalho/index.md)
-   [TUTORIAIS](snippets/tutoriais/index.md)
-   [SERVICES TASKS](snippets/services_tasks/index.md)
-   [ERRORS MAP](snippets/errors-map/index.md)
-   [ERRORS Handling](snippets/errors-handling/index.md)
-   [Merge WorkContext](snippets/workcontext-merge/index.md)

  -------------------------------------------------------------------------------------------------------
  **Campo**                                   **Tipo**          **Mandatório**    **Descrição**
  ------------------------------------------- ----------------- ----------------- -----------------------
  baselineId                                  Number            Y                 Numero identificativo
                                                                                  da Baseline e que
                                                                                  corresponde com a sua
                                                                                  versão

  orderEnrichmentRulesAdditionalDocumentKey   String            N                 Caso seja especificado
                                                                                  este campo, aqui terá o
                                                                                  valor DocumentKey
                                                                                  (campo "key" da
                                                                                  estrutura
                                                                                  "additionalDocument")
                                                                                  do arquivo que contém
                                                                                  as regras para gerar a
                                                                                  ordem enriquecida. Caso
                                                                                  este campo não seja
                                                                                  definido, a ordem
                                                                                  enriquecida será
                                                                                  igualmente gravada na
                                                                                  collection do MongoDB
                                                                                  *"enrichedOrder"*,
                                                                                  porém duplicando 100% o
                                                                                  conteúdo da outra
                                                                                  collection *"order"*
                                                                                  que contém o payload
                                                                                  original enviado pelo
                                                                                  client que chamou
                                                                                  OrderOne
  -------------------------------------------------------------------------------------------------------

Markdown heading styles {#identifier .heading1}
=======================

Markdown heading styles {#identifier2 .heading2}
-----------------------
