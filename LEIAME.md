# Linguagem Markdown

## Introdução
Este arquivo tem o propósito de apresentar meu aprendizado na linguagem Markdown.

_(Não irei demonstrar toda a linguagem e também nem todo o meu aprendizado, pois o arquivo ficaria muito grande.)_
___

## Formatações

### Negrito
É possível colocar um texto em **negrito** utilizando tanto dois __asteriscos(*)__ quanto dois **underlines(_)** atrás e na frente do texto escolhido.
___

### Itálico
É possível colocar um texto em *itálico* utilizando tanto um _asterisco(*)_ quanto um *underline(_)* atrás e na frente do texto escolhido.
___

## Listas

### Lista Numerada
Para escrever uma lista numerada, simplesmente digite _qualquer_ número seguido de um **ponto(.)** para inserir um item na lista. Para colocar um subitem, insira-o normalmente e dê um espaçamento de 3 espaços abaixo do item que se deseja colocar o subitem.

1. Item 1
   1. SubItem 1
   2. SubItem 2
2. Item 2
3. Item 3

Obs.: Ao colocar (1.), inserir o item da lista e apertar **enter** no teclado, aparecerá a continuação da lista automaticamente em alguns editores.
___

### Lista Demarcada
Para escrever uma lista demarcada, insira um **asterisco(*)** e depois digite o item da lista.

* Item 1
* Item 2
* Item 3
   * SubItem 1

Obs.: Subitem são inseridos da mesma forma, só que agora usando o **asterisco(*)** em vez de um número.
___

### Lista de Tarefas
Uma lista de tarefas consiste em uma lista com _marcadores preenchíveis_, um marcador _vazio_ indica uma tarefa **não** concluída, um marcador _preenchido_ indica uma tarefa **concluída**.
Para criar uma lista de tarefas, insira um **traço(-)**, seguido de um espaço e **colchetes fechados([])** com um espaço vazio entre eles, depois coloque a tarefa a ser feita.
Para preencher um marcador, troque o espaço _dentro_ dos colchetes por um **x**.

- [x] Criar um arquivo LEIAME mostrando meu aprendizado em **markdown**.
- [x] Postar meu primeiro repositório.
- [ ] Desenvolver um jogo de sucesso.
___

## Imagens
Há varias maneiras de se inserir uma imagem (inserindo direto dos seus arquivos; inserindo da pasta raíz do projeto; inserindo de uma URL da internet; etc.).

Irei demonstrar como inserir imagens direto da pasta raíz do projeto.

Insira **exclamação(!)** seguido de **colchetes fechados([])**, e logo depois **parênteses fechados(())**, dentro dos colchetes você vai inserir o texto alternativo da imagem, e dentro dos parênteses, o caminho da imagem em si.

### Meus Octocats Favoritos
![MegaCat](images/megacat-2.png)
![Daft-PunktoCat Thomas](images/daftpunktocat-thomas.gif)
![Daft-PunktoCat Guy](images/daftpunktocat-guy.gif)
![SteroidtoCat](images/steroidtocat.png)

Para inserir **_links_**, faça a mesma coisa que anteriormente mas dessa vez sem a exclamação no começo.

[Linguagem Markdown](https://github.com/DimiEmerick/DimiEmerick/edit/main/LEIAME.md#linguagem-markdown)

Obs.: Em vez de texto alternativo, o conteúdo dos colchetes será o texto do _hyperlink_.
___

