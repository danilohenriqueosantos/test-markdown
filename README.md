<h1 id="repositório-com-as-documentações-oms">Repositório com as documentações OMS</h1>
<h2 id="sobre">Sobre</h2>
<p>Este repositório contém a documentação do OMS</p>
<ul>
<li><a href="snippets/overview/index.md">OVERVIEW OMS</a></li>
<li><a href="snippets/avancado/index.md">CONFIGURAÇÕES AVANÇADAS OMS</a></li>
<li><a href="snippets/prepare-env-dev/README.md">START para começar o DEV, VM local, códigos, etc.</a></li>
<li><a href="snippets/exposed-apis/index.md">EXPOSED API’s</a></li>
<li><a href="snippets/consoles-weblogic/index.md">CONSOLES WEBLOGIC</a></li>
<li><a href="snippets/confg-envs/index.md">CONFIGURAÇÕES DE AMBIENTES</a></li>
<li><a href="snippets/data-model/index.md">2 - OMS Interface Details</a></li>
<li><a href="snippets/data-model/index.md">3 - OMS Data Model</a></li>
<li><a href="snippets/order-data-model-mapping/index.md">4 - OMS Order Data Model Mapping</a></li>
<li><a href="snippets/negotiation/index.md">5 - OMS Negotiation</a></li>
<li><a href="snippets/decomposition/index.md">6 - OMS Decomposition</a></li>
<li><a href="snippets/negotiation-pre/index.md">7 - OMS Negotiation Siebel Pre</a></li>
<li><a href="snippets/data-model/index.md">8 - OMS EPC Data Model</a></li>
<li><a href="snippets/ofp-engine/index.md">9 - OMS OFP Engine Overview</a></li>
<li><a href="snippets/sca/index.md">10 - OMS SCA</a></li>
<li><a href="snippets/gui/index.md">11 - OMS GUI</a></li>
<li><a href="snippets/aprovisionamento/aprovisionamento.md">PROVISIONAMENTO</a></li>
<li><a href="snippets/links/links.md">LINKS UTEIS</a></li>
<li><a href="snippets/tables/tables.md">TABELAS OMS</a></li>
<li><a href="snippets/downloads/OMS%20Architecture%20Diagram%20AS-IS.pdf">ARQUITETURA OMS</a></li>
<li><a href="snippets/fluxo-trabalho/index.md">FLUXO DE TRABALHO</a></li>
<li><a href="snippets/tutoriais/index.md">TUTORIAIS</a></li>
<li><a href="snippets/services_tasks/index.md">SERVICES TASKS</a></li>
<li><a href="snippets/errors-map/index.md">ERRORS MAP</a></li>
<li><a href="snippets/errors-handling/index.md">ERRORS Handling</a></li>
<li><a href="snippets/workcontext-merge/index.md">Merge WorkContext</a></li>
</ul>
<style>
.heading1 {
    color: red;
    font-weight:700;
    font-size: 35px;
}
.heading2 {
    color: blue;
    font-weight:700;
    font-size: 30px;
}
.campo {
    color: purple;
    width: 90px;
    word-break: break-word;
}
</style>
<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 40%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Campo</strong></th>
<th><strong>Tipo</strong></th>
<th><strong>Mandatório</strong></th>
<th><strong>Descrição</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>baselineId</td>
<td>Number</td>
<td>Y</td>
<td>Numero identificativo da Baseline e que corresponde com a sua versão</td>
</tr>
<tr class="even">
<td>orderEnrichmentRulesAdditionalDocumentKey {.campo}</td>
<td>String</td>
<td>N</td>
<td>Caso seja especificado este campo, aqui terá o valor DocumentKey (campo “key” da estrutura “additionalDocument”) do arquivo que contém as regras para gerar a ordem enriquecida. Caso este campo não seja definido, a ordem enriquecida será igualmente gravada na collection do MongoDB <em>“enrichedOrder”</em>, porém duplicando 100% o conteúdo da outra collection <em>“order”</em> que contém o payload original enviado pelo client que chamou OrderOne</td>
</tr>
</tbody>
</table>
<p>orderEnrichmentRulesAdditionalDocumentKey{.field .campo}</p>
<h1 class="heading1" id="identifier">Markdown heading styles</h1>
<h2 class="heading2" id="identifier2">Markdown heading styles</h2>
