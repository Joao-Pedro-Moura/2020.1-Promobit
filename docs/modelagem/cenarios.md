# Cenários

## Introdução
<p style="text-indent: 20px; text-align: justify">
É uma narrativa textual rica em detalhes contextual, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais. Cenários são poderesos, requerem menos tempo quando comparados a modelos e protótipos complexos.
</p>

## Metodologia
Usaremos a tabela abaixo como molde para descrever os cenários.

|Elemento|Resposta|
|---|---|
|**Objetivo**|Objetivo do cenário, o que motiva as ações realizadas|
|**Ambiente**|A situação, o momento, o porquê e seus detalhes em que ocorre o cenário|
|**Atores**|Atores Envolvidos|
|**Planejamento**|Atividade para transformar um objetivo em um comportamento ou conjunto de ações|
|**Ação**| Comportamento observável |
|**Evento**| **Eventos que disparam:** <br /> > Quais eventos causam a necessidade de cumprir este objetivo <br /> **Eventos que são disparados:** <br /> > Quais eventos são disparados após cumprir o objetivo |
|**Avaliação**| Atividade para interpretar a situação|
|**Rastreabilidade**| Requisito(s) associados ao cenário|
<br />

## Cenários

### C01 - Sugerir oferta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir uma oferta encontrada |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir uma oferta que ele encontrou, ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre a oferta. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir oferta <br /> - Ator entra no sistema <br /> - Ator vai até a seção de sugerir oferta <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de oferta |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação da oferta no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação da oferta pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF3 Sugerir oferta, RNF1 A oferta deverá ser segura|

### C02 - Sugerir cupom

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir uma cupom encontrado |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir um cupom que ele encontrou, ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre o cupom. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir cupom <br /> - Ator entra no sistema <br /> - Ator vai até a seção de sugerir cupom <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de cupom |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação do cupom no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do cupom pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF2 Sugerir cupom |


### C03 - Sugerir um tópico no fórum

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir um tópico |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir um tópico no fórum que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema e submete informações sobre o tópico a ser criado. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir tópico no fórum <br /> - Ator entra no sistema <br /> - Ator vai até a seção de criação de tópico <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de tópico para o fórum |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação de tópico do fórum no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do tópico do fórum pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF10 Cadastrar tópico no fórum |

### C04 - Fazer login

|Elemento|Resposta|
|---|---|
|**Objetivo**| Logar no sistema |
|**Ambiente**| Ocorre porque o usuário deseja utilizar as outras funcionalidades do sistema  |
|**Atores**| Usuário |
|**Planejamento**| O Ator abre o app, seleciona a forma de *login*: <br /> - Conta do app <br /> - Google <br /> - Facebook |
|**Ação**|  O ator terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. Caso utilize as outras plataformas para logar, pode ser redirecionado para fazer o *login* <br /> Caso não possua e queira criar uma conta o usuário pode se cadastrar no sistema |
|**Evento**| - |
|**Avaliação**| O sistema redireciona para a página principal caso o *login* seja realizado com sucesso |
|**Rastreabilidade**| - |

### C05 - Criar conta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Criar uma conta no sistema |
|**Ambiente**| Ocorre para que se possa entrar no app e realizar as demais funcionalidades |
|**Atores**| Usuário |
|**Planejamento**| O Ator abre o app, vai na opção de cadastro. Seleciona a forma de cadastro: <br /> - Conta do app <br /> - Google <br /> - Facebook |
|**Ação**|  O ator terá que preencher os campos necessários, caso o email já esteja cadastrado o usuário será informado. Caso utilize as outras plataformas para logar, pode ser redirecionado para fazer o *login* |
|**Evento**| **Eventos que são disparados:** email de confirmação de email é enviado para o usuário confirmar seu cadastro |
|**Avaliação**| O sistema informa o resultado do cadastrado e o ao confirmar seu email já possível realizar o *login* |
|**Rastreabilidade**| - |

### C06 - Alterar própria senha

|Elemento|Resposta|
|---|---|
|**Objetivo**| Alterar própria senha |
|**Ambiente**| Ocorre para que usuário deseja alterar sua senha |
|**Atores**| Usuário |
|**Planejamento**| O Ator abre o app, vai no seu perfil clica nas opções e clica em alterar senha. Ou vai nas configurações e seleciona a opção de alterar senha |
|**Ação**|  O ator terá que informar a senha atual e a senha nova |
|**Evento**| **Eventos que são disparados:** email de notificação é enviado para o usuário |
|**Avaliação**| O sistema informa o resultado da alteração de senha |
|**Rastreabilidade**| RF46 Alterar própria senha |

### C07 - Visualizar oferta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Visualizar oferta |
|**Ambiente**| Ocorre porque o usuário quer visualizar as informações sobre uma determinada oferta.  |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema e seleciona uma oferta que o interesse. |
|**Ação**| <br/> - Ator entra no sistema <br /> - Ator seleciona uma oferta <br /> - Ator visualiza as informações da oferta selecionada. |
|**Evento**| - |
|**Avaliação**| O sistema redireciona o ator para a página com os detalhes da oferta. |
|**Rastreabilidade**| RF1 Visualizar oferta |

### C08 - Sugerir um tópico

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir um tópico |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir um tópico no fórum que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete algumas informações sobre o tópico a ser criado. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir tópico no fórum <br /> - Ator entra no sistema <br /> - Ator vai até a seção de criação de tópico <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de tópico para o fórum |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação de tópico do fórum no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do tópico do fórum pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF10 Cadastrar tópico no fórum |

### C09 - Pesquisar uma oferta
<!-- PARA ARRUMAR -->

|Elemento|Resposta|
|---|---|
|**Objetivo**| Pesquisar uma oferta |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer pesquisar uma oferta de um produto que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre o tópico a ser criado. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir tópico no fórum <br /> - Ator entra no sistema <br /> - Ator vai até a seção de criação de tópico <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de tópico para o fórum |
|**Ação**|  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação de tópico do fórum no sistema. |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do tópico do fórum pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF10 Cadastrar tópico no fórum e RF12 Buscar produto específico|

### C10 - Pesquisar um cupom

|Elemento|Resposta|
|---|---|
|**Objetivo**| Pesquisar um cupom |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer pesquisar um cupom que seja de seu interesse. Ele dispõe de um celular, de alguns minutos de seu tempo, e também do produto relacionado ao cupom |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, altera para a seção de pesquisa e então digita o produto relacionado e logo em seguida altera para a seção de cupons. Existe ao menos 3 caminhos de se obter o que deseja. |
|**Ação**|  O ator entra no sistema e altera para a seção de pesquisa, ele terá que preencher no campo de busca o produto que ele deseja procurar o cupom ou selecionar um assunto buscado recentemente ou selecionar um produto dentre os mais buscados por fim ele altera para a seção de cupons, erros de preenchimento de campo são possíveis e o ator será atrapalhado a concluir seu objetivo. |
|**Evento**| - |
|**Avaliação**| O sistema exibe a existência ou não do cupom associado a pesquisa |
|**Rastreabilidade**| RF8 Pesquisar cupom |


### C11 - Sugerir pauta para o blog 

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir pauta para o blog |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir uma pauta para o blog que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, e submete algumas outras informações sobre a pauta que ele deseja que seja criada. Precisa seguir a ordem certa para alcancar seu objetivo- Ator deseja sujerir pauta para o blog <br /> - Ator entra no sistema <br /> - Ator vai até a seção de blog <br /> - Ator acessa a página de sugestão de pauta para o blog <br /> - Ator envia sugestão de pauta para o blog |
|**Ação**| Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. <br />As ações disparam o evento de avaliação de sugestão de pauta para o blog  |
|**Evento**| **Eventos que são disparados:** <br /> > Avaliação da pauta para o blog pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF10 Cadastrar tópico no fórum |

### C12 - Priorizar ofertas listadas

|Elemento|Resposta|
|---|---|
|**Objetivo**| Personalizar as ofertas que aparecem na tela principal do sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer visualizar ofertas e cupons de categorias que sejam de seu interesse. Ele dispõe de um celular, de alguns minutos de seu tempo|
|**Atores**| Usuário |
|**Planejamento**| O ator personaliza as ofertas logo após fazer o seu cadastro ou após entrar no sistema, há duas maneiras de cumprir este objetivo sendo que a primeira é limitada a apenas a primeira vez logo após realizar o cadastro. Nos instantes finais, na hora de selecionar os tópicos o ator deve tomar as decisões corretas baseadas em seus interesses. O ator tamabém tem a opção de descartar as alerações realizadas.|
|**Ação**| O ator entra no sistema altera para a seção de personalizar ofertas, seleciona os tópicos de seu interesse. O outro caminho de cumprir este objetivo depende de o ator estar nas etapas finais do cadastro de usuário lá poderá selecionar os tópicos de interesse. Erros de seleção são possíveis e o alteram o resultado final embora não atrapalhe o cumprimento do objetivo além do mais, caso o ator não selecione uma quantidade mínima pré definida de tópicos o sistema irá informar. Caso o ator abandone a seção, será informado se realmente deseja descartar as alterações.|
|**Evento**| - |
|**Avaliação**| O sistema passa a exibir as ofertas de acordo com os tópicos escolhidos |
|**Rastreabilidade**| RF19 Priorizar ofertas a serem exibidas |

### C13 - Criar lista de desejos

| Elemento | Resposta |
|---|---|
|**Objetivo**| Adicionar as ofertas e cupons à uma lista de desejos |
|**Ambiente**| Ocorre porque o usuário deseja adquirir determinados produtos |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema e seleciona a opção Lista de desejos |
|**Ação**| Caso o ator queira adicionar uma oferta a sua lista de desejos:<br/> - O ator digita o nome do produto que deseja<br/> - O ator clica em ADICIONAR <br/> - O ator clica na engranagem <br/> - O ator seleciona a faixa de preço que está disposta a pagar<br/>Caso o ator queira adicionar um cupom a sua lista de desejos:<br/> - O ator clica na aba CUPONS<br/> - O ator clica no campo de texto<br/> - O ator seleciona a loja que deseja receber o cupom |
|**Evento**| - |
|**Avaliação**| A oferta ou o cupom é adicionado  lista de desejo. |
|**Rastreabilidade**| RF9 Criar uma lista de desejos |

### C14 - Deslogar

| Elemento | Resposta |
|---|---|
|**Objetivo**| Deslogar |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário deseja deslogar do aplicativo |
|**Atores**| Usuário |
|**Planejamento**|  Ator entra no sistema, acessa a página de configurações e desloga da sua conta. Precisa seguir a ordem certa para alcancar seu objetivo- |
|**Ação**|  Ator deseja deslogar da sua conta <br /> - Ator entra no sistema <br /> - Ator vai até à página de configurações <br /> - Ator acessa a página de logoff <br /> - Ator desloga da aplicação |
|**Evento**| - |
|**Avaliação**| O ator é redirecionado à página inicial |
|**Rastreabilidade**| - |

### C15 - Editar perfil

|Elemento|Resposta|
|---|---|
|**Objetivo**| Editar perfil do usuário |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em mudar algum dado de seu perfil. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, e submete as informações que deseja alterar em seu perfil. Precisa seguir a ordem certa para alcancar seu objetivo |
|**Ação**| Ator deseja alterar seu perfil <br /> - Ator entra na área de configuração do sistema <br /> - Ator vai até a seção de editar perfil <br /> - Ator insere as alterações que deseja <br /> - Ator envia as informações alteradas. |
|**Evento**| **Eventos que são disparados:** <br /> > Altera os dados do ator |
|**Avaliação**| Os dados que o ator desejou alterar são salvos no perfil do usuário, contendo os novos dados |
|**Rastreabilidade**| RF56 O usuário poderá editar seu perfil |

### C16 - Desativar conta 

|Elemento|Resposta|
|---|---|
|**Objetivo**| Desativar a conta do ator |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o ator quer desativar a sua própria conta por motivos pessoais. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema vai na aba de configurações entra na subseção de dados pessoais preenche um formulário para desativação da conta. Não há caminhos alternativos. Decisões erradas podem fazer com que o ator tenha que criar uma conta nova do zero perdendo tudo o que já havia feito |
|**Ação**| O ator entra no sistema, altera para a seção de configuração e depois seção de dados pessoais, procura pela opção de desativação de conta, preenche os dados do formulário e submete o formulário. Erros de preenchimento de formulário podem atrapalhar a conclusão do objetivo.|
|**Evento**| **Eventos que são disparados:** <br /> > Análise do formulário de desativação  |
|**Avaliação**| O sistema notifica o autor que a desativação foi concluída e manda um *email* informando se a operação foi bem sucedida |
|**Rastreabilidade**| RF35 Desativar própria conta de usuário |

### C17 - Visualizar medalhas

|Elemento|Resposta|
|---|---|
|**Objetivo**| Visualizar as medalhas que o usuário já conseguiu |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em visualizar as medalhas que já conseguiu. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator entra no sistema vai na aba de perfil e clica na seção de medalhas |
|**Ação**| Ator entra no sistema <br /> - Ator clica na aba de perfil <br /> - Ator encontra a seção de visualizar medalhas e clica nela <br /> - Ator visualiza as medalhas que já obteve |
|**Evento**| **Eventos que são disparados:** <br /> > O ator tem suas medalhas exibidas na interface |
|**Avaliação**| O ator visualiza as medalhas que já obteve |
|**Rastreabilidade**| RF44 Visualizar medalhas de usuário |

### C18 - Compartilhar tópico do fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Compartilhara um tópico do fórum em outros meios de comunicação específico. |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em compartilhar um tópico. Ele dispõe do celular, de alguns minutos de seu tempo e pode também ter em mente o título do fórum |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, entra no fórum, seleciona um tópico do seu agrado e o compartilha. Um outro caminho é o ator saber qual o título do tópico no fórum e pesquisar por ele. Decisões erradas alteram o produto final mas não o objetivo. Na conclusão do objetivo cabe ao ator decidir em qual meio será compartilhado o tópico. |
|**Ação**| O ator entra no sistema, encontra o tópico que deseja ou busca pelo nome do tópico, visualiza o tópico, pressiona o botão de compartilhar o sistema exibe a tela final para escolher em qual meio compartilhar. Erros finais na seleção do meio de compartilhamento vão requerir que o ator refaça os passos atrasando assim o objetivo.|
|**Evento**| **Eventos que são disparados:** <br /> > Exibir tela de compartilhamento |
|**Avaliação**| A tela do meio em que será compartilhado aparecerá |
|**Rastreabilidade**| RF49 Compartilhar tópico do fórum |

### C19 - Validar oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Avaliar uma oferta publicada por um usuário |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário sugere uma oferta. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Administrador |
|**Planejamento**| O Ator entra no sistema, acessa a página de avaliação de ofertas, verifica se a oferta é segura e verdadeira, e com base nisso, decide se será aprovada ou não.|
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página de ofertas sugeridas <br /> - O ator escolhe uma oferta sugerida <br /> - O ator avalia a oferta |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| A oferta poderá ser aprovada ou não |
|**Rastreabilidade**| RF51 Validação de ofertas e cupons sugeridos |

### C20 - Seguir usuário

| Elemento | Resposta |
|---|---|
|**Objetivo**| Seguir um usuário |
|**Ambiente**| Ocorre na página de uma oferta ou pela a barra de pesquisa na qual o usuário clica em algum usuário e ocorre porque um usuário deseja ver as ofertas e cupons compartilhados por um usuário específico |
|**Atores**| Usuário e outro usuário |
|**Planejamento**| O ator entra no sistema, acessa o perfil de um usuário e o segue |
|**Ação**| Seguir um usuário a partir de uma oferta: <br/> - O ator entra no sistema <br/> - O ator seleciona uma oferta <br/> - O ator clica em SEGUIR na frente do nome do usuário que publicou a oferta <br/> Pesquisar por um usuário e segui-lo: <br/> - O ator clica no ícone: :mag:, na página principal <br/> - O ator digita o nome do usuário que deseja seguir <br/> - O ator clica no botão SEGUIR na frente do nome do usuário |
|**Evento**| **Eventos que são disparados:** <br /> > Começa a seguir o usuário |
|**Avaliação**| O texto do botão muda de SEGUIR para SEGUINDO |
|**Rastreabilidade**| - |

### C21 - Visualizar perfil dos usuários

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar o perfil de outros usuários |
|**Ambiente**| Ocorre na página de uma oferta ou pela a barra de pesquisa na qual o usuário clica em algum usuário e ocorre porque o usuário quer visualizar perfis de outros usuários que sejam de seu interesse. Ele dispõe de um celular e de alguns minutos de seu tempo |
|**Atores**| Usuário e outro usuário |
|**Planejamento**| O ator clica no usuário que deseja visualizar o perfil |
|**Ação**| O ator entra no sistema, clica no usuário que deseja visualizar o perfil, é redirecionado ao perfil do usuário desejado |
|**Evento**| - |
|**Avaliação**| O sistema passa a exibir o perfil usuário |
|**Rastreabilidade**| RF37 Visualizar perfil dos usuários |

### C22 - Enviar Feedback

| Elemento | Resposta |
|---|---|
|**Objetivo**| Enviar feedback para os desenvolvedores do sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer enviar algum tipo de feedback para os desenvolvedores. Ele dispõe de um celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator vai até as configurações do sistema, em seguida vai até a seção do feedback e escreve o feedback que deseja enviar para o sistema |
|**Ação**| O ator entra no sistema, se redireciona para as configurações do usuário e nessa seção o usuário vai até a área de "Enviar feedback", nessa área o usuário seleciona o motivo e escreve o feedback que deseja enviar o sistema e por final clica em "enviar feedback". |
|**Evento**| **Eventos que são disparados:** <br /> > Enviar *feedback* para o sistema |
|**Avaliação**| O *feedback* com sugestões é enviado para o sistema |
|**Rastreabilidade**| RF36 Enviar *feedback* |

### C23 - Curtir com oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Curtir uma oferta |
|**Ambiente**|  Não ocorre em nenhum lugar em especial e ocorre quando um usuário deseja curtir uma oferta. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, visualiza uma oferta e então a curte. Há maneiras alternativas de visualizar uma oferta. Não há erros decorrentes de decisão|
|**Ação**| - O ator entra no sistema <br /> - O ator busca por uma oferta ou escolhe uma das ofertas sugeridas <br /> - O ator curte a oferta. |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| O sistema irá alterar as cores do botão para o ator saber quer o objetivo está concluído |
|**Rastreabilidade**| RF20 Curtir uma Oferta |

### C24 - Validar cupom

| Elemento | Resposta |
|---|---|
|**Objetivo**| Validar um cupom submetido por um usuário |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário sugere um cupom. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Administrador |
|**Planejamento**| O Ator entra no sistema, acessa a página de avaliação de cupons, verifica se o cupom é seguro e verdadeiro, e com base nisso, decide se será aprovado ou não.|
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página de cupons sugeridos <br /> - O ator escolhe um cupom sugerido <br /> - O ator avalia o cupom |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| O cupom poderá ser aprovada ou não |
|**Rastreabilidade**| RF51 Validação de ofertas e cupons sugeridos |

### C25 - Bloquear um usuário

| Elemento | Resposta |
|---|---|
|**Objetivo**| Bloquear um usuário cadastrado no sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário deseja bloquear outro usuário. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa o perfil do usuário que deseja bloquear, e clica no botão de bloqueio. |
|**Ação**| - O ator entra no sistema <br /> - O ator accessa o perfil do usuário <br /> - O ator acessa o botão de bloqueio <br /> - O ator avalia o cupom |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| O cupom poderá ser aprovada ou não |
|**Rastreabilidade**| RF18 Bloquear um usuário |

### C26 - Visualizar notificações

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar as notificações |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o sistema envia notificações para o ator e o ator tem o interesse de visualizá-las. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator entra no sistema, se redireciona para a seção de notificação e observa as notificações que o sistema exibe |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a seção de notificações <br /> - O visualiza as suas notificações |
|**Evento**| **Eventos que são disparados:** <br /> > Notificações que o sistema encaminha para o ator |
|**Avaliação**| O ator é notificado dos produtos e o visualiza |
|**Rastreabilidade**| RF28 Visualizar notificações |


### C27 Visualizar tópicos do fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar tópicos do fórum |
|**Ambiente**| Ocorre na aba de fórum ou na barra de pequisae ocorre quando um usuário deseja visualizar os tópicos do fórum. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa a página do fórum ou vai na aba de pesquisa e visualiza os tópicos do fórum |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página do fórum ou barra de pesquisa <br /> - Visualiza os tópicos |
|**Evento**| - |
|**Avaliação**| O ator é redirecionado para a página do fórum |
|**Rastreabilidade**| RF11 Visualizar tópicos do fórum |

### C28 Ordenar tópicos do fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Filtar as discussões do fórum de acordo com um tópico específico |
|**Ambiente**| Ocorre no fórum do promobit. Ocorre porque o usuário deseja ver apenas as discussões de um tópico específico |
|**Atores**| Usuário |
|**Planejamento**| O ator acessa o fórum do aplicativo e seleciona o tópico referente ao assunto que deseja visualizar |
|**Ação**| - O ator entra no sistema <br/> - O ator clica na opção Fórum <br/> - O ator seleciona o tópico da discussão que deseja visualizar |
|**Evento**| - |
|**Avaliação**| As discussões exibidas passam a ser somente aquelas que, durante a criação, foram categorizadas com o tópico selecionado |
|**Rastreabilidade**| RF30 Ordenar tópicos do fórum |

### C29 Visualizar mensagens recebidas

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar mensagens enviadas pela moderação |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário recebe uma mensagem. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa as notificações, acessa a notificação de mensagem, e visualiza o |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página de cupons sugeridos <br /> - O ator escolhe um cupom sugerido <br /> - O ator avalia o cupom |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| O cupom poderá ser aprovada ou não |
|**Rastreabilidade**| RF45 Visualizar mensagens recebidas |


### C30 Visualizar últimos comentários de ofertas e fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar últimos comentários de ofertas e fórum |
|**Ambiente**| Ocorre na aba de últimos comentários e ocorre quando um usuário deseja visualizar os últimos comentários de oferta ou do fórum. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa a página do fórum ou vai na aba de pesquisa e visualiza os tópicos do fórum. Há uma outro método que consiste em ir pela aba de últimos comentários, a decisão entre um ou outro não altera o cumprimento do objetivo |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página do fórum ou barra de pesquisa <br /> - Visualiza os últimos comentários |
|**Evento**| - |
|**Avaliação**| O ator é redirecionado para a página de últimos comentários |
|**Rastreabilidade**| RF33 - Visualizar últimos comentários de ofertas e RF50 - Visualizar últimos comentários de fórum |

### C31 - Compartilhar oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Compartilhara uma oferta em outros meios de comunicação específico |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em compartilhar uma oferta. Ele dispõe do celular, de alguns minutos de seu tempo e pode também ter em mente a oferta ser partilhada |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, visualiza uma oferta e compartilha, podendo a partir daí selecionar em qual meio ou outro app compartilhar. Um outro caminho é o ator saber qual o título da oferta e pesquisar por ela. Decidir entre as duas opções alteram o produto final mas não o objetivo. Na conclusão do objetivo cabe ao ator decidir em qual meio será compartilhada a oferta.|
|**Ação**| O ator entra no sistema, encontra a oferta que deseja ou busca pelo nome da mesma, visualiza o tópico, pressiona o botão de compartilhar o sistema exibe a tela final para escolher em qual meio compartilhar. Erros finais na seleção do meio de compartilhamento vão requerir que o ator refaça os passos atrasando assim o objetivo.|
|**Evento** | **Eventos que são disparados:** <br /> > Exibir tela de compartilhamento |
|**Avaliação**| A tela do meio em que será compartilhado aparecerá |
|**Rastreabilidade**| RF13 Compartilhar ofertas |


### C32 - Visualizar avaliação de outros usuários

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar avaliação de outros usuários |
|**Ambiente**| Ocorre em alguma oferta publicada. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra nas informações de uma oferta que já foi publicada e visualiza as avaliações realizadas por outros usuários que também entraram em contato com essa oferta |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a seção de ofertas <br /> - O ator clica em alguma oferta <br /> - O ator visualiza as avalições da oferta selecionada |
|**Evento**| **Eventos que são disparados:** <br /> > Exibir a avaliação dos usuários que já avaliaram a oferta selecionada |
|**Avaliação**| O ator visualiza as avaliações de outros usuários |
|**Rastreabilidade**| RF52 Visualizar avaliação de outros usuários |

### C33 - Reportar oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Reportar oferta |
|**Ambiente**| Ocorre na página da oferta, quando um usuário deseja reportar uma oferta. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator entra no sistema, seleciona uma oferta, vai em reportar oferta, seleciona um motivo |
|**Ação**| - O Ator entra no sistema <br /> - Acessa a página de uma oferta <br /> - Clicar em reportar oferta <br /> - Seleciona o motivo <br /> - A oferta é reportada |
|**Evento**| - |
|**Avaliação**| O ator recebe um feedback da sua solicitação |
|**Rastreabilidade**| RF26 Reportar oferta |

## Referências Bibliográficas

>BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 06/10/2020 | Criação do documento de cenários e criação do C01 | Marcelo Victor e Rhuan Carlos  |
| 2.0 | 07/10/2020 | Adição dos cenários C02 até o cenário C34 | Todos os integrantes |
