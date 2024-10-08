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
   2. Description:
      How to link to another section on the same page
   3. Example
      1. Head <h>
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
      2. Custom Anchor Point
         ```
         <a name="objecta">Object A</a>
         <p>
         <a href="https://docs.github.com/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#custom-anchors">Some text I want to provide a direct link to, but which doesn't have its own heading.</a>
         </p>
         <a name="objectb">Object B</a>
         <a href="#objecta">Go to Object A</a>
         <p>BBB</p>
         ```
         <a name="objecta">Object A</a>
         <p>
           <a href="https://docs.github.com/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#custom-anchors">Some text I want to provide a direct link to, but which doesn't have its own heading.</a>
         </p>
         <a name="objectb">Object B</a>
         <a href="#objecta">Go to Object A</a>
         <p>BBB</p>

~~3. Internal Link~~
<details>
  <summary>Details</summary>
  1. Grammer
     ```
     <a href="#/URL">name</a>
     ```
  
  2. Description:
     Specifies the URL of the internal page represented by `name`
</details>

4. 说明
   1. Grammer
      ```
      <a href="/" title="A">Aa</a>
      ```

      <a href="https://google.com" title="Aa">Aa</a>

    3.  












    <html>
      <body>
        <h1 style="background-color:Blue;">Hello World</h1>
        <h2 style="color:Red;">Hello World</h2> 
      </body>
      </html>   

