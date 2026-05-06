<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Aman Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      text-align: center;
    }
    header {
      background: #000;
      padding: 15px;
      font-size: 24px;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid red;
      box-shadow: 0 0 20px red;
      object-fit: cover;
      margin-top: 20px;
    }
    .btn {
      padding: 10px 20px;
      background: red;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .card {
      background: #222;
      margin: 10px;
      padding: 15px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<header>
  Aman Kumar Portfolio
</header>

<section>
  <!-- Yaha apna photo ka naam dalna -->
  <img src="myphoto.jpg" class="profile-img">

  <h2>Hello, I'm Aman 👋</h2>
  <p>I am a Graphic Designer & Editor</p>
  <button class="btn">Contact Me</button>
</section>

<section>
  <h2>My Skills</h2>
  <div class="card">Photo Editing</div>
  <div class="card">Poster Design</div>
  <div class="card">Thumbnail Design</div>
</section>

<section>
  <h2>Contact</h2>
  <p>Email: your@email.com</p>
</section>

</body>
</html>
