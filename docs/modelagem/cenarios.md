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
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre a oferta. Precisa seguir a ordem certa para alcancar seu objetivo. Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos.|
|**Ação**|  - Ator deseja sujerir oferta <br> - Ator entra no sistema <br /> - Ator vai até a seção de sugerir oferta <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de oferta |
|**Evento**| **Eventos que disparam:** <br> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação da oferta pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF3 Sugerir oferta<br>RNF1 A oferta deverá ser segura|

### C02 - Sugerir cupom

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir um cupom encontrado |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir um cupom que ele encontrou, ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, submete o link e algumas outras informações sobre o cupom. Precisa seguir a ordem certa para alcancar seu objetivo. Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos.|
|**Ação**|  - Ator deseja sujerir cupom <br /> - Ator entra no sistema <br /> - Ator vai até a seção de sugerir cupom <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de cupom |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do cupom pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF4 Sugerir cupom |


### C03 - Sugerir um tópico no fórum

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir um tópico no fórum |
|**Ambiente**| Ocorre na aba de fóruns e ocorre porque o usuário quer sugerir um tópico no fórum que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema e submete informações sobre o tópico a ser criado. Precisa seguir a ordem certa para alcancar seu objetivo.  Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos.|
|**Ação**| - Ator deseja sujerir tópico no fórum <br /> - Ator entra no sistema <br /> - Ator vai até a seção de criação de tópico <br /> - Ator preenche todos os campos necessários <br /> - Ator envia sugestão de tópico para o fórum |
|**Evento**| **Eventos que disparam:** <br /> > Ganhar Medalhas <br /> **Eventos que são disparados:** <br /> > Avaliação do tópico do fórum pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF10 Cadastrar tópico no fórum |

### C04 - Fazer login

|Elemento|Resposta|
|---|---|
|**Objetivo**| Logar no sistema |
|**Ambiente**| Ocorre porque o usuário deseja utilizar as outras funcionalidades do sistema  |
|**Atores**| Usuário |
|**Planejamento**|  O ator terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos. Caso utilize as outras plataformas para logar, pode ser redirecionado para fazer o *login*. <br /> Caso não possua e queira criar uma conta o usuário pode se cadastrar no sistema. |
|**Ação**|  O Ator abre o app, seleciona a forma de *login*: <br /> - Conta do app <br /> - Google <br /> - Facebook  |
|**Evento**| - |
|**Avaliação**| O sistema redireciona para a página principal caso o *login* seja realizado com sucesso |
|**Rastreabilidade**| RF57	Fazer login de usuário |

### C05 - Criar conta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Criar uma conta no sistema |
|**Ambiente**| Ocorre para que se possa entrar no app e realizar as demais funcionalidades |
|**Atores**| Usuário |
|**Planejamento**|  O ator terá que preencher os campos necessários, caso o email já esteja cadastrado o usuário será informado. Caso utilize as outras plataformas para logar, pode ser redirecionado para fazer o *login*. |
|**Ação**|  - O Ator abre o app <br> - Seleciona a opção de cadastro<br> - Seleciona a forma de cadastro: <br /> - Conta do app <br /> - Google <br /> - Facebook|
|**Evento**| **Eventos que são disparados:** <br /> > email de confirmação de email é enviado para o usuário confirmar seu cadastro |
|**Avaliação**| O sistema informa o resultado do cadastrado e o ao confirmar seu email já possível realizar o *login* |
|**Rastreabilidade**| RF56	Criar conta de usuário |

### C06 - Alterar própria senha

|Elemento|Resposta|
|---|---|
|**Objetivo**| Alterar própria senha |
|**Ambiente**| Ocorre para que usuário deseja alterar sua senha |
|**Atores**| Usuário |
|**Planejamento**| O ator terá que preencher os campos necessários informando a antiga senha e a nova senha. Erros são possíveis e o ator será informado|
|**Ação**|  - O ator abre o app <br> - O ator abre a aba de configurações <br> - O ator seleciona a opção de alterar senha <br> - O ator preenche os campos necessários |
|**Evento**| **Eventos que são disparados:** <br /> > email de notificação é enviado para o usuário |
|**Avaliação**| O sistema informa o resultado da alteração de senha |
|**Rastreabilidade**| RF46 Alterar própria senha |

### C07 - Visualizar oferta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Visualizar oferta |
|**Ambiente**| Ocorre porque o usuário quer visualizar as informações sobre uma determinada oferta.  |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema e seleciona uma oferta que o interesse. |
|**Ação**| - Ator entra no sistema <br /> - Ator seleciona uma oferta <br /> - Ator visualiza as informações da oferta selecionada. |
|**Evento**| - |
|**Avaliação**| O sistema redireciona o ator para a página com os detalhes da oferta. |
|**Rastreabilidade**| RF1 Visualizar oferta |

### C08 - Pesquisar uma oferta

|Elemento|Resposta|
|---|---|
|**Objetivo**| Pesquisar uma oferta |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer pesquisar uma oferta de um produto que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, altera para a seção de pesquisa e então digita o nome do produto desejado |
|**Ação**|  - O ator entra no sistema<br> - O ator altera para a seção de pesquisa<br> - O ator preenche os campos com as informações necessárias|
|**Evento**| - |
|**Avaliação**| O sistema exibe a existência ou não da oferta associado a pesquisa |
|**Rastreabilidade**| RF12 Buscar produto específico|

### C09 - Pesquisar um cupom

|Elemento|Resposta|
|---|---|
|**Objetivo**| Pesquisar um cupom |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer pesquisar um cupom que seja de seu interesse. Ele dispõe de um celular, de alguns minutos de seu tempo, e também do produto relacionado ao cupom |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, altera para a seção de pesquisa e então digita o produto relacionado e logo em seguida altera para a seção de cupons. Existe ao menos 3 caminhos de se obter o que deseja. Erros de preenchimento de campo são possíveis e o ator será atrapalhado a concluir seu objetivo. |
|**Ação**|  - O ator entra no sistema<br> - O ator altera para a seção de pesquisa<br> - O ator preenche os campos com as informações necessárias <br> - O ator altera para a seção de cupons|
|**Evento**| - |
|**Avaliação**| O sistema exibe a existência ou não do cupom associado a pesquisa |
|**Rastreabilidade**| RF8 Pesquisar cupom |


### C10 - Sugerir pauta para o blog 

|Elemento|Resposta|
|---|---|
|**Objetivo**| Sugerir pauta para o blog |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer sugerir uma pauta para o blog que seja de seu interesse. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, e submete algumas outras informações sobre a pauta que ele deseja que seja criada. Precisa seguir a ordem certa para alcancar seu objetivo. Ele terá que preencher os campos necessários, erros de preenchimento de campo são possíveis e o ator será informado dos mesmos.  |
|**Ação**|  - Ator deseja sujerir pauta para o blog <br /> - Ator entra no sistema <br /> - Ator vai até a seção de blog <br /> - Ator acessa a página de sugestão de pauta para o blog <br /> - Ator envia sugestão de pauta para o blog |
|**Evento**| **Eventos que são disparados:** <br /> > Avaliação da pauta para o blog pelo sistema |
|**Avaliação**| O sistema notifica o autor que sua sugestão foi realizada com sucesso |
|**Rastreabilidade**| RF29	Sugerir pauta no blog |

### C11 - Priorizar ofertas listadas

|Elemento|Resposta|
|---|---|
|**Objetivo**| Personalizar as ofertas que aparecem na tela principal do sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer visualizar ofertas e cupons de categorias que sejam de seu interesse. Ele dispõe de um celular, de alguns minutos de seu tempo|
|**Atores**| Usuário |
|**Planejamento**| O ator personaliza as ofertas logo após fazer o seu cadastro ou após entrar no sistema, há duas maneiras de cumprir este objetivo sendo que a primeira é limitada a apenas a primeira vez logo após realizar o cadastro. Nos instantes finais, na hora de selecionar os tópicos o ator deve tomar as decisões corretas baseadas em seus interesses. O ator tamabém tem a opção de descartar as alerações realizadas.|
|**Ação**| - O ator entra no sistema<br> - O ator altera para a seção de personalizar ofertas<br> - O ator seleciona os tópicos de seu interesse.|
|**Evento**| - |
|**Avaliação**| O sistema passa a exibir as ofertas de acordo com os tópicos escolhidos |
|**Rastreabilidade**| RF19 Priorizar ofertas a serem exibidas |

### C12 - Criar lista de desejos

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

### C13 - Deslogar

| Elemento | Resposta |
|---|---|
|**Objetivo**| Deslogar |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário deseja deslogar do aplicativo |
|**Atores**| Usuário |
|**Planejamento**|  Ator entra no sistema, acessa a página de configurações e desloga da sua conta. Precisa seguir a ordem certa para alcancar seu objetivo. |
|**Ação**|  - Ator deseja deslogar da sua conta <br /> - Ator entra no sistema <br /> - Ator vai até à página de configurações <br /> - Ator acessa a página de logoff <br /> - Ator desloga da aplicação |
|**Evento**| - |
|**Avaliação**| O ator é redirecionado à página inicial |
|**Rastreabilidade**| - |

### C14 - Editar perfil

|Elemento|Resposta|
|---|---|
|**Objetivo**| Editar perfil do usuário |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em mudar algum dado de seu perfil. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, e submete as informações que deseja alterar em seu perfil. Precisa seguir a ordem certa para alcancar seu objetivo |
|**Ação**| - Ator deseja alterar seu perfil <br /> - Ator entra na área de configuração do sistema <br /> - Ator vai até a seção de editar perfil <br /> - Ator insere as alterações que deseja <br /> - Ator envia as informações alteradas. |
|**Evento**| **Eventos que são disparados:** <br /> > Altera os dados do ator |
|**Avaliação**| Os dados que o ator desejou alterar são salvos no perfil do usuário, contendo os novos dados |
|**Rastreabilidade**| RF44	O usuário poderá editar seu perfil |

### C15 - Desativar conta 

|Elemento|Resposta|
|---|---|
|**Objetivo**| Desativar a conta do ator |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o ator quer desativar a sua própria conta por motivos pessoais. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema vai na aba de configurações entra na subseção de dados pessoais preenche um formulário para desativação da conta. Não há caminhos alternativos. Decisões erradas podem fazer com que o ator tenha que criar uma conta nova do zero perdendo tudo o que já havia feito |
|**Ação**| - O ator entra no sistema<br> - O ator altera para a seção de configuração<br> - O ator seleciona a opção "Desativar minha conta" <br> - O ator preenche os campos informando os motivos da escolha|
|**Evento**| **Eventos que são disparados:** <br /> > Análise do formulário de desativação  |
|**Avaliação**| O sistema notifica o autor que a desativação foi concluída e manda um *email* informando se a operação foi bem sucedida |
|**Rastreabilidade**| RF35 Desativar própria conta de usuário |

### C16 - Visualizar medalhas

|Elemento|Resposta|
|---|---|
|**Objetivo**| Visualizar as medalhas que o usuário já conseguiu |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em visualizar as medalhas que já conseguiu. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator entra no sistema vai na aba de perfil e clica na seção de medalhas |
|**Ação**| - Ator entra no sistema <br /> - Ator clica na aba de perfil <br /> - Ator encontra a seção de visualizar medalhas e clica nela <br /> - Ator visualiza as medalhas que já obteve |
|**Evento**| **Eventos que são disparados:** <br /> > O ator tem suas medalhas exibidas na interface |
|**Avaliação**| O ator visualiza as medalhas que já obteve |
|**Rastreabilidade**| RF39	Visualizar medalhas de um usuário |

### C17 - Compartilhar tópico do fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Compartilhara um tópico do fórum em outros meios de comunicação específico. |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em compartilhar um tópico. Ele dispõe do celular, de alguns minutos de seu tempo e pode também ter em mente o título do fórum |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, entra no fórum, seleciona um tópico do seu agrado e o compartilha. Um outro caminho é o ator saber qual o título do tópico no fórum e pesquisar por ele. Decisões erradas alteram o produto final mas não o objetivo. Na conclusão do objetivo cabe ao ator decidir em qual meio será compartilhado o tópico. |
|**Ação**| - O ator entra no sistema<br> - O ator abre a sessão de fórums <br> - O ator encontra o tópico que deseja ou busca pelo nome do tópico<br> - O ator visualiza o tópico<br> - O ator pressiona o botão de compartilhar<br> - O sistema exibe a tela final para escolher em qual meio compartilhar.|
|**Evento**| **Eventos que são disparados:** <br /> > Exibir tela de compartilhamento |
|**Avaliação**| A tela do meio em que será compartilhado aparecerá |
|**Rastreabilidade**| RF49 Compartilhar tópico do fórum |

### C18 - Validar oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Avaliar uma oferta publicada por um usuário |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário sugere uma oferta. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Administrador |
|**Planejamento**| O Ator entra no sistema, acessa a página de avaliação de ofertas, verifica se a oferta é segura e verdadeira, e com base nisso, decide se será aprovada ou não.|
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página de ofertas sugeridas <br /> - O ator escolhe uma oferta sugerida <br /> - O ator avalia a oferta |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| A oferta poderá ser aprovada ou não |
|**Rastreabilidade**| RF51 Validação de ofertas e cupons sugeridos<br>RNF1	A oferta deverá ser segura|

### C19 - Seguir usuário

| Elemento | Resposta |
|---|---|
|**Objetivo**| Seguir um usuário |
|**Ambiente**| Ocorre na página de uma oferta ou pela a barra de pesquisa na qual o usuário clica em algum usuário e ocorre porque um usuário deseja ver as ofertas e cupons compartilhados por um usuário específico |
|**Atores**| Usuário e outro usuário |
|**Planejamento**| O ator entra no sistema, acessa o perfil de um usuário e o segue |
|**Ação**| Seguir um usuário a partir de uma oferta: <br/> - O ator entra no sistema <br/> - O ator seleciona uma oferta <br/> - O ator clica em SEGUIR na frente do nome do usuário que publicou a oferta <br/> Pesquisar por um usuário e segui-lo: <br/> - O ator clica no ícone: 🔍, na página principal <br/> - O ator digita o nome do usuário que deseja seguir <br/> - O ator clica no botão SEGUIR na frente do nome do usuário |
|**Evento**| **Eventos que são disparados:** <br /> > Começa a seguir o usuário |
|**Avaliação**| O texto do botão muda de SEGUIR para SEGUINDO |
|**Rastreabilidade**| RF16	Seguir um usuário |

### C20 - Visualizar perfil dos usuários

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar o perfil de outros usuários |
|**Ambiente**| Ocorre na página de uma oferta ou pela a barra de pesquisa na qual o usuário clica em algum usuário e ocorre porque o usuário quer visualizar perfis de outros usuários que sejam de seu interesse. Ele dispõe de um celular e de alguns minutos de seu tempo |
|**Atores**| Usuário e outro usuário |
|**Planejamento**| O ator clica no usuário que deseja visualizar o perfil |
|**Ação**| Visualizar o perfil de um usuário a partir de uma oferta: <br/> - O ator entra no sistema <br/> - O ator seleciona uma oferta <br/> - O ator clica na foto de perfil do usuário <br/> Pesquisar por um usuário: <br/> - O ator clica no ícone: 🔍, na página principal <br/> - O ator digita o nome do usuário que deseja visualizar o perfil <br/> - O ator clica na foto de perfil do usuário |
|**Evento**| - |
|**Avaliação**| O sistema passa a exibir o perfil usuário |
|**Rastreabilidade**| RF37 Visualizar perfil dos usuários |

### C21 - Enviar Feedback

| Elemento | Resposta |
|---|---|
|**Objetivo**| Enviar feedback para os desenvolvedores do sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre porque o usuário quer enviar algum tipo de feedback para os desenvolvedores. Ele dispõe de um celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator vai até as configurações do sistema, em seguida vai até a seção do feedback e escreve o feedback que deseja enviar para o sistema |
|**Ação**| - O ator entra no sistema<br> - O ator seleciona a opção as configurações do usuário<br> - O ator vai até a área de "Enviar feedback"<br> - O ator seleciona o motivo<br> - O ator escreve o feedback que deseja enviar ao sistema<br> - O ator clica em "enviar feedback". |
|**Evento**| **Eventos que são disparados:** <br /> > Enviar *feedback* para o sistema |
|**Avaliação**| O *feedback* com sugestões é enviado para o sistema |
|**Rastreabilidade**| RF36 Enviar *feedback* |

### C22 - Curtir uma oferta

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

### C23 - Validar cupom

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

### C24 - Bloquear um usuário

| Elemento | Resposta |
|---|---|
|**Objetivo**| Bloquear um usuário cadastrado no sistema |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário deseja bloquear outro usuário. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa o perfil do usuário que deseja bloquear, e clica no botão de bloqueio. |
|**Ação**| - O ator entra no sistema <br /> - O ator accessa o perfil do usuário que deseja bloquear <br /> - O ator clica no botão de bloqueio |
|**Evento**| **Eventos que são disparados:** <br /> > Feedback ao usuário |
|**Avaliação**| As ofertas sugeridas pelo usuário bloqueado não serão exibidas para o usuário que o bloqueou |
|**Rastreabilidade**| RF18 Bloquear um usuário |

### C25 - Visualizar notificações

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar as notificações |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o sistema envia notificações para o ator e o ator tem o interesse de visualizá-las. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O ator entra no sistema, se redireciona para a seção de notificação e observa as notificações que o sistema exibe |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a seção de notificações <br /> - O visualiza as suas notificações |
|**Evento**| **Eventos que são disparados:** <br /> > Notificações que o sistema encaminha para o ator |
|**Avaliação**| O ator visualiza as notificações do sistema |
|**Rastreabilidade**| RF28 Visualizar notificações |


### C26 Visualizar tópicos do fórum

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

### C27 Ordenar tópicos do fórum

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

### C28 Visualizar mensagens recebidas

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar mensagens enviadas pela moderação |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando um usuário recebe uma mensagem. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa as notificações, acessa a notificação de mensagem, e visualiza as mensagens recebidas.|
|**Ação**| - O ator entra no sistema <br /> - O ator seleciona a opção de notificações <br /> - O ator clica na mensagem recebida|
|**Evento**| **Eventos que são disparados:** <br /> > Notificação ao usuário|
|**Avaliação**| O usuário será redirecionado para a mensagem recebida |
|**Rastreabilidade**| RF45 Visualizar mensagens recebidas |


### C29 Visualizar últimos comentários de ofertas e fórum

| Elemento | Resposta |
|---|---|
|**Objetivo**| Visualizar últimos comentários de ofertas e fórum |
|**Ambiente**| Ocorre na aba de últimos comentários e ocorre quando um usuário deseja visualizar os últimos comentários de oferta ou do fórum. Ele dispõe do celular e de alguns minutos de seu tempo |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, acessa a página do fórum ou vai na aba de pesquisa e visualiza os tópicos do fórum. Há uma outro método que consiste em ir pela aba de últimos comentários, a decisão entre um ou outro não altera o cumprimento do objetivo |
|**Ação**| - O ator entra no sistema <br /> - O ator acessa a página do fórum ou barra de pesquisa <br /> - Visualiza os últimos comentários |
|**Evento**| - |
|**Avaliação**| O ator é redirecionado para a página de últimos comentários |
|**Rastreabilidade**| RF33 - Visualizar últimos comentários de ofertas<br>RF50 - Visualizar últimos comentários de fórum |

### C30 - Compartilhar oferta

| Elemento | Resposta |
|---|---|
|**Objetivo**| Compartilhar uma oferta em algum meios de comunicação específico |
|**Ambiente**| Não ocorre em nenhum lugar em especial e ocorre quando o usuário tem interesse em compartilhar uma oferta. Ele dispõe do celular, de alguns minutos de seu tempo e pode também ter em mente a oferta ser partilhada |
|**Atores**| Usuário |
|**Planejamento**| O Ator entra no sistema, visualiza uma oferta e compartilha, podendo a partir daí selecionar em qual meio ou outro app compartilhar. Um outro caminho é o ator saber qual o título da oferta e pesquisar por ela. Decidir entre as duas opções alteram o produto final mas não o objetivo. Na conclusão do objetivo cabe ao ator decidir em qual meio será compartilhada a oferta.|
|**Ação**| - O ator entra no sistema<br> - O ator encontra a oferta que deseja ou busca pelo nome da mesma<br> - O ator visualiza o tópico<br> - O ator pressiona o botão de compartilhar<br> - O sistema exibe a tela final para escolher em qual meio compartilhar.|
|**Evento** | **Eventos que são disparados:** <br /> > Exibir tela de compartilhamento |
|**Avaliação**| A tela do meio em que será compartilhado aparecerá |
|**Rastreabilidade**| RF13 Compartilhar ofertas |


### C31 - Visualizar avaliação de outros usuários

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

### C32 - Reportar oferta

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
| 2.0 | 07/10/2020 | Adição dos cenários C02 até o cenário C33 | Todos os integrantes |
| 2.0.1 | 07/10/2020 | Correção do versionamento 2.0 | Thiago Guilherme |
| 3.0 | 12/11/2020 | Correção dos erros encontrados durante a verificação | Thiago Guilherme
