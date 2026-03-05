# Roadmap: DTA-Experten-Applikation

## Phase 1 — Studenten-Meldeverfahren (aktuell)
- [x] Repository & Struktur einrichten
- [x] Mockup v0.1: Testdaten-Generator
- [ ] Verfahrensdaten aus gkv-datenaustausch.de vollständig einpflegen
- [ ] Next.js Projekt initialisieren
- [ ] Testdaten-Generator als echte App-Komponente umsetzen

## Phase 2 — Erweiterung (geplant)
- [ ] §302 Verfahren: Fehlercodes + Testdaten
- [ ] §295 Verfahren
- [ ] KV45 Verfahren

## Prinzip
Jedes Verfahren bekommt einen eigenen Ordner unter src/verfahren/.
Fähigkeiten (Testdaten, Fehlercodes, Plausibilitätsprüfung) 
sind pro Verfahren einzeln aktivierbar.
```

4. Commit-Nachricht: `docs: Roadmap anlegen`
5. Branch: `develop` → **"Commit new file"**

---

### ✅ Ergebnis — So sollte euer Repository jetzt aussehen
```
dta-experten-app/  (Branch: develop)
├── .github/
│   └── ISSUE_TEMPLATE/
├── docs/
│   ├── roadmap.md
│   └── verfahren/
├── mockup/
├── src/
│   └── verfahren/
│       └── studenten/
└── README.md
