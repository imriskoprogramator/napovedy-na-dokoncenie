# 🔐 Projekt: Postup k dohraniu hry 

Tento dokument obsahuje kompletný návod na dokončenie hry krok za krokom. Úlohou je získať heslá, dekódovať informácie, obísť overenie a nakoniec získať kľúč z trezoru.

---

## 🧩 1. Instagram

- Navštív profil: **[imrichsklenar](https://instagram.com/imrichsklenar)**
- Otvor **3. fotku**
- V popise sa nachádza **odkaz na GitHub**

---

## 🧑‍💻 2. GitHub

- Profil: **[imriskoprogramator](https://github.com/imriskoprogramator)**
- Prezri si **históriu commitov**, hľadaj slovo `env`
- Nájdeš **`APP_SECRET`**
- Dekóduj `APP_SECRET` cez **base64 decoder**
- Výsledný string **pridaj na koniec odkazu** od Google Disku

---

## 🗂️ 3. Steganografia

- Extrahuj súbory zo ZIP archívu
- Pravým klikni na **prvú fotku → Vlastnosti → Podrobnosti**
- Nájdeš tam **stegoheslo**
- Choď na stránku [futureboy.us/stegano](https://futureboy.us/stegano/)
  - Nahraj **druhú fotku**
  - Zadaj heslo z prvej fotky
- Získaš: `5t3gan0graf14`

---

## 🔓 4. Odomknutie súboru

- Otvor súbor z predchádzajúceho kroku
- Zadaj heslo: `5t3gan0graf14`
- V súbore nájdeš číslo v **binárnej sústave**
- Zadaj ho do **binary decoderu**
- Získaš **IP adresu** stránky

---

## 🧪 5. SQL Injection & Overenie

- Na stránke pre **registráciu**:
  - Prezri **HTML zdrojový kód**
  - V `<script>` časti nájdeš overenie inputov – `staff validation code`
- Skopíruj si tento kód
- Zaregistruj sa s hocijakými údajmi – systém ťa pustí
- Si vo **warehouse**:
  - Vyhľadávaj veci **bez tagu**
  - Do názvu zadaj: `%' OR '1'='1`

---

## 🔑 6. Trezor

- Na konci stránky nájdeš heslo: `tajneheslo`
- Zadaj ho do **počítača**
- Odomkneš **miestnosť s trezorom**
- Zober si **kľúč**
- Choď na **prízemie → garáž**
- ✅ **Hra je úspešne dokončená!**

---

### 📁 Poznámky

> Tento projekt slúži ako výukový materiál pre pochopenie základných princípov CTF hier, steganografie, dekódovania a penetračného testovania vo fiktívnom prostredí.
