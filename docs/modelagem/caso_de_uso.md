# Casos de uso

## Introdução

<p align="justify">
&nbsp;&nbsp;Um documento de caso de uso é uma metodologia que descreve como o usuário realizará uma determinada tarefa dentro do contexto de um software. Ele descreve o ponto de vista do usuário e como o sistema responde a partir de suas ações, cada caso de uso é uma sequência de passos que são descritos a partir de fluxos, que começam com um objetivo principal e terminam quando esse objetivo está realizado.
</p>

## Casos de Uso

#### UC01: Sugerir oferta

|         UC01           |                                           Informações                                           |
| :--------------------: | -------------------------------------------------------------------------------------------- |
|       Descrição        | O ato do usuário sugerir uma oferta que poderá ser publica no promobit |
|          Ator(es)      | Usuário |
|   Pré-condições        | O ator deve estar logado, deve estar na seção de ofertas do promobit e deve ter o link de uma oferta |
|    Fluxo principal     | **FP01:**<br> 1. O ator clica no icone de "+" <br> 2. O promobit expõe uma tabela de opções <br> 3. O ator clica em sugerir oferta <br> 4. O promobit redireciona o ator para a seção de sugerir nova oferta <br> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br> 6. O ator coloca uma imagem da oferta no campo de imagem <br> 7. O ator clica no botão "Enviar oferta" <br> 8. O promobit gera um pop-up para o autor com o feedback do envio <br> 9. O ator clica em fechar <br> 10. O ator é redirecionado para a aba de ofertas. |
| Fluxo alternativo      | **FA01:** Fluxo de quando o ator sugeri uma oferta pela primeira vez:<br> 1. O ator clica no icone de "+" <br> 2. O promobit expõe uma tabela de opções <br> 3. O ator clica em sugerir oferta <br> 4. O promobit redireciona o ator para a seção de sugerir nova oferta <br> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br> 6. O ator coloca uma imagem da oferta no campo de imagem <br> 7. O ator clica no botão "Enviar oferta" <br> 8. O promobit gera um pop-up parabenizando o ator pela sua primeira oferta e o premia com uma medalha <br> 9. O ator clica no botão "Fechar" <br> 10. O promobit gera outro pop-up para o autor com o feedback do envio <br> 11. O ator clica em fechar <br> 12. O ator é redirecionado para a aba de ofertas. <br><br> **FA02:** Fluxo de quando o ator deseja sugerir uma oferta seguida de uma anterior <br> 1. O ator clica no icone de "+" <br> 2. O promobit expõe uma tabela de opções <br> 3. O ator clica em sugerir oferta <br> 4. O promobit redireciona o ator para a seção de sugerir nova oferta <br> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br> 6. O ator coloca uma imagem da oferta no campo de imagem <br> 7. O ator clica no botão "Enviar oferta" <br> 8. O promobit gera um pop-up para o autor com o feedback do envio <br> 9. O ator clica em "Adicionar outra" <br> 10. O ator é redirecionado para a aba de sugerir oferta.|
|   Fluxo de exceções    | **FE01:** O ator não completa os campos obrigatórios para sugerir a oferta <br> 1. O ator clica no icone de "+" <br> 2. O promobit expõe uma tabela de opções <br> 3. O ator clica em sugerir oferta <br> 4. O promobit redireciona o ator para a seção de sugerir nova oferta <br> 5. O ator não preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br> 6. O ator coloca uma imagem da oferta no campo de imagem <br> 7. O ator clica no botão "Enviar oferta" <br> 8. O promobit gera um pop-up alertando o ator sobre a necessidade de preencher o campo obrigatório <br><br> **FE02:** Ocorre a perda de conexão durante o uso do aplicativo <br> 1. O ator clica no icone de "+" <br> 2. O promobit expõe uma tabela de opções <br> 3. O ator clica em sugerir oferta <br> 4. O sistema gera um pop-up alertando sobre a impossíbilidade de realizar a ação <br> 5. O ator clica no botão "ok" |
|     Pós condições      | O ator poderá ter uma oferta publicada e o ator terá a oferta que sugeriu no seu histórico de ofertas |
|    Rastreabilidade     | Requisito Funcional 3 do documento contendo todos os requisitos - RF3 Sugerir oferta |

#### UC02: Sugerir cupom

#### UC03: Fazer tópico no forum

#### UC04: Configurações

#### UC05: Pesquisar oferta


## Referências Bibliográficas

>Use Cases, Disponível em: https://www.usability.gov/how-to-and-tools/methods/use-cases.html

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 04/10/2020 | Criação da estrutura do documento de caso de uso | Marcelo Victor |
| 2.0 | 04/10/2020 | Adição do caso de uso de sugerir oferta | Marcelo Victor |