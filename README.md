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
