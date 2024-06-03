# Projeto CSS Padrão

Este repositório contém um arquivo CSS padrão que pode ser reutilizado em diversos projetos. Ele define alguns estilos básicos e boas práticas que ajudam a manter a consistência e a performance das suas páginas web.

## Conteúdo do Arquivo CSS

O arquivo CSS incluído no repositório possui os seguintes estilos:

### Reset Básico

```css
* {
    padding: 0;
    margin: 0;
    border: 0;
    outline: none;
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

Este bloco de código aplica um reset básico em todos os elementos (*):

* padding: 0; e margin: 0;: Remove os preenchimentos e margens padrão de todos os elementos.
* border: 0; e outline: none;: Remove bordas e contornos padrão.
* box-sizing: border-box;: Define o modelo de caixa para incluir preenchimento e borda no tamanho total do elemento, facilitando o controle do layout.
* -webkit-font-smoothing: antialiased; e -moz-osx-font-smoothing: grayscale;: Melhoram a renderização de fontes em diferentes sistemas operacionais.

### The Root

```css
:root {
    font-size: 65.5%;
}
```

O seletor :root define variáveis globais para o documento:

* font-size: 65.5%;: Define o tamanho da fonte base para 10px, facilitando o uso de rems para tamanhos de fonte e espaçamentos.

### O Corpo

```css
body {
    font-size: 1.6rem;
}
```
O seletor body define estilos básicos para o corpo do documento:

* font-size: 1.6rem;: Define o tamanho da fonte para 16px, que é uma escolha comum para garantir legibilidade.

## Como Usar

Para utilizar este arquivo CSS em seus projetos:

1. Clone este repositório ou baixe o arquivo CSS.
2. Inclua o arquivo CSS no <head> do seu documento HTML:

```html
<link rel="stylesheet" href="caminho/para/seu/arquivo.css">
```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.


