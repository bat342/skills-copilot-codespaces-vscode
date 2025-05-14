# Emir Lastik Web Sitesi

Bu proje, Emir Lastik web sitesinin kaynak kodudur. Modern web teknolojileri kullanılarak geliştirilmiştir.

## Özellikler

- Responsive tasarım
- Lastik arama sistemi
- Ürün listeleme
- Mobil uyumlu menü
- Modern ve kullanıcı dostu arayüz

## Teknolojiler

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome ikonları

## Kurulum

1. Projeyi klonlayın:
```bash
git clone [repo-url]
```

2. Proje dizinine gidin:
```bash
cd emir-lastik
```

3. `index.html` dosyasını bir web tarayıcısında açın.

## Klasör Yapısı

```
emir-lastik/
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── products/
├── index.html
└── README.md
```

## Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Bir Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

# Emir Lastik - Proje Notları

- Demo alertleri ve çalışmayan butonlar kaldırıldı.
- 'Ödemeye Geç' butonu artık kullanıcıyı 'odeme.html' sayfasına yönlendiriyor.
- Menü ve footer'da boş veya '#' olan linkler tıklanınca hiçbir şey yapmıyor.
- Gerçek ödeme ve bazı sayfalar için entegrasyon gereklidir. 