# $${\color{red}Windows \space DOS\space işlevsel\space cmd\space komutları}$$ :computer:
## :red_circle: $${\color{blue}Klosör\space oluşturma\space komutu}$$
:point_right: `mkdir` komutu yeni bir klasör veya dizin oluşturmak için kullanılan bir komuttur. <br>
```
mkdir ornek1
```
*ornek1 adlı klosör oluşturma*👇:<br>
![1 mkdir](https://github.com/user-attachments/assets/9acb33d7-36e3-47d8-9fac-61b34dd03760)

## :orange_circle:  $${\color{blue}Dizin\space değiştirme,\space klosöre\space girme\space komutu}$$
:point_right: `cd` komutu dizin değiştirmeye yarayan bir komuttur.<br> 
bir klosörün içine girmek istiyorsak `cd` komutunu yazdıktan sonra klosörün adı yazılır. <br>
```
cd ornek1
```
*ornek1 adlı klosörün içine girme*👇:<br>
![2 cd](https://github.com/user-attachments/assets/bf4ca414-9488-409a-a3c0-f3c298e341b0)

## :yellow_circle:  $${\color{blue}Boş\space metin\space belgesi\space oluşturma\space komutu}$$
:point_right: `type nul>metin.txt` komutu boş bir metin belgesini oluşturmaya yarar.<br> 
```
type nul>metin.txt
```
*ornek1 adlı klosörün içine boş metin dosyası oluşturma*👇:<br>
![3 boş metin dosyası oluşturma](https://github.com/user-attachments/assets/50ba6696-4a61-40c6-9f1e-e8f70ca814f5)

## :green_circle:  $${\color{blue}Metin\space dosyasına\space yazı\space yazmak}$$
:point_right: `echo` komutu bir yazıyı yazdırmak için kullanılan komuttur. <br>
`echo` yazdıktan sonra metnimizi ekrana yazarız.`>` işaretini koyduktan sonra dosyamızın adını yazarız ve yazılar oraya işlenir. <br>
```
echo bu benim yazdigim metindir>metin.txt
```
*ornek1 adlı klosörde bulunan metin adlı metin belgesine yazı yazmak*👇:<br>
![4 yazı yazma kodu](https://github.com/user-attachments/assets/255b400a-1b1d-435c-ae17-dad0e04d0574)

## :large_blue_circle:  $${\color{blue}Dosyanın\space içeriğini\space ekrana\space yazdırma}$$
:point_right: `type` komutu belirttiğimiz dosyanın içeriğini ekrana yazmak için kullanılan komuttur. <br>
`type` yazdıktan sonra dosyanın adını ve türünü yazarız. <br>
```
type metin.txt
```
*ornek1 adlı klosörde bulunan metin belgesinin içeriğini ekrana yansıtmak*👇:<br>
![5 içeriği ekrana yazma](https://github.com/user-attachments/assets/95d43841-164b-44a7-822c-4003f0a1ad12)

## :purple_circle:  $${\color{blue}Dosya\space silme}$$
:point_right: `del` komutu belirttiğimiz dosyayı silmeye yarayan bir komuttur. <br>
`del` yazdıktan sonra dosyanın adı ve türünü yazarız. <br>
```
del metin.txt
```
*ornek1 adlı klosörde bulunan metin belgesini silmek*👇:<br>
![6 dosya silme](https://github.com/user-attachments/assets/af922cc5-836c-4986-97b4-bd21e0f7b532)

## :brown_circle:  $${\color{blue}Komut\space geçmişini\space ekrana\space yazdırmak}$$
:point_right: `doskey /history` komutu istemcisinde kullandığımız önceki komutları listeler.<br>
```
doskey /history
```
*komut geçmişinin ekrana yazdırılması*👇:<br>
![7 ekran komut geçmişi yazdırma](https://github.com/user-attachments/assets/0a88a2bf-d12f-4e1e-9716-755d2dedcca4)

## :black_circle:  $${\color{blue}Komut\space ekranını\space temizleme}$$
:point_right: `cls` komut istemcisinin ekranını temizler.<br>
```
cls
```
*İstemcinin ekranını temizleme*👇:<br> 
![8  istemci ekranı temizleme](https://github.com/user-attachments/assets/1e164902-0788-46a5-b8ce-af9d46c94a69)

## :white_circle:  $${\color{blue}Bilgisayar\space adını\space öğrenme}
:point_right: `hostname` pc'nizin adını ekrana yazdıran komuttur.<br>
```
hostname
```
*Bilgisayar adının ekrana yazılması*👇:<br> 
![9 pc adını yazdırma](https://github.com/user-attachments/assets/e26b871b-1664-4a36-9ea8-6b6bc9364941)

## 	:red_square:  $${\color{blue}Sistem\space bilgilerini\space gösterme}$$
:point_right: `systeminfo` bilgisayarınızn yazılım ve donanım bilgilerini listeleyen komuttur.<br>
```
systeminfo
```
*sistem bilgilerinin ekrana yazılması*👇:<br> 
![10 sistem bilgileri](https://github.com/user-attachments/assets/cadfc586-e99e-4387-95ce-52b321b6e107)

## :orange_square:  $${\color{blue}Çalışan\space tüm\space işlemleri\space listeleme}$$
:point_right: `tasklist` o anda çalışan tüm işlemleri ekrana yazdıran komuttur.<br>
```
tasklist
```
*çalışan işlemlerin ekrana yazılması*👇:<br> 
![11 tasklist](https://github.com/user-attachments/assets/4c44d7c1-ff6a-4cbb-a641-e51ca3b67532)

## 	:yellow_square:  $${\color{blue}Kullanıcı\space hesabının\space parolasını\space değiştirmek}$$
:point_right: `net user` kullanıcı hesaplarıyla ilgili bir komuttur.<br>
`net user` yazdıktan sonra Kullanıcı adını ve yeni parolanı yazarsan, hesabın yeni parolasını belirlersin.<br>
```
net user KullaniciAdi YeniParola
```
*parola değiştirme işleminin ekrana yazılması*👇:<br> 
![12 yeni parola](https://github.com/user-attachments/assets/165918cf-813b-441e-a11a-5a63347fc9fe)

## :green_square:  $${\color{blue}Tarih\space ve\space saati\space görüp\space değiştirmek}$$
:point_right: `time` komutunu yazarak saati anlık olarak kaç olduğunu gösteren ve ayarlamaya izin veren komuttur.<br>
`date` komutu tarihi gösteren ve değiştirmeye izin veren komuttur.<br>
```
time
```
```
date
```
*tarih ve saatin görsterilme ve değiştirilme işlemlerinin yazılması*👇:<br> 
![13 saat](https://github.com/user-attachments/assets/79eed7af-56e6-45fd-9587-203ff7e7af62) 
![13 tarih](https://github.com/user-attachments/assets/8e9e82ef-6cb9-4f8b-ace9-f73dd0a24fae)

## :blue_square:  $${\color{blue}Dosya\space veya\space klosör\space arama}$$
:point_right: `dir /s` komutunu yazarak ardından dosyanın adını yazarsak bizim için arar.<br>
`dir` listelemek için kullanılır. `/s` komutu dizinleri arar ve dosyayı bulmaya çalışır.
```
dir /s DosyaAdi
```
*Games adlı klosörün aranma işleminin yapılması*👇:<br> 
![14 klosör dosya arama](https://github.com/user-attachments/assets/cef1ab1f-a25a-46a8-bbd5-483ae75c0b1e)

## :purple_square:  $${\color{blue}Zamanlayıcı\space ile\space PC\space kapamak}$$
:point_right: `shutdown /s /t 60` komutu PC'nin 60 saniye içinde kapanmasını sağlayacak komuttur. <br>
`shutdown /s` PC'nin kapanmasını ifade eder. `/t 60`saniye cinsinden zamanlayıcıyı kurar.
```
shutdown /s /t 60
```
*Zamanlayıcının kurulma işlemi*👇:<br> 
![15 pc kapama](https://github.com/user-attachments/assets/6a03bb0c-1b41-4717-b25b-05d78efbec2e)

## :brown_square:  $${\color{blue}Zamanlayıcı\space ile\space kapanacak\space PC'nin\space iptal\space edilmesi}$$
:point_right: `shutdown /a` komutu PC için kapama zamanlayıcısı kurulduysa bunu iptal eder.
`/a` kapanma işlemini iptal eden komuttur.
```
shutdown /a
```
*İptal işleminin yapıması*👇:<br> 
![16 pc kapama iptali](https://github.com/user-attachments/assets/bcae72e6-437f-4cb9-9aa9-336593914093)

## :black_large_square:  $${\color{blue}Hesap\space makinesini\space açma}$$
:point_right: `calc.exe` komutu ile hesap makinesi açılır.
```
calc.exe
```
*hesap makinesini açılması*👇:<br> 
![f](https://github.com/user-attachments/assets/b64e4aff-a2f4-4a77-9fe7-e902a65f7e16)


## :white_large_square:  $${\color{blue}Ekran\space klavyesini\space açma}$$
:point_right: `osk.exe` ekran klavyesini açan komuttur.
```
osk.exe
```
*Ekran klavyesinin açılması*👇:<br> 
![e](https://github.com/user-attachments/assets/fd82eabe-de0a-4983-9582-21047360fcdb)


## :large_orange_diamond:  $${\color{blue}Program\space ekle,\space kaldır\space ekranını\space açma}$$
:point_right: `appwiz.cpl` programlar ve özellikler menüsünü açan komuttur.
```
appwiz.cpl
```
*programlar ve özellikleri menüsünün açılması*👇:<br>
![d](https://github.com/user-attachments/assets/a973c32b-9a8a-4f47-97a0-e28959da4300)


## :large_blue_diamond:  $${\color{blue}Ses\space ayarlarını\space açma}$$
:point_right: `mmsys.cpl` ses ayarlarını açan komuttur.
```
mmsys.cpl
```
*ses ayarlarının açılması*👇:<br>
![c](https://github.com/user-attachments/assets/9e088179-89b5-43dd-b504-b7a1aa90a8f4)


## :small_red_triangle:  $${\color{blue}Görev\space yöneticisini\space açma}$$
:point_right: `taskmgr.exe` görev yöneticisinin açılmasını sağlayan komuttur.
```
taskmgr.exe
```
*Görev yöneticisinin açılması*👇:<br>
![b](https://github.com/user-attachments/assets/9d6f7d54-9a74-454c-b19c-54e6a566816b)

## :small_red_triangle_down:  $${\color{blue}İnternet\space kontrol\space ekranını\space açma}$$
:point_right: `inetcpl.cpl` internet kontrol ekranının açılmasını sağlayan komuttur.
```
inetcpl.cpl
```
*İnternet kontrol ekranının açılması*👇:<br>
![a](https://github.com/user-attachments/assets/6331899a-7a60-47b2-80ae-043d962b8fba)









