# 🌐 Варианты блока «ссылка на сайт» для профиля

> Открой этот файл в GitHub-превью или в любом Markdown-вьюере, чтобы увидеть, как варианты выглядят живьём (анимация SVG работает только при рендере).
> Каждый вариант кликабельный — попробуй ткнуть.

---

## Вариант 1 — Анимированный «печатающийся» терминал (вайб текущего README, GitHub-синий)

<div align="center">

<a href="https://eze.sh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&height=70&lines=%24+curl+-L+https%3A%2F%2Feze.sh;Loading+portfolio...;%E2%96%B6+Welcome+to+my+CRT+terminal_" alt="Visit eze.sh"/>
</a>

</div>

```markdown
<a href="https://eze.sh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&height=70&lines=%24+curl+-L+https%3A%2F%2Feze.sh;Loading+portfolio...;%E2%96%B6+Welcome+to+my+CRT+terminal_" alt="Visit eze.sh"/>
</a>
```

---

## Вариант 2 — ASCII-бокс «HTTP response» (полностью статика, ноль зависимостей)

<div align="center">

```bash
root@portfolio:~# curl -I https://eze.sh
```

```http
╔══════════════════════════════════════════════════╗
║  HTTP/2 200 OK                                   ║
║  server: nginx                                   ║
║  content-type: text/html; charset=utf-8          ║
║  x-powered-by: caffeine & python                 ║
║  x-portfolio: open-for-collab                    ║
║                                                  ║
║  → https://eze.sh                                ║
╚══════════════════════════════════════════════════╝
```

### 👉 [**`open https://eze.sh`**](https://eze.sh)

</div>

---

## Вариант 3 — 🔥 В вайбе eze.sh: CRT-терминал, янтарь на тёмном (анимация)

<div align="center">

<a href="https://eze.sh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=900&color=FFB000&background=1A1A1AFF&center=true&vCenter=true&multiline=true&width=760&height=140&lines=%5B+CRT+TERMINAL+%E2%80%94+eze.sh+%5D;%24+ssh+visitor%40eze.sh;%E2%80%BA+portfolio+ready_" alt="eze.sh CRT terminal"/>
</a>

</div>

```markdown
<a href="https://eze.sh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=900&color=FFB000&background=1A1A1AFF&center=true&vCenter=true&multiline=true&width=760&height=140&lines=%5B+CRT+TERMINAL+%E2%80%94+eze.sh+%5D;%24+ssh+visitor%40eze.sh;%E2%80%BA+portfolio+ready_" alt="eze.sh CRT terminal"/>
</a>
```

---

## Вариант 4 — 🔥 В вайбе eze.sh: «boot sequence» + большая amber-кнопка

<div align="center">

```log
[  OK  ] Mounted   /portfolio
[  OK  ] Started   nginx.service
[  OK  ] Reached   target  Multi-User System
[  OK  ] Loaded    crt-phosphor (amber)
[ INFO ] Listening on https://eze.sh ...
```

<a href="https://eze.sh">
  <img src="https://img.shields.io/badge/%E2%96%B6%20VISIT%20PORTFOLIO-eze.sh-FFB000?style=for-the-badge&labelColor=1A1A1A&color=FFB000" height="48" alt="Visit eze.sh"/>
</a>

</div>

```markdown
<a href="https://eze.sh">
  <img src="https://img.shields.io/badge/%E2%96%B6%20VISIT%20PORTFOLIO-eze.sh-FFB000?style=for-the-badge&labelColor=1A1A1A&color=FFB000" height="48" alt="Visit eze.sh"/>
</a>
```

---

## Вариант 5 — Большой ASCII «PORTFOLIO» с кликабельным заголовком

<div align="center">

<a href="https://eze.sh">

```ascii
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   ██████╗  ██████╗ ██████╗ ████████╗███████╗ ██████╗ ██╗     │
│   ██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝██╔═══██╗██║     │
│   ██████╔╝██║   ██║██████╔╝   ██║   █████╗  ██║   ██║██║     │
│   ██╔═══╝ ██║   ██║██╔══██╗   ██║   ██╔══╝  ██║   ██║██║     │
│   ██║     ╚██████╔╝██║  ██║   ██║   ██║     ╚██████╔╝███████╗│
│   ╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝      ╚═════╝ ╚══════╝│
│                                                              │
│              >  https://eze.sh  <  click_anywhere            │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

</a>

### 🔗 [**https://eze.sh**](https://eze.sh)

</div>

> ⚠️ В GitHub Markdown `<a>` вокруг `code-fence` не делает блок кликабельным — поэтому под ASCII-арт продублирована обычная ссылка. На вид всё равно цельно.

---

## 📝 Шпаргалка после выбора

- Если зайдёт **№1 / №3** — это SVG-сервис `readme-typing-svg.demolab.com`, можно крутить параметры: `lines=` (через `;`), `color=`, `background=` (8 hex с альфой), `size=`, `width=/height=`, `font=` (любой шрифт с Google Fonts).
- Если **№4** — `img.shields.io/badge/...` принимает любой текст и hex без `#`.
- Если **№2 / №5** — чистый Markdown, ничего лишнего, рендерится одинаково везде.

Скажи номер — вмонтирую в `EZEMATIX.md` в нужное место (под ASCII-шапкой / в «Connect With Me» / отдельной секцией).
