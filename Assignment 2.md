<!DOCTYPE html>
<html>
<head>
  <title>Responsive Card Layout</title>
  <style>
    .card-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      width: 300px;
      height: 300px;
      background-color: #f2f2f2;
      padding: 20px;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .card-title {
      font-size: 20px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .card-image {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    .card-content {
      font-size: 14px;
      color: #666666;
    }

    @media screen and (max-width: 600px) {
      .card {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="card-container">
    <div class="card">
      <h2 class="card-title">Card 1</h2>
      <img class="card-image" src="image1.jpg" alt="Card 1 Image">
      <p class="card-content">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    <div class="card">
      <h2 class="card-title">Card 2</h2>
      <img class="card-image" src="image2.jpg" alt="Card 2 Image">
      <p class="card-content">Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </div>
    <div class="card">
      <h2 class="card-title">Card 3</h2>
      <img class="card-image" src="image3.jpg" alt="Card 3 Image">
      <p class="card-content">Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
  </div>
</body>
</html>
