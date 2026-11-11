# Poligon 3D

Botlarga qarshi jamoaviy 3D otishma o'yini. Android telefonlar uchun APK sifatida yig'iladi.

## Telefonga o'rnatish

1. Shu reponing **Releases** bo'limini oching.
2. Eng oxirgi relizdan `Poligon3D.apk` faylini telefoningizga yuklab oling.
3. Faylni oching. Telefon "noma'lum manbadan o'rnatish"ga ruxsat so'raydi, ruxsat bering.

## O'yinda nima bor

- 3 ta xarita: Qal'a (cho'l shaharchasi), Port (konteynerlar), Shahar (kechki payt)
- 2 ta rejim: raundlar (xarid bilan) va qayta tirilish jangi
- 7 ta qurol, 3 xil granata, zirh
- Jamoadoshlar va raqiblar soni, qiyinlik, grafika sifati sozlanadi
- Daraja, statistika, yutuqlar, qurol va kiyim ranglari

## Boshqaruv

- Ekranning chap tomoni: yurish (barmoqni oldinga oxirigacha sursangiz yuguradi)
- Ekranning o'ng tomoni: atrofga qarash
- Tugmalar: otish, nishonga olish, sakrash, cho'kkalash, qayta o'qlash, qurol almashtirish, granata
- Avto-otish va nishon yordami sozlamalardan yoqiladi yoki o'chiriladi
- Tugmalar joyi va o'lchami "Boshqaruv" bo'limida o'zgartiriladi

## Loyiha tuzilishi

- `app/src/main/assets/index.html` — o'yinning o'zi (bitta fayl, brauzerda ham ochiladi)
- `app/src/main/java/.../MainActivity.java` — o'yinni to'liq ekranda ko'rsatadigan Android qobig'i
- `.github/workflows/build.yml` — `main` ga har bir push'da APK yig'ib, relizga joylaydi

3D grafika uchun [three.js](https://threejs.org) (MIT litsenziyasi) ishlatilgan.
