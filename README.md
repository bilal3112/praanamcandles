# Praanam Candles - Luxury Handmade Candle Website

This repository contains the source code for the official website of Praanam Candles, a brand specializing in luxurious, handmade candles for the modern soul. The website is a single-page, fully responsive design created to provide an elegant and seamless user experience.

**Tagline:** *Where Life Meets Light*

## ✨ Features

-   **Elegant & Modern Design:** A premium, visually appealing layout with a sophisticated purple color palette and elegant typography.
-   **Fully Responsive:** Optimized for a flawless experience on all devices, including desktops, tablets, and mobile phones.
-   **Dynamic Content:** Features smooth scroll animations, an offer marquee, and interactive product cards.
-   **Product Showcase:** A categorized shop section to display "New Arrivals" and the full collection.
-   **Interactive Card View:** A clean modal pop-up for viewing detailed product information without leaving the page.
-   **Instagram Integration:** "DM to Order" buttons seamlessly redirect customers to your Instagram business page (`praanam.candles`).
-   **Customizable:** Easily update product images, text, and prices by editing the HTML files.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, or Safari) to view the website.

### Installation

1.  **Clone the repo:**
    ```sh
    git clone [https://github.com/your_username/praanam-candles-website.git](https://github.com/your_username/praanam-candles-website.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd praanam-candles-website
    ```
3.  **Open `index.html` in your browser:**
    Simply double-click the `index.html` file, or right-click and choose "Open with" your preferred browser.

## 🎨 How to Customize

This website is designed to be easily customizable.

### 1. Updating Images

-   Place all your images inside the `assets/` folder.
-   Open `index.html` and `shop.html` in a text editor.
-   Find the `<img>` tags and replace the placeholder `src` paths (e.g., `assets/hero-background.png`) with the file names of your own images.
-   Make sure the product card `data-img` attributes are also updated with the correct image paths.

**Example:**
```html
<!-- Before -->
<img src="assets/mysore-sandalwood.png" alt="Mysore Sandalwood Candle">

<!-- After -->
<img src="assets/your-sandalwood-image.jpg" alt="Mysore Sandalwood Candle">
```

### 2. Updating Text and Prices

-   Open `index.html` and `shop.html`.
-   Locate the text you want to change (e.g., product descriptions, prices, testimonials).
-   Update the text directly in the HTML. For product cards, remember to update the text inside the `<h4>`, `<p>`, and `<span>` tags, as well as the `data-title`, `data-price`, and `data-description` attributes on the `view-btn` button to ensure the pop-up modal displays the correct information.

## 🛠️ Technologies Used

-   **HTML5:** For the structure and content of the website.
-   **Tailwind CSS:** For all styling and responsive design.
-   **JavaScript:** For interactive features like the mobile menu, product modal, and scroll animations.
-   **Google Fonts:** For the elegant typography (`Great Vibes`, `Playfair Display`, `Montserrat`).

## ✒️ Crafted By

This website was beautifully crafted by **Asad**.

---

Feel free to reach out with any questions!
