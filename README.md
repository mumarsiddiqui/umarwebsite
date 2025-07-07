# umarwebsite
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Mobile-Friendly Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; 
      padding: 20px;
      background: #f9f9f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
    }

    h1 {
      color: #333;
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p {
      color: #555;
      max-width: 90%;
      font-size: 1.1rem;
      line-height: 1.5;
      margin: 0 auto;
    }

    .btn {
      display: inline-block;
      margin-top: 30px;
      padding: 15px 30px;
      background: #007bff;
      color: #fff;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background: #0056b3;
    }

    @media (min-width: 768px) {
      body {
        padding: 40px;
      }
      h1 {
        font-size: 3rem;
      }
      p {
        max-width: 600px;
        font-size: 1.2rem;
      }
    }
  </style>
</head>
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a simple, responsive website that looks great on mobile devices too! You can easily customize it for your own projects.</p>
  <a href="#" class="btn">Learn More</a>
</body>
</html>
