<div align="center">

<img src="https://opentalk.wwiw.uz/assets/emojis/emojis/smiling-face-with-sunglasses.png" width="64"/>

# BladeClient

**Minecraft 1.8.9 uchun qurilgan zamonaviy Forge client**

Minecraft `1.8.9` · Forge `11.15.1.2318` · Java `8`

*Ushbu loyiha yopiq kodli (closed source). Faqat foydalanish uchun mo'ljallangan.*

</div>

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/books.png" width="22"/> Mundarija

- [BladeClient nima?](#bladeclient-nima)
- [O'rnatish](#ornatish)
- [Ishga tushirish](#ishga-tushirish)
- [Asosiy tugmalar](#asosiy-tugmalar)
- [Mod menyu (ClickGUI)](#mod-menyu-clickgui)
- [HUD Editor](#hud-editor)
- [Modullar](#modullar)
- [Kosmetikalar](#kosmetikalar)
- [Sozlamalar](#sozlamalar)
- [Tillar](#tillar)

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/star-struck.png" width="22"/> BladeClient nima?

BladeClient — Minecraft 1.8.9 uchun maxsus ishlab chiqilgan Forge mod. PvP o'yinchilar uchun mo'ljallangan bo'lib, 50 dan ortiq modul, zamonaviy dark flat dizayn, kosmetikalar va Discord RPC ni o'z ichiga oladi.

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/inbox-tray.png" width="22"/> O'rnatish

### Talablar

- Minecraft **1.8.9**

### Qadamlar

**1.** [BladeClienni yuklab oling](https://github.com/BladeClient/client/releases/download/Release-1.0/BladeClient-1.0.jar) ni yuklab o'rnating.

**2.** JAR faylni `.minecraft/mods/` papkasiga joylashtiring:

```
.minecraft/
└── mods/
    └── BladeClient-1.0.jar
```

**4.** Minecraft Launcher da **Forge 1.8.9** profilini tanlang va ishga tushiring.

> <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/warning.png" width="16"/> **Eslatma:** Faqat Forge 1.8.9 bilan ishlaydi. Boshqa versiyalar qo'llab-quvvatlanmaydi.

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/rocket.png" width="22"/> Ishga tushirish

O'rnatgandan so'ng Minecraft ni ishga tushiring. Bosh menyu avtomatik ravishda BladeClient dizayniga o'zgaradi:

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/keyboard.png" width="22"/> Asosiy tugmalar

| Tugma | Vazifasi |
|---|---|
| `RShift` | Mod menyuni ochish / yopish |
| `LCtrl` | HUD Editorni ochish / yopish |
| `C` (ushlab turish) | Zoom — kattalashtirish |
| `LAlt` (ushlab turish) | Freelook — erkin qarash |
| `Esc` | Har qanday menyuni yopish |

> Har bir modul uchun alohida tugma belgilash mumkin. Buning uchun ClickGUI da modulni toping va Settings bo'limida keybind ni o'rnating. Barcha modullar **default bo'yicha tugmasiz** — siz o'zingiz belgilaysiz.

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/control-knobs.png" width="22"/> Mod menyu (ClickGUI)

O'yinda `RShift` tugmasini bosing. Mod menyu interfeysi ochiladi:

### Modulni yoqish / o'chirish

Modul kartochkasidagi **toggle** (o'ng tomondagi ko'k tugma) ni bosing.

### Modul sozlamalarini ochish

Kartochka pastidagi **Settings** tugmasini bosing. Sozlamalar kartochka ichida kengayib chiqadi:

- **Boolean** — on/off toggle
- **Number** — slider orqali qiymat o'zgartirish
- **Mode** — bosib keyingi variantga o'tish
- **Color** — rang ko'rsatgich

### Qidiruv

Tab bar o'ng tomonidagi qidiruv maydoniga modul nomini yozing — ro'yxat avtomatik filtrlanadi.

### Kategoriya filtri

Chap sidebar da kategoriyani tanlang:

| Kategoriya | Modullar |
|---|---|
| All | Barcha modullar |
| PvP | Combat modullari |
| Movement | Harakat modullari |
| Visual | Ko'rinish modullari |
| Player | O'yinchi ma'lumotlari |
| Misc | Boshqa modullar |

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/puzzle-piece.png" width="22"/> Modullar

### <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/crossed-swords.png" width="18"/> Combat

| Modul | Tavsif | Sozlamalar |
|---|---|---|
| **AimAssist** | Yaqin dushmanlarga nishon olishda yordam beradi | Range, Strength, FOV, Vertical |
| **AutoGG** | O'yin tugaganda `gg`, boshlanishida `!gl` yuboradi | GG Message, GL Message |
| **ComboCounter** | Ketma-ket zarba hisoblagich | — |
| **HitBoxes** | Kengaytirilgan hitbox | Hitbox Size |
| **HitDelayFix** | Zarba kechikishini olib tashlaydi | — |
| **KillEffects** | O'ldirganingizda chaqmoq chaqadi | — |
| **TargetHUD** | Nishon haqida ma'lumot ko'rsatadi | — |

### <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/running-shoe.png" width="18"/> Movement

| Modul | Tavsif |
|---|---|
| **Sprint** | Avtomatik yugurish (omni-sprint) |
| **MouseDelayFix** | Sichqoncha bosish kechikishini olib tashlaydi |

### <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/eyes.png" width="18"/> Visual

| Modul | Tavsif | Sozlamalar |
|---|---|---|
| **Fullbright** | Hamma joyni yorug' qiladi | — |
| **Freelook** | `LAlt` ushlab erkin qarash (smooth) | — |
| **ESP** | Devor orqali entitylarni ko'rish | Mode, Color, Players Only |
| **Tracers** | Entitylarga chiziq tortadi | — |
| **ChestESP** | Devor orqali sandiqlarni ko'rish | Chest Color, Ender Color |
| **Nametags** | Yaxshilangan nametag (HP bar + icon) | — |
| **CrosshairEditor** | Nishon belgisini sozlash | Size, Gap, Thickness, Dot, Color |
| **BlockOverlay** | Tanlangan blokni ajratib ko'rsatish | Overlay Color |
| **1.7 Visuals** | 1.7 uslubidagi blok urish animatsiyasi | Block Hit |
| **Zoom** | `C` tugmasi bilan kattalashtirish (smooth) | Zoom Factor |
| **ClearGlass** | Shishani ko'rinmas qiladi | — |
| **TNTTimer** | TNT portlash sanagichi | — |
| **WeatherChanger** | Ob-havoni client tomonida o'zgartirish | Weather |
| **TimeChanger** | Vaqtni client tomonida o'zgartirish | Time |
| **MinimalViewBobbing** | Kamera tebranishini kamaytiradi | — |
| **RemoveScreenShake** | Barcha kamera silkinishlarini olib tashlaydi | — |
| **RemoveHurtCam** | Zarar kamera effektini olib tashlaydi | — |

### <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/bust-in-silhouette.png" width="18"/> Player

| Modul | Tavsif |
|---|---|
| **Keystrokes** | WASD va sichqoncha tugmalarini ko'rsatadi |
| **ArmorStatus** | Zirh holati HUD |
| **PotionStatus** | Faol effektlar HUD |
| **PingDisplay** | Ping HUD |
| **FPSDisplay** | FPS HUD |
| **CPSCounter** | CPS (chap / o'ng) HUD |
| **LevelHead** | O'yinchi boshi ustida darajasini ko'rsatadi |
| **ServerDisplay** | Joriy server HUD |
| **ResourcePackDisplay** | Faol resurs paketi HUD |

### <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/gear.png" width="18"/> Misc

| Modul | Tavsif | Sozlamalar |
|---|---|---|
| **Chat** | Chat background ni o'chirish, o'yinchi yuz ikonkalari | Disable Background, Heads |
| **DiscordRPC** | Discord da faoliyatingizni ko'rsatadi | — |
| **FPSBoost** | Ishlash optimizatsiyasi | — |
| **EntityCulling** | Ko'rinmas entitylarni yashiradi | — |
| **ChunkOptimizer** | Chunk yuklash optimizatsiyasi | — |
| **MemoryOptimizer** | Xotira tozalash | Free Memory % |
| **RenderDistanceOptimizer** | FPS ga qarab render masofasini sozlaydi | Min Distance, FPS Threshold |

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/t-shirt.png" width="22"/> Kosmetikalar

Bosh menyudan **Cosmetics** tugmasini bosing yoki ClickGUI → **Cosmetics** tabiga o'ting.

Mavjud kosmetikalar:

| Tur | Variantlar |
|---|---|
| **Plash (Cape)** | Creeper Anniversary, Crown Event, Microsoft Migration, Minecraft Creeper, Mojang Official |
| **Bandana** | Moon Crescent, Red |

Kosmetikani yoqish uchun kartochkadagi toggle ni bosing. Kosmetikalar **faqat sizga ko'rinadi** (local preview).

> <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/information.png" width="16"/> Kosmetikalar server tomonida sinxronlanmaydi — faqat o'z ekraningizda ko'rinadi.

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/floppy-disk.png" width="22"/> Sozlamalar

Barcha sozlamalar avtomatik saqlanadi:

```
.minecraft/config/bladeclient/
├── modules/
│   ├── module.sprint.json
│   ├── module.fullbright.json
│   └── ...
├── hud.json
└── cosmetics.json
```

Sozlamalar **serverdan uzilganda** saqlanadi va **keyingi kirishda** yuklanadi.

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/globe-showing-asia-australia.png" width="22"/> Tillar

BladeClient **Ingliz** va **O'zbek** tillarini qo'llab-quvvatlaydi.

Tilni o'zgartirish: **ClickGUI → Settings → Switch Language**

---

## <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/warning.png" width="22"/> Muhim eslatmalar

- <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/locked.png" width="16"/> Bu loyiha **yopiq kodli** — kodlar tarqatilmaydi
- <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/no-entry.png" width="16"/> Faqat **Minecraft 1.8.9 + Forge** bilan ishlaydi
- <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/shield.png" width="16"/> AimAssist do'stlaringizga ta'sir qilmaydi — Friend Manager orqali do'st qo'shing
- <img src="https://opentalk.wwiw.uz/assets/emojis/emojis/memo.png" width="16"/> Nametags faqat haqiqiy o'yinchilar uchun ishlaydi (NPC lar ko'rinmaydi)

---

<div align="center">

<img src="https://opentalk.wwiw.uz/assets/emojis/emojis/red-heart.png" width="20"/> BladeClient — by BladeClient

</div>
