# documentação do css :)

## geral

### classes
o css do site utiliza classes, ou seja, não é nescessário duplicar um elemento  
do css para o reutilizar.

> <h1 class="titulo-base">
> <h1 class="titulo-base2">
> algo assim não é nescessário

> <h1 class="titulo-base">
> <h1 class="titulo-base">
> o css pode ser usado dessa forma

## :root

 usado para definir variáveis

### variáveis

ao invés de digitar todos os valores manualmente, usa-se variaveis para  
agilizar o processo de escrita e refatoração do css

> #### exemplo:
> color: #ca9ee6; :x:
> se torna:
> color: var(--mauve) :white_check_mark:

## conteiner

div que guarda todo o conteúdo da página

## sections

seções são grandes areas de conteúdo, cada uma com sua cor de fundo

## div-btn

o fundo de um botão grande, quadrado, com bordas redondas

## texto-btn

o texto que vai dentro de um *div-btn*

## btn-texto-puro

um botão sem plano de fundo, somente um texto com um link

## titulo principal

o maior titulo da página, junto com um *subtitulo-principal* ocupa uma tela inteira

## titulo colorido

um titulo genérico, tem sua cor indicada no nome de sua classe

> ### exemplo:
> <h1 class="**titulo-branco**">
> <h1 class="**titulo-mauve**">

## subtitulo principal

usado em conjunto de um *titulo-principal* para fazer uma tela de aprensetação

## paragrafo

uma tag *<p>* formatada, seu nome indica seu tamanho - p, m ou g - e sua cor, podendo ser  
invertido ou não.  
Um paragrafo invertido tem sua cor escura, caso contrario tem sua cor clara.

## menu topo

div que guarda os botões do menu no topo da página.

