# Frontend Mentor - NFT preview card component solution


This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

## Overview

### Screenshot

![](Screenshot.png)


### Link

- [Demo](https://azeezqad.github.io/frontend-mentor-challenges/nft-preview-card-component-main/)

### Built with

[![My Skills](https://skills.thijs.gg/icons?i=html,css)](https://skills.thijs.gg)


### What I learned

I learned how to make overlay effect to an image on hover.

```html
 <div class="container">
        <img src="./images/image-equilibrium.jpg" alt="equilibrium image" />
        <div class="overlay">
          <svg class="svg" width="48" height="48" xmlns="http://www.w3.org/2000/svg">
            <g fill="none" fill-rule="evenodd">
              <path d="M0 0h48v48H0z" />
              <path
                d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z"
                fill="#FFF"
                fill-rule="nonzero"
              />
            </g>
          </svg>
        </div>
      </div>
```

```css
     .container {
        position: relative;
        width: 100%;
      }
      img {
        width: 100%;
        border-radius: 10px;
      }

      .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        height: 100%;
        width: 100%;
        opacity: 0;
        transition: 0.5s ease;
        background-color: var(--cyan);
        border-radius: 10px;
      }

      .container:hover .overlay {
        opacity: 0.8;
        cursor: pointer;
      }

      .svg {
        color: white;
        font-size: 20px;
        position: absolute;
        top: 50%;
        left: 50%;
        -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
        text-align: center;
      }
```


### Continued development

I will continue practice and solving new challenges to improve my skills and keep learning new things everyday.


### Useful resources

- [How TO - Image Hover Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - I leared how to create a fading overlay effect to an image, on hover.

## Author

- Frontend Mentor - [@azeezqad](https://www.frontendmentor.io/profile/azeezqad)
