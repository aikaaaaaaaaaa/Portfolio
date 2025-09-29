# Portfolio```html name=index.html
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ポートフォリオ</title>
<style>
body {
margin: 0;
font-family: 'Hiragino Kaku Gothic ProN', sans-serif;
background-color: #ff6f30;
color: #000;
text-align: center;
}
header {
padding: 40px 20px 10px;
}
header h1 {
font-size: 4rem;
margin: 0;
font-weight: bold;
}
.gallery {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
gap: 20px;
padding: 20px;
max-width: 1200px;
margin: 0 auto;
}
.gallery img {
width: 100%;
border-radius: 12px;
box-shadow: 0 4px 8px rgba(0,0,0,0.3);
background: #fff;
}
footer {
padding: 20px;
font-size: 0.9rem;
color: #222;
}
</style>
</head>
<body>
<header>
<h1>ポートフォリオ</h1>
</header>

<section class="gallery">
<img src="portfolio1.jpg" alt="イラスト作品">
<img src="portfolio2.jpg" alt="デッサン作品1">
<img src="portfolio3.jpg" alt="デッサン作品2">
<img src="portfolio4.jpg" alt="デッサン作品3">
</section>

<footer>
&copy; 2025 あなたの名前
</footer>
</body>
</html>
```
