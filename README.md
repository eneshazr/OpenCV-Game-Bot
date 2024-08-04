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
* pip install -r requirements.txt ile gerekli modülleri kurun.

main.py dosyası eski, onu kullanmanıza gerek yoktur. gui.py üzerinden anlatacağım.

* gui.py dosyasını açıp 107. satırdaki cascade değişkenine cascade.xml dosya yolunu yazın.
* CMD ekranını yönetici olarak çalıştırın.
* Dosyaların bulunduğu dizine cd komutu ile gidin (örn: cd C:\OpenCV-Game-Bot)
* Ekrana **python gui.py** yazarak enter yapın.
* Oyunda skill barında ki kamerayı saldır olarak değişin.
* Program ekranındaki 'Ara' butonuna basıp oyun ekranını seçin.
* Metin kesme sürenizi yazın ve başlata basın.

# SSS
* **No module named ...** := Adı geçen modül yüklü değil demektir.
* **NameError: name 'wincap' is not defined** := Adı geçen ekran bulunamadı demektir.
* **win32ui.error: BitBlt failed** := Oyunda ekran yakalama engelli demektir.
* **Fare metinin üzerine gidiyor ama tıklamıyor?** := Programı ve Oyunu yönetici olarak açın. Yine olmadıysa çözümü hakkında bir fikrim yok.

# Güncel(son) Video
https://youtu.be/leYyXPpeUNk (haksız teliften dolayı kanal kapandı)


Kaynak:

https://www.youtube.com/watch?v=KecMlLUuiE4&list=PL1m2M8LQlzfKtkKq2lK5xko4X-8EZzFPI
https://docs.opencv.org/3.4/dc/d88/tutorial_traincascade.html
