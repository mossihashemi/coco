# CoCo
A Beautiful, Responsive, Fast and Pure HTML/CSS website.

## Editor
[Visual Studio Code (VSCode)](https://code.visualstudio.com/)
* Useful VSCode Extentions
  * **HTML CSS Support** (by ecmel)
  * **CSS Peek** (by Pranay Prakash)
  * **Prettier - Code formatter** (by Prettier)
    - In VSCode go to File > Prefrences > Settings (search for : format on save) > enable the "Editor:Format On Save"
  * **Highlight Matching Tag** (by vincaslt)
  * **TODO Highlight** (by Wayou Liu)
  * **Live Server** (by Ritwick Dey)

## Version Control System
[Git](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

## HTML
  - index.html
    - vscode trick  
       ``` 
       h${Heading $}*3
       <p>lorem50</p>
       ul>list>li{Item $}*3
       .media>.media__image+.media__body
       ```

     
## CSS
- [Normalize.css](https://necolas.github.io/normalize.css/)
  A modern, HTML5-ready alternative to CSS resets. It makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing. 
- style.css (Modular **mobile first** CSS, Bottom up(**components first**))
  - Color Palette
    ```
    :root {
    --color-primary: #2584ff;
    --color-secondary: #00d9ff;
    --color-accent: #ff3400;
    --color-Headings: #1b0760;
    --color-body: #918ca4;
    --color-border:   #ccc;
    }
    ```
   - Box-Sizing
     ```
        *,
        *::after,
        *::before{
         box-sizing: border-box;
         }
     ```
   - Typography
     - Set the **rem** size => 62.5% * of 16px = 10px
        ```
            html {
               font-size: 62.5%;
            }
            h1 {
              font-size: 7rem; /* 70px */
            }
       ```
     - Desktop version
       ```
       @media screen and (min-width: 1024px) {
         body {
            font-size: 1.8rem;
         }
       }
       ```
   - Image Sprite
      - is a single image that combined multiple images. with this, we reduce the number of HTTP send to the server.(optimization technic)
          google > svg sprite generator > [svgsprit](https://svgsprit.es/)
       
