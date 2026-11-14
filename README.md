[style.css](https://github.com/user-attachments/files/34859809/style.css)
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Çapa Ticaret | Yedek Parça & Tamir Merkezi</title>
    <link rel="stylesheet" href="style.css">
    <!-- FontAwesome İkonları -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <!-- Üst İletişim Bandı -->
    <div class="top-bar">
        <div class="container top-bar-content">
            <span class="location"><i class="fa-solid fa-location-dot"></i> Çorum Merkez, Hamit Camii Karşısı</span>
            <a href="https://wa.me/905374974283" target="_blank" class="phone"><i class="fa-brands fa-whatsapp"></i> 0537 497 42 83</a>
        </div>
    </div>

    <!-- Menü (Header) -->
    <header>
        <div class="container header-content">
            <div class="logo" onclick="showPage('home')">
                ÇAPA <span>TİCARET</span>
            </div>
            <nav>
                <button class="nav-btn active" onclick="showPage('home')">Anasayfa</button>
                <button class="nav-btn" onclick="showPage('kulplar')">Demlik Kulpları</button>
                <button class="nav-btn" onclick="showPage('lastikler')">Düdüklü Lastiği</button>
                <button class="nav-btn" onclick="showPage('kapaklar')">Cam Kapak</button>
                <button class="nav-btn" onclick="showPage('supurge')">Süpürge Torbası</button>
                <button class="nav-btn contact-btn" onclick="showPage('iletisim')">İletişim</button>
            </nav>
        </div>
    </header>

    <!-- SAYFALAR (SPA Mimarisi) -->

    <!-- 1. ANASAYFA -->
    <main id="page-home" class="page active">
        <!-- Karşılama Alanı (Hero) -->
        <section class="hero" style="background-image: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), url('https://images.unsplash.com/photo-1556910103-1c02745aae4d?q=80&w=2070&auto=format&fit=crop');">
            <div class="hero-text">
                <h1>Mutfak Aletlerinizi Yenilemenin <br><span>En Hesaplı Yolu</span></h1>
                <p>Kırılan, eskiyen veya kaybolan yedek parçalar için cihazınızı atmayın. Çorum'un en büyük mutfak eşyası yedek parça merkezi.</p>
                <div class="hero-buttons">
                    <a href="https://wa.me/905374974283" target="_blank" class="btn-primary"><i class="fa-brands fa-whatsapp"></i> Fotoğraf Gönder, Parça Sor</a>
                    <button class="btn-secondary" onclick="showPage('iletisim')">Konumumuza Bak</button>
                </div>
            </div>
        </section>

        <!-- Kategori Vitrini -->
        <section class="container showcase">
            <div class="section-title">
                <h2>Ürün Kategorilerimiz</h2>
                <p>İhtiyacınız olan parçayı seçin, WhatsApp üzerinden anında sipariş verin.</p>
            </div>
            
            <div class="grid">
                <div class="card" onclick="showPage('kulplar')">
                    <img src="format_webp.webp" alt="Demlik Kulpu">
                    <div class="card-content">
                        <h3>Demlik & Tencere Kulpları</h3>
                        <p>Yanmaz bakalit ve çelik kulp modelleri.</p>
                    </div>
                </div>
                
                <div class="card" onclick="showPage('lastikler')">
                    <img src="IMG-2554860835369761932.webp" alt="Düdüklü Tencere">
                    <div class="card-content">
                        <h3>Düdüklü Lastikleri</h3>
                        <p>Fissler, Tefal, Korkmaz uyumlu contalar.</p>
                    </div>
                </div>

                <div class="card" onclick="showPage('kapaklar')">
                    <img src="shopping.webp" alt="Cam Kapak">
                    <div class="card-content">
                        <h3>Isıya Dayanıklı Cam Kapaklar</h3>
                        <p>14cm'den 32cm'e kadar temperli kapaklar.</p>
                    </div>
                </div>

                <div class="card" onclick="showPage('supurge')">
                    <img src="d0.jpg" alt="Süpürge">
                    <div class="card-content">
                        <h3>Süpürge Torbaları</h3>
                        <p>Her markaya uygun toz torbası ve hortumlar.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- 2. DEMLİK KULPLARI -->
    <main id="page-kulplar" class="page">
        <div class="container content-page">
            <div class="page-header">
                <h2>Demlik & Tencere Kulpları</h2>
                <p>Eskiyen kulplarınızı orijinal hissiyatında, yüksek ısıya dayanıklı yeni kulplarla değiştirin.</p>
            </div>
            
            <div class="product-grid">
                <div class="product-card">
                    <img src="format_webp.webp" alt="Kırmızı Kulp">
                    <div class="product-info">
                        <span class="badge">Çok Satan</span>
                        <h3>Kırmızı Çaydanlık & Tencere Kulpu</h3>
                        <p>Isınma yapmaz, el yakmaz şık tasarım. Standart tencerelere perçinli veya vidalı uyum sağlar.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20kırmızı%20tencere/demlik%20kulpu%20almak%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> Sipariş Ver</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="1_org_zoom.webp" alt="Siyah Kulp">
                    <div class="product-info">
                        <span class="badge">Dayanıklı</span>
                        <h3>Siyah Silikon Kulp Tutacakları</h3>
                        <p>Tencere kulplarına geçirilen, yüksek ısıya dayanıklı siyah yanmaz tutacaklar.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20siyah%20kulp%20tutacağı%20almak%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> Sipariş Ver</a>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- 3. DÜDÜKLÜ LASTİKLERİ -->
    <main id="page-lastikler" class="page">
        <div class="container content-page">
            <div class="page-header">
                <h2>Düdüklü Tencere Sızdırmazlık Lastikleri</h2>
                <p>Buhar kaçıran düdüklü tencereleriniz için gıdaya uygun %100 silikon contalar.</p>
            </div>
            
            <div class="product-grid">
                <div class="product-card">
                    <img src="IMG-2554860835369761932.webp" alt="Standart Lastik">
                    <div class="product-info">
                        <span class="badge">Klasik Tip</span>
                        <h3>Standart Çember Lastikler</h3>
                        <p>20-22-24cm gibi farklı çap ölçülerinde, klasik düdüklü tencereler için yüksek ısıya dayanıklı contalar.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20standart%20çember%20düdüklü%20lastiği%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="korkmaz-a153-tessa-z.avif" alt="Korkmaz Tipi Conta">
                    <div class="product-info">
                        <span class="badge">Yeni Nesil</span>
                        <h3>Korkmaz Tessa Tipi Conta</h3>
                        <p>Özel çentikli yapısıyla yeni nesil klipsli düdüklü tencerelere tam uyum sağlayan orijinal silikon.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20Korkmaz%20Tessa%20tipi%20düdüklü%20lastiği%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="images.jpg" alt="Çentikli Conta">
                    <div class="product-info">
                        <span class="badge">Özel Kesim</span>
                        <h3>Dalgalı / Çentikli Conta</h3>
                        <p>Fissler ve benzeri özel kapak mekanizmalı tencereler için sızdırmazlığı garantileyen dalgalı lastik.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20dalgalı/çentikli%20düdüklü%20lastiği%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="IMG-2075745436794213090.webp" alt="Geniş Tabanlı Conta">
                    <div class="product-info">
                        <span class="badge">Geniş Profil</span>
                        <h3>Geniş Tabanlı Dudaklı Conta</h3>
                        <p>Tefal Clipso ve benzeri geniş yuvalı tencereler için tasarlanmış, buhar kaçışını %100 önleyen kalın conta.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20geniş%20tabanlı%20Tefal%20tipi%20lastik%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- 4. CAM KAPAKLAR -->
    <main id="page-kapaklar" class="page">
        <div class="container content-page">
            <div class="page-header">
                <h2>Isıya Dayanıklı Temperli Cam Kapaklar</h2>
                <p>Çelik, granit veya döküm tüm tencereleriniz için buhar delikli çelik çerçeveli kapaklar.</p>
            </div>
            
            <div class="product-grid">
                <div class="product-card">
                    <img src="shopping.webp" alt="Cam Kapak">
                    <div class="product-info">
                        <span class="badge">Isıya Dayanıklı</span>
                        <h3>Tencere & Tava Cam Kapağı</h3>
                        <p>14, 16, 18, 20, 22, 24, 26, 28, 30 ve 32 cm ölçülerinde, kırılmaz temperli cam kapaklar.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20cam%20kapak%20istiyorum.%20Tenceremin%20ağız%20çapı%20ölçüsü:" target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> Ölçünü Yazıp Sor</a>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- 5. SÜPÜRGE TORBALARI -->
    <main id="page-supurge" class="page">
        <div class="container content-page">
            <div class="page-header">
                <h2>Süpürge Torbaları & Aksesuarlar</h2>
                <p>Motor ömrünü uzatan ve %99 toz hapseden orijinal bez ve kağıt süpürge torbaları.</p>
            </div>
            
            <div class="product-grid">
                <div class="product-card">
                    <img src="d0.jpg" alt="Karton Girişli Torba">
                    <div class="product-info">
                        <span class="badge">Kağıt Torba</span>
                        <h3>Standart Toz Torbası</h3>
                        <p>Yüksek emiş gücü sağlayan, standart karton girişli dayanıklı toz torbası.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20karton%20girişli%20kağıt%20toz%20torbası%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="arcelik-s-4240-s-4250-s-6260-supurge-bez-toz-torbasi-20-adet-kc3371619-1-3a9595da26854a44918c99b65b9904c4.jpg" alt="Mavi Plastik Girişli Torba">
                    <div class="product-info">
                        <span class="badge">Bez Torba</span>
                        <h3>Arçelik / Beko Uyumlu Torba</h3>
                        <p>Mavi plastik girişli, motoru koruyan uzun ömürlü sentetik bez toz torbası.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20mavi%20plastik%20girişli%20bez%20torba%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>

                <div class="product-card">
                    <img src="20244781_r1_1000_1000.jpg" alt="Siyah Plastik Girişli Torba">
                    <div class="product-info">
                        <span class="badge">Sentetik</span>
                        <h3>Yüksek Performanslı Torba</h3>
                        <p>Tozu %99 hapseden, yırtılmaz siyah plastik girişli sentetik model.</p>
                        <a href="https://wa.me/905374974283?text=Merhaba,%20siyah%20plastik%20girişli%20torba%20istiyorum." target="_blank" class="btn-whatsapp"><i class="fa-brands fa-whatsapp"></i> WhatsApp'tan Sor</a>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- 6. İLETİŞİM -->
    <main id="page-iletisim" class="page">
        <div class="container content-page">
            <div class="page-header">
                <h2>İletişim & Dükkan Konumu</h2>
                <p>Çorum merkezdeki mağazamıza gelip ürünleri elden alabilir veya tüm Türkiye'ye kargo isteyebilirsiniz.</p>
            </div>
            
            <div class="contact-box">
                <div class="info-item">
                    <i class="fa-solid fa-location-dot"></i>
                    <div>
                        <h3>Açık Adresimiz</h3>
                        <p>Çapa Ticaret Yedek Parça<br>Çorum Merkez, Hamit Camii Karşısı</p>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fa-brands fa-whatsapp"></i>
                    <div>
                        <h3>Telefon & WhatsApp</h3>
                        <p>0537 497 42 83</p>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fa-solid fa-truck-fast"></i>
                    <div>
                        <h3>Kargo Bilgisi</h3>
                        <p>Saat 15:00'a kadar verilen siparişler aynı gün anlaşmalı kargoya teslim edilir.</p>
                    </div>
                </div>
                <a href="https://wa.me/905374974283" target="_blank" class="btn-whatsapp" style="margin-top: 30px;"><i class="fa-brands fa-whatsapp"></i> Mesaj Göndermek İçin Tıklayın</a>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© Çapa Ticaret - Tüm Hakları Saklıdır. | Çorum Yedek Parça & Tamir</p>
        </div>
    </footer>

    <!-- JS: Sayfa Geçiş Scripti -->
    <script>
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('page-' + pageId).classList.add('active');
            
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('active'));
            event.currentTarget.classList.add('active');
            
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    </script>
</body>
</html>
