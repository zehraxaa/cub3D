# 🧊 Cub3D - My First RayCasting Engine

![42 School](https://img.shields.io/badge/42-School-000000?style=flat-square&logo=42&logoColor=white)
![Language](https://img.shields.io/badge/Language-C-blue?style=flat-square&logo=c)
![Library](https://img.shields.io/badge/Library-MiniLibX-orange?style=flat-square)
![OS](https://img.shields.io/badge/OS-Linux-yellow?style=flat-square&logo=linux)

![Gameplay Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjEx/placeholder.gif)

> **"Wolfenstein 3D"** efsanesinden ilham alınan, C ve MiniLibX kullanılarak sıfırdan geliştirilmiş bir 3D oyun motoru.

## 🎮 Hakkında

Cub3D, 2 boyutlu bir haritayı **RayCasting** (Işın Döküm) teknolojisi kullanarak MinilibX kütüphanesi yardımıyla 3 boyutlu bir dünyaya dönüştüren bir grafik projesidir. Bu proje, modern oyun motorlarının atası sayılan matematiksel prensipleri anlamak ve uygulamak amacıyla geliştirilmiştir.

### ✨ Özellikler

* 🚧 **Gelişmiş Raycasting:** DDA algoritması ile hassas duvar tespiti.
* 🎨 **Doku Kaplama (Texture Mapping):** Duvarların yönüne göre (Kuzey, Güney, Doğu, Batı) farklı dokular.
* 🏃 **Akıcı Hareket:** W, A, S, D ile pürüzsüz oyuncu hareketi ve kamera rotasyonu.
* 🛡️ **Çarpışma Sistemi:** Duvarların içinden geçmeyi engelleyen hitbox mantığı.
* 🗺️ **Harita Doğrulama:** .cub dosya formatı için katı parsing kuralları ve hata yönetimi.
* 🧹 **Sızıntısız:** Valgrind ile test edilmiş, bellek sızıntısı olmayan temiz kod.

## 🛠️ Kurulum ve Çalıştırma

Projeyi yerel makinenize klonlayın ve terminalde şu komutları yazın:

```bash
# Repoyu klonla
git clone [https://github.com/KULLANICI_ADIN/cub3d.git](https://github.com/KULLANICI_ADIN/cub3d.git)

# Dizin içine gir
cd cub3D

# Projeyi derle. Proje derlendiğinde minilibx kütüphanesi otomatik olarak yüklenecektir
make

# maps/good klsörü içerisinde olan dilediğiniz bir haritayla projeyi çalıştırabilirsiniz
örn: ./cub3D maps/good/map1.cub

# Hareket etme
W, A, S, D tuşlarıyla hareket edebilirsiniz; sağ ve sol ok tuşlarıyla da yön değiştirebilirsiniz.

```

(bu proje linux sistemlere uygun şekilde geliştirilmiştir)
