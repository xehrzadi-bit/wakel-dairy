# Wakeel Diary — Real APK Banane Ka Sabse Aasan Tareeqa
(No software install karna — sirf browser use karna hai)

Ye 5 files (index.html, manifest.json, icon-192.png, icon-512.png, sw.js) aapke app ka
poora "web version" hain. Inko 2 free websites ke zariye asal `.apk` mein convert karna hai.

---

## STEP 1 — App ko free hosting par daalna (GitHub Pages)

1. https://github.com par jayein → free account banayein (agar nahi hai)
2. Top-right "+" icon → **New repository** click karein
3. Naam dein: `wakeel-diary` → **Public** select karein → **Create repository**
4. Naye page par **"uploading an existing file"** link par click karein
5. Is zip ke andar ki 5 files (index.html, manifest.json, icon-192.png, icon-512.png, sw.js)
   drag-and-drop karein → neeche **Commit changes** button dabayein
6. Ab top mein **Settings** tab kholein → left side **Pages** par click karein
7. "Branch" ke neeche **main** select karein, folder **/ (root)** rehne dein → **Save**
8. 1-2 minute wait karein, phir page refresh karein — yahan ek link milega jaisa:
   `https://yourusername.github.io/wakeel-diary/`
   **Ye link copy kar lein — agle step mein chahiye hoga.**

---

## STEP 2 — Us link ko real APK mein convert karna (PWABuilder)

1. https://www.pwabuilder.com par jayein
2. Box mein Step 1 wala link paste karein → **Start**
3. Thora wait karein jab tak ye aapki site scan kar le
4. Neeche **"Package For Stores"** button dabayein
5. **Android** option select karein → defaults rehne dein → **Generate** / **Download** dabayein
6. Ek `.apk` (ya `.aab`) file download ho jayegi seedha aapke computer/phone par

---

## STEP 3 — Phone par install karna

1. Wo `.apk` file apne Android phone par le aayein (agar laptop se banayi hai to
   WhatsApp/email/Google Drive se phone par bhej dein)
2. Phone par us file ko tap karein
3. Agar message aaye **"Install blocked"** ya **"unknown source"** — Settings mein jaa kar
   "Allow installs from this app/source" ko ON kar dein, phir wapas try karein
4. **Install** dabayein → app phone par aa jayegi, icon home screen par dikhega

---

## Zaroori baatein

- Ye **5-10 minute** ka kaam hai, bina kisi coding ke — sirf clicking
- Agar koi step atak jaye, screenshot le kar mujhe dikha dein, main aagay guide kar dungi
- App mein abhi jo case-results aate hain wo **sample/demo data** hain (real PLD/PLJ nahi) —
  publisher se licensing milne ke baad hi real data connect hoga
- Ye apk "demo/testing" level ki hai — Google Play Store par publish karne ke liye alag
  process (signing key, listing, review) hota hai, jo baad mein developer ke sath karna hoga
