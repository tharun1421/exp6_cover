# Ex.06 Book Front Cover Page Design
## Date:12-12-2025

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
```
Cover.HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Cover</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="book-cover">
        <div class="content">
            <h1>The Biography of DRAGON</h1>
            <p class="tagline">Unleash the power within yourself</p>

            <span>By tharun d
                (25014765)
            </span>
            
        </div>
    </div>

</body>
</html>

style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Georgia", serif;
}


body {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #0f0f0f;
}


.book-cover {
    width: 400px;
    height: 600px;

    background-image: url("image-cover.jpeg.jpeg");
    background-size: cover;
    background-position: center;

    position: relative;
    border-radius: 12px;
    box-shadow:
        0 10px 25px rgba(0,0,0,0.7),
        inset 0 0 0 1px rgba(221, 216, 216, 0.13);
    overflow: hidden;
}


.content {
    position: relative;
    height: 100%;
    padding: 36px 28px;

    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: center;
    color: #ffffff;
}

.content h1 {
    font-size: 34px;
    font-weight: 600;
    letter-spacing: 2px;
    line-height: 1.2;
    text-transform: uppercase;
}


.tagline {
    font-size: 20px;
    font-style: italic;
    color: #ffffff;
    letter-spacing: 1px;
    margin: 12px 0 25px;
    text-align: top;
}

.content span {
    font-size: 14px;
    letter-spacing: 1px;
    opacity: 0.9;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-28 150648.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
