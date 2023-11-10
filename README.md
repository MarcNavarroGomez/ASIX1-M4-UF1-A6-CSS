<!DOCTYPE html>
<html lang="en">

<head>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Edu+TAS+Beginner&display=swap'64);
        font-family: 'Edu TAS Beginner', cursive;
      </style>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors</title>
</head>

<body>
    <h1>CSS Selectors</h1>
    <p>A CSS selector selects the HTML element(s) you want to style.</p>
    <div class="selectors">
        <h2>CSS Selectors</h2>
        <p>CSS selectors are used to "find" (or select) the HTML elements you want to style.</p>
        <p>We can divide CSS selectors into five categories:</p>
        <ul>
            <li>Simple selectors (select elements based on name, id, class)</li>
            <li><a href="https://www.w3schools.com/css/css_combinators.asp"></a>Combinator selectors (select elements based on a specific relationship between them)</li>
            <li><a href="https://www.w3schools.com/css/css_pseudo_classes.asp"></a>Pseudo-class selectors (select elements based on a certain state)
            </li>
            <li><a href="https://www.w3schools.com/css/css_pseudo_elements.asp"></a>Pseudo-elements selectors (select and style a part of an element)</li>
            <li><a href="https://www.w3schools.com/css/css_attribute_selectors.asp"></a>Attribute selectors (select elements based on an attribute or attribute value)</li>
        </ul>
    </div>
    <hr>
    <h2 class="selector">The CSS <span>element</span> Selector</h2>
    <p>The element selector selects HTML elements based on the element <span>name</span> (body, p, h1, h5, a, div, etc.).</p>
    <hr>
    <h2 class="selector">The CSS <span>id</span> Selector</h2>
    <p>The id selector uses the id attribute of an HTML element to select a specific element.</p>
    <p>The id of an element is unique within a page, so the id selector is used to select one unique element!</p>
    <p>To select an element with a specific id, write a hash <span>(#)</span> character, followed by the id of the element.</p>
    <hr>
    <h2 class="selector">The CSS <span>class</span> Selector</h2>
    <p>The class selector selects HTML elements with a specific class attribute.</p>
    <p>To select elements with a specific class, write a period <span>(.)</span> character, followed by the class name.</p>
    <hr>

    <h2 id="universal">The CSS <span>Universal</span> Selector</h2>
    <p>The universal selector <span>(*)</span> selects all HTML elements on the page.</p>

    <div>
        <p>Use our <a href="https://www.w3schools.com/cssref/trysel.asp" target="_blank">CSS Selector Tester</a> to demonstrate the different selectors. </p>
    </div>
    <hr>

    <div id="gallery">
        <div>
            <h3>CSS Syntax</h3>
            <img src="./resources/regla_css.jpg" alt="">
        </div>
        <div>
            <h3>All CSS Simple Selectors</h3>
            <img src="./resources/selectors.png" alt="">
        </div>
    </div>

</body>

</html>