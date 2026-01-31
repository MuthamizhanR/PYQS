# 🏥 JIPMER MBBS High-Yield PYQ Analysis (2008–2024)

**A data-driven approach to mastering Final Year MBBS exams.**

This repository contains a structured, frequency-analyzed collection of Previous Year Questions (PYQs) from JIPMER (Jawaharlal Institute of Postgraduate Medical Education & Research) examinations ranging from **2008 to 2024**.

## 📖 About The Project

Preparing for final year MBBS is overwhelming due to the sheer volume of the syllabus. This project aims to streamline the study process by identifying **High-Yield Topics**.

By analyzing over 15 years of exam papers, we have categorized questions into **Long Essays** and **Short Notes** and assigned a **Frequency Score** to each topic. This allows students to study smarter, not just harder.

## 🩺 Subjects Covered

* **General Medicine** 💊
* **General Surgery** ✂️
* **Obstetrics & Gynaecology (OBG)** 🤰
* **Paediatrics** 👶

## 📊 How to Interpret the Data

The data is structured to help you prioritize. You will see topics listed with a frequency count.

* **Topic:** The core disease or condition (e.g., *Myocardial Infarction*).
* **Frequency:** How many times this topic has appeared in past exams.
* `x10` or higher: **Ultra High Yield** (Must know thoroughly).
* `x5` - `x9`: **High Yield** (Frequently repeated).
* `x1` - `x4`: **Essential** (Commonly asked).


* **Details:** Specific keywords found in questions (e.g., "Management," "Pathophysiology," "Differential Diagnosis").

### Example (JSON Format):

```json
"Hypertensive Disorders of Pregnancy": {
  "frequency": 16,
  "details": "Management of severe preeclampsia (32-36 weeks), Magnesium Sulphate regimens, HELLP syndrome."
}

```

## 📂 Repository Structure

```text
├── data/
│   ├── medicine_topics.json       # JSON data for Internal Medicine
│   ├── surgery_topics.json        # JSON data for General Surgery
│   ├── obg_topics.json            # JSON data for OBG
│   └── pediatrics_topics.json     # JSON data for Paediatrics
├── analysis/                      # (Optional) Scripts used to filter the data
├── assets/                        # Logos and images
└── README.md

```

## 🚀 How to Use This for Study

1. **Start with the High Frequency:** Filter topics with a frequency > 5. These are your "bread and butter" questions.
2. **Review the Details:** The `details` section tells you *what* specifically to learn about the topic (e.g., for *Snake Bite*, focus on "Neurotoxic management" and "ASV").
3. **Cross-Reference:** Use standard textbooks (Harrison's, Bailey & Love, Dutta, Ghai) to read up on these specific areas.

## 🤝 Contributing

This project is open-source! If you have recent question papers (2025 onwards) or find a topic that was missed:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/NewPaper2025`).
3. Update the JSON files.
4. Commit your changes.
5. Push to the branch and open a **Pull Request**.

## ⚠️ Disclaimer

* **Not Medical Advice:** This repository is strictly an educational aid for medical students. It does not constitute medical advice for patient care.
* **Unofficial:** This project is **not** officially affiliated with JIPMER administration. It is a student-led initiative based on publicly available past papers.
* **Completeness:** While we strive for accuracy, relying solely on PYQs is not recommended. Please cover your entire syllabus.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
<i>Made with ❤️ for JIPMERites.</i>
</p>
