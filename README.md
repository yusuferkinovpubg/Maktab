# Intellectual Game — The Circle of Clever Students (Web Version)

Ushbu loyiha `Game.pptx` taqdimotidagi intellektual o'yinning to'liq interaktiv veb-versiyasidir. Taqdimot ichidagi barcha **18 ta rasm va animatsiyalar** (`assets/` papkasida) hamda **25 ta savol va javoblar** (5 ta bo'lim: *Parallelepiped, Kub, Slindr, Konus, Shar*) saqlangan.

## 📁 Loyiha tuzilishi
- `index.html` — O'yinning asosiy veb-sahifasi (Bosh sahifa, 5x5 Savollar doskasi, Savol slaydlar, Jamoalar hisobi va Natijalar).
- `assets/` — `Game.pptx` faylidan ajratib olingan barcha 18 ta original rasm va GIF animatsiyalar (`image1.jpeg` .. `image18.png`).
- `vercel.json` — Vercel platformasi uchun tayyor konfiguratsiya fayli.
- `package.json` — Loyiha metama'lumotlari.

## 🚀 Vercel.app ga joylash bo'yicha qisqa yo'riqnoma

### 1-usul: GitHub orqali (Eng oson va avtomatik usul)
1. Ushbu ZIP arxivni kompyuteringizda oching.
2. [GitHub](https://github.com/new) da yangi repozitoriy yarating va ushbu papkadagi barcha fayllarni (`index.html`, `vercel.json`, `package.json`, `assets/`) yuklang.
3. [Vercel Dashboard](https://vercel.com/new) sahifasiga kiring, GitHub repozitoriyngizni tanlab **Deploy** tugmasini bosing.
4. 10–15 soniyada saytingiz `https://sizning-loyihangiz.vercel.app` manzilida ishga tushadi!

### 2-usul: Vercel CLI orqali (Terminaldan)
Agar kompyuteringizda Node.js o'rnatilgan bo'lsa, ushbu papka ichida terminalni ochib quyidagi buyruqni yozing:
```bash
npx vercel --prod
```
