
- Miről szól a weboldalad (téma rövid bemutatása).
    - A weboldalam, egy webshop, ami a regi Animal Crossing City Folk Video Jatek Temaju (ami a Nintendo Wii-n debutalt). 

- Milyen technológiákkal valósítottad meg (HTML, CSS, JS stb.).
    - Hasznalok HTML, CSS, JS-t is a kodomban.

- Az egyes részek és függvények funkciójának rövid leírása (nem kell a működést részletezni).

---

## Az egyes részek és függvények funkciójának rövid leírása

### Oldalak
- **lap1.html** – A nyitóoldal, ahol a felhasználó beléphet a boltba. Tartalmaz egy gombot, amely a vásárlási felületre irányít.
- **lap2.html** – A webshop főoldala, ahol a felhasználó különböző eszközöket vásárolhat. Itt történik az interaktív vásárlás és az összegzés.
- **lap3.html** – Köszönőoldal, amely animált szöveggel fejezi ki a vásárlás utáni hálát.

### Függvények
- **BUY(id)** – Vásárláskor meghívódik, növeli az összesített összeget, és ha az meghaladja a 10 000 Bell-t, átirányít a köszönőoldalra.
- **NOOK(id)** – Egérrel a "Buy" gomb fölé lépve megjeleníti Tom Nook képét és egy üzenetet, amely ösztönzi a vásárlást.
- **HIDE_NOOK()** – Elrejti a Tom Nook popupot, amikor az egér elhagyja a gombot.
- **animateText()** – A `lap3.html` oldalon animálja a "Thank You!" szöveget, betűnként megjelenítve és visszavonva, ciklikusan.

### Egyéb technikai elemek
- **Tömb** – Az eszközök neveit egy tömb tárolja (`itemNames`), amely alapján dinamikusan generálódnak a kártyák.
- **Ciklus** – A kártyák generálása `for` ciklussal történik.
- **Elágazás** – A `BUY()` függvényben ellenőrizzük, hogy az összeg meghaladja-e a küszöbértéket.
- **Aritmetikai művelet** – Az összeg növelése (`osszes += price`) vásárláskor.
- **Logikai művelet** – A feltételvizsgálat (`if (osszes > 10000)`).
- **Programozási tétel: összegzés** – A vásárlások összegének nyilvántartása az `osszes` változóban.

---


- A dokumentációban add meg, milyen témában** készíted a weboldalt.
    - Animal Crossing City Folk

