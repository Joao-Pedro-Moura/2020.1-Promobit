# Casos de uso

## Introdução

<p style="text-indent: 20px; text-align: justify">
Um documento de caso de uso é uma metodologia que descreve como o usuário realizará uma determinada tarefa dentro do contexto de um software. Ele descreve o ponto de vista do usuário e como o sistema responde a partir de suas ações, cada caso de uso é uma sequência de passos que são descritos a partir de fluxos, que começam com um objetivo principal e terminam quando esse objetivo está realizado.
</p>

## Casos de Uso

#### UC01: Sugerir oferta

![Sugerir cupom](../assets/casos_de_uso/sugerir_oferta.png)

<a target="_blank" href="https://drive.google.com/file/d/1dwBC5pR36BVoyWM6lZ7Mv37wBde9F1Hf/view?usp=sharing">Link para o diagrama acima</a>


|         UC01           |                                           Informações                                           |
| :--------------------: | -------------------------------------------------------------------------------------------- |
|       Descrição        | O ato do usuário sugerir uma oferta que poderá ser publica no sistema |
|          Ator(es)      | Usuário |
|   Pré-condições        | O ator deve estar logado, deve estar na seção de ofertas do sistema e deve ter o link de uma oferta |
|    Fluxo principal     | **FP01:**<br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma tabela de opções <br /> 3. O ator clica em sugerir oferta <br /> 4. O sistema redireciona o ator para a seção de sugerir nova oferta <br /> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br /> 6. O ator coloca uma imagem da oferta no campo de imagem <br /> 7. O ator clica no botão "Enviar oferta" <br /> 8. O sistema gera um pop-up para o autor com o feedback do envio <br /> 9. O ator clica em fechar <br /> 10. O ator é redirecionado para a aba de ofertas. |
| Fluxo alternativo      | **FA01:** Fluxo de quando o ator sugeri uma oferta pela primeira vez:<br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma tabela de opções <br /> 3. O ator clica em sugerir oferta <br /> 4. O sistema redireciona o ator para a seção de sugerir nova oferta <br /> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br /> 6. O ator coloca uma imagem da oferta no campo de imagem <br /> 7. O ator clica no botão "Enviar oferta" <br /> 8. O sistema gera um pop-up parabenizando o ator pela sua primeira oferta e o premia com uma medalha <br /> 9. O ator clica no botão "Fechar" <br /> 10. O sistema gera outro pop-up para o autor com o feedback do envio <br /> 11. O ator clica em fechar <br /> 12. O ator é redirecionado para a aba de ofertas. <br /><br /> **FA02:** Fluxo de quando o ator deseja sugerir uma oferta seguida de uma anterior <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma tabela de opções <br /> 3. O ator clica em sugerir oferta <br /> 4. O sistema redireciona o ator para a seção de sugerir nova oferta <br /> 5. O ator preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br /> 6. O ator coloca uma imagem da oferta no campo de imagem <br /> 7. O ator clica no botão "Enviar oferta" <br /> 8. O sistema gera um pop-up para o autor com o feedback do envio <br /> 9. O ator clica em "Adicionar outra" <br /> 10. O ator é redirecionado para a aba de sugerir oferta.|
|   Fluxo de exceções    | **FE01:** O ator não completa os campos obrigatórios para sugerir a oferta <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma tabela de opções <br /> 3. O ator clica em sugerir oferta <br /> 4. O sistema redireciona o ator para a seção de sugerir nova oferta <br /> 5. O ator não preenche os campos de "Link da oferta", "Titulo da oferta", "Preço" <br /> 6. O ator coloca uma imagem da oferta no campo de imagem <br /> 7. O ator clica no botão "Enviar oferta" <br /> 8. O sistema gera um pop-up alertando o ator sobre a necessidade de preencher o campo obrigatório <br /><br /> **FE02:** Ocorre a perda de conexão durante o uso do aplicativo <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma tabela de opções <br /> 3. O ator clica em sugerir oferta <br /> 4. O sistema gera um pop-up alertando sobre a impossíbilidade de realizar a ação <br /> 5. O ator clica no botão "ok" |
|     Pós condições      | O ator poderá ter uma oferta publicada, também terá a validação do oferta e o ator terá a oferta que sugeriu no seu histórico de ofertas |
|    Rastreabilidade     | Requisito Funcional 3 do documento contendo todos os requisitos - RF3 Sugerir oferta |

#### UC02: Sugerir cupom

![Sugerir cupom](../assets/casos_de_uso/sugerir_cupom.png)

<a target="_blank" href="https://drive.google.com/file/d/1zAUoT6XMh90Hab5c4NDPnkKojwSVqCsD/view?usp=sharing">Link para o diagrama acima</a>

|         UC01           |                                           Informações                                           |
| :--------------------: | -------------------------------------------------------------------------------------------- |
|       Descrição        | O ato do usuário sugerir um cupom que poderá ser publicado no sistema |
|          Ator(es)      | Usuário |
|   Pré-condições        | O ator deve estar logado, deve estar na seção de "últimos cupons" e "cupons por loja" do sistema e deve ter o link e as informações de um cupom |
|    Fluxo principal     | **FP01:**<br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma lista de opções <br /> 3. O ator clica em sugerir cupom <br /> 4. O sistema redireciona o ator para a seção de sugerir um novo cupom <br /> 5. O ator preenche os campos de "Link da cupom", "Descreva o cupom", "Loja", "Código do cupom", "Regras de aplicação" <br /> 7. O ator clica no botão "Enviar cupom" <br /> 8. O sistema gera um pop-up para o autor com o feedback do envio <br /> 9. O ator clica em fechar <br /> 10. O ator é redirecionado para a aba de cupons. |
| Fluxo alternativo      | **FA01:** Fluxo de quando o ator deseja sugerir um cupom seguido de um anterior <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma lista de opções <br /> 3. O ator clica em sugerir cupom <br /> 4. O sistema redireciona o ator para a seção de sugerir um novo cupom <br /> 5. O ator preenche os campos de "Link da cupom", "Descreva o cupom", "Loja", "Código do cupom", "Regras de aplicação" <br /> 7. O ator clica no botão "Enviar cupom" <br /> 8. O sistema gera um pop-up para o autor com o feedback do envio <br /> 9. O ator clica em "Adicionar outra" <br /> <br /> 10. O ator é redirecionado para a aba de cupons. |
|   Fluxo de exceções    | **FE01:** O ator não completa os campos obrigatórios para sugerir o cupom <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma lista de opções <br /> 3. O ator clica em sugerir cupom <br /> 4. O sistema redireciona o ator para a seção de sugerir um novo cupom <br /> 5. O ator preenche os campos de "Link da cupom", "Descreva o cupom", "Loja", "Código do cupom", "Regras de aplicação" <br /> 7. O ator clica no botão "Enviar cupom" <br /> 8. O sistema gera um pop-up alertando o ator sobre a necessidade de preencher o campo obrigatório <br /><br /> **FE02:** Ocorre a perda de conexão durante o uso do aplicativo <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema expõe uma lista de opções <br /> 3. O ator clica em sugerir cupom <br /> 4. O sistema gera um pop-up alertando sobre a impossibilidade de realizar a ação <br /> 5. O ator clica no botão "ok" |
|     Pós condições      | O ator poderá ter um cupom publicado, caso esse seja válido, e o ator terá o cupom que sugeriu no seu histórico de cupons |
|    Rastreabilidade     | Requisito Funcional 4 do documento contendo todos os requisitos - RF4 Sugerir cupom |

#### UC03: Sugerir tópico no forum
![Pesquisar oferta](../assets/casos_de_uso/sugerir_topico_forum.png)

<a target="_blank" href="https://drive.google.com/file/d/1-XXfg-auieUWLq4-1gGUXKMaHHq1MWju/view?usp=sharing">Link para o diagrama acima</a>

|         UC03           |                                           Informações                                           |
| :--------------------: | -------------------------------------------------------------------------------------------- |
|       Descrição        | O ato do usuário sugerir uma oferta que poderá ser publica no sistema |
|       Ator(es)         | Usuário, moderador |
|      Pré-condições     | O ator deve estar logado, e deve estar na seção de fórum do sistema. |
|    Fluxo principal     | **FP01:** <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema redireciona o ator para a seção de novo tópico no fórum <br /> 3. O ator preenche os campos de "Título do fórum", "Categoria do fórum" e "Descrição do tópico" <br /> 4. O ator clica no botão "Enviar tópico" <br /> 5. O sistema gera um pop-up para o autor com o feedback do envio <br /> 6. O ator clica em fechar <br /> 7. O ator é redirecionado para a aba de fórum. |
| Fluxo alternativo      | **FA01:** 1. O ator clica no icone de "+" <br /> 2. O sistema redireciona o ator para a seção de novo tópico no fórum <br /> 3. O ator preenche os campos de "Título do fórum", "Categoria do fórum" e "Descrição do tópico" <br /> 4. O ator clica no botão "Enviar tópico" <br /> 5. O sistema gera um pop-up para o autor com o feedback do envio <br /> 6. O ator clica em "Adicionar outra" <br /> 7. O ator é redirecionado para a aba de sugerir oferta.|
|   Fluxo de exceções    | **FE01:** <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema redireciona o ator para a seção de novo tópico no fórum <br /> 3. O ator não preenche um dos campos de "Título do fórum", "Categoria do fórum" ou "Descrição do tópico" <br /> 4. O ator clica no botão "Enviar tópico" <br /> 5. O sistema alerta o autor sobre a necessidade de inserção de informações do campo obrigatório não preenchido. <br /><br /> **FE02:** <br /> 1. O ator clica no icone de "+" <br /> 2. O sistema redireciona o ator para a seção de novo tópico no fórum <br /> 3. O ator não preenche um dos campos de "Título do fórum", "Categoria do fórum" ou "Descrição do tópico" <br /> 4. O ator clica no botão "Enviar tópico" <br /> 4. O sistema gera um pop-up alertando sobre a impossíbilidade de realizar a ação <br /> 5. O ator clica no botão "ok" |
|     Pós condições      | O ator poderá ter um tópico publicado no fórum caso ele seja aprovado e o ator terá o tópico sugerido em seu histórico de tópicos no fórum |
|    Rastreabilidade     | Requisito Funcional 10 do documento contendo todos os requisitos - RF10 Cadastrar tópico no fórum |

#### UC04: Configurações
|         UC04           | Informações |
| :---------: |----------- |
|       Descrição        | O ato do usuário configurar o sistema |
|          Ator(es)      | Usuário |
|   Pré-condições        | O ator deve estar logado |
|    Fluxo principal     | |
|  Fluxo alternativo     | |
|   Fluxo de exceções    | |
|     Pós condições      | O ator poderá ter o sistema configurado como ele quiser |
|    Rastreabilidade     | |

#### UC05: Pesquisar oferta
![Pesquisar oferta](../assets/casos_de_uso/pesquisar_oferta.png)

<a target="_blank" href="https://drive.google.com/file/d/1f86K51EvlZQsOZ11wir1Y0Vo_DeTyA4B/view?usp=sharing">Link para o diagrama acima</a>

|         UC05           | Informações |
| :---------: |----------- |
|       Descrição        | O ato do usuário pesquisar uma oferta no sistema |
|          Ator(es)      | Usuário |
|   Pré-condições        | O ator deve estar logado, deve estar na seção de ofertas do sistema além de saber o que procura |
|    Fluxo principal     | **FP01:**<br /> 1. O ator clica no icone de :mag: <br /> 2. O sistema expõe uma tabela de busca <br /> 3. O ator clica na caixa de pesquisa <br /> 4. O ator digita a oferta que procura <br /> 5. O ator seleciona a aba ofertas <br /> 6. O sistema lista as ofertas que correspondem à busca|
| Fluxo alternativo      | **FA01:** Fluxo de quando o ator pesquisou recentemente um produto:<br /> 1. O ator clica no icone de :mag: <br /> 2. O ator clica no nome do produto buscado recentemente <br /> 3. O ator seleciona a aba ofertas <br /> 4. O sistema lista as ofertas que correspondem à busca <br /> <br /> **FA02:** Fluxo de quando o ator prefere buscar um produto dentre os mais buscados:<br /> 1. O ator clica no icone de :mag: <br /> 2. O ator clica no nome do produto listado na seção "Produtos mais buscados" <br /> 3. O ator seleciona a aba ofertas <br /> 4. O sistema lista as ofertas que correspondem à busca|
|   Fluxo de exceções    | **FE02:** Ocorre a perda de conexão durante o uso do aplicativo <br /> 1. O ator clica no icone de :mag: <br /> 2. O sistema expõe uma tabela de busca <br /> 3. O ator clica na caixa de pesquisa <br /> 4. O ator digita a oferta que procura <br />  5. O ator seleciona a aba ofertas <br /> 6. O sistema não lista as ofertas que correspondem à busca |
|     Pós condições      | O ator poderá ter encontrado uma oferta publicada e do produto desejado |
|    Rastreabilidade     | Requisito Funcional 7 do documento contendo todos os requisitos - RF7 Pesquisar oferta |


## Referências Bibliográficas

>Use Cases, Disponível em: https://www.usability.gov/how-to-and-tools/methods/use-cases.html

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 04/10/2020 | Criação da estrutura do documento de caso de uso | Marcelo Victor |
| 2.0 | 04/10/2020 | Adição do caso de uso de sugerir oferta | Marcelo Victor |
| 2.1 | 06/10/2020 | Correção tags HTML | Igor Paiva |
| 3.0 | 06/10/2020 | Adição do caso de uso de pesquisar oferta | Rhuan Carlos |
| 3.1 | 06/10/2020 | Correção geral no caso de uso pesquisar oferta | Rhuan Carlos |
| 4.0 | 06/10/2020 | Adição da tabela de caso de uso configurações | Rhuan Carlos |
| 5.0 | 06/10/2020 | Adição caso de uso de sugerir cupom | Igor Paiva |
| 5.0.1 | 06/10/2020 | Correções leves | Rhuan Carlos |
| 5.1.0 | 06/10/2020 | Adição do diagrama de caso de uso 4 | Rhuan Carlos |
| 6.0.0 | 06/10/2020 | Adição do caso de uso de sugerir tópico no fórum | Thiago Lopes |
| 6.1.0 | 06/10/2020 | Adição da tabela de caso de uso de sugerir oferta| Marcelo Victor |
