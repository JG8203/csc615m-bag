# 📘 CSC615M Project 1: Text Cleaning

**Course**: Automata, Computability, and Formal Languages
**Instructor**: Nathaniel Oco
**Email**: [nathaniel.oco@dlsu.edu.ph](mailto:nathaniel.oco@dlsu.edu.ph)
**Course Repository**: AnimoSpace, Google Drive
**Deadline**: **June 23, 8:00 AM** (Demo: **Week 8**)

---

## 🧾 Description

This project is aligned with **Learning Outcome 6 (LO6)** — to **develop formal machines addressing research and societal problems**. The goal is to **clean noisy text data** (Bible texts in three languages) using **regular expressions** and **search-replace techniques**.

---

## ✅ Tasks Checklist

### 📂 1. Data Selection

* [ ] Select **Bible texts** from an online/electronic source
* [ ] Retrieval methods may include:

  * [ ] Highlight-copy-paste
  * [ ] Downloading source files
  * [ ] Using a scraping app
* [ ] Ensure **at least 100,000 words** per individual (see rubric below)

---

### 🧹 2. Pre-processing

* [ ] Remove document tags
  Example:

  ```
  Before: <indig>Kumain kami</indig>  
  After: Kumain kami
  ```
* [ ] Remove unnecessary spaces
* [ ] Remove unrelated keywords and symbols

---

### ✂️ 3. Segmentation

* [ ] Segment paragraphs into **verses**
* [ ] Further segment verses into **sentences**
  Example:

  ```
  Before: Sentence 1. Sentence 2. Sentence 3.  
  After:
  Sentence 1.  
  Sentence 2.  
  Sentence 3.
  ```

---

### 📝 4. Documentation

* [ ] Include source information and retrieval method
* [ ] Acknowledge use of AI and other tools (with prompts + outputs)
* [ ] Ensure each step is **replicable**
* [ ] Sample documentation table:

  | Step | Search     | Replace   | Mode / Remarks | Explanation                    |
  | ---- | ---------- | --------- | -------------- | ------------------------------ |
  | 1    | `^ +`      | `<empty>` | RegEx          | Remove leading spaces          |
  | 2    | `\r\n\r\n` | `\r\n`    | Extended       | Remove unnecessary blank lines |

---

## 🏅 Rubric

| Criteria                    | Full Points (20)     | Satisfactory (15) | Developing (10) | Beginning (5)   |
| --------------------------- | -------------------- | ----------------- | --------------- | --------------- |
| **Data selection**          | ≥ 100,000 words      | ≥ 10,000 words    | ≥ 1,000 words   | < 1,000 words   |
| **Cleanliness**             | 100% clean           | ≥ 90% clean       | ≤ 80% clean     | ≤ 50% clean     |
| **Segmentation – verse**    | Properly segmented   | ≥ 90% segmented   | ≤ 80% segmented | ≤ 50% segmented |
| **Segmentation – sentence** | Properly segmented   | ≥ 90% segmented   | ≤ 80% segmented | ≤ 50% segmented |
| **Documentation & Demo**    | All steps documented | 90% complete      | 80% complete    | 50% complete    |

### 🎁 Bonus Points

* [ ] +5: Project released under a custom license allowing DLSU students to use the clean data
* [ ] +10: Output includes **parallel sentences**, when applicable

---

## 🤖 Declaration of AI Usage (Per Individual)

* [ ] **1. AI Tool(s) Used**: *(List them here)*
* [ ] **2. Usage Description**: *(Describe how you used them, e.g., grammar checking, summarizing references)*
* [ ] **3. Extent of Use**:

  * [ ] Minimal – Grammar/spell check only
  * [ ] Moderate – Inspiration, significantly reworded
  * [ ] Extensive – Relied heavily, minimal editing
* [ ] **4. Reflection** (2–3 sentences):
  *(How did AI help or why didn’t you use it?)*

---

## 📦 Deliverables

Please upload all the following:

* [ ] ✅ `raw_source.txt` – Raw data file
* [ ] ✅ `processed_text.txt` – Cleaned output
* [ ] ✅ `processed_text.xlsx` – Spreadsheet version
* [ ] ✅ `documentation.docx` – Contains:

  * [ ] Source information
  * [ ] AI usage declaration
  * [ ] Detailed processing steps
* [ ] ✅ `demo_video.mp4` – Brief walkthrough
* [ ] ✅ `source_code/` – Code, executable, sample command file (if applicable)

---

Let me know if you'd like this exported as a downloadable `.md` file.

