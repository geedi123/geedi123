<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sticky Header Example</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #333;
      padding: 10px;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    /* Add additional styling as needed */

    section {
      height: 800px; /* Just for demo content */
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sticky Header</h1>
  </header>

  <section>
    <p>Your website content goes here.</p>
  </section>

</body>
</html>

