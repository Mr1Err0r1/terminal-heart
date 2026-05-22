# 💚 terminal-heart

```
  ──────────────────────────────────────────
  INCOMING MESSAGE
  RECIPIENT : you
  ──────────────────────────────────────────
```

> A retro CRT terminal that delivers a heartfelt message to someone you care about —
> with animations, mini-games, and a lo-fi soundtrack. One HTML file. No installation.

---

## 🌐 Languages / Языки / Sprachen

- [English](#english)
- [Русский](#русский)
- [Deutsch](#deutsch)

---

<a name="english"></a>
## ✦ English

### What is this?

**terminal-heart** is a self-contained HTML page styled as a retro green-phosphor terminal.
You open it in any browser and it boots up, types out a warm personal message, asks how you're doing, reacts to your answers — and finishes with a firework.

It was originally made for one girl. Now it's for any girl. Or anyone, really.

### Features

| Feature | Description |
|---|---|
| 🖥️ CRT aesthetic | Scanlines, screen flicker, phosphor glow — pure retro |
| ✍️ Typewriter effect | Text appears character by character |
| 🌸 Bloom animation | An SVG flower grows in real time |
| ⭐ Starfall | 30 coloured stars cascade down the screen |
| 🎆 Fireworks | CSS particle bursts at the end |
| 🎵 Lo-fi music | Soft background audio (v4, unmuted on start) |
| 🎮 Mini-games | Typing challenge, memory card flip, number guess |
| 💬 Branching responses | Reacts differently to how your day is going |
| 📱 Mobile-friendly | Works on phone browsers too |

### Customisation

Open the file in a text editor and find the `CFG` block near the top of the `<script>`:

```js
const CFG = {
  NAME: '',   // ← name of the recipient
  FROM: '',           // ← optional: your name (leave empty to stay anonymous)
};
```

Change `NAME` to her name (or his, or yours, or anyone's) and save.  
That's it — the whole experience adapts automatically.

### How to use

1. Download `terminal-heart.html`
2. Edit the two lines in `CFG`
3. Open in any modern browser — or host it on GitHub Pages for a shareable link

### Commands available in the terminal

| Command | Action |
|---|---|
| `help` | show all commands |
| `again` | restart from the beginning |
| `bloom` | grow the flower again |
| `stars` | trigger a starfall |
| `fire` | launch fireworks |
| `game` | open the mini-game menu |
| `clear` | clear the screen |

---

<a name="русский"></a>
## ✦ Русский

### Что это?

**terminal-heart** — это один HTML-файл, стилизованный под ретро-терминал с зелёным свечением.
Открываешь в браузере — и он загружается, печатает тёплое личное сообщение, спрашивает как у тебя дела, реагирует на ответы и заканчивает фейерверком.

Изначально сделан для одной девочки. Теперь — для любой. Или вообще для любого человека.

### Возможности

- **CRT-эстетика** — сканлайны, мерцание экрана, фосфорное свечение
- **Эффект печатной машинки** — текст появляется посимвольно
- **Анимация цветка** — SVG-цветок распускается в реальном времени
- **Звездопад** — 30 разноцветных звёзд
- **Фейерверк** — CSS-частицы в финале
- **Лоу-фай музыка** — тихое фоновое аудио (v4)
- **Мини-игры** — набор слова, карточная память, угадай число
- **Ветвящиеся ответы** — реагирует на то, как проходит день
- **Работает на телефоне** — адаптирован под мобильные браузеры

### Настройка

Открой файл в текстовом редакторе и найди блок `CFG` в начале `<script>`:

```js
const CFG = {
  NAME: '',   // ← имя получателя
  FROM: '',           // ← необязательно: твоё имя (оставь пустым для анонимности)
};
```

Измени `NAME` на её имя (или его, или своё) — и всё, страница адаптируется сама.

### Как использовать

1. Скачай `terminal-heart.html`
2. Измени две строчки в `CFG`
3. Открой в любом современном браузере — или выложи на GitHub Pages для красивой ссылки

### Доступные команды в терминале

| Команда | Действие |
|---|---|
| `help` | показать все команды |
| `again` | начать сначала |
| `bloom` | снова вырастить цветок |
| `stars` | запустить звездопад |
| `fire` | фейерверк |
| `game` | меню мини-игр |
| `clear` | очистить экран |

---

<a name="deutsch"></a>
## ✦ Deutsch

### Was ist das?

**terminal-heart** ist eine einzelne HTML-Datei im Stil eines retro CRT-Terminals mit grünem Phosphorleuchten.
Im Browser geöffnet startet sie hoch, tippt eine persönliche, herzliche Nachricht, fragt wie es dir geht, reagiert auf deine Antworten — und endet mit Feuerwerk.

Ursprünglich für ein Mädchen gemacht. Jetzt für jedes Mädchen. Oder für jeden Menschen.

### Features

- **CRT-Ästhetik** — Scanlines, Bildschirmflackern, Phosphorglühen
- **Schreibmaschineneffekt** — Text erscheint Zeichen für Zeichen
- **Blütenanimation** — eine SVG-Blume öffnet sich in Echtzeit
- **Sternschnuppenregen** — 30 bunte Sterne fallen herab
- **Feuerwerk** — CSS-Partikel zum Abschluss
- **Lo-fi Musik** — sanfte Hintergrundmusik (v4)
- **Mini-Spiele** — Wort tippen, Karten-Memory, Zahl erraten
- **Verzweigte Antworten** — reagiert darauf, wie der Tag läuft
- **Mobilfreundlich** — funktioniert auch auf dem Handy

### Anpassung

Öffne die Datei in einem Texteditor und finde den `CFG`-Block am Anfang des `<script>`-Bereichs:

```js
const CFG = {
  NAME: '',   // ← Name der Empfängerin
  FROM: '',           // ← optional: dein Name (leer lassen für Anonymität)
};
```

Ändere `NAME` auf ihren Namen (oder seinen, oder irgendjemandes) — fertig.

### So verwendest du es

1. Lade `terminal-heart.html` herunter
2. Ändere die zwei Zeilen in `CFG`
3. Öffne es in einem modernen Browser — oder hoste es auf GitHub Pages für einen teilbaren Link

### Befehle im Terminal

| Befehl | Aktion |
|---|---|
| `help` | alle Befehle anzeigen |
| `again` | von vorne beginnen |
| `bloom` | Blume nochmal wachsen lassen |
| `stars` | Sternschnuppenregen starten |
| `fire` | Feuerwerk starten |
| `game` | Mini-Spiel-Menü öffnen |
| `clear` | Bildschirm löschen |

---

## Version history

| Version | What's new |
|---|---|
| v3 | Bloom, starfall, fireworks, mini-games, branching responses |
| v4 | Start screen, lo-fi background music, input replies |

---

## License

Do whatever you want with it. Just be kind to someone today. ✦
