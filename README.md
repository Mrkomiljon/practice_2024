# practice_2024

Bu repository GitHub'ga folder qo'shish jarayonini namoyish etish uchun yaratilgan.

## Folder'ni Repository'ga Qo'shish

GitHub orqali to'g'ridan-to'g'ri folder yuklash mumkin emas, chunki GitHub faqat fayllarni qabul qiladi. Biroq, siz folder'ni va uning ichidagi fayllarni lokal Git orqali quyidagi qadamlarni bajarib GitHub'ga yuklashingiz mumkin:

### 1. Repository'ni Lokalga Klonlash

Dastlab, agar siz hali qilmagan bo'lsangiz, GitHub repository'ni lokal kompyuteringizga klonlab oling:

```bash
git clone https://github.com/Mrkomiljon/practice_2024.git
```

```bash
cd practice_2024
```
Yuklamoqchi bo'lgan folder'ni ushbu papkaga ko'chiring yoki yangidan yarating. Masalan, documents nomli yangi papka yaratish:

```bash
mkdir documents
```

O'zgarishlarni Git'ga Qo'shish va Commit Qilish
Barcha o'zgarishlarni git'ga qo'shing va ularni commit qiling:
```bash
git add .
git commit -m "Added new documents folder"
```
O'zgarishlarni GitHub'ga Push Qilish
O'zgarishlarni GitHub'dagi repository'ga yuboring:
*** Please tell me who you are.

Run
```bash
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
to set your account's default identity.
Omit --global to set the identity only in this repository.
```bash
git push origin main
```

Faylni Lokalda O'chirish

Endi o'chirmoqchi bo'lgan faylingizni toping va uni git rm komandasi yordamida o'chiring:

```bash

git rm path/to/your/file.txt
```

O'zgarishlarni Commit Qilish

Faylni o'chirganingizdan so'ng, bu o'zgarishni commit qiling:

```bash
git commit -m "Remove file.txt
```
O'zgarishlarni GitHub'ga Push Qilish

O'zgartirilgan commit'ni GitHub repositoriyangizga yuboring:

```bash
git push origin main
```
__  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __  __ __  __  __  __  __  __
## 1. GitHub LFS ni o‘rnatish (katta fayllar uchun)
Agar yuklayotgan .pdf yoki .py fayllaringiz katta hajmda bo‘lsa, GitHub LFS dan foydalanish tavsiya etiladi:

```bash
git lfs install
```
2. .pdf fayllarni GitHub LFS orqali kuzatishga qo‘shish
GitHub LFS ni faqat katta hajmli fayllarga qo‘llaniladi. Agar .pdf fayllaringiz kattaroq bo‘lsa, kuzatishga qo‘shishingiz mumkin:

```bash
git lfs track "*.pdf"
```
.py fayllar odatda katta hajmda bo‘lmaganligi sababli, ularni oddiy git orqali yuklash kifoya qiladi.

3. lesson papkasini qo‘shish va yuklash
lesson papkasidagi fayllarni GitHub-ga yuklash uchun quyidagi buyruqlarni bajaring:

```bash
git init                          # Repositoriyani ishga tushirish (faqat birinchi marta kerak)
git add lesson/                   # lesson papkasidagi barcha fayllarni qo‘shish
git commit -m "Lesson papkasini yuklamoqdamiz"
git remote add origin <repository-url>  # GitHub repositoriya URL manzilini qo‘shish
git push -u origin main           # Yaratilgan commit-ni yuklash
```
