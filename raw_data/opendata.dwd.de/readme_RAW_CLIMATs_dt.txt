Beschreibung des Datensatzes, der sich vom ASCII-Format der CLIMAT-Reports FM 71 ableitet

Parameter von Abschnitt 1 des CLIMAT-Reports: 
year;month;IIiii;G1;Po;G1;P;G1;sn;T;st;G1;sn;Tx;sn;Tn;G1;e;G1;R1;Rd;nr;
G1;S1;ps;G1;mp;mT;mTx;mTn;G1;me;mR;mS

sn  = Vorzeichen der Daten, codiert
0 Positiv or Null (für Temperatur)
1 Negativ (für Temperatur)
9 Indikator, dass relative Feuchte folgt

year = Jahr
 
month = Monat des Jahres 

IIiii = WMO Stations-Nummer

G1  = Gruppenindex von Abschnitt 1 des CLIMAT-Reports

Po  = Monatsmittel des Luftdrucks auf Stationshöhe in Zehntel in 1/10 Hectopascal (hPa)

P   = Monatsmittel des Luftdrucks auf Meeresniveau in 1/10 hPA oder
      für Stationen in großen Höhen (Gebirge): Monatsmittel des Geopotentials in geopotentielllen Metern 

sn  = Vorzeichen der Daten oder Indikator für relative Feuchte

T   = Monatsmittel der Lufttemperatur, in 1/10 Grad Celsius, ihr Vorzeichen ist durch sn gegeben

st  = Standardabweichung der Tagesmittelwerte des Monats in 1/10 °C

Tx  = Mittlere tägliche Maximumtemperatur des Monats in 1/10 °C, ihr Vorzeichen ist durch sn gegeben
	  
Tn  = Mittlere tägliche Minimumtemperatur des Monats in 1/10 °C, ihr Vorzeichen ist durch sn gegeben

e   = Mittlerer Dampfdruck des Monats in 1/10 hPA 

R1  = Monatliche Niederschlagshöhe in Millimetern (mm)

Rd  = Häufigkeitsgruppe (Qiuintil), in die R1 fällt 

nr  = Anzahl der Tage in dem Monat mit Niederschlag gleich oder größer als 1 mm

S1  = Sonnenscheindauer des Monats in Stunden (h)

ps  = Sonnenscheindauer in Prozent des vieljährigen Mittelwerts in Prozent (%) 

mP  = Anzahl der Tage, die an den Monatsmitteln des Luftdrucks fehlen 

mT  = Anzahl der Werte, die am Monatsmittel der Lufttemperatur fehlen

mTx = Anzahl der Tage, die am Mittel der täglichen Maximumtemperatur fehlen

mTn = Anzahl der Tage, die am Mittel der täglichen Minimumtemperatur fehlen

me  = Anzahl der Tage, die am Mittel des Dampfdrucks fehlen 

mR  = Anzahl der Tage, die an der Summe des Niederschlags fehlen 

mS  = Anzahl der Tage, die an der Summe der Sonnenscheindauer fehlen


Parameter von Abschnitt 2 der CLIMAT Reports (vieljährige Mittelwerte): 
G2;Yb;Yc;G2;Po;G2;P;G2;sn;T;st;G2;sn;Tx;sn;Tn;G2;e;G2;R1;nr;G2;S1;G2;YP;YT;YTx;G2;Ye;YR;YS;

G2  = Gruppenindex von Abschnitt 2 

Yb  = Jahr des Beginns des Bezugszeitraums für die vieljährigen Mittelwerte

Yc  = Endjahr des Bezugszeitraums für die vieljährigen Mittelwerte

Po  = Monatsmittel des Luftdrucks auf Stationshöhe in 1/10 hPA 

P   = Monatsmittel des Luftdrucks auf Meeresniveau in 1/10 hPA oder
	  für Stationen in Höhenlagen (Gebirge): Monatsmittel des Gepotentials in geopotentiellen Metern

sn  = Vorzeichen der Daten oder Indikator für relative Feuchte

T   = Monatsmittel der Lufttemperatur in 1/10 °C|, ihr Vorzeichen wird durch sn angegeben

st  = Standardabweichung der Tagesmittelwerte des Monats in 1/10 °C

Tx  = Mittlere tägliche Maximumtemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben

Tn  = Mittlere tägliche Minimumtemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben

e   = Mittlerer Dampfdruck des Monats in 1/10 hPA 

R1  = Monatliche Niederschlagshöhe in mm

nr  = Anzahl der Tage mit Niederschlag gleich oder größer als  1 mm

S1  = Monatliche Sonnenscheindauer in h

yP  = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte des Luftdrucks fehlen

yR  = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte der Niederschlagshöhe fehlen

yS  = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte der Sonnenscheindauer fehlen
      
yT  = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte der Lufttemperatur fehlen

yTx = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte der Extremtemperaturen fehlen

ye  = Anzahl der Jahre, die innerhalb des Bezugszeitraums an der Berechnung der Mittelwerte des Dampfdrucks fehlen
      pressure normal


arameter von Abschnitt 3 der CLIMAT Reports: 
G3;T25;T30;G3;T35;T40;G3;Tn0;Tx0;G3; R01;R05;G3;R10;R50;G3;R100;R150;G3;s00;s01;
G3;s10;s50;G3;f10;f20;f30;G3;V1;V2;V3;

G3   = Gruppenindex von Abschnitt 3

T25  = Anzahl der Tage im Monat mit einer Maximumtemperatur gleich oder größer als 25°C

T30  = Anzahl der Tage im Monat mit einer Maximumtemperatur gleich oder größer als 30°C

T35  = Anzahl der Tage im Monat mit einer Maximumtemperatur gleich oder größer als 35°C

T40  = Anzahl der Tage im Monat mit einer Maximumtemperatur gleich oder größer als 40°C

Tn0  = Anzahl der Tage im Monat mit einer Minimumtemperatur unter 0°C

Tx0  = Anzahl der Tage im Monat mit einer Maximumtemperatur unter 0°C

R01  = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 1.0 mm

R05  = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 5.0 mm

R10  = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 10.0 mm

R50  = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 50.0 mm

R100 = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 100.0 mm

R150 = Anzahl der Tage im Monat mit einer Niederschlagshöhe gleich oder größer als 150.0 mm

s00  = Anzahl der Tage im Monat mit einer Schneehöhe über 0 cm

s01  = Anzahl der Tage im Monat mit einer Schneehöhe über 1 cm

s10  = Anzahl der Tage im Monat mit einer Schneehöhe über 10 cm

s50  = Anzahl der Tage im Monat mit einer Schneehöhe über 50 cm

f10  = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Windgeschwindigkeit gleich
	   oder größer als 10 Meter pro Sekunde (m/s) oder 20 Knoten (kn)

f20  = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Windgeschwindigkeit gleich
	   oder größer als 20 m/s oder 40 kn

f30  = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Windgeschwindigkeit gleich
	   oder größer als 30 m/s oder 60 kn

V1   = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Sichtweite unter 50 m, unabhängig 
       von der Dauer des Beobachtungszeit

V2   = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Sichtweite unter 100 m, unabhängig 
       von der Dauer des Beobachtungszeit 

V3   = Anzahl der Tage im Monat mit einer beobachteten oder gemessenen Sichtweite unter 1000 m, unabhängig 
       von der Dauer des Beobachtungszeit 

Parameter von Abschnitt 4 des CLIMAT Reports: 
G4;sn;Txd;yx;G4;sn;Tnd;yn;G4;sn;Tax;yax;G4;sn;Tan;yan;G4;Rx;yr;G4;iw;fx;yfx;G4;Dts;Dgr;G4;iy;Gx;Gn

G4  = Gruppenindex von Abschnitt 4

sn  = Vorzeichen der Daten oder Indikator für relative Feuchte

Txd = Höchste Tagesmitteltemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben
      
yx  = Tag, an dem die höchste Tagesmitteltemperatur im Monat aufgetreten ist 

Tnd = Tiefste Tagesmitteltemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben

yn  = Tag, an dem die tiefste Tagesmitteltemperatur im Monat aufgetreten ist 

Tax = Höchste Lufttemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben

yax = Tag, an dem die höchste Lufttemperatur im Monat aufgetreten ist 

Tan = Tiefste Lufttemperatur des Monats in 1/10 °C, ihr Vorzeichen wird durch sn angegeben

yan = Tag, an dem die tiefste Lufttemperatur im Monat aufgetreten ist

Rx  = Größte tägliche Niederschlagshöhe im Monat in 1/10 mm

yr  = Tag, an dem die größte Niederschlagshöhe im Monat aufgetreten ist 

iw  = Indikator für Ursprung und Einheit der Windgeschwindigkeit 

fx  = Höchste Windböe, die im Monat beobachtet oder gemessen wurde in Zehntel der Einheit, die iw angibt

yfx = Tag, an dem die größte beobachtete oder gemessene Windböe im Monat aufgetreten ist 

Dts = Anzahl der Tage mit Gewitter 

Dgr = Anzahl der Tage mit Hagel

iy  = Indikator zur Ablesezeit der Extremtemperaturen (ist nur bei Änderungen zu melden)

Gn  = Zeit der täglichen Erfassung der Minimumtemperatur in UTC (Stunde)

Gx  = Zeit der täglichen Erfassung der Maximumtemperatur in UTC (Stunde)