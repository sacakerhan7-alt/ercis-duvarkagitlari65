# ercis-duvarkagitlari65<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erciş Duvar Kağıtları | Profesyonel Duvar Kağıdı Satışı ve Uygulama</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root { --primary: #1a1a2e; --secondary: #16213e; --accent: #e94560; --gold: #c9a96e; --light: #f5f5f5; --white: #ffffff; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Poppins', sans-serif; color: var(--primary); line-height: 1.6; overflow-x: hidden; }
        .hero { height: 100vh; background: linear-gradient(135deg, rgba(26,26,46,0.95) 0%, rgba(22,33,62,0.9) 100%), url('https://images.unsplash.com/photo-1558618666-fcd25c85f82e?w=1920'); background-size: cover; background-position: center; display: flex; align-items: center; justify-content: center; text-align: center; position: relative; }
        .hero-content { z-index: 2; color: var(--white); padding: 0 20px; max-width: 900px; }
        .hero h1 { font-family: 'Playfair Display', serif; font-size: 4rem; margin-bottom: 20px; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        .hero .subtitle { font-size: 1.5rem; margin-bottom: 40px; font-weight: 300; color: var(--gold); }
        .hero-buttons { display: flex; gap: 20px; justify-content: center; flex-wrap: wrap; }
        .btn { padding: 15px 40px; border-radius: 50px; text-decoration: none; font-weight: 600; transition: all 0.3s ease; display: inline-flex; align-items: center; gap: 10px; }
        .btn-primary { background: var(--accent); color: var(--white); border: 2px solid var(--accent); }
        .btn-primary:hover { background: transparent; color: var(--accent); transform: translateY(-3px); box-shadow: 0 10px 30px rgba(233,69,96,0.3); }
        .btn-outline { background: transparent; color: var(--white); border: 2px solid var(--white); }
        .btn-outline:hover { background: var(--white); color: var(--primary); transform: translateY(-3px); }
        .contact-bar { position: fixed; bottom: 0; left: 0; right: 0; background: var(--primary); padding: 15px; display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; z-index: 1000; box-shadow: 0 -5px 20px rgba(0,0,0,0.2); }
        .contact-bar a { color: var(--white); text-decoration: none; display: flex; align-items: center; gap: 8px; font-size: 0.95rem; transition: color 0.3s; }
        .contact-bar a:hover { color: var(--gold); }
        .contact-bar i { font-size: 1.2rem; }
        section { padding: 80px 20px; }
        .container { max-width: 1200px; margin: 0 auto; }
        .section-title { text-align: center; margin-bottom: 60px; }
        .section-title h2 { font-family: 'Playfair Display', serif; font-size: 2.5rem; color: var(--primary); margin-bottom: 15px; }
        .section-title p { color: #666; font-size: 1.1rem; }
        .gallery { background: var(--light); }
        .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; }
        .gallery-item { position: relative; overflow: hidden; border-radius: 15px; box-shadow: 0 5px 20px rgba(0,0,0,0.1); cursor: pointer; height: 350px; }
        .gallery-item img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.5s ease; }
        .gallery-item:hover img { transform: scale(1.1); }
        .gallery-overlay { position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); padding: 30px 20px 20px; color: var(--white); transform: translateY(100%); transition: transform 0.3s ease; }
        .gallery-item:hover .gallery-overlay { transform: translateY(0); }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; }
        .service-card { background: var(--white); padding: 40px 30px; border-radius: 15px; text-align: center; box-shadow: 0 5px 20px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 1px solid #eee; }
        .service-card:hover { transform: translateY(-10px); box-shadow: 0 15px 40px rgba(0,0,0,0.15); border-color: var(--gold); }
        .service-icon { width: 80px; height: 80px; background: linear-gradient(135deg, var(--primary), var(--secondary)); border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 25px; color: var(--gold); font-size: 2rem; }
        .service-card h3 { font-size: 1.3rem; margin-bottom: 15px; color: var(--primary); }
        .service-card p { color: #666; font-size: 0.95rem; }
        .contact { background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%); color: var(--white); text-align: center; }
        .contact .section-title h2 { color: var(--white); }
        .contact .section-title p { color: #aaa; }
        .contact-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; margin-top: 50px; }
        .contact-card { background: rgba(255,255,255,0.05); padding: 40px 30px; border-radius: 15px; border: 1px solid rgba(255,255,255,0.1); transition: all 0.3s ease; }
        .contact-card:hover { background: rgba(255,255,255,0.1); transform: translateY(-5px); }
        .contact-card i { font-size: 2.5rem; color: var(--gold); margin-bottom: 20px; }
        .contact-card h3 { font-size: 1.3rem; margin-bottom: 10px; }
        .contact-card a { color: var(--gold); text-decoration: none; font-size: 1.1rem; word-break: break-all; }
        .contact-card a:hover { text-decoration: underline; }
        footer { background: #0f0f1a; color: #666; text-align: center; padding: 30px 20px; margin-bottom: 60px; }
        footer p { font-size: 0.9rem; }
        .fade-in { opacity: 0; transform: translateY(30px); transition: all 0.8s ease; }
        .fade-in.visible { opacity: 1; transform: translateY(0); }
        @media (max-width: 768px) { .hero h1 { font-size: 2.5rem; } .hero .subtitle { font-size: 1.1rem; } .contact-bar { gap: 15px; padding: 10px; } .contact-bar a { font-size: 0.8rem; } }
    </style>
</head>
<body>
    <section class="hero">
        <div class="hero-content">
            <h1>Erciş Duvar Kağıtları</h1>
            <p class="subtitle">Profesyonel Duvar Kağıdı Satışı ve Uygulama Hizmeti</p>
            <div class="hero-buttons">
                <a href="#galeri" class="btn btn-primary"><i class="fas fa-images"></i> Galeriyi Gör</a>
                <a href="#iletisim" class="btn btn-outline"><i class="fas fa-phone"></i> Bize Ulaşın</a>
            </div>
        </div>
    </section>
    <section class="services">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Hizmetlerimiz</h2>
                <p>Erciş ve çevresinde profesyonel duvar kağıdı çözümleri sunuyoruz</p>
            </div>
            <div class="services-grid">
                <div class="service-card fade-in">
                    <div class="service-icon"><i class="fas fa-store"></i></div>
                    <h3>Geniş Ürün Yelpazesi</h3>
                    <p>Modern, klasik, 3D, çocuk odası ve daha fazlası. Binlerce farklı desen ve renk seçeneği.</p>
                </div>
                <div class="service-card fade-in">
                    <div class="service-icon"><i class="fas fa-tools"></i></div>
                    <h3>Profesyonel Uygulama</h3>
                    <p>Deneyimli ekibimizle kusursuz ve hızlı duvar kağıdı uygulama hizmeti.</p>
                </div>
                <div class="service-card fade-in">
                    <div class="service-icon"><i class="fas fa-ruler-combined"></i></div>
                    <h3>Ücretsiz Keşif</h3>
                    <p>Adresinize gelip ölçü alıyor, en uygun seçenekleri sunuyoruz.</p>
                </div>
                <div class="service-card fade-in">
                    <div class="service-icon"><i class="fas fa-hand-holding-usd"></i></div>
                    <h3>Uygun Fiyatlar</h3>
                    <p>Kaliteli ürünleri rekabetçi fiyatlarla sunuyoruz. Bütçenize uygun çözümler.</p>
                </div>
            </div>
        </div>
    </section>
    <section class="gallery" id="galeri">
        <div class="container">
            <div class="section-title fade-in">
                <h2>Örnek Çalışmalarımız</h2>
                <p>En popüler duvar kağıdı modellerinden örnekler</p>
            </div>
            <div class="gallery-grid">
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1558618666-fcd25c85f82e?w=800" alt="Mermer Desenli">
                    <div class="gallery-overlay"><h3>Mermer Desenli</h3><p>Lüks ve modern görünüm</p></div>
                </div>
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1558618047-f4b511d0e435?w=800" alt="Klasik Damask">
                    <div class="gallery-overlay"><h3>Klasik Damask</h3><p>Zamansız şıklık</p></div>
                </div>
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1513519245088-0e12902e5a38?w=800" alt="Botanik Desen">
                    <div class="gallery-overlay"><h3>Botanik Desen</h3><p>Doğal ve ferah atmosfer</p></div>
                </div>
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1557672172-298e090bd0f1?w=800" alt="Geometrik Desen">
                    <div class="gallery-overlay"><h3>Geometrik Desen</h3><p>Modern ve dinamik</p></div>
                </div>
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1558618666-fcd25c85f82e?w=800" alt="Vintage Desen">
                    <div class="gallery-overlay"><h3>Vintage Desen</h3><p>Nostaljik dokunuş</p></div>
                </div>
                <div class="gallery-item fade-in">
                    <img src="https://images.unsplash.com/photo-1558618666-fcd25c85f82e?w=800" alt="Tropikal Desen">
                    <div class="gallery-overlay"><h3>Tropikal Desen</h3><p>Egzotik ve canlı</p></div>
                </div>
            </div>
        </div>
    </section>
    <section class="contact" id="iletisim">
        <div class="container">
            <div class="section-title fade-in">
                <h2>İletişim</h2>
                <p>Hemen bizimle iletişime geçin, hayalinizdeki duvar kağıdını birlikte seçelim</p>
            </div>
            <div class="contact-grid">
                <div class="contact-card fade-in">
                    <i class="fas fa-phone-alt"></i>
                    <h3>Telefon</h3>
                    <a href="tel:+905419750065">0541 975 00 65</a>
                    <p style="margin-top:10px; font-size:0.9rem; color:#aaa;">7/24 WhatsApp</p>
                </div>
                <div class="contact-card fade-in">
                    <i class="fab fa-instagram"></i>
                    <h3>Instagram</h3>
                    <a href="https://instagram.com/ercisduvarkagitlari" target="_blank">@ercisduvarkagitlari</a>
                    <p style="margin-top:10px; font-size:0.9rem; color:#aaa;">Güncel çalışmalar</p>
                </div>
                <div class="contact-card fade-in">
                    <i class="fas fa-envelope"></i>
                    <h3>E-posta</h3>
                    <a href="mailto:sacakyapiinsaat@gmail.com">sacakyapiinsaat@gmail.com</a>
                    <p style="margin-top:10px; font-size:0.9rem; color:#aaa;">Teklif için yazın</p>
                </div>
                <div class="contact-card fade-in">
                    <i class="fas fa-map-marker-alt"></i>
                    <h3>Konum</h3>
                    <span style="color: var(--gold);">Erciş, Van</span>
                    <p style="margin-top:10px; font-size:0.9rem; color:#aaa;">Erciş ve çevresi</p>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Erciş Duvar Kağıtları | Tüm Hakları Saklıdır</p>
        <p style="margin-top:5px; font-size:0.8rem;">Sacak Yapı İnşaat</p>
    </footer>
    <div class="contact-bar">
        <a href="tel:+905419750065"><i class="fas fa-phone"></i><span>0541 975 00 65</span></a>
        <a href="https://wa.me/905419750065" target="_blank"><i class="fab fa-whatsapp"></i><span>WhatsApp</span></a>
        <a href="https://instagram.com/ercisduvarkagitlari" target="_blank"><i class="fab fa-instagram"></i><span>@ercisduvarkagitlari</span></a>
        <a href="mailto:sacakyapiinsaat@gmail.com"><i class="fas fa-envelope"></i><span>E-posta</span></a>
    </div>
    <script>
        const observer = new IntersectionObserver((entries) => { entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('visible'); }); }, { threshold: 0.1 });
        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
        document.querySelectorAll('a[href^="#"]').forEach(a => a.addEventListener('click', function(e) { e.preventDefault(); document.querySelector(this.getAttribute('href'))?.scrollIntoView({ behavior: 'smooth' }); }));
    </script>
</body>
</html>
