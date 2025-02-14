```md
# Müzik Albümü Görevleri

Aşağıdaki nesneye göre:

```js
const album = {
  artist: "The Clash",
  title: "The Clash",
  genre: "punk",
  year: 1977,
  tracklist: [
    { title: "Janie Jones", duration: "2:05" },
    { title: "Remote Control", duration: "3:00" },
    { title: "I'm So Bored With The U.S.A.", duration: "2:24" },
    { title: "White Riot", duration: "1:55" },
    { title: "Hate & War", duration: "2:05" },
    { title: "What's My Name", duration: "1:40" },
    { title: "Deny", duration: "3:03" },
    { title: "London's Burning", duration: "2:10" },
    { title: "Career Opportunities", duration: "1:51" },
    { title: "48 Hours", duration: "1:34" },
    { title: "Garageland", duration: "3:13" },
  ],
  credits: [
    {
      name: "Joe Strummer",
      instruments: ["Guitar", "Vocals"],
    },
    {
      name: "Mick Jones",
      instruments: ["Guitar", "Vocals"],
    },
    {
      name: "Paul Simonon",
      instruments: ["Bass Guitar"],
    },
    {
      name: "Tory Crimes",
      instruments: ["Drums"],
    },
  ],
};
```

## Görev 1

Tracklist içerisindeki 6. şarkının `title` (başlık) ve `duration` (süre) bilgilerini yazdırın.

Beklenen çıktı:

```plaintext
What's my name (1:40)
```

## Görev 2

`credits` özelliğine bakarak, listedeki ilk müzisyenin adını ve çaldığı enstrümanları (virgülle ayrılmış şekilde) yazdırın.

Beklenen çıktı:

```plaintext
Joe Strummer: Guitar, Vocals
```

## Görev 3

Bir döngü kullanarak, tüm şarkı başlıklarını numaralandırarak yazdırın (1'den başlayarak).

Beklenen çıktı:

```plaintext
1. Janie Jones
2. Remote Control
3. I'm So Bored With The U.S.A.
4. White Riot
5. Hate & War
6. What's My Name
7. Deny
8. London's Burning
9. Career Opportunities
10. 48 Hours
11. Garageland
```

## Görev 4

Nesnedeki `credits` özelliğini kullanarak, her bir grup üyesinin adını ve çaldığı enstrümanları yazdırın.

Beklenen çıktı:

```plaintext
Joe Strummer: Guitar, Vocals
Mick Jones: Guitar, Vocals
Paul Simonon: Bass Guitar
Tory Crimes: Drums
```
```