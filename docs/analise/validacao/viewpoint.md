# Validação por pontos de vista

## Introdução

<p style="text-indent: 20px; text-align: justify">
A análise e comparação utilizando a técnica de viewpoint é um processo informal proposto por Ross 'SADT e Mullery's CORE, eles são semelhantes ao que chamamos de "uso de verificação informal" e dependem fortemente de serem realizados por um bom analista de sistemas. Em suma, a técnica de ponto de vista é um processo que identifica discrepâncias entre duas diferentes visões, classifica e avalia essas discrepâncias e integra as soluções alternativas em uma única representação.
</p>

## Domínio

<p style="text-indent: 20px; text-align: justify">
O domínio utilizado para os dois pontos de vista é o próprio domínio geral da aplicação, tendo base todos os artefatos gerados.
</p>

## Perspectivas
<p style="text-indent: 20px; text-align: justify">
Dentro do contexto de uma <i>view</i> existem três perspectivas possiveis, somente uma delas será abordada nesse documento.
</p>

## *Viewpoint* A

```
Perspectiva de Processo:
    ((usuario =id-usuario =nome =numero-medalhas)
     (oferta =id-oferta =nome =produto =categoria =valor-original =valor-promocional =numero-curtidas)
     (cupom =id-cupom =nome =produto =categoria =descricao =data-expiracao) (forum =nome)
     (produto =id-produto =nome) 
     (lista-desejo =id-lista-desejo)
     (topico =id-topico =titulo =conteudo) (comentario =autor =conteudo)
     (foto =url) (moderador =id-moderador =nome))

Hierarquia:
(é-um
    (objeto (oferta cupom forum topico comentario foto produto lista-desejo))
    (agente (usuario moderador)))

(parte-de
    (objeto (usuario id-usuario nome numero-medalhas)
            (foto url))
    (objeto (forum nome)
            (topico id-topico titulo conteudo))
    (objeto (oferta id-oferta nome produto categoria valor-original valor-promocional numero-curtidas)
            (comentario autor conteudo))
    (objeto (cupom id-cupom nome produto categoria descricao data-expiracao)
            (comentario autor conteudo))
    (objeto (topico id-topico titulo conteudo)
            (comentario autor conteudo))
    (objeto (usuario id-usuario nome numero-medalhas)
            (comentario autor conteudo))
    (objeto (lista-desejo id-lista-desejo))
            (produto id-produto nome))
    (objeto (oferta id-oferta nome produto categoria valor-original valor-promocional numero-curtidas))
            (produto id-produto nome))
    (objeto (cupom id-cupom nome produto categoria descricao data-expiracao))
            (produto id-produto nome))
```              

## *Viewpoint* B

```
Perspectiva de Processo:
    ((usuario =usuario-id =pontuacao =comentarios =nome =e-mail =senha =medalhas-adquiridas =lista-seguidores =lista-seguindo)
     (oferta =id-oferta =nome =loja =curtidas =visualizacao =categorias =imagem-produto =preco =comentarios =denuncias)
     (cupom =id-oferta =nome =loja =autor =categorias =imagem-cupom =informacoes) (forum =id-forum =nome =lista-comentarios) 
     (topico =id-topico =titulo =informacao) (comentario =id-comentario =autor =conteudo =denuncias =curtidas)
     (foto =id-foto =url) (moderador =id-moderador =nome =e-mail =senha))

Hierarquia:
(é-um
    (objeto (oferta cupom forum topico comentario foto))
    (agente (usuario moderador)))

(parte-de
    (objeto (usuario usuario-id pontuacao comentarios nome e-mail senha medalhas-adquiridas lista-seguidores lista-seguindo)
            (foto id-foto url))
            (comentario id-comentario autor conteudo denuncias curtidas)
    (objeto (forum id-forum nome lista-comentarios)
            (topico id-topico titulo informacao))
    (objeto (oferta id-oferta nome loja curtidas visualizacao categorias imagem-produto preco comentarios denuncias)
            (comentario id-comentario autor conteudo denuncias curtidas))
    (objeto (cupom id-oferta nome loja autor categorias imagem-cupom informacoes)
            (comentario id-comentario autor conteudo denuncias curtidas))
    (objeto (topico id-topico titulo informacao)
            (comentario id-comentario autor conteudo denuncias curtidas)))
```


## Identificação e Classificação

<p style="text-indent: 20px; text-align: justify">
Após a realização e definição das <i>views</i> identificamos em A e em B e listaremos a seguir as discrepâncias já classificadas.
</p>

### Inconsistências

#### Fatos em A

<p style="text-indent: 20px; text-align: justify">
Não há inconsistências em A.
</p>


#### Fatos em B

- Há vários objetos 'comentario' e se tornam redudantes.

### Fatos Errados

#### Fatos em A

- Faltam atributos no usuário e no moderador.
- O objeto cupom tem atributo produto e depois é definido que o produto faz parte do cupom.
- O objeto oferta tem atributo produto e depois é definido que o produto faz parte da oferta.

#### Fatos em B

<p style="text-indent: 20px; text-align: justify">
Não há fatos errados em B.
</p>

### Fatos faltantes

#### Fatos em A

- Reportar (ação)
- Curtir (ação)
- Comentar (ação)
- Bloquear (ação)
- Seguir (ação)
- Filtrar (ação)
- Visualizar medalhas (ação)
- Avaliar (ação)
- Sugerir (ação)
- Validar (ação)
- Medalhas (objeto)
- Loja (objeto)
- Categoria (objeto)

#### Fatos em B

- Reportar (ação)
- Curtir (ação)
- Comentar (ação)
- Bloquear (ação)
- Seguir (ação)
- Filtrar (ação)
- Visualizar medalhas (ação)
- Avaliar (ação)
- Sugerir (ação)
- Validar (ação)
- Medalhas (objeto)
- Loja (objeto)
- Lista de desejos (objeto)

## Avaliação

<p style="text-indent: 20px; text-align: justify">
Esta fase consiste em propor soluções alternativas para os pontos de vistas.
</p>

### Solução alternativa para A
<p style="text-indent: 20px; text-align: justify">
Inclusão dos fatos faltantes com seus respectivos atributos. Corrigir os fatos errados.
</p>

### Solução alternativa para B
<p style="text-indent: 20px; text-align: justify">
Inclusão dos fatos faltantes com seus respectivos atributos. Corrigir os fatos errados.
</p>

## Integração

<p style="text-indent: 20px; text-align: justify">
Nesta fase integramos as soluções propostas em uma solução conciliada de ambas os pontos de vista. </br>
</p>

<p style="text-indent: 20px; text-align: justify">
O ponto de vista B contém seus fatos, em grande maioria melhor definidos, que os fatos em A. Nota-se que há muitos fatos faltantes em ambos os pontos de vista, fatos do tipo de ação, alguns do tipo objeto também não foram apresentados. É evidente que os agentes são coerentes com o domínio.
</p>

## Referências

> do Prado Leite, Julio Cesar Sampaio, and Peter Freeman. "Requirements validation through viewpoint resolution." IEEE Trans. Software Eng. 17.12 (1991): 1253-1269.

> Messaoudi, Mohammed. "Requirements Engineering Through Viewpoints." International Journal of Computing 2.2 (2013): 49-59.

## Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 07/11/2020 | Criação do documento com os pontos de vista | Todos os integrantes |
