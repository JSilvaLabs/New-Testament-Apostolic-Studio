# Apostolic Atlas & Epistles Studio

Interactive seminary studio developed for [Bible Doctrine Academy](https://www.bibledoc.academy/) supporting **Certificate 6: Certificate in New Testament Bible Studies**:
- **NTBS-201:** Acts & The Apostolic Church
- **NTBS-202:** The Pauline Epistles Corpus
- **NTBS-203:** Hebrews & The General (Catholic) Epistles
- **NTBS-204:** Exegesis of the Epistle to the Romans
- **NTBS-205:** The Apocalypse of John (Revelation)
- **BBS-103:** New Testament Survey & Synthesis

## Four Interactive Studio Modules (`30` Masterable Items + `15`-Question Exam)

1. **Acts & Seven Churches Mediterranean Atlas (`?tab=journeys`, `16` Stations):**
   - Powered by **Leaflet.js 1.9.4** with dual-theme CartoDB Voyager (Warm Parchment Light) and Dark Matter (Obsidian Dark) basemaps and strict `dir="ltr"` canvas isolation for RTL locales.
   - **6 Color-Coded Filterable Route Layers:** *Acts 1–12 Jerusalem to Antioch*, *Paul's 1st Journey (Acts 13–14)*, *Paul's 2nd Journey (Acts 15:36–18:22)*, *Paul's 3rd Journey (Acts 18:23–21:16)*, *Voyage to Rome (Acts 27–28)*, and *Seven Churches of Revelation (Rev 1–3)*.
   - **16 Apostolic & Apocalypse Stations** featuring Berean Standard Bible (BSB) anchor texts, archaeological inscriptions (*Pilate Stone*, *Sergius Paulus inscriptions*, *Vardar Gate Politarch Arch*, *Delphi Gallio Inscription*, *Erastus Paving Stone*, *Ephesus Theater & Asiarchs*, *Malta Protos Inscription*), and apostolic sermons/epistles.
   - **Interactive 7-Church Asia Minor Postal Circuit (`Rev 2–3`):** Fly-to inspector for *Ephesus, Smyrna, Pergamum, Thyatira, Sardis, Philadelphia,* and *Laodicea*, mapping Christ's Title, Commendation, Rebuke, Counsel, Overcomer Promise, and civic archaeology.

2. **Romans 1–16 Argument Flow Architect & Pauline Corpus Explorer (`?tab=romans`, `7` Movements):**
   - **7 Interactive Doctrinal Movements of Romans** (`1:1–17`, `1:18–3:20`, `3:21–5:21`, `6:1–8:39`, `9:1–11:36`, `12:1–15:13`, `15:14–16:27`) with core Greek theological lexicon jumpers (*euangelion*, *dikaiosynē Theou*, *hilastērion*, *logizomai*, *hagiasmos*, *huiothesia*), BSB anchor texts, and step-by-step propositional logic chains.
   - **Interactive 13 Pauline Epistles Matrix** filterable across *Early / Galatian-Thessalonian (3)*, *Major Soteriological (3)*, *Prison Christological (4)*, and *Pastoral (3)* groups.

3. **General Epistles & Apocalypse Chiasm Decoder (`?tab=epistles-revelation`, `7` Synthesis Cards):**
   - *Hebrews:* Old Mosaic Shadow vs. New Covenant Reality matrix (`kreittōn` & `ephapax`).
   - *James:* Living Faith & Wisdom from Above (`James 2` vs. `Romans 4` harmony matrix).
   - *1 & 2 Peter:* Suffering Exiles, Royal Priesthood (`1 Pet 2:9`) & Spirit-Borne Prophetic Word (`2 Pet 1:19–21`).
   - *1–3 John & Jude:* Incarnational Christology, Light/Love Assurance Tests & Contending for the Faith.
   - *Revelation 4–5:* Heavenly Throne Room & Worthy Slain Lamb (*Ezekiel 1 + Isaiah 6 + Daniel 7* synthesis).
   - *Revelation 6–19:* Progressive Recapitulation Explorer (*7 Seals, 7 Trumpets, Cosmic Signs Rev 12–14, 7 Bowls & White-Horse Rider*) + Concentric Apocalypse Chiasm (`A–B–C–D–C'–B'–A'`).
   - *Revelation 20–22:* Eden Restored (`Genesis 1–3` Curse vs. `Revelation 21–22` New Creation Tree of Life inclusio).

4. **Apostolic New Testament Mastery Quiz (`?tab=quiz`, `15` Questions):**
   - Comprehensive 15-question seminary assessment filterable by course with instant grading, exegetical explanations, and Study Passport progress sync.

## Technical & Embed Parameters

- **Study Passport Telemetry:** Syncs `localStorage` (`bda_passport_nt-apostolic-studio`) and `window.parent.postMessage` (`type: 'BDA_APP_PROGRESS'`, `app: 'nt-apostolic-studio'`, `total: 30`).
- **Query Parameters:**
  - `?tab=journeys|romans|epistles-revelation|quiz` — Deep-link directly to any studio module.
  - `?theme=light|dark` — Defaults to Warm Manuscript Parchment (`light`) with instant Light/Dark toggle.
  - `?lang=en|es|pt|fr|id|tl|he|ar|fa` — 9-language UI localization with automatic RTL layout for Hebrew (`he`), Arabic (`ar`), and Persian (`fa`).
  - `?embed=1` (or automatic `iframe` detection) — Activates sleek distraction-free LearnDash lesson embed mode with compact header bar, 9-language selector, theme toggle, and Live Mastery Pill (`X / 30 Mastered`).
