# For Tanu ♥ — Birthday Website

An elegant, single-file birthday surprise website — rose gold & blush theme,
built with nothing but HTML, CSS and a sprinkle of JavaScript.
No installs, no build tools — works offline, opens anywhere.

## ✨ What's inside

- 💝 **Sealed envelope opening** — she taps it to begin (wax seal + confetti)
- ⏳ **Live countdown** to October 3rd — on the day itself it turns into a celebration message
- 💌 **A love letter** on an elegant card with a wax seal & drop-cap
- 💗 **"Why I Love You"** — reasons in shimmering gold-numbered cards
- 📖 **Our Story** — an alternating memory timeline
- 🖼️ **Frames of Us** — a tilted polaroid photo gallery (drop your photos in `photos/`)
- 🤞 **Promises** — keepsake promise cards
- 🎂 **Interactive cake finale** — press & hold to blow the candles → final surprise card
- 🎊 Confetti bursts, floating hearts, cursor sparkles, and a soft **music-box tune** (♪ button)

## 🚀 How to open it

Just double-click `index.html` — it opens in any browser.
To see it full-screen on your phone or her phone, host it for free:

- **Netlify Drop** — drag the whole `birthday-website` folder onto
  [app.netlify.com/drop](https://app.netlify.com/drop) → get a shareable link in seconds
- **GitHub Pages** — push this folder to a repo and enable Pages
- **Vercel** — `vercel deploy` from inside the folder

## 🖼️ Adding your photos

Copy images into the `photos/` folder, then open `index.html` and fill in the
`photos:` list inside the `CONFIG` section (full instructions in
`photos/README.txt`).

## ✏️ Personalizing the words

Everything editable lives in **one CONFIG block** near the bottom of `index.html`
(search for `EDIT EVERYTHING HERE`):

| Field | What it changes |
|---|---|
| `name` / `fromName` | Her name everywhere, and your signature |
| `birthday` | The countdown date |
| `letter` | The love letter paragraphs |
| `reasons` | The "Why I Love You" cards |
| `memories` | The "Our Story" timeline |
| `photos` | The polaroid gallery |
| `promises` | The promise cards |
| `finalMessage` | The last surprise card after the candles |

## 💡 Surprise tips

- Open it once on her phone/browser yourself first — test the envelope → cake flow
- Send the link at midnight on Oct 3rd with a message like:
  *"Something's been waiting for you all day… open it when you're alone 😉"*
- The music starts when she opens the envelope — volume is gentle by design
