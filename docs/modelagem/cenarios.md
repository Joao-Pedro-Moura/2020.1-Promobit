# Cenários

## Introdução
<p style="text-indent: 20px; text-align: justify">
É uma narrativa textual rica em detalhes contextual, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais.
<br/>Cenários são poderesos, requerem menos tempo quando comparados a modelos e protótipos complexos.
</p>

## Metodologia
Usaremos a tabela abaixo como molde para descrever os cenários.

|Numero Cenário|Nome do cenário|
|---|---|
|**Objetivo**|Objetivo do cenário, o que motiva as ações realizadas|
|**Ambiente**|A situação, o momento, o porquê e seus detalhes em que ocorre o cenário|
|**Atores**|Atores Envolvidos|
|**Planejamento**|Atividade para transformar um objetivo em um comportamento ou conjunto de ações|
|**Ação**| Comportamento observável |
|**Evento**| **Eventos que disparam:** <br /> > Quais eventos causam a necessidade de cumprir este objetivo <br /> **Eventos que são disparados:** <br /> > Quais eventos são disparados após cumprir o objetivo |
|**Avaliação**| Atividade para interpretar a situação|
|**Rastreabilidade**| Requisito(s) associados ao cenário|

## Cenários

### C01 - Sugerir oferta

|Numero Cenário|Nome do cenário|
|---|---|
|**Objetivo**| Sugerir uma oferta encontrada |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir uma oferta que ele encontrou, ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre a oferta. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir oferta <br /> - Ator entra no sistema <br /> - Ator vai até a seção de sugerir oferta <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de oferta |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação da oferta no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação da oferta pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF3 Sugerir oferta, RNF1 A oferta deverá ser segura|

## Referências Bibliográficas

>BARBOSA. Simone. SILVA. Bruno. 2010. Interação Humano-computador.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 06/10/2020 | Criação do documento de cenários e criação do C01 | Marcelo Victor e Rhuan Carlos  |