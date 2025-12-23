# Ex.05 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Cover</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #111;
            font-family: Arial, sans-serif;
        }

        .book-cover {
            width: 350px;
            height: 500px;
            position: relative;
            background-image: url("virat.jpg");
            background-size: cover;
            background-position: center;
            box-shadow: 0 10px 30px rgba(246, 243, 243, 0.7);
            border-radius: 8px;
            overflow: hidden;
        }

        
        .content {
            position: absolute;
            inset: 0;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 20px;
            z-index: 1;
            text-align: center;
        }

        .title {
            font-size: 26px;
            font-weight: bold;
            margin-top: 30px;
        }

        .subtitle {
            font-size: 16px;
            opacity: 0.9;
            margin-top: 10px;
        }

        .author {
            font-size: 18px;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="content">
            <div>
                <div class="title">THE SPIRIT OF VICTORY</div>
                
            </div>

            <div class="author">By Ganesh Kanna(25003130)</div>
        </div>
    </div>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (18).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
