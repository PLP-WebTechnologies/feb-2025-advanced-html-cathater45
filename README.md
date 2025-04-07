# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample HTML5 Document</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f5f5f5;
        }
        header, footer {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        main {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <main>
        <h2>About This Page</h2>
        <p>This is a simple and clean HTML5 document structure. It includes a header, main content, and footer section.</p>
    </main>

    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>

</body>
</html>

- Ensure semantic correctness.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Semantic HTML5 Example</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
    }
    header, footer {
      background-color: #2c3e50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      background-color: white;
    }
    section {
      margin-bottom: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Semantic HTML5 Page</h1>
    <nav>
      <a href="#about" style="color: white; margin-right: 15px;">About</a>
      <a href="#contact" style="color: white;">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About This Page</h2>
      <p>This page demonstrates the use of semantic HTML5 elements to structure a clean and accessible document.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>If you have any questions, feel free to reach out at <a href="mailto:info@example.com">info@example.com</a>.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Website. All rights reserved.</p>
  </footer>

</body>
</html>
