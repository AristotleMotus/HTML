https://www.w3schools.com/tags/tag_a.asp

# Definition and Usage
- The `<a>` tag defines a hyperlink, which is used to link from one page to another.
- The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.
- By default, links will appear as follows in all browsers:
  - An unvisited link is underlined and blue
  - A visited link is underlined and purple
  - An active link is underlined and red
- A linked page is normally displayed in the current browser window, unless you specify another target.

## `href` Sort
1. External Link
   1. Grammer
      ```
      <a href="URL">name</a>
      ```
   2. Description:
      Specifies the URL of the external page represented by `name`
   3. Example
      ```
      <a href="https://pages.github.com">GitHub Pages</a>
      ```
This site was built using <a href="https://pages.github.com">GitHub Pages</a>.
2. Anchor
   1. Grammer
      ```
      <a href="#id">name</a>
      ```  
   3. Description:
      How to link to another section on the same page
   5. Example
      ```
      <h1 id="unit1">Unit 1</h1>
      <a href="#sectionB">Go to Section B</a>
      <h2 id="sectionA">Section A</h2>
      <p>AAA</p>
      <h2 id="sectionB">Section B</h2>
      <p>AAA</p>
      ```
      <h1 id="unit1">Unit 1</h1>
      <a href="#sectionB">Go to Section B</a>
      <h2 id="sectionA">Section A</h2>
      <p>AAA</p>
      <h2 id="sectionB">Section B</h2>
      <p>BBB</p>
      
      <a name="object-name">Object</a>
      <a href="#object-name">Go to Object</a>
7.    1. Grammer
   2. Description:
   3. Example
      
8. 
      <html>
      <body>
        <h1 style="background-color:Blue;">Hello World</h1>
        <h2 style="color:Red;">Hello World</h2> 
      </body>
      </html>   
