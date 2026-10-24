# Tabiiy Fanlar (tabiiy-fanlar.uz) — Android Mobil Ilovasi

Ushbu loyiha **https://www.tabiiy-fanlar.uz** veb-sayti uchun to'liq funksional Android WebView mobil ilovasi hisoblanadi.

## Ilova imkoniyatlari:
- **To'liq WebView integratsiyasi:** JavaScript, DOM Storage va zamonaviy veb-texnologiyalarni qo'llab-quvvatlaydi.
- **Pull-to-Refresh:** Sahifani yuqoridan pastga tortib yangilash imkoniyati.
- **Yuklanish indikatori (ProgressBar):** Sahifa yuklanish jarayonini ko'rsatib turadi.
- **Fayllarni yuklab olish:** Saytdagi PDF, DOCX va boshqa o'quv materiallarini yuklab olishni qo'llab-quvvatlaydi.
- **Orqaga qaytish navigatsiyasi:** Telefondagi "Orqaga" tugmasi bosilganda ilovadan chiqib ketmasdan oldingi sahifaga qaytadi.

---

## Tayyor `.apk` faylini qanday olish mumkin? (3 xil oson usul)

Sun'iy intellekt muhitida Android SDK kompilyatori bo'lmaganligi sababli, tayyor kodlardan 1-2 daqiqa ichida quyidagi usullardan biri orqali `.apk` fayl yaratib olishingiz mumkin:

### 1-usul: Hech qanday dastur o'rnatmasdan (Onlayn xizmat orqali — 1 daqiqada)
Agar ushbu kodlarni kompilyatsiya qilmasdan tezda `.apk` olmoqchi bo'lsangiz:
1. **WebIntoApp.com** yoki **AppsGeyser.com** yoki **PWABuilder.com** saytiga kiring.
2. URL maydoniga `https://www.tabiiy-fanlar.uz` manzilini kiriting.
3. Ilova nomiga **Tabiiy Fanlar** deb yozing va ikonka tanlang.
4. **"Make App"** tugmasini bosing va tayyor `.apk` faylni yuklab oling.

### 2-usul: GitHub Actions orqali (Kompyuterga dastur o'rnatmasdan, bepul)
Ushbu arxiv ichida `.github/workflows/build_apk.yml` fayli tayyorlab qo'yilgan:
1. GitHub.com profilida yangi repozitoriy yarating.
2. Arxivdagi barcha fayllarni shu repozitoriyga yuklang.
3. **Actions** bo'limiga o'tsangiz, GitHub avtomatik ravishda `.apk` faylni yig'ib beradi va uni **Artifacts** bo'limidan yuklab olasiz.

### 3-usul: Android Studio orqali (Kompyuterda)
1. Arxivni kompyuteringizda oching.
2. **Android Studio** dasturida **Open** tugmasini bosib, shu papkani tanlang.
3. Yuqori menyudan **Build -> Build Bundle(s) / APK(s) -> Build APK(s)** tugmasini bosing.
