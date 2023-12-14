# Pontozólap

Név: Marton Kata

Neptun: B1Y4Q1

## Egyéb, extra
- `1p` Scaffold-DbContext használata ORM osztályok létrhozására

Részösszeg: `1p`
## User Interface
- `1x2p` Az alkalmazásból a kilépés csak megerõsítõ kérdés után lehetséges.

![kilépés](kilepes.jpg)

- `3x2p` Olyan alkalmazás elrendezés, melyben gombok lenyomására UserControl-ok kerülnek elhelyezésre egy Panel vezérlõben, teljesen kitöltve azt. Minden gombra jár a pont, amennyiben az funckuonlalitással rendelkezõ UserControl-t tölt be.
Három db UserContol.

![usercontrolok](usercontrolok.jpg)

- `3x1p` Többablakos alkalmazás legalább két felugró ablakkal. Minden Form-nak saját osztályon kell alapulnia, és funcionalitással kell rendelkeznie. Az ablakok nyílhatnak gombokkal vagy felsõ menübõl is. (Három Form)

- `1x2p` Anchorok alkalmazása: az alkalmazás egészében meg van oldva, hogy az ablak átméretezésekor ki legyen használva a rendelkezésre álló terület.

Részösszeg: `13p` Eddig: `14p`

## Tábla adatainak megjelenítése ListBox-ban.
- `1x2p` Adatok megjelenítése

![listbox](listbox.jpg)
- `2x2p` Ha az adatok tetszõleges módszerrel, pl. TextBox-on keresztül szûrhetõek.
Adatok szûrése TextBox-on keresztül és másik ListBoxxal.
- `1x2p` Ha a tábla adatforrása saját osztály.

Részösszeg: `8p` Eddig: `22p`

## Tábla adatainak megjelenítése DataGridView-ban
- `1x2p` Adatok megjelenítése

![datagridview](datagridview.jpg)
- `1x2p` Ha a tábla idegen kulcsot is tartalmaz, melynek megjelenítése DataGridViewComboBoxColumn-on keresztül történik.
- `1x2p` Ha a tábla adatforrása saját osztály.

Részösszeg: `6p` Eddig: `28p`
## Adatkötés BindingSource -on keresztül
- `1x2p` Mûködõ BindingSource
- `3x1p` Egy BindingSource-ra egy gyûjemény megjelenítésére alkalmas vezérlõ (ListÍBox, ComboBox, DataGridVIew) mellett más adatkötött vezérlõ is van kötve, mint TextBox, DateTimePicker, ComboBox idegen kulcs értékének beállítására, stb.

![adatkötés](adatkotes.jpg)
Részösszeg: `5p` Eddig: `33p`

## Új rekord rögzítése
A pontok összeadódnak.

- `2x2p` master-detail reláció detail táblájába ÉS/VAGY több-a-több kapcsolatban álló táblák kapcsolótáblájába
- `1x2p` Ha csak az idegen kulcsok vannak felvéve
- `1x1p` Ha legalább egy nem kulcs mezõ, pl. Mennyiség is fel van véve
- `1x2p` Ellenõrzéshez kötött adatfelvitel (egyszerû validáció pl: String.IsNullOrEmpty())
- `1x2p` Felugró ablakon keresztül történik Ok és Mégse gombbal
- `1x2p` Ha az ûrlap legördülõ dobozon vagy listán keresztül beállítható idegen kulcsot is tartalmaz
- `2x1p` A kitöltési hiba ErrorProvider-en keresztül kerülnek köközlésre a felhasználóval, hibás kitöltés esetén nem enged rányomni az Ok gombra
- `1x2p` Regex alapú validáció
- `1x1p` Hibás kitöltés esetén nem lehet megynomni az Ok gombot.

Feladat elkészítésébe belekezdtem de nem fejeztem be:


### Megvan:

![reláció](relacio.jpg)

- `1x2p` Ellenõrzéshez kötött adatfelvitel (egyszerû validáció pl: String.IsNullOrEmpty())

![isnullorempty](isnullorempty.jpg)
- `2x1p` A kitöltési hiba ErrorProvider-en keresztül kerülnek köközlésre a felhasználóval, hibás kitöltés esetén nem enged rányomni az Ok gombra

![error](error.jpg)
- `1x2p` Regex alapú validáció

![regex](regex.jpg)





Részösszeg: `6p` Eddig: `39p`

# Összesen: 39p

# pontok