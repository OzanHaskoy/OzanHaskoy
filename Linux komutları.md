#  $${\color{red}İŞLEVSEL\space LİNUX\space KOMUTLARI :penguin:}$$
## :red_circle:  $${\color{darkblue}Klosör\space oluşturma}$$
:point_right: `mkdir` komutu ile klosör oluşturulur.
```
mkdir DosyaAdi
```
*dosya1 adlı klosörün oluşturulması*:point_down:	<br>
![1](https://github.com/user-attachments/assets/f2020569-4a4d-4bb7-b50b-e1fdaf279533)

## :orange_circle:  $${\color{darkblue}Boş\space bir\space klosörü\space silme}$$
:point_right: `rmdir` eski boş klosörü silmeye yarayan komuttur.
```
rmdir DosyaAdi
```
*dosya1 adlı klosörün silinmesi*:point_down:<br>
![2](https://github.com/user-attachments/assets/ab3fa377-1248-48b2-bbdd-78dfe5cde66a)

## :yellow_circle:  $${\color{darkblue}Dosya,\space metin\space belgesi\space oluturma}$$
:point_right: `touch` komutu ile yeni metin belgesi, dosya oluşturulur.
```
touch DosyaAdi
```
*metin isimli dosyanın oluşturulması*:point_down:<br>
![3](https://github.com/user-attachments/assets/cb4d1251-ed89-4155-9b0f-af90f3d6963f)

## :green_circle: $${\color{darkblue}Dosyayı\space yeniden\space adlandırma}$$
:point_right: `mv` komutunu yazdıktan sonra eski dosyamızın adnı ardından yeni koyacağımız ismi yazarak yeniden adlandırmış oluruz.
```
mv eski_isim yeni_isim
```
*metin isimli dosyanın yeniad isimli dosya olarak adlandırılması*:point_down:<br>
![4](https://github.com/user-attachments/assets/17d7a59e-28ca-4ee7-9dc6-8b213f7767ed)

## 	:large_blue_circle: $${\color{darkblue}Dosyayı\space silme}$$
:point_right: `rm` dosyayı silmeye yarayan komuttur.
```
rm dosyaadi.txt
```
*yeniad isimli dosyanın silinmesi*:point_down:<br>
![5](https://github.com/user-attachments/assets/0c3da98f-9366-43a2-a47f-e80527849442)

## 	:purple_circle:  $${\color{darkblue}Dosyanın\space içeriğini\space ekrana\space aktarma}$$
:point_right: `cat` komutu ile dosyanın içeriği komut ekranında görüntülenir.
```
cat dosyaadi.txt
```
*Dosya isimli dosyanın içeriğinin görüntülenmesi*:point_down:<br>
![6](https://github.com/user-attachments/assets/dbd42b3e-b453-4e48-9d1a-054c51d588f8)

## 	:brown_circle: $${\color{darkblue}Sistemdeki\space kullanıcı\space adını\space gösterme}$$
:point_right: `whoami` komutu ile sistem kullanıcı adınız gözükür.
```
whoami
```
*Sistem kullanıcı adının gösterilmesi*:point_down:<br>
![7](https://github.com/user-attachments/assets/3e862eaf-fb96-4169-a97f-e72e6359c68f)

## 	:black_circle: $${\color{darkblue}Sistem\space bilgilerini\space gösterme}$$
:point_right: `uname -a` sistem bilgilerinizi ekrana döken komuttur
```
uname -a
```
*Sistem bilgilerinin ekranda gösterilmesi*:point_down:<br>
![8](https://github.com/user-attachments/assets/b1a3a574-0534-4917-aab4-82fa4c1e088b)

## :white_circle:  $${\color{darkblue}Disk\space kullanımının\space ekranda\space gösterilmesi}$$
:point_right: `df -h` disk kullanımını gösteren komuttur.
```
df -h
```
*disk kullanımının ekranda gösterilmesi*:point_down:<br>
![9](https://github.com/user-attachments/assets/1e257ae5-e524-43ce-a2ad-520fee9c49fa)

## :red_square: $${\color{darkblue}Klosör\space boyutunu\space gösterme}$$
:point_right: `du -sh` komutu ardından belirtilen klosörün boyutunu ekrana yazar.
```
du -sh KlosörAdi
```
*Resimler adlı klosörün boyutunu gösterme*:point_down:<br>
![10](https://github.com/user-attachments/assets/6eb0b6a1-049b-4c16-8dc1-df7cedbd8972)

## :orange_square: $${\color{darkblue}Sistemde\space çalışan\space işlemleri\space ve\space kaynak\space kullanımını\space gösterme}$$
:point_right: `top` komutu sistemde çalışan işlemleri ve kaynak kullanımını ekrana yazar.
```
top
```
*İşlemlerin ve kaynak kullanımının ekran yazılması*:point_down:<br>
![11](https://github.com/user-attachments/assets/dbbecdbe-a8fd-49ff-b47c-32f240710e0d)

## :yellow_square: $${\color{darkblue}RAM\space kullanımını\space gösterme}$$
:point_right: `free -m` komutu bellek kullanımınızı ekrana yazar.
```
free -m
```
*Bellek kullanımın ekrana yazılması*:point_down:<br>
![12](https://github.com/user-attachments/assets/ece6ffc5-2914-44ad-8850-3d7a843cd31c)

## :green_square: $${\color{darkblue}Tüm\space çalışan\space işlemleri\space listeleme}$$
:point_right: `ps -aux` Linux sistemlerinde çalışan süreçleri listelemek için kullanılan bir komuttur.
```
ps -aux
```
*Çalışan işlemlerin ekrana yazılması*:point_down:<br>
![13](https://github.com/user-attachments/assets/0cfe557c-3cac-4752-b840-838b01fef41b)

## :blue_square:  $${\color{darkblue}Dosyada\space belirli\space bir\space kelimeyi\space arama}$$
:point_right: `grep` komutu ile arama yapılır. bu komuttan sonra tırnak içinde kelime ve tırnaksız dosyanın adı yazılır.
```
grep "kelime" DosyaAdi.txt
```
*metin kelimesinin dosya adlı dosyada aranması*:point_down:<br>
![14](https://github.com/user-attachments/assets/cbb0c890-a6b9-43c7-90eb-60328923d389)

## :purple_square: $${\color{darkblue}Dosyadaki\space satır,\space kelime\space ve\space karakter\space sayısını\space görüntüleme}$$
:point_right: `wc` komutu ile ardından adı yazılan dosyanın sırasıyla satır,kelime ve karakter sayısı ekrana yazılır.
```
wc dosya.txt
```
*dosya adlı dosyanın satır,kelime ve karakter sayısının görüntülenmesi*:point_down:<br>
![15](https://github.com/user-attachments/assets/da734006-a068-4dad-9922-46ea3b2d1b6f)

## :brown_square: $${\color{darkblue}Tarih\space ve\space saati\space gösterme}$$
:point_right: `date` mevcut tarih ve saati gösteren komuttur.
```
date
```
*tarih ve saatin gösterilmesi*:point_down:<br>
![16](https://github.com/user-attachments/assets/a91a856a-f5ec-463b-87ce-8904d0ce96e9)

## :black_large_square: $${\color{darkblue}Bilgisayarı\space kapatma}$$
:point_right: `shutdown -h now`bilgisayarı anında kapatmaya yarayan koddur.
```
shutdown -h now
```
*Kapatma komutunun gösterilmesi*:point_down:<br>
![17](https://github.com/user-attachments/assets/a62e71bc-acc4-433f-b2cf-f6f142996ba0)

## :white_large_square:  $${\color{darkblue}Komut\space geçmişini\space görüntüleme}$$
:point_right: `history` kullanılan komutların geçmişini ekrana listeleyen komuttur.
```
history
```
*Komut geçmişinin ekranda listelenmesi*:point_down:<br>
![18](https://github.com/user-attachments/assets/429bcd7b-27bc-4940-bd32-a17f9500d6d6)

## 	:large_orange_diamond: $${\color{darkblue}Terminal\space ekranını\space temizleme}$$
:point_right: `clear` komutu ile terminal ekranına yazdıklarımız silinir.
```
clear
```
*Terminal ekranının silinmesi*:point_down:<br>
![19](https://github.com/user-attachments/assets/192fde3f-6be0-4a86-85a4-1354cc1621b8)

## :large_blue_diamond: $${\color{darkblue}Sistemin\space ne\space kadardır\space süre\space çalıştığını\space ve\space yük\space durumunu\space gösterme}$$
:point_right: `uptime` sistemin ne zamandır çalıştığını ve yük durumunu gösteren koddur.
```
uptime
```
*Sistemin çalışma süresi ve yük durumunun gösterilmesi*:point_down:<br>
![20](https://github.com/user-attachments/assets/978ca2d5-df0a-4f58-a6a7-adeb4510677f)







