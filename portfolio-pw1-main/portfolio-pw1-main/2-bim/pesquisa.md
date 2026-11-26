# Definição css
CSS ou Cascading Style Sheets, é uma linguagem de estilo, ou seja, ela tem como função definir como cada elemento será mostrado na tela, no papel, na fala ou em outras mídiasde um documento escrito em HTML ou XML. 
# Formato do css
começa com um seletor, uma tag como h1, seguido por um bloco de declarações delimitado por chaves. As declarações consistem em uma propriedade, como cor e tamnho da fonte, e um valor, caracteristicas das propriedades, separados por dois pontos, e terminam com um ponto e vírgula. Exemplo:


h1{
color: blue; font-size: 12px;
}
# Tipos de css

## in-line
O CSS inline é usado para dar estilo a um elemento HTML específico. Para este estilo de CSS, você somente vai precisar adicionar o atributo style para cada tag HTML, sem usar os seletores.

Este tipo de CSS não é realmente recomendado, já que cada tag HTML precisa ser estilizada de maneira individual. Gerenciar o seu site pode se tornar uma tarefa bem difícil de você só usa o CSS inline.

Contudo, o CSS nline no HTML pode ser útil para algumas situações. Por exemplo, sem casos onde você não tem acesso aos arquivos CSS ou precisa aplicar estilos para um elemento único.

### Vantagens do CSS Inline :

- Você pode inserir elementos CSS de maneira fácil e rápida numa página HTML. É por isso que esse método é útil para testar e pré-visualizar mudanças, assim como executar correções rápidas no seu site.
- Você não precisa criar e fazer upload de um documento separado como no estilo externo.

### Desvantagens do Inline CSS:

- Adicionar regras CSS para cada elemento HTML consome muito tempo e faz a sua estrutura HTML ficar bagunçada.
- Estilizar múltiplos elementos pode afetar o tamanho da sua página o tempo para download.


## in-folder
O CSS interno ou incorporado requer que você adicione a tags <style> na seção <head> do seu documento HTML.

Este estilo de CSS é um método efetivo de estilizar uma única página. Contudo, usar esse estilo em múltiplas páginas pode consumir muito tempo, já que você precisa definir as regras CSS para cada página do seu site.
### Vantagens de CSS Interno:
- Classes e seletores de IDs podem ser usados ​​por stylesheet interno.
- Não há necessidade de carregar vários arquivos. HTML e CSS podem estar no mesmo arquivo.
### Desvantagens de CSS Interno:
- Adicionar o código para o documento HTML pode aumentar o tamanho da página e o tempo de carregamento.

## external
Com o CSS externo, você vai linkar as páginas da internet com um arquivo .css externo, que você pode criar usando qualquer editor de texto no seu dispositivo (ex.: Notepad++).

Este tipo de CSS é um método mais eficiente, especialmente se você está estilizando um site grande. Ao editar um arquivo .css, você pode modificar um site inteiro de uma só vez.

### Vantagens de CSS Externo:
- Como o código CSS está num documento separado, os seus arquivos HTML terão uma estrutura mais limpa e serão menores
- O mesmo arquivo .css pode ser usado em várias páginas.
### Desvantagens de CSS Externo:

- Até que o CSS externo seja carregado, a página pode não ser processada corretamente.
- Fazer o upload ou links para múltiplos arquivos CSS pode aumentar o tempo de download do seu site.

### referencias
https://developer.mozilla.org/pt-BR/docs/Web/CSS
https://blog.grancursosonline.com.br/sintaxe-declaracao-e-seletores-css/#:~:text=A%20sintaxe%20do%20CSS%20%C3%A9,com%20um%20ponto%20e%20v%C3%ADrgula.
https://www.hostinger.com/br/tutoriais/diferenca-entre-estilos-css#h-css-externo
