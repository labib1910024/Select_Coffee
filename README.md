# Starbucks Landing Page Clone

A visually engaging and responsive **Starbucks-themed landing page** created using **HTML**, **CSS**, and **JavaScript**. The page includes product image swapping and dynamic background color changes based on user interaction.

## Live Website
https://labib1910024.github.io/Select_Coffee/

## Features

- Eye-catching layout with modern design
- Interactive coffee cup image that updates when thumbnails are clicked
- Dynamic background color transition based on selected product
- Smooth hover animations
- Fully responsive for various screen sizes (with minor adjustments)

##  Demo

To see the live preview:
- Open `index.html` in any modern web browser


## How It Works

- The `header` contains a logo and a navigation bar.
- The main `content` section showcases a coffee cup image and promotional text.
- Below the cup, a series of thumbnail buttons (`thumb`) allow users to:
  - Change the main coffee image
  - Dynamically switch the theme color
- A decorative `.circle` background also changes color based on the selection.
- Social media icons (`.sci`) float vertically on the side.

    document.querySelector('.starbucks').src = image;
}

function changecolor(color){
    const circle = document.querySelector('.circle');
    circle.style.background = color;
}
