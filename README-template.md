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

- Solution URL: [QR code component solution](https://github.com/tortiman/qr-challenge)

## My process

Proceso de creacion:
-Creación de la estructura html:
-Creacion del contenedor, clase .cuadro, ahi se ubica el codigo QR con los textos. - Creacion de la clase .qr donde va ubicada la imagen. - Creacion de la clase imagen .imagen donde va la imagen, que a su vez tambien tiene una clase .imagen-qr. - Creacion de la clase .titulo donde va el texto principal y de mas tamaño - Creacion de la clase .parrafo donde va el texto secundario y de menos tamaño

- Creacion de los estilos en el fichero styles.css:

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
- Visual studio code
- Framer

### What I learned

1. Create a repository in Github.
2. Initialize a project as a public repository on GitHub.
3. Configure a repository in Github.
4. Deploy the project in Github.
5. Create a custom **README.md**
6. Submit my solution.
7. Share my solution.

## Author

- Frontend Mentor - @tortiman

## Acknowledgments
