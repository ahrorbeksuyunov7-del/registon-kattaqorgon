# Registon o‘quv markazi — Kattaqo‘rg‘on filiali sayti

Sayt: https://ahrorbeksuyunov7-del.github.io/registon-kattaqorgon/ (bepul GitHub Pages manzili).
Qisqa havola: https://da.gd/registon (da.gd — bepul qisqartirgich; yangi havola birinchi soatda tasdiq sahifasini ko‘rsatadi).

`index.html` — butun sayt bitta faylda (rasmlar va shriftlar ichida). U yopiq `registon-avtopost` omboridagi
`sayt/manba/` dan yig‘iladi (`python3 sayt/manba/build.py`) — bu yerda qo‘lda o‘zgartirmang.
Arizalar Edu tizimdagi «Web sayt Kattakurgan» anketasiga tushadi.

Ingliz tili daraja testi: https://ahrorbeksuyunov7-del.github.io/registon-kattaqorgon/test/ (`test/index.html`, manbasi ham
`registon-avtopost` omborida: `sayt/test/`). Natijalar va speaking bahosi markazning Google Sheets jadvaliga tushadi
(jadvalga bog‘langan Apps Script orqali; speaking’ni Gemini baholaydi, kalit sahifada emas, skriptda).

Keyinchalik o‘z domeni ulansa: ombor ildiziga `CNAME` fayli (domen nomi) qo‘yiladi va domen panelida DNS yozuvlari
GitHub Pages’ga yo‘naltiriladi.
