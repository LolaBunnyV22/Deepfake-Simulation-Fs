# Deepfake-Simulation-Fs# First Order Motion Model - Deepfake Simulation Study

Bu proje, durağan görselleri hareketli video verileriyle canlandıran bir simülasyon çalışmasıdır.

## 🛠 Kullanılan Teknolojiler
* **Model:** First Order Motion Model (FOMM)
* **Dil:** Python 3.x
* **Kütüphaneler:** PyTorch, OpenCV, ImageIO, Scikit-Image
* **Platform:** Google Colab (GPU Destekli)

## 📂 Veri Seti
* **Kaynak Videolar:** 3 adet farklı mimik içeren sürüş videosu.
* **Hedef Görseller:** 50 adet farklı insan yüzü fotoğrafı.
* **Sonuç:** Toplam 150 adet simülasyon videosu üretilmiştir.

## 🚀 Kurulum ve Çalıştırma
1. Model ağırlıklarını (`vox-adv-cpk.pth.tar`) ilgili dizine ekleyin.
2. `vids/` klasörüne kaynak videoları, `imgs/` klasörüne fotoğrafları yükleyin.
3. Ana kodu çalıştırarak sonuçları `outputs/` klasöründen alın.
