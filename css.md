## Estrutura  

```css
.class-name {
    property: value;
}

tag-name {
    property: value;
}

#identificacao-id {
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

- height  
  Definição da altura do elemento

- width  
  Definição da largura do elemento
  
- border  
  Definição do tamanho da borda e seu estilo. Exemplo:
  ```css
  .classe {
      border: 10px solid #000000;
  }
  ```
  
- padding ou padding-direcao  
  Espaçamento interno das bordas do elemento.

- margin ou margin-direcao
  Espaçamento externo das bordas do elemento.

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