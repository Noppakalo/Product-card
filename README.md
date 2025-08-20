# Frontend Mentor - Product preview card component

## Table of contents

-   [Overview](#overview)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### Screenshot

#### Desktop

![Desktop Screenshot](./design/desktop-design.png)

#### Mobile

![Mobile Screenshot](./design/mobile-design.png)

### Links

-   Solution URL: [https://github.com/Noppakalo/Product-card.git](https://github.com/Noppakalo/Product-card.git)
-   Live Site URL: [https://noppakalo.github.io/Product-card/](https://noppakalo.github.io/Product-card/)

## My process

### Built with

-   Flexbox
-   Mobile-first workflow
-   Semantic HTML5 markup
-   [Tailwind CSS](https://tailwindcss.com/) - Css Framework

### What I learned

-   Write tailwind css

 <main class="container flex items-center justify-center m-auto h-svh">
            <div
                class="max-w-lg w-full h-[400px] flex bg-white rounded-lg max-md:flex-col max-md:h-[650px] mx-4"
            >
                <img
                    src="./images/image-product-desktop.jpg"
                    alt="image-product-desktop"
                    class="w-1/2 object-cover rounded-l-lg max-md:w-full max-md:rounded-t-lg max-md:rounded-bl-none max-md:size-80 max-md:object-[65%_25%]"
                />
                <div
                    class="w-1/2 p-6 flex flex-col justify-between max-md:w-full max-md:h-full"
                >
                    <p
                        class="text-xs font-medium text-[var(--gray)] tracking-[0.5em]"
                    >
                        PERFUME
                    </p>
                    <h1>Gabrielle Essence Eau De Parfum</h1>
                    <p class="text-xs/5 font-medium text-[var(--gray)]">
                        A floral, solar and voluptuous interpretation composed
                        by Olivier Polge, Perfumer-Creator for the House of
                        CHANEL.
                    </p>
                    <div class="flex items-center gap-6">
                        <p class="text-2xl font-bold text-[var(--green500)]">
                            $149.99
                        </p>
                        <p
                            class="text-xs font-medium line-through text-[var(--gray)]"
                        >
                            $169.99
                        </p>
                    </div>
                    <button
                        class="bg-[var(--green500)] px-4 py-2.5 rounded-lg text-xs text-white font-medium cursor-pointer hover:bg-[var(--green700)]"
                    >
                        <img
                            src="./images/icon-cart.svg"
                            alt="add to cart"
                            class="inline-block mr-2 w-3.5 h-3.5"
                        /><span>Add to Cart</span>
                    </button>
                </div>
            </div>
        </main>

-   Responsive design support all device

### Continued development

-   CSS Animations
-   Accessibility (a11y)

### Useful resources

-   [Google Fonts](https://fonts.google.com/) - Used the Outfit font family from here for this project.
-   [Tailwind CSS](https://tailwindcss.com) - Used style css from project

## Author

-   Frontend Mentor - [@Noppakalo](https://www.frontendmentor.io/profile/Noppakalo)
