# Especificação Suplementar

## 1. Introdução
<p style="text-indent: 20px; text-align: justify">
A especificação suplementar aborda os requisitos funcionais e principalmente os não funcionais do sistema, basicamente se aliando com outras técnicas de requisitos como a modelagem e a elicitação possibilitando ter uma margem mais robusta de alcançar os requisitos do sistema. Nesse contexto nós temos os atributos de qualidade do sistema, os requisitos de usabilidade, segurança, desempenho e suportabilidade, além de outros requisitos, como requisitos de compatibilidade, restrições de design, legislação associada, sistemas operacionais e ambientes.
</p>

### 1.1 Propósito
<p style="text-indent: 20px; text-align: justify">
Este documento serve para dar uma descrição detalhada dos requisitos de um software. Contém as restrições de sistema, interface, interações com aplicações externas.
</p>

### 1.2 Escopo
<p style="text-indent: 20px; text-align: justify">
O promobit é um aplicativo mobile que tem como carro chefe a exibição das ofertas e cupons de maneira dinâmica e rapida, tendo segurança e veracidade. Além disso, conta também com uma rede de interação e discussão entre usuários acerca das ofertas, cupons e tópicos tudo isso atrelado a um sistema gamificado e tudo isso contido num aplicativo grátis disponível na Play Store e na App Store.
</p>

## 2. Descrição geral
### 2.1 Funções do produto 
<p style="text-indent: 20px; text-align: justify">
Com o fato de ser um aplicativo móvel os usuários vão ser capazes de buscar por produtos específicos, ofertas, cupons. Os resultados são baseados nas entradas dos usuários e contém diversos critérios de busca, filtragem e classificação. O usuário também pode se relacionar com outros usuários, discutir sobre as ofertas e cupons nos fóruns do sistema. Além do mais, pode ser notificado via <i>email</i> e/ou notificações.
</p>

### 2.2 Características do usuário
<p style="text-indent: 20px; text-align: justify">
Assim como já listado nas personas referentes aos projeto, os usuários de maneira geral também podem ser definidos em: usuários comuns e administradores.
<br />
Acerca dos <b>usuários</b> são pessoas que costumam utilizar <i>e-commerce</i> e por consequente tem interesse em ficar por dentro das melhores ofertas e cupons de suas lojas virtuais favoritas. Já os <b>administradores</b> são tipos diferentes de usuário que se referem a administração do aplicativo e que tem pápeis importantes quanto a segurança e veracidade das ofertas.
</p>

### 2.3 Restrições
<p style="text-indent: 20px; text-align: justify">
As restrições se referem as necessidades de funcionamento do sistema de um modo geral, podemos definir a conexão a internet como uma restrição de funcionamento do aplicativo dado que, é inviável realizar as funções mais básicas sem conexão a rede, exemplo: atualizar lista de oferta, login, cadastro.
</p>

### 2.4 Suposições e dependências

<p style="text-indent: 20px; text-align: justify">
O aplicativo depende de um servidor geral para o seu correto funcionamento.
</p>

## 2.5 Repartição de Requisitos
<p style="text-indent: 20px; text-align: justify">
Em caso de atraso na execução do projeto, os requisitos podem ser dividos para a próxima <i>release</i>.
</p>

## 3. Recursos do sistema e requisitos

### 3.1 Requisitos funcionais
<p style="text-indent: 20px; text-align: justify">
Os requisitos funcionais em sua grande maioria foram levantados em documentos anteriores.
</p> 

### 3.2 Requisitos de interface externa

#### 3.2.1 Interfaces de Usuário
<p style="text-indent: 20px; text-align: justify">
Um usuário do aplicativo pela primeira vez irá se deperar com a interface de login e cadastro.
<br />
Usuários já cadastrados e/ou logados se deparam com a interface de ofertas podendo mudar por meio de butões para a interface do fórum, a interface de busca, a interface de configuração, a interface de perfil de usuário, a interface de últimos comentários, a interface de lista de desejos.
</p> 

#### 3.2.2. Interface de Hardware
<p style="text-indent: 20px; text-align: justify">
O hardware deve ser capaz de lidar com a requisição de dados a partir de algum método de conexão com a internet. Essas comunicações são abstraídas para a comunicação aplicativo - servidor.
</p> 

#### 3.2.3 Interface de Software
<p style="text-indent: 20px; text-align: justify">
A comunicação do aplicativo com seus componentes envolvem operações de leitura e escrita.
</p> 

#### 3.2.4 Interface de Comunicação
<p style="text-indent: 20px; text-align: justify">
Não é importante para o sistema pois as operações e comunicações com as diferentes partes do sistema são abstraídas.
</p> 

### 3.3 Requisitos de perfomance

- Pesquisa proeminente: a feature buscada deve ser fácil de ser encontrada pelo usuário.

- Pesquisa fácil: as diferentes opções de busca devem ser evidentes, simples e fáceis de entender.

- Tempo de resposta: o tempo de resposta do aplicativo deve ser rápido considerando a velocidade de atualização de ofertas no mercado.

- Dependabilidade do sistema: se o sistema perder a conexão o usuário deve ser informado do mesmo.

- Armazenamento: O aplicativo precisa de 20.1 megabytes de armazenamento em sistemas IOS e 28.49 em sistemas Android.

### 3.4 Atributos do sistema de software

#### 3.4.1 Confiabialidade

- O sistema deve assegurar a menor taxa de erro, 1 caso em 10000, possível nas buscas do usuário.

- O sistema deve assegurar a veracidade das ofertas taxa de erro: 1 caso em 100.

#### 3.4.2 Disponibilidade

- O sistema deve estar disponível preferencialmente durante o dia, tendo sua manutenção dentro de horários noturnos.

#### 3.4.3 Segurança

- É imprescindível que o sistema assegure os dados do usuário de forma mais eficaz possível.

- O sistema deverá informar possíveis logins indesejados na sua conta.

- O sistema não deverá permitir login com contas inexistentes.

- Se o usuário ao criar ao realizar o cadastro se deparar com um um nome de usuário em uso, o usuário deverá ser informado.

#### 3.4.4 Manutenibilidade

- A aplicação deve ser fácil de ser escalonada para situações de maiores usos.

- O código deve ser escrito seguindo um padrão previamente definido de modo a facilitar a implementação de novas funcionalidades.

#### 3.4.5 Portabilidade

- A aplicação deve ser suportado por sistemas Android e IOS.


## Referências
> "How to Write a Software Requirements Specification (SRS Document)". Acesso em: 7 out 2020. Disponivel em: https://www.perforce.com/blog/alm/how-write-software-requirements-specification-srs-document

> "Software Requirements Specification Amazing Lunch Indicator". Acesso em: 7 out 2020. Disponível em: http://www.cse.chalmers.se/~feldt/courses/reqeng/examples/srs_example_2010_group2.pdf 
## Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 07/10/2020 | Criação do documento de especificação suplementar | Rhuan carlos e Marcelo Victor |