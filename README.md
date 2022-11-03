# JAVASCRİPT TARİH ( DATE ) İŞLEMLERİ TANIMLAMA

### Get Metotlarının Kullanımı

 - **getDate()**: Tarih bilgisinin gün kısmını alarak 1-31 arasında bir sayı şeklinde gösterir.
 - **getDay()**: Haftanın günü bilgisini 0-6 arasında bir sayı şeklinde
   gösterir.
 - **getFullYear()**: Yıl kısmını alır.
 - **getHours()**: 0-23 arasında olacak şekilde saat kısmını alır.
 - **getMilliseconds()**: Milisaniye kısmını alır (0-999).
 - **getMinutes()**: 0-59 şeklinde dakika kısmını alır.
 - **getMonth()**: 0-11 arasında olacak şekilde ay bilgisini alır. Ocak için 0, Şubat için 1, ..
 - **getSeconds()**:  Saniye kısmını alır. (0-59)
 - **getTime()**: 1 Ocak 1970 tarihi ile aradaki zamanı milisaniye cinsinden verir.

### Set Metotlarının Kullanımı

 - **setDate**(): Gün kısmını ayarlamakta kullanılır.1 ile
   31 arasında bir değer alır.
 - **setFullYear**(): Sırasıyla yıl, ay ve gün kısımlarını ayarlamakta kullanılır. Ay ve gün kullanılmayabilir.
 - **setHours**(): Saat kısmını ayarlar.
 - **setMilliseconds**(): Milisaniye kısmını ayarlar. (0-999)
 - **setMinutes**(): Dakika kısmını ayarlar. (0-59)
 - **setMonth**(): Ay kısmını ayarlar.  Ocak için 0, Şubat için1, … (0-11)
 - **setSeconds**(): Saniye kısmını ayarlar. (0-59)
 - **setTime**(): 1 Ocak 1970’e milisaniye cinsinden değer eklenerek yeni bir tarih elde edilmesini sağlar.

```
var zaman = new Date();
var yıl = zaman.getMonth();
document.write(yıl);
```

### Technologies used

- **Javascript**
- **HTML**
- **CSS**
