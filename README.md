# Pontoz�lap

N�v: Marton Kata

Neptun: B1Y4Q1

## Egy�b, extra
- `1p` Scaffold-DbContext haszn�lata ORM oszt�lyok l�trhoz�s�ra

R�sz�sszeg: `1p`
## User Interface
- `1x2p` Az alkalmaz�sb�l a kil�p�s csak meger�s�t� k�rd�s ut�n lehets�ges.

![kil�p�s](kilepes.jpg)

- `3x2p` Olyan alkalmaz�s elrendez�s, melyben gombok lenyom�s�ra UserControl-ok ker�lnek elhelyez�sre egy Panel vez�rl�ben, teljesen kit�ltve azt. Minden gombra j�r a pont, amennyiben az funckuonlalit�ssal rendelkez� UserControl-t t�lt be.
H�rom db UserContol.

![usercontrolok](usercontrolok.jpg)

- `3x1p` T�bbablakos alkalmaz�s legal�bb k�t felugr� ablakkal. Minden Form-nak saj�t oszt�lyon kell alapulnia, �s funcionalit�ssal kell rendelkeznie. Az ablakok ny�lhatnak gombokkal vagy fels� men�b�l is. (H�rom Form)

- `1x2p` Anchorok alkalmaz�sa: az alkalmaz�s eg�sz�ben meg van oldva, hogy az ablak �tm�retez�sekor ki legyen haszn�lva a rendelkez�sre �ll� ter�let.

R�sz�sszeg: `13p` Eddig: `14p`

## T�bla adatainak megjelen�t�se ListBox-ban.
- `1x2p` Adatok megjelen�t�se

![listbox](listbox.jpg)
- `2x2p` Ha az adatok tetsz�leges m�dszerrel, pl. TextBox-on kereszt�l sz�rhet�ek.
Adatok sz�r�se TextBox-on kereszt�l �s m�sik ListBoxxal.
- `1x2p` Ha a t�bla adatforr�sa saj�t oszt�ly.

R�sz�sszeg: `8p` Eddig: `22p`

## T�bla adatainak megjelen�t�se DataGridView-ban
- `1x2p` Adatok megjelen�t�se

![datagridview](datagridview.jpg)
- `1x2p` Ha a t�bla idegen kulcsot is tartalmaz, melynek megjelen�t�se DataGridViewComboBoxColumn-on kereszt�l t�rt�nik.
- `1x2p` Ha a t�bla adatforr�sa saj�t oszt�ly.

R�sz�sszeg: `6p` Eddig: `28p`
## Adatk�t�s BindingSource -on kereszt�l
- `1x2p` M�k�d� BindingSource
- `3x1p` Egy BindingSource-ra egy gy�jem�ny megjelen�t�s�re alkalmas vez�rl� (List�Box, ComboBox, DataGridVIew) mellett m�s adatk�t�tt vez�rl� is van k�tve, mint TextBox, DateTimePicker, ComboBox idegen kulcs �rt�k�nek be�ll�t�s�ra, stb.

![adatk�t�s](adatkotes.jpg)
R�sz�sszeg: `5p` Eddig: `33p`

## �j rekord r�gz�t�se
A pontok �sszead�dnak.

- `2x2p` master-detail rel�ci� detail t�bl�j�ba �S/VAGY t�bb-a-t�bb kapcsolatban �ll� t�bl�k kapcsol�t�bl�j�ba
- `1x2p` Ha csak az idegen kulcsok vannak felv�ve
- `1x1p` Ha legal�bb egy nem kulcs mez�, pl. Mennyis�g is fel van v�ve
- `1x2p` Ellen�rz�shez k�t�tt adatfelvitel (egyszer� valid�ci� pl: String.IsNullOrEmpty())
- `1x2p` Felugr� ablakon kereszt�l t�rt�nik Ok �s M�gse gombbal
- `1x2p` Ha az �rlap leg�rd�l� dobozon vagy list�n kereszt�l be�ll�that� idegen kulcsot is tartalmaz
- `2x1p` A kit�lt�si hiba ErrorProvider-en kereszt�l ker�lnek k�k�zl�sre a felhaszn�l�val, hib�s kit�lt�s eset�n nem enged r�nyomni az Ok gombra
- `1x2p` Regex alap� valid�ci�
- `1x1p` Hib�s kit�lt�s eset�n nem lehet megynomni az Ok gombot.

Feladat elk�sz�t�s�be belekezdtem de nem fejeztem be:


### Megvan:

![rel�ci�](relacio.jpg)

- `1x2p` Ellen�rz�shez k�t�tt adatfelvitel (egyszer� valid�ci� pl: String.IsNullOrEmpty())

![isnullorempty](isnullorempty.jpg)
- `2x1p` A kit�lt�si hiba ErrorProvider-en kereszt�l ker�lnek k�k�zl�sre a felhaszn�l�val, hib�s kit�lt�s eset�n nem enged r�nyomni az Ok gombra

![error](error.jpg)
- `1x2p` Regex alap� valid�ci�

![regex](regex.jpg)





R�sz�sszeg: `6p` Eddig: `39p`

# �sszesen: 39p

# pontok