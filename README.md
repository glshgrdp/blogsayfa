# blogsayfa
Kişisel Blog Sayfa Hazırlama


<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>GÜLŞAH BALLI GİRDAP - Blog</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #f8c0c8, #ffdede, #f4c6ff);
        }

        
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-around;
            padding: 60px 20px;
        }

        .hero img {
            width: 330px;
            height: auto;
            border-radius: 25px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.2);
        }

        .text-box {
            max-width: 450px;
        }

        .text-box h1 {
            font-size: 48px;
            font-family: "Georgia", serif;
            font-style: italic;
            margin-bottom: 15px;
        }

        .text-box p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .btn {
            display: block;
            width: 300px;
            text-align: center;
            padding: 12px;
            margin: 10px 0;
            font-size: 18px;
            border-radius: 10px;
            border: 2px solid black;
            background: white;
            cursor: pointer;
            transition: 0.2s;
            text-decoration: none;
            color: black;
        }

        .btn:hover {
            background: #f5f5f5;
        }

        #iletisimBox {
            display: none;
            margin-top: 10px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        
        .blog-container {
            background: white;
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            border-radius: 15px;
        }

        .blog-post {
            margin-bottom: 40px;
        }

        
        .blog-post img {
    width: 50%;
    display: block;
    margin: 10px auto;
    border-radius: 10px;
         
        }

        h2 {
            color: #333;
        }

        ul, ol {
            margin-left: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            color: #444;
        }
    </style>

    <script>
        function showIletisim() {
            const div = document.getElementById("iletisimBox");
            if (div.style.display === "block") {
                div.style.display = "none";
            } else {
                div.style.display = "block";
            }
        }
    </script>

</head>

<body>

    <section class="hero">
    <img src="profil/gulsah.jpg" alt="Gülşah Ballı Girdap Fotoğrafı">

        <div class="text-box">
            <h1>Selam, Adım Gülşah Ballı Girdap.</h1>
            <p>İstanbul'da büyüdüm, Sakarya'da yaşıyorum. Blog yazarıyım.</p>

            <a href="#blog" class="btn">BLOG</a>
            <button class="btn" onclick="showIletisim()">İŞBİRLİĞİ</button>

            <div id="iletisimBox">
                <p><strong>Mail:</strong> gulsah@gmail.com</p>
                <p><strong>Telefon:</strong> 0542 542 42 42</p>
            </div>
        </div>
    </section>

    <!-- BLOG ALANI -->
    <section id="blog" class="blog-container">

        <h1>Blog Yazılarım</h1>

        <!-- 1. Blog -->
        <article class="blog-post">
            <h2>Barcelona Gezisi</h2>
            <img src="gezi/barcelona.jpg" alt="Barcelona Manzarası">
            <img src="gezi/larambla.jpg" alt="La Rambla">
            <img src="gezi/sagra.jpg" alt="Sagrada Familia">
            <img src="gezi/0654EURS2018.jpg" alt="Las Tapas(Mezeler)">
            <p>Geçen yıl Barcelona’ya gitme fırsatım oldu ve gerçekten unutulmaz bir deneyimdi.</p>

            <ul>
                <li>Sagrada Familia ziyareti</li>
                <li>La Rambla’da yürüyüş</li>
                <li>Deniz kenarında tapas</li>
            </ul>

            <p>Daha fazla bilgi için şu bağlantılara bakabilirsiniz:</p>
            <a href="https://www.barcelonaturisme.com/wv3/en/" target="_blank">Barcelona Rehberi</a><br>
            <a href="https://www.spain.info/en/destination/barcelona/" target="_blank">Spain Resmi Turizm Sitesi</a>
        </article>

        <!-- 2. Blog -->
        <article class="blog-post">
            <h2>Web Tasarım Öğrenme Sürecim</h2>
            <img src="web/web.jpg" alt="Web Tasarım Görseli">
            <p>Frontend öğrenirken birçok yeni bilgi edindim. Basit projeler yaparak ilerledim.</p>

            <ol>
                <li>HTML yapısını kavramak</li>
                <li>CSS ile düzenlemeler yapmak</li>
                <li>JavaScript öğrenmeye başlamak</li>
            </ol>

            <p>Kaynaklar:</p>
            <a href="https://frontendmasters.com/" target="_blank">FrontEnd Masters</a><br>
            <a href="https://fullstackopen.com/en/" target="_blank">Free Course</a>
        </article>

        <!-- 3. Blog -->
        <article class="blog-post">
            <h2>En Sevdiğim Kitaplar</h2>
            <img src="kitap/71wANojhEKL.jpg" alt="Kitap Görseli">
            <img src="kitap/kitap.jpg" alt="Kitap Görseli">
            <img src="kitap/wi_800.jpg" alt="Kitap Görseli">
            <p>Okumak benim için bir rutin değil, bir kaçış alanı.</p>

            <ul>
                <li>1984 – George Orwell</li>
                <li>Küçük Prens – Antoine de Saint-Exupéry</li>
                <li>Martı – Richard Bach</li>
            </ul>

            <p>Kitap satın alma ve önerileri için:</p>
            <a href="https://www.kitapyurdu.com" target="_blank">KitapYurdu</a><br>
            <a href="https://www.dr.com.tr" target="_blank">D&R</a>
        </article>

    </section>

    <footer>
        © 2025 Gülşah Ballı Girdap
    </footer>

</body>
</html>


