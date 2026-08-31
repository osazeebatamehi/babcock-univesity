<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Payment</title>
<style>
  html, body {
    margin: 0;
    padding: 0;
    min-height: 100vh;
    background: #14173a;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .card {
    max-width: 420px;
    width: 100%;
    max-height: 95vh;
    box-shadow: 0 20px 60px rgba(0,0,0,0.35);
    border-radius: 12px;
    overflow: hidden;
    display: flex;
  }
  img {
    display: block;
    width: 100%;
    height: 95vh;
    object-fit: cover;
    object-position: top;
  }
</style>
</head>
<body>
  <div class="card">
    <img src="data:image/jpeg;base64,<...image data...>" alt="Payment details">
  </div>
</body>
</html>

