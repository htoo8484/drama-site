# drama-site
<!DOCTYPE html>
<html lang="my">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>မြန်မာ Drama ပြသမှု</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .drama-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }

    .drama-card {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      width: 220px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .drama-card img {
      width: 100%;
      height: auto;
    }

    .drama-card h3 {
      margin: 10px;
    }

    .drama-card p {
      padding: 0 10px 10px;
      font-size: 14px;
      color: #444;
    }

    .watch-btn {
      background-color: #ff5722;
      color: white;
      padding: 10px;
      text-align: center;
      text-decoration: none;
      display: block;
      border-top: 1px solid #ddd;
    }

    .watch-btn:hover {
      background-color: #e64a19;
    }
  </style>
</head>
<body>

<header>
  <h1>မြန်မာ Drama များ</h1>
  <p>လက်ရှိ ထွက်ရှိထားသော Drama Series များကို ကြည့်ရှုပါ</p>
</header>

<div class="drama-container">

  <div class="drama-card">
    <img src="https://via.placeholder.com/220x300?text=Drama+1" alt="Drama 1">
    <h3>တစ်နေ့လုံးမင်းအတွက်</h3>
    <p>အချစ်နဲ့ အလှတွေ ပြည့်နှက်တဲ့ ဇာတ်လမ်းအတိုင်း...</p>
    <a class="watch-btn" href="#">ကြည့်မယ်</a>
  </div>

  <div class="drama-card">
    <img src="https://via.placeholder.com/220x300?text=Drama+2" alt="Drama 2">
    <h3>နှလုံးသားခေါ်သောအသံ</h3>
    <p>မသန်စွမ်းမှုအပြင်မှာ မုန်းစကားတွေထက် အချစ်ကပါရှိတယ်။</p>
    <a class="watch-btn" href="#">ကြည့်မယ်</a>
  </div>

  <div class="drama-card">
    <img src="https://via.placeholder.com/220x300?text=Drama+3" alt="Drama 3">
    <h3>မေတ္တာရဲ့တံတား</h3>
    <p>အတိတ်နဲ့လက်ရှိကြားက ကြိုးတစ်စင်းကြောင့်...</p>
    <a class="watch-btn" href="#">ကြည့်မယ်</a>
  </div>

</div>

</body>
</html>
