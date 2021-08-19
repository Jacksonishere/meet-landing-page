# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot


![mobile](https://user-images.githubusercontent.com/44249712/130094137-bd7d6f98-1835-4c39-bcd4-50b0fda0e57f.mov)

![tablet](https://user-images.githubusercontent.com/44249712/130097425-9a92861b-2af8-4a81-bd13-3ddb79749bca.mov)

![desktop](https://user-images.githubusercontent.com/44249712/130097106-e73b1d7b-19cb-43ba-bf98-71aa54b1efd2.mov)



### Links

- Live Site URL: https://ecstatic-jones-2d0589.netlify.app/


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SASS


### What I learned
1. How to make a basic responsive image-grid using flex-box. 
2. Using the flex to break up the flex-box. 
3. Make sure background-image z-index is -1 otherwise the content becomes uninteractable because it is sitting on top. 
4. Margin: 0 auto centers the div but if given a max-width, as the screen grew, and the other elements in the flexbox also reached its max-width, margin auto would add margins to left/right because of the margin auto making the element out of place. Instead, what I did was use flex and just did align items center of the container that contains the hidden images the article. Since I had already handled the flex properties when it reached laptop screen size, I didn't have to change anything after that.

### Useful resources

- https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp


