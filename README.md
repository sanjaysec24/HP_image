# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>⚡ Harry Potter Gallery ⚡</title>
  <style>
    body {
      font-family: "Cinzel", serif;
      margin: 0;
      padding: 0;
      color: white;
      text-align: center;
      background: 
        linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)),
        url("HPB.jpg") center center / cover no-repeat fixed;
    }

    .title {
      margin: 25px 0;
      font-size: 2.2em;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>
  <h1 class="title">⚡ Harry Potter Gallery ⚡</h1>

  <div class="gallery">
    <a href="hp1.png">
      <img src="hp1.png" alt="Hogwarts Castle">
    </a>
    <a href="her.png">
      <img src="her.png" alt="Harry Potter">
    </a>
    <a href="ron.png">
      <img src="ron.png" alt="Hermione Granger">
    </a>
    <a href="sns.png">
      <img src="sns.png" alt="Ron Weasley">
    </a>
    <a href="dum.png">
      <img src="dum.png" alt="Hogwarts Express">
    </a>
    <a href="vol.png">
      <img src="vol.png" alt="Dumbledore">
    </a>
  </div>
</body>
</html>
```
## OUTPUT

![alt text](<Screenshot 2025-11-09 105021.png>)
![alt text](<Screenshot 2025-11-09 105032.png>)
![alt text](<Screenshot 2025-11-09 105045.png>)
![alt text](<Screenshot 2025-11-09 105056.png>)
![alt text](<Screenshot 2025-11-09 105107.png>)
![alt text](<Screenshot 2025-11-09 105117.png>)
## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
