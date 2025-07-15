# lingram-prompts-presentation
# Telegram Vocabulary Prompt – README

This repository contains a refined prompt system for generating **Telegram-ready vocabulary lists** for English teachers.  
It uses adaptive logic, formatting rules, and grouped structuring to produce visually clear, cognitively optimized lists for learners.

---

## 📌 Purpose

This prompt is designed for integration into **Mono Application's GitHub repo**.  
It supports lesson preparation, prompt engineering, and vocabulary automation for English language education in fast-paced, mobile-first environments like Telegram.

---

## 📋 Features

- Adaptive thematic grouping using emojis
- Clear formatting rules:
  - **bold** for words and titles
  - __italics__ for grammar and usage examples
  - **BOLD CAPS** for prepositions and short function words (contrast/mistake potential only)
  - ❌ ~~strikethrough~~ for errors
  - ✔️ for corrections
  - `/IPA/` transcriptions for tricky words
- Formatting optimized for **Telegram** markdown (no extra blank lines)

---

## 🧪 Simulated Input

Below is a realistic teacher log copied from Zoom or Google Meet.  
The assistant parses this into clean study material:

```
Victoria Khylchuk
09:21  
take part in  
freedoom  
abroad p  
invoice  

Victoria Khylchuk
09:24  
people – народи  
peoples – ❌  
~~he go~~  
✔️ he goes  
comfortible  

Victoria Khylchuk
09:26  
to participate IN  
Do you work **FOR** Google?  
depends of  
to be ready for  

Victoria Khylchuk
09:28  
read FOR exam  
grammar  
multicultural  
```

---

## ✅ Output Example

```
**🧠 Daily Life**

**abroad** /əˈbrɔːd/ – за кордоном  
**comfortable** /ˈkʌmf.tə.bəl/ – зручно  
**multicultural** – мультикультурний  
**people** – люди  
❌ ~~peoples~~  
✔️ **people** – народи, етнічні групи

**📌 Preposition Practice**

**take part IN** – брати участь **У**  
**participate IN** – брати участь **У**  
**ready FOR** – готовий **ДО**  
**read FOR** – читати **ДО** (екзамену)  
**depends ON** – залежить **ВІД**  
❌ ~~depends OF~~  
✔️ **depends ON**

**🧾 Business English**

**invoice** – рахунок  
__We sent the invoice yesterday.__  
**freedom** – свобода  
__Freedom of speech is important.__

**📚 Grammar**

❌ ~~he go~~  
✔️ __He goes to school every day.__
```

---

## ⚠️ Note on Usage

This README demonstrates how the output **should look**.  
The actual internal prompt logic is not shown here to preserve instructional design integrity and prevent unauthorized reuse.

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
Prompt structure, formatting logic, and educational design are © 2025 Victoria Khylchuk (Mono Application).
