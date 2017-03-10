# HW-Responsive-Portfolio

## Live Link: 
https://joycetio.github.io/Responsive-Portfolio/

## Instructions: (No Bootstrap)
1. Write your media queries at the bottom of the style.css. 
    * Use three @media screen tags, each with one of these max-widths: 980px, 768px, and 640px. 
    * You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off. 
    * 768px is about the width of a tablet and 640px is about the width of a phone in landscape. 
2. Make the position of the header static (the default positioning) when the screen is 640px wide. 
3. Be sure to include the viewport tag in all your HTML fiels, otherwise your media-queries won't function as expected on mobile devices. 

## Technologies Used: 
* HTML
* Media Queries for CSS 

## Code Explanation: 
By using media queries, the webpage becomes responsive based on the user's screen width, avoiding possible cut off of the page's content. Here's an example of what my code looks like for one of the media queries:  
````
@media screen and (max-width: 980px) {
  body {
    position: static;
  }

  #masthead {
    width: 980px;
  }

  #logo {
    width: 250px;
    margin-left: 50px;
  }

  nav {
    margin-right: 100px;
  }
};
````
