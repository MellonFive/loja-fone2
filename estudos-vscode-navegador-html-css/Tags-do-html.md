- `<!DOCTYPE html>` - No HTML, o doctype é a introdução "<!DOCTYPE html>" encontrada no topo de todos os documentos. Seu único propósito é evitar que o browser mude para os chamados “quirks mode” quando renderizar um documento; isto é, o "<!DOCTYPE html>" doctype garante que o browser faça um esforço na tentativa de seguir as especificações relevantes, em vez de usar um modo de renderização diferente e que seja incompatível com algumas especificações.

- `<html>` - O elemento HTML <html> (ou HTML root element) representa a raiz de um HTML ou XHTML documento. Todos os outros elementos devem ser descendentes desse elemento.

- `<head>` - Elemento providencia informações gerais (metadados) sobre  documento, incluindo seu título e links para scripts e folhas de estilos.

- `<link>` - Especifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo.

- `<meta>` - Define qualquer informação de metadados que não podem ser definidos por outros elementos HTML. (<base>, <link>, <script>, <style> ou <title>).

- `<title>` - Elemento HTML Título define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas. 

- `<body>` - Representa o conteúdo de um documento HTML. è permitido apenas um <body> por documento.

- `<header>` - Representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.

- `<h1>` - Os elementos HTML <h1>–<h6> representam seis níveis de título de seção. <h1> é o nível de seção mais alto e <h6> é o mais baixo.

- `<nav>` - Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.

- `<a>` - O elemento HTML <a> (ou o Elemento Ancora HTML define uma hiperligação (hyperlink), o destino de uma hiperligação, ou ambos.


- `id` - Em um documento HTML, os seletores de ID do CSS selecionam um elemento baseado no conteúdo de seu atributo id, o qual deve ser exatamente igual ao valor dado ao seletor. Um identificador exclusivo que deve ser único por todo o documento. Seu objetivo é identificar o elemento ao navegar por âncoras (usando um identificador de fragmento), quando utilizar scripts ou estilizando (com CSS).

O valor deste atributo é uma string opaca: isso significa que os desenvolvedores não devem utilizá-lo para transmitir nenhuma informação. Significados específicos como, por exemplo, significado semântico não devem ser provenientes desta string.

O valor deste atributo não deve conter lacunas (espaços, tabulações etc.). Navegadores tratam IDs inadequadas que contenham lacunas como se as lacunas fossem parte do ID. Em contraste com o atributo class, que permite múltiplos valores separados por espaço, os elementos podem ter somente um único ID.

- `class` - O atributo global class é uma lista das classes de um elemento, separada por espaços. Classes permitem a CSS e Javascript selecionar e acessar elementos específicos através dos seletores de classe ou funções como o métodos DOM.

Apesar da especificação não impor requesitos sobre os nomes de classes, é considerada boa prática usar nomes que descrevam o propósito semântico do elemento, em vez de sua representação (e.g. atributo para descrever um atributo em vez de ítalico, mesmo que um elemento desta classe possa ser representado por ítalico). Nomes baseados em semântica permanecem coerentes mesmo se a representação da página mude.

- `<button>` - Representa um botão clicável

- `div` - É um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como *lang*. Ele deve ser utilizado somente quando não tiver outro elemento de semântica (tal como <article> ou <nav>).

- `<dl>(Description list)` - 

- `<dt>(Description title)` -

- `<dd>(define description` - 