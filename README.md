<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PAKMART</title>
  
  <style>



    /* Reset styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    /* Header */
    header {
      background-color: #ef0707fd;
      color: #fff;
      padding: 10px 20px;
    }

    header .logo {
      font-size: 24px;
      font-weight: bold;
      text-align: center;
    }

    header .search-bar {
      margin: 10px 0;
      display: flex;
      justify-content: center;
    }

    header input[type="text"] {
      width: 50%;
      padding: 8px;
      border: none;
      border-radius: 20px;
    }

  /* Navigation Bar */
  nav {
      background-color: #fff;
      padding: 10px 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 1000; }

      nav ul {
      list-style: none;
      display: flex;
      justify-content: space-around;
    }

    nav ul li {
      display: inline;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-size: 16px;
      padding: 10px;
    }

    nav ul li a:hover {
      color: #ff3f6c; }

    body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        .product-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 1rem;
            padding: 2rem;
        }

        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
            padding: 1rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .product img {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 0.5rem;
        }

        .product h2 {
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }

        .product p {
            font-size: 1rem;
            color: #666;
        }

        .buy-now {
            background-color: red;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.2s;
        }

        .buy-now:hover {
            background-color: darkred;
        }



    /* Footer */
    footer {
      background-color: #0a0909;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    </style>

</head>






<body>
  <!-- Header -->
  <header>

   

    <div class="logo">WELCOME TO PAKMART</div>
    <div class="search-bar">
      <input type="text" placeholder="Search for products, brands and more">
    </div>
  </header>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#">Men</a></li>
      <li><a href="#">Women</a></li>
      <li><a href="#">Kids</a></li>
      <li><a href="#">Home & Living</a></li>
      <li><a href="#">Beauty</a></li>
    </ul>
  </nav>
<hr>

<img src="pakmart.jpg" width="100%" height="500">


<br>

<pre><h1>                                  MEDAL WORTHY BRAND TO CHANGE</h1></pre>

  

    <br>
    <br>
  
 <body>
  

    <div class="product-container">
      <div class="product">
          <img src="jacket.jpg" alt="Product 1">
          <h2>Product 1</h2>
          <p>$10.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 2">
          <h2>Product 2</h2>
          <p>$20.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 3">
          <h2>Product 3</h2>
          <p>$30.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 4">
          <h2>Product 4</h2>
          <p>$40.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 5">
          <h2>Product 5</h2>
          <p>$50.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 6">
          <h2>Product 6</h2>
          <p>$60.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 7">
          <h2>Product 7</h2>
          <p>$70.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 8">
          <h2>Product 8</h2>
          <p>$80.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 9">
          <h2>Product 9</h2>
          <p>$90.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
      <div class="product">
          <img src="jacket.jpg" alt="Product 10">
          <h2>Product 10</h2>
          <p>$100.00</p>
          <button class="buy-now">Buy Now</button>
      </div>
    </div>
      

</body>

  <!-- Footer -->
  <footer>
    © 2025 PAKMART. All Rights <br>
    <a href="#">FACEBOOK</a><br>
    <a href="#">TWITTER</a><br>
    <a href="#">INSTAGRAM</a>

  </footer>
</body>
</html>
