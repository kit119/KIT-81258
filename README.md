# KIT-81258  
## Koreana Inscription Tripitaka  
### Digital Transliteration for Reading & Chanting Aids (Experimental)

KIT-81258 is a **personal experimental project** for the digital transliteration of the  
**Koreana (Tripitaka Koreana) inscriptions**, with the sole aim of **restoring readability and chantability** to a cultural heritage text that is increasingly unreadable to modern readers.

This project focuses on **transliteration, not translation**.

## Disclaimer
This is a personal, non-official transliteration experiment.

No claim is made regarding textual accuracy, authority, or liturgical correctness.

Source textual data is based on publicly available Daejanggyeong digital resources (AC Muller / DDB).

---

## 📜 Project Concept

The Tripitaka Koreana is one of the world’s most important Buddhist textual heritages.  
Yet today, the majority of Korean readers can no longer **read or vocalize** the original Hanja inscriptions fluently.

This project follows a simple but firm principle:

> **A scripture that is never read aloud is effectively dead.**

Historical precedent across Buddhist traditions shows that:
- Pāli → Sinhala / Thai / Burmese: phonetic shifts occurred
- Sanskrit → Chinese: pronunciation drifted
- Chinese → Korean / Japanese / Vietnamese: further drift followed

Yet **oral reading and chanting survived**, even when textual purity did not.

This project accepts imperfection as the cost of continuity.

---

## 🔄 Transliteration Pipeline

The workflow implemented in this repository is:

Hanja (unofficial source)
↓
Hangul (readable, Sino-Korean based)
↓
Romanization (chant-acceptable)


### Key Characteristics
- **No semantic interpretation**
- **No doctrinal correction**
- **No claim of canonical accuracy**
- Focused on **pronounceability and continuity**

Accuracy is expected to degrade across stages:
- Hangul ≈ readable approximation
- Roman ≈ chant-supportive notation

This is intentional.

---

## 📂 Input Data

- Source data: `koreana.zip`
- Format: UTF-8 `.txt` files containing Hanja text
- Source is considered **unofficial** and used solely for experimental purposes

---

## ⚙️ How It Works

The script performs the following steps for each `.txt` file in the ZIP archive:

1. **Hanja → Hangul**
   - Uses Sino-Korean substitution
   - Unknown characters are preserved as-is

2. **Hangul → Roman**
   - Romanizes per Hangul syllable
   - Preserves original line breaks
   - Inserts spaces to support oral reading / chanting
   - Normalizes spacing without collapsing structure

Each input file produces:
- `*-hangul.txt`
- `*-roman.txt`

---

## ▶️ Usage

```bash
python convert.py koreana.zip



### Key Characteristics
- **No semantic interpretation**
- **No doctrinal correction**
- **No claim of canonical accuracy**
- Focused on **pronounceability and continuity**

Accuracy is expected to degrade across stages:
- Hangul ≈ readable approximation
- Roman ≈ chant-supportive notation

This is intentional.

---

## 📂 Input Data

- Source data: `koreana.zip`
- Format: UTF-8 `.txt` files containing Hanja text
- Source is considered **unofficial** and used solely for experimental purposes

---

## ⚙️ How It Works

The script performs the following steps for each `.txt` file in the ZIP archive:

1. **Hanja → Hangul**
   - Uses Sino-Korean substitution
   - Unknown characters are preserved as-is

2. **Hangul → Roman**
   - Romanizes per Hangul syllable
   - Preserves original line breaks
   - Inserts spaces to support oral reading / chanting
   - Normalizes spacing without collapsing structure

Each input file produces:
- `*-hangul.txt`
- `*-roman.txt`

---

## ▶️ Usage

```bash
python convert.py koreana.zip

Output will be written to:

koreana_output/
  ├── file01-hangul.txt
  ├── file01-roman.txt
  ├── file02-hangul.txt
  └── file02-roman.txt

🧪 Project Status

Experimental

Unreviewed

Uncertified

Unendorsed

This repository is published as-is.

Anyone may:

Fork

Audit

Correct

Improve

Replace parts entirely

⚖️ Disclaimer

This project does not claim textual authority.

This project does not represent any institution.

This project does not seek approval, validation, or endorsement.

Errors, distortions, and historical mismatches are expected.

The author assumes full responsibility for this experiment.

🧭 Motivation

Across Buddhist history, texts survived not because they were perfect, but because someone kept reading them.

Perfect scriptures without readers disappear.
Imperfect texts with voices endure.

This project exists to keep the voice alive.

📄 License

Educational, research, and cultural preservation use.

Please verify source text licensing before redistribution.

🙏 Closing Note

This is not a final form.
This is a continuation attempt.

If this work enables even one person to read or chant a text that would otherwise remain silent, it has served its purpose.


