# Kurta szimulátor

Humorjáték: minden böfi erősebb az előzőnél. Kurta – rövid, sötét szakállas, rózsaszín crop topban, farmerban és tűsarkúban, hosszú műkörmökkel – kólát és Bika energiaitalt iszik. Ha 100%-os gázzal böfög, szintet lép: a következő böfi hangosabb, hosszabb és pusztítóbb. 16 szint van, 60 dB-től (Nagyi úgy tesz, mintha nem hallotta volna) 440 dB-ig (a Föld darabokra szakad).

Játszható a böngészőben: https://buhallamate-del.github.io/Kurta-SIM-/

- **Kóla, Bika:** gázt adnak. **Spréjt:** az egyetlen, ami elveszi a töltöttséget (−25%).
- **100%-on** nem várhatsz sokáig, különben orron át távozik (−1 élet).
- **Nagyi papucsa** 20% gázt vesz el; később tégla és meteor hullik, azok életbe kerülnek.
- Statisztika, böfinapló, rekord.

## Multiverzum

A játék a szerző többi játékával közös naplót vezet (`univerzum-naplo` a böngésző helyi tárhelyén): Eseményhorizont, Kísérleti Lőtér, Raktár 3D, Égtorony, Mézország, Mélység, Jeltörő, Toldaléktorony.

- **Más világok:** kapuk azokba a játékokba, ahol már jártál.
- **Ajándékok:** a többi világ nagy eseményei (pl. Holdra jutás, a Föld közepe) egyszer +1 életet adnak a következő menetre.
- **Kurta saját eseményei a naplóban:** `ku:jart`, `ku:elso`, `ku:lokeshullam` (200 dB fölötti MAX böfi), `ku:fold` (szétböfögte a Földet) – a többi játék erre reagálhat.
- **Heti böfögőverseny:** a heti legjobb pontszám egy nyilvános MQTT üzenetközvetítőn (HiveMQ) megy át, a közös `multiverzum-bajnoksag` csatornán. A könyvtár: `vendor/mqtt/` (MIT licenc).

Egyetlen fájl (`index.html`), a mentés a böngésző helyi tárhelyén él.

## Hangok

A böfik valódi felvételek, a szint szerint mélyítve és granulárisan nyújtva:

- artisticdude – RPG Sound Pack, OpenGameArt.org (CC0)
- KAPLAY Team – `burp.mp3` (MIT, Copyright (c) 2025 KAPLAY Team)
- XQ359 – `Burp.mp3`, github.com/XQ539/burp-and-fart (MIT, Copyright (c) 2025 XQ359)
