# Oynanış

- Karakterimiz bir küre. Küre bir platforma iniyor ve indiği yüzeye -rastgele konumlarda- kutucuklar iniyor. İki tür kutucuk iniyor; birisi puan toplamamıza yarayan sarı kutucuklar,
 diğeri ise toplamamızın yasak olduğu kırmızı kutucuklar. Sarı kutucuk bize +1 puan sağlarken, kırmızı kutucuklar 1 puan düşürüyor. Eğer puanımız 0'ın altına düşecek olursa oyun tekrardan
başlatılıyor.
- Platformumuz sonlu bir yüzeye sahip. Bu yüzden kürenin hareket alanı sınırlı ve eğer platformdan düşecek olursa oyun tekrar başlatılıyor.
- Oyunu durdurmak veya yeniden başlatmak istersek, 'esc' tuşuna basmamız yeterli. Bu bize içinde 'Devam Et' ve 'Yeniden Başlat' butonları bulunan bir duraklat menüsü açacak ve işlemlerimizi buradan gerçekleştirebiliriz.
Tekrar 'esc' tuşuna basarak devam edebiliriz.
# Tuşlar:
 - w: Küreyi ileri hareket ettirir.
 - s: Küreyi geri hareket ettirir.
 - a: Küreyi sola hareket ettirir.
 - d: Küreyi sağa hareket ettirir.
 

# Oyun içi Görsel

![oyun içi görsel](https://user-images.githubusercontent.com/119112193/204590693-02038c9f-1a1d-4f9c-baef-47a0d6ddd904.png)


![image](https://user-images.githubusercontent.com/119112193/204598264-6dbb77e4-6ecf-42c6-8835-1fa1f055687a.png)


Ben;
- Sahnenin ve platformun oluşumu
- Oyuncunun hareket kontrolü(oyuncu_script)
- Rastgele kutuların oluşması(kutucuk_script)
- Oyuncu platform düşünce oyunun yeniden başlaması(menu_control) kısımlarıyla ilgilendim.

Ekip arkadaşım Kerem Parlak ise;
- Kamera takibi(camera_follow)
- Çarpma komutları ve puan toplama ,eksiltme,yazdırma ve yasaklı kutuların oluşması(oyuncu_script,kutucuk_script)
- Puan sıfırın altına düşünce oyunu yeniden başlatma(menu_control)
- Menü oluşturma(menu_control) kısımlarıyla ilgilendi.


Oyunu oynamak için aşağıdaki linke tıklayınız:

https://keremparlak0.itch.io/3d-object-collecting-game 

