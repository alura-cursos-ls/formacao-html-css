## Tags

Estrutura da tag:
```html 
<tag-name> Content </tag-name>
```
Tipos de tag: conteúdo (c) e informação (i)

- **!DOCTYPE** [i]  
Definição da versão do html que estamos utilizando através do atributo html para que o browser a interprete

- **html** [c]  
Para determinar tudo que será definido como html na página que será apresentada.  
Atributos:  
lang = definição da lingagem que está utilizando na página, isso facilitará quando oferecer tradução automatica.

- **meta** 
Passa informações para o navegador.   
Atributos:  
charset = definição do conjunto de caracteres da página. Geralente na America utiliza-se propriedade UTF-8

- **title**  
Altera o título da página

- **head**  
Informações que serão passadas para o navegador, como configurações e importações

- **body**  
Informações que serão exibidas no navegador (conteúdo)

- **style**  
Inserção do css diretamente pelo html.

- **link**  
  Ligação entre documentos  
  Atributos:  
  rel = responsável por especificar o tipo de relacionamento.  
  href = caminho do arquivo que será referenciado  
  Exemplo:  
  ```html
  <link rel="stylesheet" href="style.css">
  ```
- **H1 - H5** [c]:  
    Títulos das páginas  
    Exemplo: 
    ```html
    <h1> Título Principal </h1>
    ```

- **p** [c]
Paragrafos

- **strong** (para dar importância à determinado conteudo) [c]  
Marcar com negrito.

- **em** [c]  
Marcar como itálico

- **img**  
  carregar imagem diretamente no html  
  Atributos:  
  src = caminho da imagem.

- **ul**  
  Lista não ordenada

- **ol**  
  Lista ordenada

- **li**  
  Item da lista

- **div**  
  Bloco de conteúdo

- **header**  
  Cabeçalho da página

- **a**  
  Ancora para um link  
  Atributos:  
  href = endereço de referência

### Atributos Genéricos:

- **style**  
Adiciona estilização(css) da página através do html  
(css-inline)