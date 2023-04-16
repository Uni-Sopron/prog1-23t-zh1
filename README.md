JSON fájlokban meg vannak adva a márciusi időjárási mérések adatai néhány nagyvároshoz:
`["Sopron", "Gyor", "Szombathely", "Budapest", "Veszprem", "Szekesfehervar", "Zalaegerszeg"]`

Minden fájlban találhatóak a feladat szempontjából mellékes metaadatok, valamint a `"daily"` kulcs alatt időbélyegek és különböző időjárási jellemzők napi mérési adatsorai:

- `"time"`: dátumok (minden városnál azonos)
- `"temperature_2m_max"`: napi maximális hőmérséklet
- `"precipitation_hours"`: napi csapadékos órák száma
- `"windspeed_10m_max"`: napi maximális szélsebesség

### 1. feladat

Hol és melyik napon mérték a legnagyobb szélsebességet, és mennyi volt az értéke?

Elvárt programkimenet: `Maximális szélsebesség: 41.8 km/h, Sopron, 2023-03-11`

### 2. feladat

Hány olyan nap volt, amikor legalább az egyik városban 1 vagy több órán át hullott csapadék?

Elvárt programkimenet: `Csapadékos napok száma: 22`

### 3. feladat

Készíts egy `max_temp.csv` fájlt, mely megadja, hogy az egyes napokon melyik városban mérték a legmagasabb hőmérsékletet, és az mennyi volt.

Az eredmény fájl első 4 sora:

```
2023-03-01;10.1;Budapest
2023-03-02;11.6;Gyor
2023-03-03;12.0;Budapest
2023-03-04;13.3;Sopron
```
