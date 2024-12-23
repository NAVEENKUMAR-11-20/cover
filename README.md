# Ex.06 Book Front Cover Page Design
## Date: 09.12.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

HTML CODE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <link rel="stylesheet" href="app.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lucide/0.344.0/lucide.min.css">
</head>
<body>
    <div class="container">
        <div class="book-cover">
            <!-- Pattern Overlay -->
            <div class="pattern-overlay"></div>

            <!-- Content Container -->
            <div class="content">
                <!-- Top Section -->
                <div class="top-section">
                    <i class="lucide-book-open"></i>
                    <div class="bestseller">BESTSELLER</div>
                </div>

                <!-- Middle Section -->
                <div class="middle-section">
                    <h1>The Art of Modern Development</h1>
                    <p>A comprehensive guide to building scalable applications</p>
                </div>

                <!-- Bottom Section -->
                <div class="bottom-section">
                    <div class="separator"></div>
                    <p class="author">Sarah J. Thompson</p>
                </div>
            </div>
        </div>
    </div>
    <script src="https://unpkg.com/lucide@latest"></script>
</body>
</html>

CSS CODE:

*{
margin: 0;
padding: 0;
box-sizing: border-box;
}

body {
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
background-color: #111827;
min-height: 100vh;
display: flex;
align-items: center;
justify-content: center;
padding: 2rem;
}
.container {
perspective: 1000px;
}
.book-cover {
position: relative;
width: 400px;
height: 600px;
background: linear-gradient(135deg, #4f46e5 0%, #7e22ce 100%);
border-radius: 0.5rem;
box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
overflow: hidden;
color: white;
transition: transform 0.3s ease;
}

.book-cover:hover {
transform: rotateY(10deg);
}


.pattern-overlay {
position: absolute;
inset: 0;
opacity: 0.1;
background-image: url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjAiIGhlaWdodD0iNjAiIHZpZXdCb3g9IjAgMCA2MCA2MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0zNiAzNGM0LjQxOCAwIDgtMy41ODIgOC04cy0zLjU4Mi04LTgtOC04IDMuNTgyLTggOCAzLjU4MiA4IDggOHptMC0yYzMuMzE0IDAgNi0yLjY4NiA2LTZzLTIuNjg2LTYtNi02LTYgMi42ODYtNiA2IDIuNjg2IDYgNiA2eiIgZmlsbD0iI2ZmZiIvPjwvZz48L3N2Zz4=');
}

.content {
position: relative;
height: 100%;
display: flex;
flex-direction: column;
justify-content: space-between;
padding: 2.5rem;
}

.top-section {
display: flex;
flex-direction: column;
gap: 0.5rem;
}

.lucide-book-open {
width: 3rem;
height: 3rem;
margin-bottom: 1rem;
}

.bestseller {
font-size: 0.875rem;
font-weight: 500;
letter-spacing: 0.05em;
}

.middle-section {
display: flex;
flex-direction: column;
gap: 1.5rem;
}

.middle-section h1 {
font-size: 3rem;
font-weight: 700;
line-height: 1.2;
}

.middle-section p {
font-size: 1.25rem;
font-weight: 300;
color: rgba(255, 255, 255, 0.9);
}

.bottom-section {
display: flex;
flex-direction: column;
gap: 1rem;
}

.separator {
width: 4rem;
height: 2px;
background-color: rgba(255, 255, 255, 0.5);
border-radius: 9999px;
}

.author {
font-size: 1.5rem;
font-weight: 500;
}

@media (max-width: 480px) 
{
.book-cover {
    width: 320px;
    height: 480px;
}

.middle-section h1 {
    font-size: 2.25rem;
}

.middle-section p {
    font-size: 1rem;
}

.author {
    font-size: 1.25rem;
}
}

## OUTPUT:

![alt text](<Screenshot 2024-12-09 185901.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
