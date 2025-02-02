# Penguin Fashion - E-commerce Landing Page

## Overview
This is a simple e-commerce landing page for "Penguin Fashion" built using **HTML** and **Tailwind CSS**. The page showcases a navigation bar, a hero section, and a product display section with stylish cards.

## Technologies Used
- **HTML5**
- **Tailwind CSS**
- **Google Fonts**

## Features
- Responsive design for different screen sizes
- Attractive gradient buttons
- Product showcase with images and pricing

## Code Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penguin Fashion</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Work Sans', sans-serif;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="flex justify-between p-4 bg-white shadow-md">
        <h2 class="text-xl font-bold">Penguin Fashion</h2>
        <ul class="flex gap-6">
            <li><a href="#" class="hover:text-gray-500">Home</a></li>
            <li><a href="#" class="hover:text-gray-500">Shop</a></li>
            <li><a href="#" class="hover:text-gray-500">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="bg-gray-100 py-12 px-6 flex flex-col md:flex-row items-center justify-center gap-8">
        <div class="max-w-lg">
            <h1 class="text-4xl font-bold">Be the Penguins of Winter</h1>
            <p class="text-lg text-gray-600 mt-4">Stay warm and stylish with our latest collection.</p>
            <button class="mt-6 px-8 py-4 rounded-xl font-medium text-white bg-gradient-to-r from-[#A4BC46] to-[#85A019] hover:opacity-80 transition">Shop Now</button>
        </div>
        <img class="w-80 md:w-96" src="images/model.png" alt="Winter Fashion Model">
    </header>

    <!-- Product Section -->
    <section class="px-6 py-12">
        <h2 class="text-2xl font-bold text-center mb-8">Our Collection</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Product Card -->
            <div class="p-6 shadow-lg rounded-lg">
                <img class="w-full h-64 object-cover" src="images/jacket-1.png" alt="Yellow Coat Jacket">
                <h3 class="text-lg font-semibold mt-4">Yellow Coat Jacket</h3>
                <p class="text-gray-600">Stay cozy and fashionable.</p>
                <button class="mt-4 px-6 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition">Buy Now</button>
            </div>
            <!-- Repeat for other products -->
        </div>
    </section>
</body>
</html>
```

## How to Use
1. Clone or download the repository.
2. Open the `https://shams-saniat.github.io/penguin-fashion-using-tailwind/` file in a browser.
3. Ensure that images are correctly placed in the `images/` folder.
4. Customize the text and styles as needed.

## Screenshots
_Include screenshots of your page here if needed._

## License
This project is open-source and free to use.

