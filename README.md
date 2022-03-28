# WS-HTML-CSS

# STEP 1 - HTML BASICS

Take a look at https://html.com/

## EX 00

Repeat the example below using the right HTML tags

![image](https://user-images.githubusercontent.com/76050470/159000568-8ee796b1-ae8a-473d-b842-dc77258342f4.png)

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ligula nisl, 
        hendrerit at semper eu, faucibus quis nibh. Sed aliquet, nulla a eleifend facilisis,
        ante justo sollicitudin dui, eu egestas metus est sed nibh.
        Nulla nec auctor erat. Sed et egestas quam. Donec interdum metus in massa scelerisque,
        eu fermentum massa malesuada. Proin ac velit non diam feugiat aliquet et quis turpis.
        Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

## EX01
Print 3 paragraphs with one sentence. Each sentence should be a different font. Take sentences at https://www.lipsum.com/feed/html or write them yourself.

![image](https://user-images.githubusercontent.com/76050470/159012043-ac150f45-da94-40ea-a886-e4e5df6f7425.png)

## EX02

With the pragarphs create before. Underline the first text, bold the second and italicize the last.

![image](https://user-images.githubusercontent.com/76050470/159013361-563cfb7e-1cda-4399-9932-0ff1cf8bca26.png)

## EX03

Print two lists with any information you want. One list should be an ordered list, the other list should be an unordered list.

![image](https://user-images.githubusercontent.com/76050470/159015619-2fe7681f-26ae-4262-9949-925c3c5b2e21.png)

## EX04
Create links to https://intra.epitech.eu/ and https://intra.epitech.eu/user/#!/netsoul.

Create links to https://intra.epitech.eu/planning/#, that should open in a new window.

![image](https://user-images.githubusercontent.com/76050470/159034979-4b4ef36c-af77-41a0-961a-b157d1d98d30.png)

## EX05

Create a link at the bottom of the page that when clicked will jump all the way to the top of the page.

![image](https://user-images.githubusercontent.com/76050470/159036665-c95a5ed4-85c7-4149-abed-5af80a172afa.png)

 ## EX06

Display 3 different images. Each image should have a title.

![image](https://user-images.githubusercontent.com/76050470/159040915-0ffd1256-223f-4bd9-b75c-dfd4cc6bb18e.png)

## EX07

Display an image that has a width of 200, a height of 200 and a border of size 15.

And once the image is clicked it redirects to https://intra.epitech.eu/

![image](https://user-images.githubusercontent.com/76050470/159041540-5d2e95c0-793e-4036-adf1-6b07834fe33e.png)

# STEP 2 - CSS BASICS

Take a look at https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Selectors.

Create a style.css in the STEP2 directory and include it in the STEP2/index.html file.

## EX01 - General

Some generic layout rules to implement:

- The site must be in Arial 12pt
- The site must be on the whole width of the display area
- The site must be at least the full height of the display area
- The site will be on a white background
- There should be no margin between the edges of the display area and the content

## EX02 - Header

You are going to set up the layout for the header of your site! It must respect the following constraints:

- 40px high
- The whole width of the page
- Black background color
- White text in black color
- Title of enough size, centered vertically, with only a margin of 10px on the left and on the right
- The link list must be placed on a line to the right of the title, each link must be 150px wide and the text must be centered horizontally and vertically. The underline must disappear.
- When hovering the background of the elements of the link list must change to dark gray
- For the placement, you will use the positioning via inline-block, pay attention to the vertical alignment of your `<h1>` and `<nav>` elements

For the hover, you will use a [pseudo-class](https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-classes)

## EX03 - Body

You are going to set up the layout for the body of your homepage! It must respect the following constraints:

- The article must be on the left and must take 70% of the width with an internal margin of 10px.
- In the article, the title must be on the top, in capital letters
- In the article, the image must be on the left and must take only 30% of the space allocated to the article
- In the article, the excerpt must be on the right
- The text extracted from the article must be justified
- The "Read more" link should be in red, without underlining and right aligned below the article.
- When hovering, the "Read more" link should be underlined.
- The annex content (aside) must be on the right side of the page and must take 30% of the width, with an internal margin of 10px, a margin of 20px at the top and on a light grey background
- The edges of the annex content must be rounded
- Each appendix element must be underneath each other with a 5px margin all around.
- The appendix elements must be written in black without underlining
- When hovering, the appendix elements must be underlined

To manage the internal margins with a block element in percentage, you can look at how box-sizing [box-sizing](https://la-cascade.io/box-sizing-pour-les-nuls/) works.

For arondis borders you can see how [border-radius](https://developer.mozilla.org/fr/docs/Web/CSS/border-radius) works.

## EX04 - Footer

You are going to set up the layout for the footer of your site! It must respect the following constraints:

- The footer must ALWAYS be fixed at the bottom of the screen. Attention, it must not obscure the content.
it will be on a black background with white writing, with an internal margin of 10px.
- The partners must be on the left, one below the other
- The links of the footer must be in light grey and be underlined when hovering
- The name and address must be absolutely at the bottom right of the element at 10px from the edge
- The contact link must be below the name.
the footer must have a shadow of 5px

For the placement of the footer, you can look at the functioning of the [relative, absolute and fixed positioning](https://www.alsacreations.com/tuto/lire/608-initiation-positionnement-css.html)

For the management of the shadow on an html element, see [box-shadow](https://www.alsacreations.com/tuto/lire/910-creer-des-ombrages-ombres-css-box-shadow-text-shadow.html)

## EX05 - Flexbox

Take a look at https://css-tricks.com/snippets/css/a-guide-to-flexbox/.

Go to the file STEP/Flexbox.

Repeat the example below using the flexbox tool in CSS.

![276135595_506396784490494_7272256576466751543_n](https://user-images.githubusercontent.com/76050470/159640222-175d1da0-0815-4b5d-a449-70daf241ce05.png)

![276046813_417279296832716_3303186161806347433_n](https://user-images.githubusercontent.com/76050470/159640229-e70e9850-af5d-4f3e-809e-d52d1a01c7eb.png)

![276133112_686520765829364_3500139047393511800_n](https://user-images.githubusercontent.com/76050470/159640231-e0812ce1-8b41-4fd7-b73e-537b806e4595.png)

![276145334_361545862530421_7500984022055921332_n](https://user-images.githubusercontent.com/76050470/159640235-d4b62d5b-1eae-4657-9521-2f3169479186.png)

![276947585_653814162573037_395175038975193133_n](https://user-images.githubusercontent.com/76050470/159640236-edc9a0ee-1a7f-442a-828a-f289770e87fd.png)


# STEP 3 - LIVE CODING

## Create our own landing page 
