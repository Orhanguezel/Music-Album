```md
# Music Album - Solution Guide

This solution provides JavaScript code for accessing and manipulating properties in an object structure representing a music album.

## Given Album Object

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

### Task 1

Print the title and duration of the 6th song in the tracklist.

**Solution:**
```js
console.log(`${album.tracklist[5].title} (${album.tracklist[5].duration})`);
```

**Expected Output:**
```plaintext
What's My Name (1:40)
```

---

### Task 2

Print the name and instruments (separated by commas) of the first musician in the credits.

**Solution:**
```js
console.log("\nFirst musician:");
console.log(`${album.credits[0].name}: ${album.credits[0].instruments.join(", ")}`);
```

**Expected Output:**
```plaintext
Joe Strummer: Guitar, Vocals
```

---

### Task 3

Using a loop, print all the track titles, numbering them starting from 1.

**Solution:**
```js
console.log("\nTracklist:");
for (let i = 0; i < album.tracklist.length; i++) {
  console.log(`${i + 1}. ${album.tracklist[i].title}`);
}
```

**Expected Output:**
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

---

### Task 4

Print each band member's name and the instruments they play.

**Solution:**
```js
console.log("\nBand members:");
for (let i = 0; i < album.credits.length; i++) {
  console.log(`${album.credits[i].name}: ${album.credits[i].instruments.join(", ")}`);
}
```

**Expected Output:**
```plaintext
Joe Strummer: Guitar, Vocals
Mick Jones: Guitar, Vocals
Paul Simonon: Bass Guitar
Tory Crimes: Drums
```

--- 
