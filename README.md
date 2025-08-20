# CSS-interview-questions
Css interview questions

### 1. Benifits of Sass ###

With features such as variables, nesting, and mixins, Sass enables developers to write cleaner, more efficient code. While CSS remains the fundamental language for styling web pages, Sass provides an extension that streamlines development and improves code reusability

### 2. What is a SASS in CSS? ###

SASS is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS)  
**Features** : - 
- Preprocessing (sass input.scss output.css)
- Variables    
  ```$font-stack: Helvetica, sans-serif;
   $primary-color: #333;
  body {
    font: 100% $font-stack;
    color: $primary-color;
  }```
- Nesting
- Partials - ( _partial.scss)  
- Modules
- Mixins
- Inheritance
- Operators
### 3. What is flexbos in css ###  
Flexbox is a layout method for arranging items in rows or columns. Flexbox makes it easier to design a flexible responsive layout structure  
>**Flex Container**  
`.flex-container {
  display: flex;
  }`  

**flex-direction**  
* row  
* column  
* row-reverse  
* column-reverse
   
**flex-wrap**    
* nowrap  
* wrap  
* wrap-reverse
  
**flex-flow**    
* row wrap
  
**justify-content**    
* center  
* flex-start  
* flex-end  
* space-around  
* space-between  
* space-evenly
  
**align-items**  
* center  
* flex-start  
* flex-end  
* stretch  
* baseline  
* normal
  
**align-content**  
* center  
* stretch  
* flex-start  
* flex-end  
* space-around  
* space-between  
* space-evenly

>**Flex Items**  
order  
flex-grow  
flex-shrink  
flex-basis  
flex  
align-self

### 4. CSS Pseudo-classes ###
A pseudo-class is used to define a special state of an element  
like - :active  :hover  :visited  
:checked  :empty  :enabled  :first  :first-child  :last-child  :first-of-type  :nth-child()  

### 5. CSS Pseudo-elements ###  
A CSS pseudo-element is used to style specific parts of an element.  
::after  ::before  
::first-letter  ::first-line  ::selection ::highlight() 

### 6. CSS 3 column layout with responsive ### 
```diff
#wrapper {
width:100%;
height:auto;
border:0px solid #ff0000;
+display:flex;
+flex-wrap: wrap;
padding:0px;
+gap:10px;
text-align:center;
}
div.test{
height:auto;
border:5px solid #ddd;
padding:10px;
+flex: 0 0 calc(33.3333% - 10px);
box-sizing:border-box;  
}
button{
  cursor:pointer;
}
@media (min-width: 0px) and (max-width: 500px) {
  div.test {
   flex: 0 0 calc(100% - 10px);
  }
}
@media (min-width: 501px) and (max-width: 720px) {
  div.test {
   flex: 0 0 calc(50% - 10px);
  }
}
```
### 7 -What is the CSS position property, and what is its default value? ###
**The position property controls** -  how an element is positioned on a webpage. Its default value is static.    
**Relative** -relative elements are positioned relative to their normal position in the document    
**Absolute** - absolute elements are removed from the normal document flow, and positioned relative to their closest positioned  
**fixed** - same position on the screen even when the page is scrolled  
**Sticky** - sticky elements behave like relative until a certain scroll position is reached, 
Note- property top, left, right, bottom , z-index

### 8- What is dom ###  
The Document Object Model (DOM) is a programming interface that represents an HTML document as a tree of nodes,  

### 9 - what is samentic element ###  
Semantic elements in HTML are tags that clearly describe their meaning and purpose to both the browser and the developer.  
**non-semantic elements** like <div> and <span>
Key characteristics of semantic elements:  
1- **Meaningful structure:** making it easier for humans and machines to understand the content.
2- **Improved accessibility:** Semantic elements enhance accessibility for users of assistive technologies like screen readers, 
3- **SEO benefits:** Search engines can more effectively understand the content and context of a page marked up with semantic elements, potentially leading to better search engine rankings.
**common semantic elements**
**<header>:** Represents introductory content or a set of navigational links.  
**<nav>:** Defines a section containing navigation links.  
**<main>**: Represents the dominant content of the <body>.  
**<article>**: Represents a self-contained composition in a document, page, application, or site, intended to be independently distributable or reusable.  
**<section>**: Represents a standalone section of content within an HTML document.  
**<aside>**: Represents a section of a page that consists of content tangentially related to the content around it.  
**<footer>**: Represents a footer for its nearest sectioning content or sectioning root element.  
**<figure>** and <figcaption>: Used for self-contained content like images, diagrams, or code snippets, with figcaption providing a caption.  
**<time>**: Represents a specific period in time or a date.  
