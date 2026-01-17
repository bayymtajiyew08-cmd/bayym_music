# Bayym Music 🎵

Hoş geldin!  

Bu repo, benim müzik sitem için hazırlanmıştır.  
Siteyi görmek için GitHub Pages linkini kullanabilirsin:  

[Siteyi Aç](https://bayymtajiyew08-cmd.github.io/bayym_music/)

---

## İçerik
- Şarkı 1
- Şarkı 2
- Şarkı 3
  
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bayym Music</title>
    <style>
        body { font-family: Arial; text-align:center; background:#f5f5f5; margin:0; padding:20px; }
        h1 { color:#333; }
        .song { background:#fff; border-radius:10px; padding:15px; margin:20px auto; max-width:400px; box-shadow:0 4px 8px rgba(0,0,0,0.1); }
        img { width:100%; border-radius:10px; }
        audio { width:100%; margin-top:10px; }
    </style>
</head>
<body>
    <h1>Bayym Music 🎵</h1>
    <p>Hoş geldin! Şarkılar burada olacak.</p>

    <div class="song">
        <h2>Şarkı 1</h2>
        <img src="images/song1.jpg" alt="Şarkı 1">
        <audio controls>
            <source src="songs/song1.mp3" type="audio/mpeg">
        </audio>
    </div>

    <div class="song">
        <h2>Şarkı 2</h2>
        <img src="images/song2.jpg" alt="Şarkı 2">
        <audio controls>
            <source src="songs/song2.mp3" type="audio/mpeg">
        </audio>
    </div>

</body>
</html>
