# Global Bible Tools SWORD Repository

**⚠️ MACHINE TRANSLATED - PROVISIONAL - NOT AUTHORITATIVE ⚠️**

These are AI-assisted machine translations provided as **study aids only**.
They have NOT been fully reviewed or confirmed by human translators.
**Do not use these as authoritative texts.**

We welcome feedback to improve these translations:
https://global-tools.bible.systems/feedback-chirho

---

## What Are These Translations?

These are **reader's version word-for-word glosses** designed to help you read the Bible in its original languages (Hebrew and Greek):

- **Word-for-word**: Each Hebrew/Greek word receives a corresponding gloss in the target language
- **Original word order**: The glosses follow the order of the original Hebrew/Greek text, not natural target language order
- **Reader's aid**: Like an interlinear Bible, these help readers understand the original text directly

### Example (John 3:16 in Spanish):

| Greek | Gloss |
|-------|-------|
| Οὕτως | Así |
| γὰρ | pues |
| ἠγάπησεν | amó |
| ὁ θεὸς | el Dios |
| τὸν κόσμον | el mundo |

The translations preserve Greek/Hebrew structure rather than creating natural Spanish/Hindi sentences. This is intentional - they are learning aids to help you engage directly with the original biblical languages.

---

## Available Modules

| Module | Language | Type | Description |
|--------|----------|------|-------------|
| GBTIntSpa | Spanish | Interlinear | Greek/Hebrew with Spanish glosses, Strong's, morphology |
| GBTIntHin | Hindi | Interlinear | Greek/Hebrew with Hindi glosses, Strong's, morphology |
| GBTSPA | Spanish | Bible | Word-for-word Spanish translation |
| HinGBT | Hindi | Bible | Word-for-word Hindi translation |

## Installation

### Using InstallMgr (recommended)

Add this repository URL to your SWORD application's module manager:
```
https://sword-modules-chirho.bible.systems
```

### Manual Installation

1. Download the desired module from the `raw/` directory
2. Extract to your SWORD modules directory:
   - Linux: `~/.sword/`
   - macOS: `~/.sword/` or `/usr/share/sword/`
   - Windows: `C:\Program Files\CrossWire\The SWORD Project\`

## Using Interlinear Modules

The interlinear modules (GBTIntSpa, GBTIntHin) contain:
- **Glosses**: Target language translations embedded in each word
- **Strong's Numbers**: Hebrew (H) and Greek (G) reference numbers
- **Morphology**: Grammar codes for each word

### Command Line (diatheke)

```bash
# Show interlinear with glosses, morphology, and Strong's
diatheke -b GBTIntSpa -o gmsn -k "John 3:16"

# Options:
#   -o g = show glosses (translations)
#   -o m = show morphology codes
#   -o s = show Strong's numbers
#   -o n = show footnotes
```

### SWORD Applications

In most SWORD apps (Xiphos, BibleTime, etc.):
1. Go to Settings/Preferences
2. Enable "Show Glosses" or "Interlinear Mode"
3. Enable "Show Strong's Numbers" and "Show Morphology"

## Repository Structure

```
/
├── mods.d.tar.gz      # Module configuration files (for InstallMgr)
├── mods.d/            # Individual .conf files
│   ├── gbtintspa.conf
│   ├── gbtinthin.conf
│   ├── gbtspa.conf
│   └── hingbt.conf
└── raw/               # Module zip files
    ├── GBTIntSpa.zip
    ├── GBTIntHin.zip
    ├── GBTSPA.zip
    └── HinGBT.zip
```

## License

Creative Commons Attribution 4.0 International (CC BY 4.0)

## Links

- Main Site: https://global-tools.bible.systems
- Feedback: https://global-tools.bible.systems/feedback-chirho
- Source: https://github.com/loveJesus

---

*"For God so loved the world, that He gave His only begotten Son, that all who believe in Him should not perish but have everlasting life." — John 3:16*
