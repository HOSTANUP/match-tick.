# Match Tick

Free Fire tournament host ke liye simple match tracker. Phone par app ki tarah chalta hai (PWA).

## Features

- Roz ke 48 match slots: 10:00 AM se 9:45 PM tak, har ghante 4 matches
- Ek tap mein status badlo:
  - 1 tap: ✓ **Green** = match pura complete
  - 2 tap: ↩ **Lime green** = sirf 1 banda aaya, refund hua
  - 3 tap: ✕ **Red** = match cancel
  - 4 tap: wapas khali
- Aaj ke pura / refund / cancel ki ginti
- Is hafte (Monday se Sunday) ke pura matches aur kamai
- "Pura match ₹" aur "Refund match ₹" ka rate khud set karo
- Data phone mein hi save hota hai (localStorage), internet ki zarurat nahi
- Dark mode support

## GitHub Pages se phone par chalana

1. Is repo mein `index.html` upload karo.
2. **Settings → Pages** kholo.
3. Source: **Deploy from a branch**, branch: `main`, folder: `/ (root)`, phir **Save**.
4. 1-2 minute baad link milega: `https://USERNAME.github.io/REPO-NAME/`
5. Phone ke Chrome mein link kholo, ⋮ menu → **Add to Home screen**.

## Files

- `index.html` : poora app (HTML + CSS + JS ek hi file mein)
- `README.md` : ye file

## Dhyan rakho

- Data sirf usi phone aur usi browser mein save hota hai. Browser ka data clear karoge to ticks bhi hat jayenge.
- Link ya app ka naam badlne par naya, khali data dikhega, kyunki storage address ke hisaab se alag hota hai.
