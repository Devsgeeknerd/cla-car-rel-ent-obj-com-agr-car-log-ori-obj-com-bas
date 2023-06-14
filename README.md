<!-- Título -->
# Cardinalidade de Relações Entre Objetos

***Conteúdo da Aula:***

Quando temos uma relação entre objetos, nós podemos definir a cardinalidade deste relacionamento.

Esta cardinalidade está relacionada à quantidade de elementos que estão envolvidos na relação, quer seja uma agregação, quer seja uma composição.

Nós podemos ter, basicamente, os seguintes tipos de cardinalidade no relacionamento entre objetos:

| Cardinalidade | Descrição |
| :-----------: | :-------- |
| `0/1 .. N (*)` | Um objeto pode estar associado a zero ou vários objetos. |
| `1 .. 1` | Um objeto esta associado a um único objeto. |
| `N (*) .. N (*)` | Vários objetos podem estar associados a vários objetos. |

A cardinalidade de uma relação é representada com a notação da tabela acima em cada uma das extremidades da relação.

Vamos ao exemplo da relação entre notas fiscais e itens das notas fiscais.

![Exemplo](https://d2v0x26thbzlwf.cloudfront.net/prod/13/img/rId17oma55h0t.3vu.png "Relação entre notas fiscais e itens das notas fiscais")

Perceba que, nas extremidades da notação da composição neste caso, nós temos indicadas as cardinalidades em cada extremidade do relacionamento.

No caso acima, nós temos duas indicações:

* Uma nota fiscal pode conter no mínimo 1 e no máximo vários (`N` ou `*`) itens de nota fiscal associados;
* Um item de nota fiscal pode estar associado somente a uma única nota fiscal.

Geralmente, para definirmos a cardinalidade de uma relação entre objetos, nós adotamos a maior cardinalidade.

No caso acima, um dos lados possui uma cardinalidade única (um item de nota fiscal está atrelado somente a uma nota fiscal).

Mas, o outro lado possui uma cardinalidade múltipla (uma nota fiscal pode conter um ou mais itens).

No caso de cardinalidades múltiplas, nós assumimos a maior cardinalidade para definir a cardinalidade do relacionamento.

Então, neste caso, nós podemos afirmar que temos uma relação de cardinalidade `1` para `N`.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-car-rel-ent-obj-com-agr-car-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
