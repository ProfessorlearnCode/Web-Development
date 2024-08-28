# Binary Bridges - Web Development Project

## Overview

**Binary Bridges** is a web development project that showcases my initial foray into creating a dynamic and visually appealing website. The site provides insight into various technologies, personal projects, and my background as a Computer Science major. This project demonstrates my skills in HTML, CSS, Bootstrap, and JavaScript while also reflecting my personal interests and professional aspirations.

## Features

- **Responsive Design**: The website is built using Bootstrap, ensuring it looks great on all devices.
- **Interactive Components**: The project includes interactive elements such as an accordion to showcase personal projects.
- **Navigation Bar**: A consistent navigation bar across all pages for easy access to different sections.
- **Hero Section**: A visually striking hero section introducing the website and its purpose.
- **Personal Showcase**: Detailed sections about me, my projects, and the technologies I use.
- **Footer**: A footer with links to inspiration sources, resources, and design tools used.

## File Structure

- `index.html`: The main landing page of the website, containing the introduction, personal information, and a showcase of personal projects.
- `index_style.css`: The custom CSS file specific to the styling of `index.html`.

## Index.html Breakdown

### 1. Navbar

The navigation bar is implemented using Bootstrap and includes:
- A brand logo that links back to the homepage.
- Three buttons: "Credits," "Application Form," and "Get Started," each leading to their respective pages.

### 2. Hero Section

The hero section introduces the website with the title "Binary Bridges" and a brief description of the project's purpose. This section also highlights the technologies used (HTML, CSS, JavaScript) with icons from Font Awesome.

### 3. About Me Section

This section provides an introduction to me, **Farzam Asad**, a Computer Science major at Lahore Garrison University. It includes a photo and a detailed description of my academic and personal interests.

### 4. Personal Projects Showcase

An accordion component showcases four personal projects:
- **Social Media Database System**: A Python-based program for database management.
- **Static & Dynamic Webscraper**: A web scraper for static and dynamic content.
- **ChatBot**: An interactive chatbot with a GUI built using Python and Tkinter.
- **Simple Linear Regression Model**: A linear regression model for predicting diabetes progression.

### 5. Footer

The footer provides links to inspiration sources, resources, and design tools. It also includes a back-to-top button for easy navigation. Code visualized further!


## 1. Get_Started.html Breakdown

1. **DOCTYPE and HTML Declaration**
    ```html
    <!doctype html>
    <html lang="en">
    ```
    - Specifies the document type and language of the document.

2. **Head Section**
    ```html
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <title>Get Started</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
      <link rel="stylesheet" href="index_style.css">
    </head>
    ```
    - Sets character encoding and viewport settings.
    - Includes Bootstrap CSS for styling and a custom stylesheet `index_style.css`.

3. **Body Section**
    ```html
    <body>
    ```

    - **Navbar - Redefined**
        ```html
        <div id="navbar">
          <nav class="navbar bg-body-tertiary">
              <div class="container" style="mix-blend-mode: multiply;">
                  <a class="navbar-brand" href="index.html">
                      <img id='brain-logo' src="images/logo2.png" alt="BinaryBrains" width="75" height="75">
                  </a>
                  <div class="buttons">
                      <h1 id="top"></h1>
                      <button id="credits-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Credits 🎉</button>
                      <button id="appl-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Application Form 📜</button>
                      <span>     </span>
                      <button id="gs-button" class="btn btn-success" style="background-color: lightblue; border: none; color:black; font-family: Poppins">Get Started</button>
                  </div>
              </div>
          </nav>
        </div>
        ```
        - Implements a Bootstrap navbar with buttons for navigation. Custom styles are applied to buttons and images.

    - **Header**
        ```html
        <div class="start-headline">
          <div class="headline-colorfilm">
            <div id="c-Headline">
              <h1 style="font-family: Poppins; font-size: 55px; font-weight: bolder;">
                Get Started
              </h1>
            </div>
          </div>
        </div>
        ```
        - Displays the main heading for the page.

    - **Recommendation Cards**
        ```html
        <div class="gs-body">
            <div id="text">
                <h5 style="font-family: Poppins;">If you want to get started and build cool websites then, here are the resources needed <br>👇</h3>
            </div>
            <div class="card-div">
                <div class="card" style="width: 17rem;">
                    <img src="images/html.jpg" class="card-img-top" alt="html">
                    <div class="card-body">
                      <h5 class="card-title">HTML</h5>
                      <p class="card-text">HTML (HyperText Markup Language) is the standard language for creating web pages. It structures the content and layout of a webpage using elements like headings, paragraphs, links, and images.</p>
                      <a href="https://www.w3schools.com/html/" class="btn btn-primary">Learn HTML!</a>
                    </div>
                </div>
                <div class="card" style="width: 17rem;">
                    <img src="images/CSS.jpeg" class="card-img-top" alt="html">
                    <div class="card-body">
                      <h5 class="card-title">CSS</h5>
                      <p class="card-text">CSS (Cascading Style Sheets) is used to style and layout web pages. It controls the visual presentation of HTML elements, including colors, fonts, and spacing, making web pages look attractive and consistent.</p>
                      <a href="https://www.w3schools.com/css/" class="btn btn-primary">Learn CSS!</a>
                    </div>
                </div>
                <div class="card" style="width: 17rem;">
                    <img src="images/js.jpg" class="card-img-top" alt="html">
                    <div class="card-body">
                      <h5 class="card-title">Javascript</h5>
                      <p class="card-text">JavaScript is a versatile programming language used to create dynamic and interactive web content. It enables features like form validation, animations, and real-time updates, enhancing user experience on websites.</p>
                      <a href="https://www.w3schools.com/js/" class="btn btn-primary">Learn JS!</a>
                    </div>
                </div>
            </div>
        </div>
        ```
        - Provides cards for HTML, CSS, and JavaScript, each with an image, description, and link to further learning resources.

    - **Footer - Visualized**
        ```html
        <div class="p-About">
          <div id="heading">
              <H1 style="font-family: Poppins; font-size: 100%; font-weight: bolder;"><a href="#top" style="text-decoration: none; font-size: 35px; color: black;"><i class="fa-solid fa-arrow-up"></i></a></H1>
          </div>
          <div id="footer">
              <div id="inspiration">
                  <h3>Inspiration</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">dropbox</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">github</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">HTML Cheat Sheet</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">google</a></li>
                      <li><a href="...; color:black">canva</a></li>
                     </ul>
              </div>
              <div id="resources">
                  <h3>Resources</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">CS50ai</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school-CSS</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">HTML cheat sheet</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">Font Awesome</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">bootstrap</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school-CSS</a></li>
                     </ul>
              </div>
              <div id="design">
                  <h3>Design</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">canva</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">figma</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">google</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">Font Awesome</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">bootstrap</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">freepik</a></li>
                     </ul>
              </div>
          </div>
        </div>
        ```
        - Provides links to inspirational sources, resources, and design tools.

    - **Scripts**
        ```html
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        <script>
          document.getElementById('credits-button').onclick = function() {
              window.location.href = 'credits.html'; // Replace with your actual link
          };
        
          document.getElementById('appl-button').onclick = function() {
              window.location.href = 'application_form.html'; // Replace with your actual link
          };


        
          document.getElementById('gs-button').onclick = function() {
              window.location.href = 'index.html'; // Replace with your actual link
          };
        </script>
        </body>
        </html>
        ```
        - Includes Bootstrap's JavaScript bundle for interactive elements and custom script for button navigation.

### 2. Credits.html Breakdown

1. **DOCTYPE and HTML Declaration**
    ```html
    <!doctype html>
    <html lang="en">
    ```
    - Specifies the document type and language of the document.

2. **Head Section**
    ```html
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <title>Credits</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
      <link rel="stylesheet" href="index_style.css">
    </head>
    ```
    - Sets character encoding and viewport settings.
    - Includes Bootstrap CSS for styling and a custom stylesheet `index_style.css`.

3. **Body Section**
    ```html
    <body>
    ```

    - **Navbar - Redefined**
        ```html
        <div id="navbar">
          <nav class="navbar bg-body-tertiary">
              <div class="container" style="mix-blend-mode: multiply;">
                  <a class="navbar-brand" href="index.html">
                      <img id='brain-logo' src="images/logo2.png" alt="BinaryBrains" width="75" height="75">
                  </a>
                  <div class="buttons">
                      <h1 id="top"></h1>
                      <button id="credits-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Credits 🎉</button>
                      <button id="appl-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Application Form 📜</button>
                      <span>     </span>
                      <button id="gs-button" class="btn btn-success" style="background-color: lightblue; border: none; color:black; font-family: Poppins">Get Started</button>
                  </div>
              </div>
          </nav>
        </div>
        ```
        - Implements a Bootstrap navbar similar to the "Get Started" page for navigation.

    - **Header**
        ```html
        <div class="start-headline">
          <div class="headline-colorfilm">
            <div id="c-Headline">
              <h1 style="font-family: Poppins; font-size: 55px; font-weight: bolder;">
                Credits
              </h1>
            </div>
          </div>
        </div>
        ```
        - Displays the main heading for the page.
        - Have similar functionality as "Get_started".

    - **Credits Content**
        ```html
        <div id="credits-body">
            <div id="text">
                <h4 style="font-family: Poppins;">This project was made possible with the help of various contributors and tools. Special thanks to:</h4>
                <ul>
                    <li><a href="https://github.com" style="text-decoration: none; color:black">GitHub</a> - Source control and collaboration platform.</li>
                    <li><a href="https://www.w3schools.com/" style="text-decoration: none; color:black">W3Schools</a> - Learning resources for web technologies.</li>
                    <li><a href="https://www.canva.com/" style="text-decoration: none; color:black">Canva</a> - Graphic design tool for visuals used in the project.</li>
                    <li><a href="https://www.figma.com/" style="text-decoration: none; color:black">Figma</a> - Design and prototyping tool used for mockups.</li>
                    <li><a href="https://getbootstrap.com/" style="text-decoration: none; color:black">Bootstrap</a> - CSS framework for responsive design.</li>
                    <li><a href="https://fontawesome.com/" style="text-decoration: none; color:black">Font Awesome</a> - Icons used in the project.</li>
                </ul>
            </div>
        </div>
        ```
        - Lists contributors and resources used in the project.

    - **Footer - Revisualized**
        ```html
        <div class="p-About">
          <div id="heading">
              <H1 style="font-family: Poppins; font-size: 100%; font-weight: bolder;"><a href="#top" style="text-decoration: none; font-size: 35px; color: black;"><i class="fa-solid fa-arrow-up"></i></a></H1>
          </div>
          <div id="footer">
              <div id="inspiration">
                  <h3>Inspiration</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">dropbox</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">github</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">HTML Cheat Sheet</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">google</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">canva</a></li>
                     </ul>
              </div>
              <div id="resources">
                  <h3>Resources</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">CS50ai</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school-CSS</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">HTML cheat sheet</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">Font Awesome</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">bootstrap</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">w3 school-CSS</a></li>
                     </ul>
              </div>
              <div id="design">
                  <h3>Design</h3>
                     <ul>
                      <li><a href="..." style="text-decoration: none; color:black">canva</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">figma</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">google</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">Font Awesome</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">bootstrap</a></li>
                      <li><a href="..." style="text-decoration: none; color:black">freepik</a></li>
                     </ul>
              </div>
          </div>
        </div>
        ```
        - Provides links to inspirational sources, resources, and design tools.

    - **Scripts**
        ```html
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        <script>
          document.getElementById('credits-button').onclick = function() {
              window.location.href = 'credits.html'; // Replace with your actual link
          };
        
          document.getElementById('appl-button').onclick = function() {
              window.location.href = 'application_form.html'; // Replace with your actual link
          };
        
          document.getElementById('gs-button').onclick = function() {
              window.location.href = 'index.html'; // Replace with your actual link
          };
        </script>
        </body>
        </html>
        ```
        - Includes Bootstrap's JavaScript bundle for interactive elements and custom script for button navigation.


# Application_Form.html

#### 1 Document Declaration
```html
<!DOCTYPE html>
<html lang="en">
```
- Declares the document type and language.

#### 2 Head Section
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form_style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Application Form</title>
</head>
```
- Sets the character encoding and viewport settings.
- Includes Bootstrap's CSS for responsive design and custom stylesheet `form_style.css`.

#### 3 Body Section
```html
<body>
<div class="nav-bar">
  <!--NAV BAR BOOTSTRAP IMPLEMENTED-->    
  <div id="navbar">
      <nav class="navbar bg-body-tertiary">
          <div class="container" style="mix-blend-mode: multiply;">
              <a class="navbar-brand" href="index.html">
                  <img id='brain-logo' src="images/logo2.png" alt="BinaryBrains" width="75" height="75">
              </a>
              <div class="buttons">
                  <h1 id="top"></h1>
                  <button id="credits-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Credits 🎉</button>
                  <button id="appl-button" class="btn btn-link" style="text-decoration: none; color:black; font-family: Poppins;">Application Form 📜</button>
                  <span>     </span>
                  <button id="gs-button" class="btn btn-success" style="background-color: lightblue; border: none; color:black; font-family: Poppins">Get Started</button>
              </div>
          </div>
      </nav>
  </div>
</div>
```
- **Navigation Bar**: Implemented using Bootstrap. Contains links to other pages and a logo that redirects to the home page. Redefination and similar to previous instances.

```html
<!--Background Adjust-->
<div class="body">
  <div class="color-film">
      <div class="reg-container">
          <div class="headline">
              <h1>Registration Desk</h1>
          </div>
          
          <!--User-information-->
          <div class="body-container">
              <form onsubmit="return validateForm()">
                  <div class="row">
                    <div class="col-25">
                      <label for="fname">First Name</label>
                    </div>
                    <div class="col-75">
                      <input type="text" id="fname" name="firstname" placeholder="Your name..">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-25">
                      <label for="lname">Last Name</label>
                    </div>
                    <div class="col-75">
                      <input type="text" id="lname" name="lastname" placeholder="Your last name..">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-25">
                      <label for="country">Country</label>
                    </div>
                    <div class="col-75">
                      <select id="country" name="country">
                        <option value=""></option>  
                        <option value="australia">Australia</option>
                        <option value="canada">Canada</option>
                        <option value="usa">USA</option>
                        <option value="pakistan">Pakistan</option>
                      </select>
                    </div>
                  </div>
                  <div class="row" style="margin-top: 10%;">
                      <input type="submit" value="Submit"> 
                  </div>
                </form>
          </div>
      </div>
  </div>
</div>
```
- **Registration Form**: Contains input fields for first name, last name, and country with a submit button.

#### 4 Scripts
```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

<script>
  document.getElementById('credits-button').onclick = function() {
      window.location.href = 'credits.html'; // Replace with your actual link
  };

  document.getElementById('appl-button').onclick = function() {
      window.location.href = 'application_form.html'; // Replace with your actual link
  };

  document.getElementById('gs-button').onclick = function(){
    window.location.href = 'get_started.html';
  }
  document.getElementById('brain-logo').onclick = function(){
    window.location.href = 'index.html';
  }
</script>  

<script>
function validateForm() {
    let fname = document.getElementById('fname').value;
    let lname = document.getElementById('lname').value;
    let country = document.getElementById('country').value;

    console.log(fname, lname, country); // Debugging

    if (fname && lname && country) {
        window.location.href = 'index.html';
        alert("Incomplete feature - Redirecting to home page!");
        return true; // Form is valid
    } else {
        alert("Please fill out all fields.");
        return false; // Prevent form submission
    }
}
</script>
```
- **Bootstrap JS**: Includes Bootstrap's JavaScript bundle for interactive elements.
- **Custom JavaScript**: Handles navigation for buttons and form validation.

## Styling

- **Custom CSS (`form_style.css`)**: Defines the styles for the form and page layout.

## Features

- **Responsive Design**: Utilizes Bootstrap for a responsive layout.
- **Form Validation**: Ensures that all fields are filled before submission.
- **Navigation**: Provides buttons to navigate to other pages and a logo to return to the home page.

## Usage

1. **Open the Page**: Load `index.html` in a web browser.
2. **Navigate**: Use the navigation buttons to move between pages.
3. **Submit Form**: Fill in the form and submit. The form will redirect to the home page if validation passes.

## Dependencies

- **Bootstrap**: For styling and responsive design.
- **Custom CSS**: For additional page-specific styles.


# CSS Styles for Web Pages

## Overview

This CSS file includes styles for the Index, Credits, and Getting Started pages of the web application. It provides layout and design elements such as hero sections, responsive containers, and custom styling for various components. The stylesheet uses Google Fonts, custom colors, and background images to enhance the visual appeal of the pages.

## CSS Breakdown

### 1. Global Styles

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
```
- **Google Fonts Import**: Imports the Poppins font for use throughout the stylesheet.

### 2. Hero Section

```css
.hero-section {
    background-image: url(images/collab.png);
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: auto;
    max-width: 100%;
    max-height: 100%;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
```
- **Background Image**: Sets a background image with no repeat and cover size for the hero section.
- **Flexbox**: Centers content both horizontally and vertically.

### 3. Hero Headline and Content

```css
.hero-headline-colorfilm {
    background-color: rgba(173, 216, 230, 0.7);
    height: 100%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: left;
}

#content {
    margin-right: 8%;
    padding: 10%;
}

#headline {
    font-family: Poppins;
    font-size: 70px;
    font-weight: bolder;
}

#hbody {
    font-family: Poppins;
    font-weight: lighter;
}
```
- **Background Color**: Applies a semi-transparent background color.
- **Padding and Margin**: Adds padding and margin for spacing.
- **Typography**: Defines font properties for headlines and body text.

### 4. Logos and Technology Icons

```css
#logos {
    display: flex;
    text-align: left;
}

.fa-html5 {
    font-size: 50px;
    padding-right: 7px;
    color: #e34c26;
}

.fa-css3-alt {
    font-size: 50px;
    padding-right: 7px;
    color: #264de4;
}

.fa-js {
    font-size: 50px;
    padding-right: 7px;
    color: #f0db4f;
}
```
- **Flexbox**: Aligns logos in a row.
- **Icon Styles**: Sets sizes and colors for HTML, CSS, and JavaScript icons.

### 5. Image and About Sections

```css
#Image {
    text-align: right;
    padding-right: 80px;
    z-index: 3;
    width: 17%;
    mix-blend-mode: multiply;
    margin-left: 5%;
}

#logo-img {
    width: 500px;
}

.About {
    width: 100%;
    margin-top: 5%;
    margin-bottom: 5%;
}

#heading {
    text-align: center;
    padding-top: 1%;
    padding-bottom: 1%;
}
```
- **Image Alignment**: Positions and styles images.
- **About Section**: Adds margin and centering for headings.

### 6. Content Container

```css
.content-container {
    background-color: lightblue;
    min-height: 200px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

#face {
    text-align: center;
    padding: 35px;
}

#photo {
    width: 350px;
    border-radius: 53%;
    overflow: hidden;
}

#intro-content {
    padding: 36px;
    margin-right: 6%;
    width: 100%;
}

@media (max-width: 600px) {
    .content-container {
        flex-direction: column;
        align-items: center;
    }
    
    #intro-content {
        width: 90%;
        margin-right: 0;
    }
    
    #photo {
        width: 80%;
    }
}
```
- **Responsive Design**: Adjusts layout and sizes for smaller screens.
- **Flexbox**: Centers content and adjusts direction for mobile view.

### 7. Footer

```css
.p-About {
    width: 100%;
    height: 400px;
    margin-bottom: 20px;
}

.fa-arrow-up {
    font-size: 50px;
}

#footer {
    padding-top: 2%;
    padding-left: 2%;
    font-family: Poppins;
    display: flex;
    flex-wrap: wrap;
    overflow: auto;
    justify-content: space-between;
    background-color: lightblue;
    height: fit-content;
    max-height: 450px;
    width: auto;
}

#inspiration, #resources, #design {
    width: 15%;
    height: fit-content;
}
```
- **Footer Layout**: Styles the footer with flexbox for layout and responsiveness.

### 8. Credits and Getting Started Sections

```css
.creds-headline {
    background-image: url(images/credits.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 200px;
    max-height: 200px;
    width: auto;
    max-width: auto;
    background-color: lightblue;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.start-headline {
    background-image: url(images/start\ cropped.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 200px;
    max-height: 200px;
    width: auto;
    max-width: auto;
    background-color: lightblue;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

.headline-colorfilm {
    background-color: rgba(173, 216, 230, 0.7);
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

#c-Headline {
    text-align: center;
    width: fit-content;
    z-index: 5;
}

.creds-body {
    height: auto;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    padding-top: 5%;
}

#creds-content {
    width: 50%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.content {
    margin-right: 1%;
}

#picture {
    display: flex;
    align-items: center;
    justify-content: center;
}

@media (max-width: 600px) {
    img {
        width: 100%;
        margin-top: 0;
    }
}

.gs-body {
    margin: 5%;
    text-align: center;
}

.card-div {
    margin-top: 3%;
    display: flex;
    justify-content: space-evenly;
}

.card-text {
    font-family: Poppins;
    font-size: 13px;
}
```
- **Background Images**: Applies images to the credits and getting started sections.
- **Flexbox Layout**: Centers and spaces content within these sections.
- **Responsive Adjustments**: Ensures images and layout adapt to smaller screens.

## Usage

1. **Include the CSS File**: Add a link to this stylesheet in the `<head>` section of your HTML files.
2. **Apply Classes**: Use the defined classes in your HTML elements to apply styles.
3. **Modify as Needed**: Adjust the styles to fit your design requirements or branding guidelines.

## Dependencies

- **Google Fonts**: Poppins font for typography.
- **Background Images**: Ensure images are available in the specified paths.


# CSS Styles for Application Form

## Overview

This CSS file includes styles specifically for the application form page. It provides layout and design elements for a registration form, including background images, form field styling, and responsive design.

## CSS Breakdown

### 1. Global Styles

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
```
- **Google Fonts Import**: Imports the Poppins font for consistent typography.

### 2. Body Styles

```css
.body {
    background-image: url(images/online-reg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    margin: 0;
    font-family: Poppins;
}
```
- **Background Image**: Sets a full-page background image for the body.
- **Font Family**: Applies the Poppins font to the entire body.

### 3. Color Film Overlay

```css
.color-film {
    background-color: rgba(173, 216, 230, 0.7); /* lightblue with 70% opacity */
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
```
- **Overlay Styling**: Creates a semi-transparent light blue overlay that covers the entire form area.

### 4. Registration Container

```css
.reg-container {
    min-height: auto;
    width: 500px;
    min-width: auto;
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
}
```
- **Container Styling**: Defines the appearance and layout of the registration form container, including background color, padding, and border radius.

### 5. Form Field Styling

```css
input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    resize: vertical;
}
```
- **Form Inputs**: Styles text inputs, select dropdowns, and textareas for consistency in size, padding, and border appearance.

### 6. Label Styling

```css
label {
    padding: 12px 12px 20px 0;
    display: inline-block;
}
```
- **Labels**: Styles labels to align with form inputs.

### 7. Submit and Reset Buttons

```css
input[type=submit] {
    background-color: lightblue;
    color: black;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    float: right;
}

input[type=reset] {
    background-color: lightblue;
    color: black;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    float: left;
}
```
- **Buttons Styling**: Applies consistent styling for submit and reset buttons, including background color, padding, border radius, and cursor type. The submit button floats to the right, while the reset button floats to the left.

### 8. Column Layout

```css
.col-25 {
    float: left;
    width: 25%;
    margin-top: 6px;
}

.col-75 {
    float: left;
    width: 75%;
    margin-top: 6px;
}
```
- **Column Styling**: Defines floating columns for labels (25% width) and form fields (75% width).

### 9. Clear Floats

```css
.row:after {
    content: "";
    display: table;
    clear: both;
}
```
- **Clearing Floats**: Ensures that the container wraps around floated elements to avoid layout issues.

### 10. Responsive Design

```css
@media screen and (max-width: 600px) {
    .col-25, .col-75, input[type=submit] {
        width: 100%;
        margin-top: 0;
    }
}
```
- **Responsive Layout**: Adjusts column widths and button layout for screens narrower than 600px, ensuring a mobile-friendly design.

## Usage

1. **Include the CSS File**: Add a link to this stylesheet in the `<head>` section of your HTML file that includes the application form.
2. **Apply Classes**: Use the defined classes and IDs in your HTML to apply styles to the form elements.
3. **Modify as Needed**: Adjust the styles to fit your specific design needs or branding.

## Dependencies

- **Google Fonts**: Poppins font for typography.
- **Background Images**: Ensure images are available in the specified paths.

## Contribution

Feel free to submit issues or pull requests if you have improvements or fixes for this stylesheet.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

