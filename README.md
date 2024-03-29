# fancy-product-description
HTML fancy product description  

![Descrição HTML](https://raw.githubusercontent.com/jayremias/fancy-product-description/master/documentation/images/description.png)

## Instalação
Copie o código do arquivo "description.html" e cole no editor de texto do site. Altere as informações necessárias para configurar o produto.

### Dicas iniciais
Dentro dos blocos de texto descritivos sempre utilize tags de link `<a href="/link-para-outro-produto">nome de outro produto</a>` para linkar outros produtos cadastrados no site. O link não ficara vísivel no texto, somente quando for sobreposto com o mouse.

## Adicionando mais blocos (Blocos avulsos)

### Bloco Inicial

![Bloco inicial com imagem](https://raw.githubusercontent.com/jayremias/fancy-product-description/master/documentation/images/image-header.png)

```html
<div style="clear: both; padding-bottom: 20px;">
    <h2 style="color: #e93e1b; text-transform: uppercase;">Lotem Ipsum Title</h2>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. <a href="#">Hidden link</a> Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
</div>
<div style="clear:both; padding-bottom: 30px;">
    <img style="width: 100%;" src="http://placehold.jp/1068x320.png" alt="placeholder 1068x320">
</div>
```
#### Utilização de Vídeos no Bloco Inicial

![Bloco inicial com video](https://raw.githubusercontent.com/jayremias/fancy-product-description/master/documentation/images/iframe-header.png)

Altere a imagem do bloco inicial pelo código de iframe a seguir alterando a url do vídeo no **Youtube**.

```html
<iframe style="max-width: 100%;" width="1280" height="640" src="https://www.youtube.com/embed/0ei2Q6Zf-XM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### Bloco com imagem a esquerda

![Bloco texto com imagem a esquerda](https://raw.githubusercontent.com/jayremias/fancy-product-description/master/documentation/images/left-image.png)

```html
<div style="clear: both; padding-bottom: 20px;">
    <div style="float: left; margin-right: 10px;">
        <a href="#">
            <img src="http://placehold.jp/200x200.png" aalt="placeholder 200x200">
        </a>
    </div>
    <div style="padding-top: 10px;">
        <h3 style="color: #e93e1b; text-transform: uppercase;">Lotem Ipsum Title</h3>
        <hr style="border: none; height: 2px; background-image: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.75), rgba(0,0,0,0));"/>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. <a href="#">Hidden link</a> Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div style="clear:both;">&nbsp;</div>
</div>
```

### Bloco com imagem a direita

![Bloco texto com imagem a direita](https://raw.githubusercontent.com/jayremias/fancy-product-description/master/documentation/images/right-image.png)

```html
<div style="clear: both; padding-bottom: 20px;">
    <div style="float: right; margin-left: 10px;">
        <a href="#">
            <img src="http://placehold.jp/200x200.png" alt="placeholder 200x200">
        </a>
    </div>
    <div style="padding-top: 10px;">
        <h3 style="color: #e93e1b; text-transform: uppercase;">Lotem Ipsum Title</h3>
        <hr style="border: none; height: 2px; background-image: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.75), rgba(0,0,0,0));"/>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. <a href="#">Hidden link</a> Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div style="clear:both;">&nbsp;</div>
</div>

```