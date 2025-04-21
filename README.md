
---

#### 2. `index.html` の内容
```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>大阪のケーキ屋さん</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background: url('https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
      background-size: cover;
      color: black;
      margin: 0;
      padding: 0;
    }

    .overlay {
      background-color: rgba(255, 255, 255, 0.85);
      min-height: 100vh;
      padding: 2rem;
    }

    h1 {
      text-align: center;
      color: #999999;
    }

    .cake-card {
      background-color: #fff8dc;
      border: 1px solid #ccc;
      border-radius: 15px;
      padding: 1.5rem;
      max-width: 600px;
      margin: 2rem auto;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .cake-card img {
      width: 100%;
      border-radius: 10px;
    }

    .cake-info {
      margin-top: 1rem;
    }

    .cake-info h2 {
      margin-bottom: 0.5rem;
      color: #444;
    }

    .cake-info a {
      color: #555;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1>大阪のケーキ屋さん</h1>
    <div class="cake-card">
      <img src="https://patisserie-gokan.co.jp/wp-content/themes/gokan2021/assets/images/top/kv_1.jpg" alt="GOKANのケーキ">
      <div class="cake-info">
        <h2>GOKAN</h2>
        <p><strong>エリア:</strong> 北浜</p>
        <p><strong>住所・営業時間:</strong><br>〒541-0042 大阪府大阪市中央区今橋2丁目1-1 新井ビル<br>10:00~19:00</p>
        <p><strong>おすすめコメント:</strong><br>上品な舌触りで丁寧に作られていて、どれを選んでも文句なし。</p>
        <p><a href="https://patisserie-gokan.co.jp" target="_blank">公式サイトを見る</a></p>
      </div>
    </div>
  </div>
</body>
</html>
