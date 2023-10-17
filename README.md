[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** [Klára Nováková](https://github.com/klara-novakova)
## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-klara-novakova/)** site for preview.

## Implementation
Download [dowload.css](https://github.com/pslib-cz/2023-l4-web-typographic-library-klara-novakova/blob/master/download.css) and add it to your own project!
## Usage
This Typhographic lybrary could be yoused to quickly and efficiently design your website :)
## Components and More
### Colors
This library has predefined colours. Selector `:root` defines those colours. You can change them to whatever you like.
### Headings 
You can use headings from `<h1>` to `<h6>`. Font sizes are: 
* 40px for `<h1>`
* 32px for `<h2>`
* 24px for `<h3>`
* 20px for `<h4>`
* 18px for `<h5>`
* 18px for `<h5>`
### Types of Text
The `<mark>` tag could be used for a vibrant yellow highlit of a text.
The `<code>` tag has a grey background and different font.
### Lists
There are two types of lists:
#### Unordered list
The `<ul>` tag defines an unordered list. Use the `<ul>` tag together with the `<li>` tag to create unordered lists. The bullet points are cute little bugs. Syntax:
```html
    <ul>
          <li>bug 1</li>
          <li>bug 2</li>
          <li>bug 3</li>
        </ul>
```
#### Ordered list
The `<ol>` tag defines an ordered list. An ordered list is numerical with roman numbers. The `<li>` tag is used to define each list item. Syntax:
```html
  <ol>
          <li>Ordered list item 1</li>
          <li>Ordered list item 2</li>
          <li>Ordered list item 3</li>
        </ol>
```
### Table
The table has definitions for the `<table>`, `<thead>`, `<th>` and `<td>` tags. Syntax:
```html
 <table>
          <thead>
            <tr>
              <th>Name</th>
              <th>Lifespan</th>
              <th>Size</th>
              <th>Favourite food</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Scarab beetle</td>
              <td>3 – 5 years</td>
              <td>5mm – 12cm</td>
              <td>Manure or on decomposing plant materials</td>
            </tr>
            <tr>
              <td>Stinkbug</td>
              <td>6 – 8 months</td>
              <td>1.7 cm</td>
              <td>agricultural crops</td>
            </tr>
            <tr>
              <td>Earwig</td>
              <td>approximately one year</td>
              <td>7 – 50 millimetres</td>
              <td>variety of insects and plants</td>
            </tr>
          </tbody>
        </table>
```
### Buttons
There are two variants of buttons. `class="button"` is used, than `class="button--full"` or `class="button--bordered"` depending on wich design you chose. Syntax:
```html
<a class="button button--full" href="#">Button</a>
<a class=" button button--bordered" href="#">Button</a>
```
### Pictures
Pictures are tranformed to have the aspect ratio of 1/1 and the figcaption is revealed upon hovering. Syntax:
```html
 <figure>
            <figcaption>yellow wall with shadows</figcaption>
            <img src="https://images.pexels.com/photos/4915833/pexels-photo-4915833.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="yellow wall with shadows">
          </figure>
```
