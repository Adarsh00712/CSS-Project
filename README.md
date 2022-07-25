
# CSS Project

Homepage of a Flipkart clone an E-Commerce Responsive Website by using Html and CSS.

## Task
***
Creating a homepage of an E-commerce website by using Html and CSS(Cascading Style Sheets) and their respective properties. Here the webpage is a clone of Flipkart which is an E-commerce website which is responsive in nature by using media queries.
## Skills
***
HTML and good knowledge of CSS. 
## Technologies
***
* [Visual Studio Code](https://code.visualstudio.com/Download) :Version 1.69
* [Github](https://github.com/) Version 5.10.3 
## Installation
***
Steps to install Visual Studio code:

* Click on [Visual Studio Code](https://code.visualstudio.com/Download) and install according to your operating system.
* Install Live server extention.
* Also install [Github Desktop](https://desktop.github.com/).

### Creating a CSS Project
***
* Folder -> CSS Project.
* File -> "index.html" and Css.
* Adding style.css, utils.css, responsive.css files under Css file
* Finish
## Execution
***
* After adding the Boilerplate code and titled the project I have linked the the .css files buy using link tag in head of index.html file.
* In body of index.html a header of website is created using a header tag with respective classes which further targeted in style.css to apply css on it.
* In header classes like "logo", "search" and "cart" is targeted in style.css file for styling.
* After creating header I added the footer of the webpage using footer tag to give copyright information by creating flex class which targeted in utilis.css using flex properties.
* Adding [google font](https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap) to footer in style.css file.
* Using  CSS pseudo-class root to use color #2874f0 in header and footer.
```bash
 :root {
    --main-bg-color: #2874f0;
  }
  ```
* Providing the gap between header and footer by targeting container class in style.css file.
```bash
.container{
    min-height: calc(100vh - 58px - 12vh);
}
```
* Inside the main tag in body of html a slider class is created inside container class to show images in slide using animation properties of css and targeted their respective class in style.css file.
```bash
<div class="container">
            <div class="slider">
                <img class="img1" src="https://source.unsplash.com/1600x400/?Shopping,Fashion" alt="">
                <img class="img2" src="https://source.unsplash.com/1600x400/?Shopping" alt="">
                <img class="img3" src="https://source.unsplash.com/1600x400/?Fashion" alt="">
            </div>
```
* An unsplash image API is used to provide different images for webpage with their respective links.
* @keyframes rule used inside utils.css to apply animation code for slider.
* Adding class card to add items inside using unslash image API links to different images and targeting the classes in style.css.
* Using my-1 and my-2 Bootstrap CSS class to target margin in utils.css .
* Similarly adding different items to our webpage.
* Using media queries adding responsiveness to our website for different dimensions of browsers.
```bash
@media screen and (max-width:1000px){
                           }
```







## Result
***
* The final layout of our webpage is open using live server extension to open in our local browser.

![CSS Project](https://github.com/Adarsh00712/CSS-Project/blob/master/Screenshots/1.png)

***
![CSS Project](https://github.com/Adarsh00712/CSS-Project/blob/master/Screenshots/2.png)

***
![CSS Project](https://github.com/Adarsh00712/CSS-Project/blob/master/Screenshots/3.png)
## Support
***
For Support email adarshdwivedi2@gmail.com
