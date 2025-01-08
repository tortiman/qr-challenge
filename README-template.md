# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Diseño de una pagina web que contiene un codigo qr que enlaza con frontend mentor, tiene un texto que denomino titulo y otro texto que denomino parrafo

### Screenshot

Creacion de una carpeta screenshots donde estan todas las capturas de pantalla con las caracteristicas de las clases presentes en el html.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Proceso de creacion:
-Creación de la estructura html:
-Creacion del contenedor, clase .cuadro, ahi se ubica el codigo QR con los textos. - Creacion de la clase .qr donde va ubicada la imagen. - Creacion de la clase imagen .imagen donde va la imagen, que a su vez tambien tiene una clase .imagen-qr. - Creacion de la clase .titulo donde va el texto principal y de mas tamaño - Creacion de la clase .parrafo donde va el texto secundario y de menos tamaño

- Creacion de los estilos entre las etiquetas style en el head del html:
  body {
  background-color: gray;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: "Outfit", sans-serif;
  }
  .cuadro {
  width: 950px;
  height: 670px;
  background-color: #d6e2f0;
  display: flex;
  justify-content: center;
  align-items: center;
  }

      .qr {
        width: 230px;
        height: 355px;
        background-color: white;
        border-radius: 15px;
        position: absolute;
        text-align: center;
        box-shadow: 0px 15px 10px 0px rgba(0, 0, 0, 0.04);
      }

      .imagen-qr {
        position: relative;
        width: 207px;
        height: 207px;
        border-radius: 7px;
        margin-top: 6px;
        margin-left: 6px;
      }

      .titulo {
        font-size: 15px;
        font-weight: 700;
        margin-top: 20px;
        margin-left: 15px;
        margin-right: 15px;
      }

      .parrafo {
        font-size: 10.5px;
        color: hsl(215, 15%, 48%);
        margin-top: 10px;
        margin-left: 24px;
        margin-right: 24px;
        line-height: 1.4;
        font-weight: 400;
      }

      @media (min-width: 375px) and (max-width: 700px) {
        .cuadro {
          width: 375px;
        }
      }

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
