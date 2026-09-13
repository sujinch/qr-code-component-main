# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I organized every thing inside div sections to make styling easier.
Container : is a div section I used to represent the card.
qrImg : is just the Qr code image.
card__content: is a div section I used so styling the text would be easier.
h1: is the card title I used the font Outfit weight 700  size 22px.
p: is the card description I used the font Outfit weight 400  size 15px on desktop and 22px on mobile device.



### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned
I discovered the concept of Figma file for the first time. 
I feel like my HTML coding is quite structured. 
I wondered how to handle mobile design until I recalled Responsive design:
Proud of this css:
```css
@media screen and (max-width: 375px) {
    .container{
        width: 320px;
        height: 540px;
    }  
    
    .card__content{
        width: 288px;
        height: 172px;
    }

    .card__content p{
        font-size: 22px;
    }
    
}
```

### Continued development
I found it challenging to understand Figma files, so I want to learn more about them. I need to revisit the responsive design concept, so I will devote more time to it.

### AI Collaboration

-GitHub Copilot:
When I couldn't pinpoint what I was  doing wrong, I asked Copilot to review my code. For instance, I struggled to center the text within the card, even though my CSS code seemed correct to me. Thus, I sought help from Copilot to review my CSS stylesheet and identify what I had done incorrectly.

-Google Gimini:
I ask Gimin about syntax or how to do things when I forget; for example, I forgot how to do responsive design, so I asked Gimini about it.

both tools worked really well for me.

## Author

- Frontend Mentor - [@Sujinch](https://www.frontendmentor.io/profile/yourusername)
