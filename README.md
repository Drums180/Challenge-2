# Challenge-2

## Criteria 1: Complete Presentation

The html code written for this challenge uses tags of proper html semantics like `<header>`, `<aside>`, `<section>` and `<article>` which consist of the basic elements. In order to provide a complete presentation, there is a nagivation bar as required, a photo, a small description about me and my passions, my name and the title.

The structure of the css file matches the html in order to have a proper logical structure, as well there are commentaries that divide the sections in order to have a clarity while scanning the document. 

<img width="811" alt="Captura de pantalla 2022-12-08 a la(s) 1 22 59" src="https://user-images.githubusercontent.com/118247139/206384304-e377c9fa-b854-4916-8a74-a69bbadec377.png">
<img width="618" alt="Captura de pantalla 2022-12-08 a la(s) 1 27 05" src="https://user-images.githubusercontent.com/118247139/206385122-1fe43578-6cab-447e-82c9-78de9f6f7322.png">

> ###### Note: The css uses pseudo class `:hover` wasn´t required nontheless was used in all the links, navigation included. 

## Criteria 2: Functional links

All the links presented in the webpage are completely functional, including contact links to social media. This since all the `<li>` tags count with the proper `<a>` matching tag. Additional to this, proper `<alt>`tags and descriptions where added to all the images.

<img width="487" alt="Captura de pantalla 2022-12-08 a la(s) 1 31 41" src="https://user-images.githubusercontent.com/118247139/206385988-ad858fcb-28e8-4642-8281-d6ebd6c93f57.png">

## Criteria 3: Links Inside Website

As mentioned before, all links inside the webpage are completely functional including those referencing the same page. This is made using proper `id` attributes that links one tag which normally refers to a section that will be connected by a link or button.

<img width="760" alt="Captura de pantalla 2022-11-28 a la(s) 17 15 50" src="https://user-images.githubusercontent.com/118247139/204400658-f5ed04d1-f280-4997-bc73-436d0b1151a8.png">

## Criteria 4: Sequential Order

In order to have easier accessibility when editing the website, a sequential structure must be made where the CSS file is directly related to the HTML file. For this case most of the variables in the CSS file are out of order and therefore it is necessary to make corrections as follows.

<img width="944" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 07" src="https://user-images.githubusercontent.com/118247139/204400460-864b2014-fcf9-468f-b128-1bfcdd9a82f9.png">
<img width="987" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 20" src="https://user-images.githubusercontent.com/118247139/204400474-2c16d665-20e5-4c61-94a9-3f74f22d58ff.png">
<img width="912" alt="Captura de pantalla 2022-11-28 a la(s) 17 14 33" src="https://user-images.githubusercontent.com/118247139/204400496-ce23880d-81ce-4945-9a2b-2ac1ef780b53.png">

## Add Ups

In order not to affect the functionality of the website for users, the effect of the pseudo class `@media` was modified for certain sizes in order to facilitate view. When the screen becomes smaller, the paragraph with the indications of touching the image disappear and the image changes its opacity.

```
@media (max-width: 664px){
    .small-card {
        width: 100%;
    }
    img:hover {
        opacity: 90%;
    }
}
```
> ###### Note: This effect can be changed to a general use in order to not depend or confuse the user with the text (which in fact has also a hover effect on it). Nontheless, it was decided in order to not compromise the overall esthetic of the image title since this object is also compromised when opacity is changed. Future corrections and use of documentation is needed.

Another addition to the code in the CSS was the use of the `:root` pseudo class, with this, it is eassy to change the color of the website with more ease and without risking not changing a crucial color in some point over the website.

<img width="397" alt="Captura de pantalla 2022-12-08 a la(s) 1 37 56" src="https://user-images.githubusercontent.com/118247139/206387107-e1a8f7d6-b5b1-4416-8c9b-eb86a4826029.png">
<img width="1470" alt="Captura de pantalla 2022-12-08 a la(s) 1 41 06" src="https://user-images.githubusercontent.com/118247139/206387824-009ec0d9-db6e-4e2d-9642-e5203651fe8d.png">


## Details and Future Changes 

Within the file there are different comments both in the HTML file and in the CSS of possible code configurations that can allow the page to have the best performance. Among these comments is the possibility of anchoring the header so that the user can access the menu whenever they need it, changing the title to have a more suitable one that matches the website, joining multiple elements in CSS to save code, etc.

Example (extraction of code):
```
.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2   {
    /* joined the 3 categories in order to reduce space in code as all share the same characteristics*/
    margin-bottom: 20px;
    font-size: 36px;
}
```

> Visualize the final page [here](https://drums180.github.io/Challenge-1/#social-media-marketing)
