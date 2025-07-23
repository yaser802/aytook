 <!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>آیتوک | فروشگاه آنلاین</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #ef394e;
      color: white;
      padding: 10px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .logo {
      font-weight: bold;
      font-size: 20px;
    }
    .search {
      flex-grow: 1;
      margin: 0 10px;
    }
    .search input {
      width: 100%;
      padding: 8px;
      border-radius: 5px;
      border: none;
    }
    nav {
      background-color: white;
      padding: 10px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      box-shadow: 0 1px 5px rgba(0,0,0,0.1);
    }
    nav a {
      text-decoration: none;
      color: #333;
      padding: 5px 10px;
    }
    .banner {
      width: 100%;
      height: 200px;
      background: url('https://dkstatics-public.digikala.com/digikala-adservice-banners/123.jpg') center/cover no-repeat;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .product {
      background: white;
      padding: 10px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      height: 120px;
      object-fit: contain;
    }
    .product h4 {
      font-size: 14px;
      margin: 10px 0 5px;
    }
    .product .price {
      color: green;
      font-weight: bold;
    }
    footer {
      background: #333;
      color: white;
      padding: 15px;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">آیتوک</div>
    <div class="search">
      <input type="text" placeholder="جستجو در آیتوک...">
    </div>
  </header>

  <nav>
    <a href="#">کالای دیجیتال</a>
    <a href="#">مد و پوشاک</a>
    <a href="#">خانه و آشپزخانه</a>
    <a href="#">ورزشی</a>
    <a href="#">زیبایی و سلامت</a>
  </nav>

  <div class="banner"></div>

  <section class="products">
    <div class="product">
      <img src="https://dkstatics-public.digikala.com/products/123456.jpg" alt="کالا">
      <h4>نام محصول</h4>
      <div class="price">250,000 تومان</div>
    </div>
    <div class="product">
      <img src="https://dkstatics-public.digikala.com/products/123456.jpg" alt="کالا">
      <h4>محصول دوم</h4>
      <div class="price">480,000 تومان</div>
    </div>
    <!-- محصولات بیشتر می‌تونی اضافه کنی -->
  </section>

  <footer>
    © 2025 آیتوک | تمامی حقوق محفوظ است.
  </footer>
</body>
</html>
D
