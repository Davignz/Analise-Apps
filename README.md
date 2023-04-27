
# Análise de Apps

Análise dos aplicativos Disney+, Netflix e Star+


## Autores

- [Davi Gonzaga Ferreira](https://www.github.com/davignz)

- [Carlos Eduardo Gomes Martins](https://www.github.com/martinscarlos111)

* 3ºJogos Digitais
## Tipo e organização do conteúdo 

O conteúdo é apresentado em forma de lista nos três aplicativos, tanto na horizontal quanto na vertical, com imagens e textos que referenciam as imagens. Ao clicar em uma das imagens listadas, é aberto uma nova view, nela contendo introdução, restrição de idade, atores, um button para assistir o trailer e outro para o filme, data de lançamento, e direção do filme/serie. Abaixo disso uma lista de sugestões sugeridas pelo sistema de acordo com o filme anteriormente escolhido. 

## Estrutura de navegação dos aplicativos (semelhanças e diferenças)
As estruturas de navegação dos aplicativos de stream de filmes seguem um padrão para tornar a navegação mais intuitiva. 
Essas estruturas são:

•	Botões que abrem outra View, por exemplo o botão de pesquisa, botões de download, play, adicionar à lista, trailers...

•	Interações Pop-up, como notificações (em breve, novos episódios);

•	Navegação por meio de actions 

•	Transições

## Disposição dos elementos na tela
Os elementos dispostos na tela seguem um padrão nos três aplicativos. A tela inicial dos aplicativos apresenta uma lista de conteúdos em destaque, divididos em categorias como "Originais Netflix", "Séries em alta" ou "Filmes de ação". Logo abaixo, existe uma seção de recomendações personalizadas para o usuário, baseadas no histórico de visualizações e preferências que foram definidas por ele.
Além disso, esses aplicativos possuem uma barra de navegação na parte inferior da tela, que permite o usuário acessar diferentes seções do aplicativo, como "Início", "Busca", "Minha lista" e "Perfil". Quando ele seleciona uma categoria ou título específico, é exibida uma tela com informações sobre o conteúdo, incluindo sinopse, elenco, classificação indicativa, etc. A partir disso, podem existir outras interações, como “Novidades”, “Em breve”.

## Tipo de conteúdo online e off-line:
Os aplicativos que nós escolhemos possuem o modo online e um modo off-line, o modo online permite a visualização de todos os filmes/series disponíveis. Já o modo off-line precisa que o usuário use a memória interna para baixar o conteúdo para a visualização em uma condição off-line. 

## Analisar os elementos apresentados na tela e identificar os tipos possíveis de cada elemento (de acordo com os elementos disponíveis no Android Studio)
•	Os três utilizam o componente RecyclerView para armazenar a lista de filmes, pois ele reutiliza a visualização para novos itens, que são criados dinamicamente na tela. Isso melhora o desempenho do app e sua capacidade de resposta.

•	Também utilizam o MediaPlayer, que inclui compatibilidade com diversos tipos de mídias comuns, como áudios, vídeos e imagens.

•	Ambos utilizaram uma ferramenta de permissão para a utilização da internet.

•	ImageView para trabalhar com imagens.

•	Buttons para ter seleções das opções que serão apresentadas.

•	textView para textos e descrições.

•	android:orientation="posição requerida". Essa propriedade alinha os componentes de acordo com o requerido, podendo ser vertical ou horizontal. No caso destes apps é utilizada a orientação vertical.
