# Carvon Store — Telegram Mini App

## Fayllar
- `index.html` — asosiy mini app fayli

## GitHub + Vercel da joylashtirish (bepul)

### 1-qadam: GitHub
1. github.com ga o'ting → bepul hisob oching
2. "New repository" → nom: `carvon-store`
3. `index.html` faylini yuklang

### 2-qadam: Vercel
1. vercel.com ga o'ting → GitHub bilan kiring
2. "Import Project" → carvon-store ni tanlang
3. "Deploy" bosing
4. Havola olasiz: `carvon-store.vercel.app`

### 3-qadam: Telegram Bot ga ulash
1. Telegram da @BotFather → /newbot → bot yarating
2. /mybots → botingizni tanlang → Bot Settings → Menu Button
3. URL: `https://carvon-store.vercel.app`
4. Tayyor!

### 4-qadam: HubSpot ulash
`index.html` faylida `YOUR_HUBSPOT_TOKEN` ni o'z tokeningiz bilan almashtiring.

## Mahsulotlarni o'zgartirish
`index.html` da `products` massivini tahrirlang:
```js
{ id: 1, name: "Mahsulot nomi", price: 1000000, category: "telefon", emoji: "📱", ... }
```
