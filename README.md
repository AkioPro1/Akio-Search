# Akio-Search
Search For Answers.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My Search Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 150px;
      background-color: #f9f9f9;
    }
    img {
      max-width: 300px;
      height: auto;
      margin-bottom: 30px;
    }
    input[type="text"] {
      width: 400px;
      padding: 12px;
      font-size: 18px;
      border: 1px solid #ccc;
      border-radius: 24px;
      outline: none;
      box-shadow: 0 0 5px #aaa;
      transition: box-shadow 0.3s ease;
    }
    input[type="text"]:focus {
      box-shadow: 0 0 8px #4285f4;
      border-color: #4285f4;
    }
    input[type="submit"] {
      padding: 12px 25px;
      font-size: 16px;
      margin-left: 10px;
      border: none;
      background-color: #4285f4;
      color: white;
      border-radius: 24px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    input[type="submit"]:hover {
      background-color: #3367d6;
    }
    form {
      display: inline-block;
    }
  </style>
</head>
<body>

  <!-- Replace this src with your own logo URL -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/Logo_TV_2015.png" alt="My Logo" />

  <form action="https://www.google.com/search" method="GET">
    <input type="text" name="q" placeholder="Search Google..." required />
    <input type="submit" value="Search" />
  </form>

</body>
</html>
