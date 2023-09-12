<link rel="stylesheet" href="style.css" />

| **Campo** | **Tipo** | **Mandatório** | **Descrição** |
| --- | --- | --- | --- |
| baselineId | Number | Y | Numero identificativo da Baseline e que corresponde com a sua versão |
| orderEnrichmentRulesAdditionalDocumentKey | String | N | Caso seja especificado este campo, aqui terá o valor DocumentKey (campo "key" da estrutura "additionalDocument") do arquivo que contém as regras para gerar a ordem enriquecida. Caso este campo não seja definido, a ordem enriquecida será igualmente gravada na collection do MongoDB _"enrichedOrder"_, porém duplicando 100% o conteúdo da outra collection _"order"_ que contém o payload original enviado pelo client que chamou OrderOne |

@import "git.png"
