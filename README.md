# 🗺️ ShockMatiK-Maps
**Satelitní a ortofotografické podklady závodních tratí pro ShockMatiK Suite**

Tento repozitář slouží jako centrální katalog offline mapových podkladů (ve formátu `.mbtiles`) pro telemetrický software **ShockMatiK Suite**. Mapy umožňují detailní vykreslení GPS záznamů vašich jízd na reálných satelitních snímcích trati, a to zcela bez nutnosti připojení k internetu.

---

## ⚙️ Jak balíčky fungují a proč je stahovat?
Kvůli objemu dat (často v řádu stovek MB až GB) nejsou mapové podklady přímou součástí instalátoru ShockMatiK Suite. Místo toho si stáhnete pouze ty regiony nebo okruhy, které reálně potřebujete. 

Všechny mapy jsou distribuovány formou tzv. **"Rolling Release"**. To znamená, že všechny mapy najdete vždy aktuální a pohromadě v jednom jediném vydání v záložce [Releases](../../releases/latest).

## 📥 Jak mapy importovat do ShockMatiK Suite
1. Vyberte si požadovaný balíček z tabulky níže a stáhněte si `.mbtiles` soubor.
2. Spusťte aplikaci **ShockMatiK Suite**.
3. Přejděte do *nastavení* -> *Mapový manažer*.
4. Tlačítkem *Importovat novou mapu (.mbtiles)* importujte stažený `.mbtiles` soubor.
5. Při zpracování měření s GPS daty se mapa automaticky načte jako podklad trati.

---

## 🗃️ Katalog mapových balíčků

Níže naleznete seznam všech aktuálně dostupných balíčků. Kliknutím na tlačítko ve sloupci "Ke stažení" zahájíte přímé stahování.

### 🇨🇿 Czech Tracks (`czech_tracks.mbtiles`)
Základní balíček obsahující nejznámější české okruhy a autokrosové arény.

**Obsažené tratě:**
* Autodrom Vysoké Mýto
* Dolní Bousov - Autocross AMK DB
* Humpolec - AMK Zálesí
* Most - Autodrom Most
* Nová Paka - Auto klub NP Štikov
* Poříčí nad Sázavou - Areál Homolka
* Přerov - Cross aréna Přerovská Rokle
* Sedlčany - AK RAC Sedlčany
* Třinec - STEEL RING
* Česká Lípa - Autodrom Sosnová

| Soubor | Velikost | Ke stažení |
| :--- | :---: | :--- |
| `czech_tracks.mbtiles` | *~537 MB* | [⬇️ Stáhnout balíček](https://github.com/V-Sip/ShockMatiK-Maps/releases/download/map_database/czech_tracks.mbtiles) |

---

*Chybí vám zde vaše domovská trať? Pošlete požadavek na support@shockmatik.com!*

*Ortofotografické snímky czech_maps.mbtiles © Český úřad zeměměřický a katastrální*
