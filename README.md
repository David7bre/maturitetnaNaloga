# 📱 Maturitetna naloga – Mobilna aplikacija

## 1. Vsebinski načrt dela

### a. Funkcionalnosti
V okviru maturitetne naloge bom razvil mobilno aplikacijo z naslednjimi ključnimi funkcionalnostmi:

- **Avtentikacija uporabnikov:** registracija, prijava, potrjevanje e-pošte, ponastavitev in menjava gesla.  
- **Uporabniški profil:** prikaz in urejanje osebnih podatkov.  
- **Dodajanje prijateljev:** pošiljanje in potrjevanje prošenj, upravljanje povezav.  
- **Ustvarjanje dogodkov:** dodajanje novih dogodkov z opisom, datumom in povabljenci.  
- **Povabila in udeležba:** povabljanje prijateljev ter beleženje njihovega odziva in prisotnosti.  
- **Skupinski chat:** komunikacija znotraj posameznega dogodka ter možnost dodajanja anket/pollov.  
- **Skupni urnik:** predlaganje dejavnosti, glasovanje (like/dislike) ter samodejno ohranjanje ali brisanje predlogov.  
- **Shranjevanje slik:** skupni repozitorij za fotografije vsakega dogodka, z možnostjo podmap.  
- **Upravljanje stroškov:** vnos stroškov, delni stroški (samo za določene udeležence), podmapa za različne tipe stroškov.  
- **Izračun dolgov:** samodejen izračun, kdo komu dolguje, z optimizacijo plačil (podobno Splitwise).  
- **Obvestila:** push ali e-mail notifikacije o povabilih, glasovanjih, novih slikah in spremembah.  
- **Iskanje in filtriranje:** iskanje dogodkov, prijateljev in stroškov.  

---

### b. Tehnologije

#### **React Native ekosistem**
- React Native – framework za razvoj mobilne aplikacije (Android + iOS + Web)  
- Expo – poenostavi testiranje, gradnjo in upravljanje projekta  
- TypeScript – statično tipiran jezik za večjo zanesljivost in manj napak  
- NativeWind – Tailwind-slog pisanja stilov v React Native  
- React Navigation – implementacija navigacije med zasloni  
- Zustand (po potrebi) – globalno upravljanje stanja aplikacije  
- npm – upravljanje odvisnosti projekta  

#### **Firebase (Backend)**
- Authentication – prijava, registracija, avtentikacija uporabnikov  
- Cloud Firestore – NoSQL podatkovna baza na osnovi JSON strukture  
- Firebase Storage – shranjevanje slik in drugih datotek  
- Cloud Functions (po potrebi) – logika, ki je mogoče bolj varna na strežniku  
- Cloud Messaging – pošiljanje push obvestil uporabnikom  

#### **Hosting in spletni del**
- Firebase Hosting – deploy spletne strani  

#### **Razvoj in verzioniranje**
- Git + GitHub – verzioniranje kode in varno shranjevanje projekta  

---

## 2. Terminski načrt dela 🗓️

Časovni plan razvoja aplikacije (približno 3 mesece):

- **1. teden** – Vzpostavitev okolja, inicializacija projekta, nastavitev Firebase (Authentication, Firestore, Storage), konfiguracija GitHub repozitorija, učenje tehnologij.
- **2. teden** – Implementacija avtentikacije (registracija, prijava, ponastavitev gesla), osnovna struktura navigacije.  
- **3. teden** – Uporabniški profil: prikaz podatkov, urejanje, validacije.  
- **4. teden** – Sistem prijateljev: dodajanje, potrjevanje povabil, upravljanje povezav.  
- **5. teden** – Ustvarjanje dogodkov: obrazci, koledar, povabljenci, povezava s podatkovno bazo.  
- **6. teden** – Povabila in udeležba: obdelava odzivov, prikaz prisotnih, logika potrjevanja.  
- **7. teden** – Skupinski chat: real-time komunikacija, dodajanje anket/pollov.  
- **8. teden** – Skupni urnik: predlogi dejavnosti, glasovanje (like/dislike), avtomatsko odstranjevanje predlogov.  
- **9. teden** – Upravljanje stroškov: vnos stroškov, delni stroški, kategorije in podmape.  
- **10. teden** – Izračun dolgov: algoritmi podobni Splitwise, optimizacija plačil, vizualni prikazi.  
- **11. teden** – Shranjevanje slik: integracija Firebase Storage, nalaganje, podmape po dogodkih.  
- **12. teden** – Obvestila (push/e-mail), iskanje in filtriranje, izboljšave UI.  
- **13. teden** – Testiranje, popravki, optimizacije, priprava dokumentacije, finalni pregled in zaključek projekta. 🚀  

---

## 3. Vspostavitev infrastrukture

Za začetek razvoja aplikacije bom potreboval:

- **Razvojno okolje** – Visual Studio Code  
- **Ustvarjen Firebase projekt** – storitve v okviru brezplačnega paketa  
- **Repozitorij kode** – GitHub  
- **Emulator** – Expo (na računalniku) in Expo Go (povezovanje z telefonom)  
