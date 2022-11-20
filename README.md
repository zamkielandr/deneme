# good morning vietnam
## good morning vietnam
### good morning vietnam
#### good morning vietnam
##### good morning vietnam
###### good morning vietnam

iki veya daha fazla başlık oluşturduktan sonra başığın yanındaki zincir kısmı ile paragrafın alt metnine inebiliriz
`
### yazı şekillerini düzenleme ve yazı tipleri
* kalın formda yazmak için ** ** veya __ __ | **ince** veya __ince__

* eğik (italik) formda yazmak için * * veya _ _ | *tilt* veya _tilt_

* üstü çizikli istersen (alt+ü) ~~ ~~ | ~~beni karala~~

* iç içe formda kalın ve italik **_ _** |    **eğilmez, _bükülmez_ ,kırılmaz**

* hepsi kalın ve italik *** *** | ***hoca maçı bitir hoca***

* alt metin formu ne olduğunu bilmiyorum ama deneyelim <sub> </sub> | <sub> aşağı bak </sub>

* üst metini deniyorum <sup> </sup> | <sup> hop yukardayım </sup>

* metin alıntılama > ile dene (gayet kullanışlı duruyor

söz dizimi içi <!-- büyüktür işareti kullan -->

>evet evet bu bir söz dizimi

kesme işareti arasında yazı ile kodu vurgulayabilirsin kopyalamak için komutu yapamadım >tekrar dene
paragrafı biçimlendirmeyi deniyorum kene (backtick işaretini kullan (alt+virgül)
>bununla içerisindeki yazıyı kopyalayabilirsin bunu unutma
```
bir
iki
üç
```

alıntılarda ilk üç kenenin yanına kodlama dilini yazarsan yazı dili ona göre eyleme geçecek

```python
list=["hdnejoh","seaways","hesoyam","nuttertools","panzer"]
```
```javascript
function test() {
  console.log("notice the blank line before this function?");
}
```
link eklemek için [](web sitesi linki) şeklinde yapmalısın 
>[ismail yk nın gizli sitesi](www.bombabomba.com)

şimdi sıra geldi görüntü eklemeye ![]() formunda olup kara paranteze image normal paranteze sitemizi yazıyoruz 
>bu arada cihazdan resmi kopyala diyip yapıştırınca otomatik olarak yükleniyor
![luci](https://user-images.githubusercontent.com/101600310/202918888-53d6b18a-9bfd-4db6-862e-183c8b58429e.jpg)
>ya da img src="" width="" height="" kalıbını <> içerisine yazıp yapabilirsin. Fotoğrafın boyutunu sadece bu formda yazarsan değiştirebilirsin
<img src="https://user-images.githubusercontent.com/101600310/202918888-53d6b18a-9bfd-4db6-862e-183c8b58429e.jpg" width="85" height="85">

sıralı olmaayan liste oluşturmak içinse - * + parantezin başına koyaraak deneyebilirsin
to do list
+ to do
+ to do do 
+ to do do do 
formunda

shopping list 
* lemon
* orange
* kiwi
* banana
>not * bunu ayrı yazmazsan italik formunda yazar
bir de sıralı dizi formunda deneyelim
GalaXI
1. Muslera
2. Boey
3. Kerem 
4. Icardi

iç içe liste 
1. İÇ
   - İÇE
     - LİSTE
görev listesi içinse - kara karantez aç kapa şeklinde liste yapmalısın yapılanlara x koyabilirsin
- [x]  günde 2 litre su tüket 🚰
- [ ]  50 sayfa kitap oku 📖
- [x]  kayda değer 3 iş yap ⚜️

emoji eklemek için : yanına kelime ekleyerek yapabilirsin 

kodda gözüküp çıktıda gözükmeyen yerler için !--blablabla-- formundaki yazıyı <> bunun içerisine koymalısın
<!--say my name--> ya da say my name 
```
paragraf için 1 boş satır bırakman yeterli
```
sıra geldi referans ve kaynakçaya kaynakçayı belirtmek için [^3] [^5] veya [^note] formunda yazabilirsin . kaynakça kısmındaki linklerin önüne > [^1] [^2] veya [^note] den sonra : koyman gerekli bunu unutma

Sıkılıyorum Sabri bunalıyorum isyan ediyorum isyan[^1].

Bilmez miyim ekrem Abi bilmez miyim[^2].

[^1]: Merhum Ekrem Abi
[^2]: Dolandırıcı Sabri Abi

algoritma chartına benzer akış diyagramı yapmak için 
```mermaid
graph TD;
a-->b;
b-->c;
c-->d;
a-->e;
e-->d;
```
aynı zamanda mermaid js ile pie chart da yapabilirsin
```mermaid
pie title en sevdiğim oyunlar
    "DOOM"               :16
    "CALL OF DUTY"       :24
    "BIOSHOCK"           :28
    "THE WOLF AMOUNG US" :26
    "TEAM FORTRESS 2"    :9
```
tabi bunlar basit formda biraz java script bakmanın faydası var
<details><summary>buraya tıkla</summary>
<p>
buraya bir şeyler saklayabilirsin
</p>
</details>
