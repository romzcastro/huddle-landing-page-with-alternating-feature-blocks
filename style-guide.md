# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Pink: hsl(322, 100%, 66%)

### Neutral

- Very Pale Cyan: hsl(193, 100%, 96%)
- Very Dark Cyan: hsl(192, 100%, 9%)
- Grayish Blue: hsl(208, 11%, 55%)

## Typography

### Body Copy

- Font size: 18px

### Headings

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 600

### Body, Call-to-actions

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400, 700

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)


  .topFooter__wrapper {
    padding: 8em 2em 2em 2em;
    max-width: 75em;
    margin: 0 auto;
  }
  .InfoContacts-Container {
    display: flex;
    column-gap: 2em;
  }
  .huddleInformation {
    padding: 0em;
  }
  .huddleContacts-container {
    flex: 1 0 80%;
    min-width: 18em;
  }
  .navA,
  .navB {
    flex: 1 0 5%;
  }
  .socials {
    flex: 1 0 10%;
  }
  .huddleContacts-container ul li {
    display: flex;
    flex-direction: row;
    column-gap: 1em;
    padding-bottom: 1em;
  }
  .huddleContacts-container {
    display: flex;
    max-width: 30ch;
  }
  .huddleInfo-emailA {
    color: var(--clr-neutral-0);
    text-decoration: none;
  }
  /* .huddleInfo-location {
    width: 20px;
    height: 20px;
  }
  .huddleInfo-number {
    width: 15px;
    height: 15px;
  }
  .huddleInfo-email {
    width: 18px;
    height: 15px;
  } */
  .bottomFooter p {
    color: var(--clr-neutral-3);
  }
  .bottomFooter__wrapper {
    display: flex;
    justify-content: flex-end;
    max-width: 76em;
    width: 100%;
  }
