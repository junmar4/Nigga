<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Index</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
    
    body {
      background-color: #1e1e1e;
      font-family: 'Poppins', sans-serif;
      color: white;
    }
    
    div {
      display: grid;
      place-items: center;
      align-content: center;
      border: none;
      border-radius: 15px;
      margin: 15px 8px;
      background-color: #0d0d0d;
    }
    
    .div-1 {
      min-height: 500px;
    }
    
    .div-2 {
      min-height: 250px;
    }
    
    .div-3 {
      min-height: 100px;
    }
    
    h1, p {
      margin: 15px;
      text-align: center;
    }
    
    a {
      margin: 5px;
      text-align: center;
      text-decoration: none;
      color: lightseagreen;
      display: inline-block;
    }
    
    label {
      display: grid;
      place-items: center;
      align-content: center;
      font-size: 30px;
      font-weight: bold;
    }
    
    input {
      border: none;
      border-radius: 3px;
      padding: 8px 10px;
      margin: 20px 0;
      font-family: 'Poppins', sans-serif;
      color: black;
    }
    
    button {
      display: relative;
      place-items: center;
      align-content: center;
      border: none;
      border-radius: 3px;
      padding: 8px 10px;
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: black;
      background-color: #03e5ff;
      transition: background-color ease 0.5s;
    }
    
    button:hover {
      background-color: #02abbf;
    }
  </style>
</head>

<body>
  <div class="div-1">
    <h1>Introduction</h1>
    <p>Lorem ipsum dolor sit amet, suck my dick nigga.</p>
  </div>
  <div class="div-2">
    <form method="POST" action="">
      <label>Email</label>
      <input type="email" class="email" placeholder="example@gmail.com" required>
      <button type="submit" class="sumbit" id="submit">Submit</button>
    </form>
  </div>
  <div class="div-3">
    <a href="">About Us</a>
    <a href="">Contact Us</a>
  </div>
</body>
</html>
