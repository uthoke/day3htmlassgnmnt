# day3htmlassgnmnt
<html>
<head>
<title>Responsive Card Layout</title>
<style>
.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 200px;
  height: 200px;
  margin: 10px;
}

.card img {
  width: 100%;
  height: auto;
}

.card h2 {
  margin-top: 0;
}

@media (max-width: 600px) {
  .card {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>
<div class="card">
  <img src="image.jpg" alt="Card image">
  <h2>Card title</h2>
  <p>This is the card content.</p>
</div>
<div class="card">
  <img src="image2.jpg" alt="Card image">
  <h2>Card title</h2>
  <p>This is the card content.</p>
</div>
<div class="card">
  <img src="image3.jpg" alt="Card image">
  <h2>Card title</h2>
  <p>This is the card content.</p>
</div>
</body>
</html>
