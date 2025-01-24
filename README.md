# Cub3D - RayCasting Projesi

Merhabalar, bu proje **Ecole42 Yazılım Okulu** müfredatında yer alan, temel **raycasting** prensiplerini kullanarak bir **labirent** içerisinde hareket edebileceğiniz **3 boyutlu bir oyun simülatörüdür**. Oyun, **MiniLibX** kütüphanesini kullanarak **C programlama dili** ile geliştirilmiştir ve basit bir harita yapısını içeren **.cub** dosyalarını okuyarak çalışır.

---

## 📌 Proje Özellikleri

- **Raycasting ile Görüntüleme**: Oyuncu, labirent içinde **3 boyutlu** bir ortamda gezinebilir.
- **Duvar Dokuları**: Duvarların yüzeyleri, baktıkları yönlere göre **farklı dokularla** kaplanmıştır (**Kuzey, Güney, Doğu, Batı**).
- **Zemin ve Tavan Renkleri**: Zemin ve tavan **farklı renklerle** belirlenebilir.
- **Dinamik Kontroller**:
  - **W, A, S, D** tuşları ile hareket edebilirsiniz.
  - **Sol ve Sağ ok** tuşları ile bakış açınızı değiştirebilirsiniz.
  - **ESC** tuşuna basarak oyundan çıkabilirsiniz.
  - **Pencere üzerindeki kırmızı çarpıya** tıklayarak pencereyi kapatabilirsiniz.
- **Harita Yapısı**: Harita **.cub** uzantılı dosyalardan okunur ve aşağıdaki karakterleri destekler:
  - `1` : **Duvarlar**
  - `0` : **Boş alanlar**
  - `N, S, E, W` : **Oyuncunun başlangıç pozisyonu ve yönü** (**Kuzey, Güney, Doğu, Batı**)

---

## 🚀 Kurulum ve Çalıştırma

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

```bash
git clone https://github.com/kullaniciadi/cub3D.git
cd cub3D
make
./cub3D harita.cub
```

---

## 🎮 Kontroller

| Tuş | İşlev            |
| --- | ---------------- |
| W   | İleri git        |
| A   | Sola git         |
| S   | Geri git         |
| D   | Sağa git         |
| ← → | Sağa ve sola bak |
| ESC | Oyundan çık      |

---

## 📁 Dosya Yapısı

- `cub3D.c` → Ana program dosyası
- `raycasting.c` → Ray-casting algoritmasının işlendiği dosya
- `parsing.c` → Harita dosyasının analiz edildiği kod
- `textures/` → Duvar ve zemin dokularını içeren klasör
- `Makefile` → Derleme komutlarını içeren makefile

---

## 🎯 Zorunlu Kısımlar

- **MiniLibX** kullanarak **bir labirentin içini 3D olarak göstermelidir**.
- **Farklı yönlere bakan duvar dokularını desteklemelidir** (**Kuzey, Güney, Doğu, Batı**).
- **Tavan ve zemin için farklı renkler atanabilmelidir**.
- **.cub formatında harita dosyasını okuyabilmelidir**.

---

## 🎁 Bonus Özellikler
**NOT:** BU PROJEDE BONUS KISMI BULUNMAMAKTADIR!
- **Duvar çarpışmaları**
- **Mini harita (mini-map)**
- **Açılıp kapanabilen kapılar**
- **Animasyonlu sprite desteği**
- **Fare ile görüş açısını değiştirme**

---

### 🎖️ Özel Teşekkür

Bu projeyi geliştirirken değerli katkılarıyla yanımda olan takım arkadaşım **ydunay**'a içtenlikle teşekkür ederim. Onun desteği ve işbirliği olmadan bu proje tamamlanamazdı. 🙌

