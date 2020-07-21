- `background-color` - A propriedade background-color é especificada como um único valor de cor.

<hr>

- `color` - O tipo de dado CSS cor indica uma cor no espaço RGB. Uma cor pode ser descrita em qualquer uma destas formas:
    
usando uma palavra-chave;

usando o sistema de coordenada-cúbica RGB  (via #-hexadecimal ou das notações funcional rgb() e rgba());

usando o sistema de coordenada-cilíndrica HSL (via hsl() e notações funcionais hsla()) ;

<hr>

- `text-decoration` - A propriedade text-decoration do CSS é usada para definir a formatação de  underline, overline, line-through ou blink. As decorações underline e overline são posicionadas abaixo e acima do texto (respectivamente), e line-through cortando-o.

<hr>

- `font-size` - Estabelece o tamanho da fonte.

<hr>

- Valor `inherit` - Herda propriedade do elemento pai.

<hr>

- `Float` - Determina que um elemento deve ser retirado do seu fluxo normal e colocando ao longo do lado direito ou esquerdo do seu containêr, onde textos e elementos em linha irão se posicionar ao seu redor.

Um elemento flututante é um tipo de elemento cujo valor de float é diferente de none.

Os valores são: Left, right, none, inline-start, inline-end.

`left` - É uma palavra-chave que indica que o elemento deve flutuar à esquerda do bloco.

`right` - É uma palavra-chave que indica que o elemento deve flutuar à direita do bloco.


## Como floats são posicionados

Quando um elemento é flutuado ele é retirado do seu fluxo normal no documento. Ele é reposicionado à esquerda ou à direita até tocar a borda do seu próprio box ou outro elemento flutuante.

<hr>

`opacity` - A propriedade CSS *opacity* especifica a transparência de um elemento, isto é, o grau no qual o background atrás do elemento é sobreposto.

O valor se aplica ao elemento como um todo, incluindo seu conteúdo, apesar de o valor não ser herdado por elementos filhos. Assim, um elemento e seus elementos filhos tem todos a mesma opacidade relativa do background do elemento, mesmo se o elemento e seus elementos filhos tiverem opacidades diferentes entre si.

É um número no invervalo de 0.0 a 1.0, sendo estes incluídos, representando a opacidade do canal, que é o valor de seu canal alfa. Qualquer valor fora do intervalo, apesar de válido, é aproximado ao valor amis próximo dentro do intervalo.

<hr>

`overflow` - A propriedade `overflow` especifica quando o conteúdo de um elemento de nível de bloco deve ser cortado, exibido com barras de rolagem ou se transborda do elemento.

O uso da propriedade overflow com valor diferente de visible (seu valor padrão), criará um novo contexto de formatação de bloco. Isto é tecnicamente necessário para evitar que um conteúdo flutuante que entre em contato com o objeto dentro da área de rolamento e quebre as linhas do conteúdo para ajustar a disposição do texto. A quebra das linhas ocorre sempre que a barra de rolagem é utilizada, tornando a experiência de rolagem lenta.

Valores:

`hidden` - O conteúdo é cortado e nenhuma barra de rolagem é exibida.

<hr>

`margin` - A propriedade margin do CSS define a área de margem nos quatro lados do elemento. É uma abreviação que define todas as margens individuais de uma só vez: margin-top, margin-right, margin-bottom, e margin-left.

A propriedade margin pode ser especificada usando um, dois, três ou quatro valores. Cada valor deve ser um length, uma porcentagem, ou a palavra-chave auto. Cada valor pode ser positivo, zero ou negativo.

Quando um valor é especificado, a mesma margem é aplicada para todos os quatro lados;

Quando dois valores são especificados, a primeira margem é aplicada aos lados superior e inferior, e a segunda aos lados esquerdo e direito;

Quando três valores são especificados, a primeira margem é apliacada ao topo, a segunda aos lados esquerdo e direito, e a terceira ao lado inferior;

Quando quatro valores são especificados, as margens são aplicadas aos lados superior, direito, inferior e esquerdo, nesta ordem (sentido horário);

`padding` - A propriedade padding define uma a distância entre o conteúdo de um elemento e suas bordas. É um atalho que evita definir uma distância para cada lado separadamente: padding-top, padding-right, padding-bottom, padding-left.

A propriedade padding pode ser utilizada usando um, dois, três ou todos os quatro valores. Cada valor é um comprimento ou uma porcentagem.

Quando um único é valor utilizado, ele se aplica a todos os quatro lados;

Se Dois valores forem utilizados o primeiro se aplica às bordas verticais (superior e inferior) e o segundo se aplica às bordas horizontais (esquerda e direita);

Quando Três valores são utilizados o primeiro se aplica à borda superior, o segundo será utilizado tanto para a borda esquerda quanto para a borda direita. O terceiro será aplicado à borda inferior;

Com Quatro valores a ordem de aplicação é: superior, direita, inferior e esquerda (de acordo com o movimento dos ponteiros do relógio).

`id` - Está no arquivo de Tags-do-html.md

`clear` - A propriedade clear especifica se um elemento pode ter elementos flutuantes ao seu lado ou se devem ser movidos para baixo dele (clear). Essa propriedade se aplica à elementos flutuantes ou não flutuantes.

Quando essa propriedade é aplicada em elementos não flutuantes, ele move a borda (border edge) desse elemento para a borda da margem (margin edge) de todos os elementos flutuantes relevantes. Ocorre um colapso das margens verticais dos elementos não flutuantes.

As margens verticais entre dois elementos flutuantes não irão sofrer esse colapso. Quando aplicada a elementos flutuantes, a borda de margem (margin edge) do elemento inferior é movida abaixo da borda de margem (border edge) de todos os elementos flutuantes relevantes. Isso afeta a posição dos elementos flutuantes posteriores, sendo que os elementos flutuantes posteriores não podem ser posicionados acima dos anteriores.

`display` - (Obs: a tag <a> tem como padrão do display: inline.) A propriedade CSS display especifica o tipo de caixa de renderização usada por um elemento. No HTML, os valores padrões da propriedade display são feitas a partir do comportamento descrito nas especificações HTML ou da folha de estilo pad~rao do navegador/usuário. O valor padrão em XML é inline.

Além dos muitos tipos diferentes de exibição de caixa, o valor  none permite desativar a exibição de um elemento; quando você usa none, todos os elementos descendentes também tem a sua exibição desativada. O documento é renderizado como se o elemento não existisse na árvore do documento.

Valores:

`inline` - O elemento gera uma ou mais caixas de elementos inline. (Deixa elementos na mesma linha, não define width e height).

`block` - O elemento gera uma caixa de elemento de bloco. (Não deixa na mesma linha, deixa definir width e height.)

`inline-block` - O elemento gera uma caixa de elemento de bloco que fluirá com o conteúdo circundante, como se fosse uma única caixa embutida (se comportando como um elemento substituído) (deixa elementos na mesma, deixa definir width height)

`width` - A propriedade CSS width determina a largura da área de conteúdo de um elemento. A área de conteúdo fica dentro do preenchimento, da borda, e da margem de um elemento.

`height` - A propriedade height do CSS determina a altura da área do conteúdo de um elemento. A área de conteúdo consiste no padding, margin e border do elemento.

`text-align` - A propriedade text-align descreve como conteúdo inline, como texto, é alinhado no elemento pai em bloco. text-align não controla o alinhamento de elementos em bloco, apenas o seu conteúdo inline.

`line-height` - A propriedade CSS line-height define a altura de uma caixa de linha. É comumente usado para definir a distância entre as linhas de texto. Nos elementos no nível do bloco, especifica a altura mínima das caixas de linha dentro do elemento. Em elementos inline não substituídos, especifica a altura usada para calcular a altura da caixa de linha.

`position: absolute` -(Cria um novo contexto, o que a gente consegue definir a largura e a altura do elemento é realmente o conteúdo que está dentro dele e a gente consegue com top, left, right e bottom mover em relação a página.) 
Conseguimos mover na tela, o nosso elemento de forma absoluta. A primeira regra é que quando usamos *top: 0*, *bottom: 0*, *left: 0*, *right: 0*, podemos definir em relação a página. Top e bottom no eixo => X, left e right no eixo => Y.


<hr>

Unidade de medida 

`porcentagem` -

`pixel`

<hr>

`transform` - Permite modificar o espaço coordenado do modelo de formatação CSS. Usando-a, elementos podem ser traduzidos, rotacionados, ter seu tamanho ajustado e inclinados de acordo com o valores definidos.

Se a propriedade tem um valor diferente de *none*, um contexto de empilhamento será criado. Neste caso, o bojeto atuará como um bloco recipiente para *position: fixed* para os elementos qeu estão contidos.

`border` - 

`vertical-align` - 

`box-sizing` -