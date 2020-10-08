# MoSCoW

## Introdução

<p style="text-indent: 20px; text-align: justify">
MoSCoW é uma técnica que busca priorizar os requisitos a partir de escalas, tendo como vantagem sua simplicidade quando comparada com outras técnicas, possibilitanto priorizar cada requisito elicitado para o projeto. O MoSCoW classifica os requisitos em 4 escalas:
</p>

- **Must**: o requisito deve ser satisfeito para que a solução seja considerada um sucesso.
- **Should**: o requisito é importante e deve ser incluído na solução se possível, mas não é obrigatório para o sucesso.
- **Could**: é um requisito desejado, mas um que pode ser satisfeito ou eliminado. Deve ser implementado apenas se houver tempo e recurso.
- **Won't**: é um requisito que não será implementado, mas pode ser incluída em uma futura *release* ou nem ser implementada.

## Motivo da escolha

<p style="text-indent: 20px; text-align: justify">
Nós decidimos utilizar o MoSCoW para termos uma comparação quanto a priorização dos requisitos, que já haviamos realizado utilizando o <i>First Things First</i>.
</p>

**Vantagens:**

- Fácil compreensão
- Fácil de se trabalhar
- Linguagem simples
- Permite a participação de todos os Stakeholders
- Não requer conhecimento da técnica

**Desvantagens:**

- Ele pode ser ambíguo em relação ao tempo
- As escalas devem ser bem compreendidas pelos *stakeholders*

## Requisitos funcionais

| Número | Requisito | Prioridade |
|:--:|--|--|
|RF1| Visualizar oferta | **Must**|
|RF2| Visualizar cupom | **Should** |
|RF3| Sugerir oferta | **Must** |
|RF4| Sugerir cupom | **Should** |
|RF5| Filtrar ofertas buscadas | **Must** |
|RF6| Filtrar cupons buscados | **Should** |
|RF7| Pesquisar oferta | **Must** |
|RF8| Pesquisar cupom | **Should** |
|RF9| Criar uma lista de desejos | **Must** |
|RF10| Cadastrar tópico no fórum | **Could** |
|RF11| Visualizar tópicos do fórum | **Could** |
|RF12| Buscar produto específico | **Could** |
|RF13| Compartilhar ofertas | **Should** |
|RF14| Favoritar cupom | **Could** |
|RF15| Enviar alerta de oferta | **Must** |
|RF16| Seguir um usuário | **Could** |
|RF17| Deixar de seguir um usuário | **Won't** |
|RF18| Bloquear um usuário | **Could** |
|RF19| Priorizar as ofertas a serem exibidas | **Must** |
|RF20| Curtir uma oferta | **Could** |
|RF21| Descurtir oferta | **Could** |
|RF22| Ir para a loja da oferta | **Must** |
|RF23| Comentar uma oferta | **Should** |
|RF24| Curtir um comentário | **Could** |
|RF25| Responder um comentário | **Should** |
|RF26| Reportar oferta | **Must** |
|RF27| Ativar modo escuro | **Could** |
|RF28| Visualizar notificações | **Should** |
|RF29| Sugerir pauta no blog | **Won't** |
|RF30| Ordenar tópicos do fórum | **Could** |
|RF31| Ativar notificações para respostas de um tópico do fórum | **Won't** |
|RF32| Desativar notificações | **Must** |
|RF33| Visualizar últimos comentários de ofertas | **Should** |
|RF34| Alterar próprio nome de usuário | **Must** |
|RF35| Desativar própria conta de usuário | **Must** |
|RF36| Enviar *feedback* | **Should** |
|RF37| Visualizar perfil dos usuários  | **Could** |
|RF38| Visualizar comentários de um usuário | **Could** |
|RF39| Visualizar medalhas de um usuário | **Could** |
|RF40| Visualizar cupons de um usuário | **Could** |
|RF41| Visualizar tópicos do fórum de um usuário  | **Could** |
|RF42| Visualizar quem um usuário segue | **Could** |
|RF43| Visualizar seguidores de um usuário | **Could** |
|RF44| O usuário poderá editar seu perfil | **Must** |
|RF45| Visualizar mensagens recebidas | **Should** |
|RF46| Alterar própria senha | **Must** |
|RF47| Adicionar foto de perfil | **Could** |
|RF49| Compartilhar tópico do fórum | **Could** |
|RF48| Alterar foto de perfil | **Could** |
|RF50| Visualizar últimos comentários de fórum | **Could** |
|RF51| Validação de ofertas e cupons sugeridos | **Must** |
|RF52| Visualizar avaliação de outros usuários | **Must** |
|RF53| Avaliar produtos e ofertas cadastrados | **Could** |
|RF54| Visualizar todas as ofertas | **Must** |
|RF55| Visualizar todos os cupons | **Must** |


## Requisitos não funcionais

| Número | Requisito | Prioridade |
|:--:|--|--|
|RNF1| A oferta deverá ser segura | **Must** |
|RNF2| O sistema atualiza as ofertas rapidamente | **Must** |
|RNF3| O sistema atualiza os cupons rapidamente | **Must** |
|RNF4| O sistema deverá ter alta disponibilidade | **Must** |
|RNF5| O sistema deverá executar em qualquer plataforma mobile | **Should** |
|RNF6| O sistema deverá manter os dados do usuário seguros | **Must** |
|RNF7| O sistema deverá manter o usuário entretido | **Could** |
|RNF8| O sistema deverá notificar o usuário sem falhas | **Must** |
|RNF9| Receber recompensas por utilizar o aplicativo por mais tempo | **Should** |
|RNF10| O usuário deverá ver os comentários dos usuário de forma rápida | **Should** |
|RNF11| O sistema deverá ter um design intuitivo | **Should** |
|RNF12| O ato do usuário de sugerir ofertas deve ser de fácil aprendizagem | **Must** |
|RNF13| O ato do usuário de sugerir cupons deve ser de fácil aprendizagem | **Must** |
|RNF14| O sistema deverá iniciar rapidamente | **Should** |
|RNF15| O sistema deverá fornecer modo alto contraste | **Should** |
|RNF16| Parceria com lojas confiáveis | **Won't** |
|RNF17| O sistema não é entediante | **Could** |


## Referências Bibliográficas

>WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 06/10/2020 | Criação do documento de priorização MoSCoW | Igor Paiva, Marcelo Victor, Rhuan Carlos e Thiago Lopes |

