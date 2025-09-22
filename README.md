Albatta! Men sizning HTML kodingizni **README** shaklida, alohida bo‘limlarga ajratib, tushuntiruvchi tarzda yozib beraman. Bu README sizni GitHub sahifangizda ishlatishga tayyor bo‘ladi.

---

# Rustam Saydaxmatov – Portfolio

Bu shaxsiy portfoliyo sayti, Rustam Saydaxmatovning malakalari, loyihalari, blog posti va aloqa ma’lumotlarini namoyish qiladi. Sayt **O‘zbekcha, Ruscha va Inglizcha** tillarini qo‘llab-quvvatlaydi va **dark/light theme** rejimiga ega.

---

## 1. Texnologiyalar

* **HTML5 & CSS3** – saytning tuzilishi va dizayni.
* **Bootstrap 5.3** – responsiv dizayn va komponentlar.
* **Bootstrap Icons** – ikonalar uchun.
* **AOS (Animate On Scroll)** – scroll effekti.
* **JavaScript** – interaktivlik, til va mavzu o‘zgartirish, kontakt formani Telegram orqali yuborish.

---

## 2. Foydalanuvchi interfeysi

### Navbar

* Sayt yuqorisida joylashgan va sticky-top (scroll qilinganda ham yuqorda qoladi).
* Quyidagi bo‘limlarga tezkor havolalar:

  * Men haqimda / About
  * Malakalar / Skills
  * Loyihalar / Projects
  * Blog
  * Aloqa / Contact
* Tema (dark/light) va tilni o‘zgartirish tugmalari mavjud.

### About Section

* Rustam haqida asosiy ma’lumotlar:

  * Ism, daraja, soha.
* Profil rasmi (rasm.jpg) bilan birga joylashgan.

### Skills Section

* Asosiy malakalar 3 ta kartada:

  * **Dasturlash tillari** – Python, C++, JavaScript, Bash
  * **Texnologiyalar** – AI, IoT, Web Frameworks, Linux serverlar
  * **Ilmiy yondashuvlar** – Tadqiqot, analitika, yangi bilimlarni egallash

### Projects Section

* Asosiy loyihalar:

  * Smart Home System – IoT asosida uy va sensorlar boshqaruvi
  * Personal Portfolio – Bootstrap asosida shaxsiy sayt
  * AI Chatbot – Tensorflow asosida sun’iy intellekt tizimi

### Blog Section

* Sayt yangiliklari va blog postlar:

  * Ilk blog posti
  * AI haqida fikrlar
  * O‘qiyotgan kitoblar

### Contact Section

* Kontakt formasi foydalanuvchidan **ism, email va xabar** qabul qiladi.
* Telegram bot API orqali xabarlar yuboriladi.

### Footer

* Sayt oxirida joylashgan, hozirgi yil avtomatik ko‘rsatiladi.
* Shaxsiy sahifalar:

  * Instagram
  * Telegram
  * Telefon raqam

---

## 3. Til qo‘llab-quvvatlash

Sayt uchta tilni qo‘llab-quvvatlaydi:

| Til       | HTML class | Belgilangan shrift |
| --------- | ---------- | ------------------ |
| O‘zbekcha | lang-uz    | default            |
| Ruscha    | lang-ru    | Arial, sans-serif  |
| Inglizcha | lang-en    | Georgia, serif     |

Til o‘zgartirilganda barcha matnlar avtomatik tarjima qilinadi.

---

## 4. Dark/Light Mode

* Sayt `data-bs-theme` atributi orqali mavzuni boshqaradi.
* Foydalanuvchi tugma orqali dark/light rejimni o‘zgartirishi mumkin.
* Tanlangan mavzu **localStorage** ga saqlanadi, keyingi tashriflarda avtomatik qo‘llanadi.

---

## 5. Texnik ma’lumotlar

* **Responsive dizayn** – mobil, tablet va desktop ekranlar uchun moslashgan.
* **AOS animatsiyalari** – har bir bo‘lim scroll qilinganda vizual effektlar bilan ochiladi.
* **Telegram integratsiyasi** – kontakt formadan yuborilgan xabarlar sizning Telegram hisobingizga tushadi.

**Telegram API** orqali xabar yuborish kodi:

```javascript
const botToken = 'BOT_TOKEN';
const chatId = 'CHAT_ID';
fetch(`https://api.telegram.org/bot${botToken}/sendMessage`, {
  method: 'POST',
  headers: {'Content-Type': 'application/json'},
  body: JSON.stringify({ chat_id: chatId, text: message, parse_mode: 'HTML' })
});
```

---

## 6. Foydalanish

1. HTML faylni serverga yoki GitHub Pages ga yuklash.
2. `rasm.jpg` faylini profil rasmi sifatida joylashtirish.
3. Telegram bot token va chat ID ni o‘zgartirib xabarlarni olish.
4. Sayt avtomatik responsiv va ko‘p tilli ishlaydi.

---

Agar xohlasangiz, men bu README-ni **Markdown fayl** ko‘rinishida GitHub uchun tayyorlab, to‘g‘ridan-to‘g‘ri `.md` fayl sifatida bera olaman.

Shuni qilaylikmi?
