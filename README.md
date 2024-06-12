# practice_2024 Repository

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
