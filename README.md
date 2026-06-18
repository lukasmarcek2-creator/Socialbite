# SocialBite PWA – Návod na nasadenie

## Štruktúra súborov
```
socialbite-pwa/
├── index.html       ← Hlavná aplikácia (6 jazykov)
├── manifest.json    ← PWA konfigurácia
├── sw.js            ← Service Worker (offline podpora)
└── icons/
    ├── icon-192.png ← Ikona pre Android
    └── icon-512.png ← Ikona pre splash screen
```

## Nasadenie na Netlify (ZADARMO, 3 minúty)

1. Choď na https://app.netlify.com/drop
2. Pretiahni CELÝ priečinok `socialbite-pwa` do okna prehliadača
3. Netlify ti dá URL napr. `https://amazing-name-123.netlify.app`

## Pridanie na plochu telefónu

### Android (Chrome):
1. Otvor URL v Chrome
2. Klikni na ⋮ (tri bodky) → "Pridať na plochu"
3. Alebo počkaj na automatickú ponuku "Nainštalovať aplikáciu"

### iPhone (Safari):
1. Otvor URL v Safari (nie Chrome!)
2. Klikni na ikonu Zdieľať (□↑)
3. Vyber "Pridať na plochu"
4. Potvrď "Pridať"

## Výsledok
- App sa správa ako natívna – žiadna lišta prehliadača
- Funguje offline (service worker cachuje obsah)
- Ikona SocialBite na ploche telefónu
- Načíta sa ako splash screen

## Vlastná doména (voliteľné)
V Netlify → Site settings → Domain management → Add custom domain
