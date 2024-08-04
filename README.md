# OpenCV ile Oyun Botu

![image](https://user-images.githubusercontent.com/84662757/155882729-74331959-1705-4e7c-8a9a-bc3161d6ee81.png)


Merhaba,

Bu projeye başlama amacım sadece GÖRÜNTÜ İŞLEME de nesne algılama ve doğru MODEL EĞİTME idi.
Ancak ilgi oldukça fazla olunca biraz daha geliştirip klavye fare kullanan oyun botu haline getirmiştim.
Yakın zamanda(2022 Ocak) Tkinter kullanarak GUI (Grafiksel Kullanıcı Arayüzü) halinde olan bir video paylaşmıştım. Oyunlarda fare sol tıklaması engelli olduğu için sağ tık yaptırarak metinleri kestirebiliyorduk. Şimdi sanırım o da engelli.

Velhasıl, projeyi geliştirmeyi uzun zamandır bıraktım. Aldığınız hatalara yardımcı olamayacağım, araştırıp siz çözebilirsiniz. Bu konuda yardım mesajı atmazsanız sevinirim. Programı son videoda gördüğünüz gibi kodlarını paylaşıyorum.
Kodlar github hesabımda herkese açık olarak yayındadır.

Emeğe saygı göstererek, @yazilimfuryasi olarak bizi kaynak gösterip isteyen alıp geliştirip kullanabilir.
Bizim kodlara kendi imzasını atanlara prim vermeyiniz.

# Nasıl Çalıştırırım?
* Bilgisayarda Python kurulu olması lazım. (v3.8 ve üzeri)
* CMD ekranını yönetici olarak çalıştırın.
* Dosyaların bulunduğu dizine cd komutu ile gidin (örn: cd C:\OpenCV-Game-Bot)
* **pip install -r requirements.txt** ile gerekli modülleri kurun.

main.py dosyası eski, onu kullanmanıza gerek yoktur. gui.py üzerinden anlatacağım.

* gui.py dosyasını açıp 107. satırdaki cascade değişkenine cascade.xml dosya yolunu yazın. (Örn: C:\OpenCV-Game-Bot\cascade\cascade.xml)
* Ekrana **python gui.py** yazarak enter yapın.
* Oyunda skill barında ki kamerayı saldır olarak değişin.
* Program ekranındaki '**Ara**' butonuna basıp oyun ekranını seçin.
* Metin kesme sürenizi yazın ve başlata basın.

# SSS
* **No module named ...** := Adı geçen modül yüklü değil demektir. **pip install moduladi** şeklinde kurabilirsiniz.
* **NameError: name 'wincap' is not defined** := Adı geçen ekran bulunamadı demektir.
* **win32ui.error: BitBlt failed** := Oyunda ekran yakalama engelli demektir.
* **Fare metinin üzerine gidiyor ama tıklamıyor?** := Programı ve Oyunu yönetici olarak açın. Yine olmadıysa çözümü hakkında bir fikrim yok.

# Kodlara ait güncel(son) Video
[![2024](https://i.ytimg.com/an_webp/leYyXPpeUNk/mqdefault_6s.webp?du=3000&sqp=CN6ovbUG&rs=AOn4CLDVMFcxN-CZHb_mup78Z9BQz4eW-A)](https://www.youtube.com/watch?v=leYyXPpeUNk)

# 2024 - Yeni Arayüz, Yeni Model
2024 yılında yeni model eğittim ve metin algılama hızı arttırıldı. Ek fonksiyonlar eklendi. Bu kodlar şuanda yayında değil. İlgili video;

Program arayüzü

![pythonist_53777a8d5e503a9976beb8527a1fbb84](https://github.com/user-attachments/assets/af34c9b1-dd28-4ee9-a40c-9ddce571069a)

İlgili Video

[![2024](https://i.ytimg.com/an_webp/KyYQ55jglbw/mqdefault_6s.webp?du=3000&sqp=CPSdvbUG&rs=AOn4CLAyovgC7Yqu0JBBUWyj1w2dnDNQfg)](https://www.youtube.com/watch?v=KyYQ55jglbw)


Kaynak:

https://www.youtube.com/watch?v=KecMlLUuiE4&list=PL1m2M8LQlzfKtkKq2lK5xko4X-8EZzFPI
https://docs.opencv.org/3.4/dc/d88/tutorial_traincascade.html
