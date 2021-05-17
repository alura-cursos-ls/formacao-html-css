## Estrutura  

```css
.class-name {
    property: value;
}

tag-name {
    property: value;
}

/* Afetará somente child-name que estiverem associados ao father-name */
father-name child-name {
    proprety: value;
    property: value;
}

```


## Propriedades


- text-size  
  Define o tamanho do texto que será apresentado na tela.

- text-align  
  Define o alinhamento do texto podendo ser left, center ou right.

- background
  Definição do plano de fundo, através de cores utilizando rgb, rgba, hex e url de alguma imagem.

- color  
  Definição da cor do elemento.

## Dicas
- Sempre organizar o CSS de forma em que seja um reflexo do HTML em casos de acrescímos de estilos em tags. Por exemplo:  
  ```css
  body {
      background: rgb(240,240,240);
  }
  
  h5 {
      color: #f2f2f2;
  }

  p {
      background: url('bg.png');
  }
  ```