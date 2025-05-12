# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Professional Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1 id="main-title">Business Launchpad</h1>
    <p class="tagline">Empowering your entrepreneurial journey.</p>
  </header>

  <section class="intro">
    <p>Welcome to your next big opportunity. Whether you're starting a new business or expanding an existing one, our platform is designed to support your growth.</p>
  </section>

  <img src="https://images.pexels.com/photos/3184465/pexels-photo-3184465.jpeg" alt="Teamwork" class="hero-image">

  <footer>
    <p class="footer-note">Contact us at: info@businesslaunchpad.com</p>
  </footer>

</body>
</html>




/* General styling for body */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
  margin: 0;
  padding: 0 20px;
}

/* ID selector */
#main-title {
  color: #2c3e50;
  text-align: center;
  font-size: 36px;
  margin-top: 40px;
  border-bottom: 2px solid #d4af37;
  padding-bottom: 10px;
}

/* Class selector for intro paragraph */
.intro {
  background-color: white;
  padding: 20px;
  margin: 30px auto;
  max-width: 700px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
}

/* Styling for image */
.hero-image {
  display: block;
  margin: 30px auto;
  width: 100%;
  max-width: 700px;
  border-radius: 10px;
  border: 3px solid #d4af37;
}

/* Another class selector */
.tagline {
  text-align: center;
  font-style: italic;
  color: #555;
  margin-top: -10px;
}

/* Footer styling */
.footer-note {
  text-align: center;
  font-size: 14px;
  color: #888;
  margin: 50px 0;
}



  
