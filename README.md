# 🧾 Resume Parser using NLP (spaCy)

This project extracts structured data from unstructured resume text files using Natural Language Processing with Python.

It parses resumes to identify and extract:
- Name
- Email address
- Phone number
- Education
- Skills

---

## 🎯 Project Goals

- Demonstrate practical NLP using `spaCy` and regex
- Structure real-world resume data into usable formats
- Lay the foundation for future PDF, UI, or job-matching expansion

---

## 🛠️ Tools Used

- Python 3.12
- `spaCy`
- `re` (regex)
- `pandas` (for export)
- Jupyter Notebook

---

## 🧪 Example Output

```json
{
    "Name": "Jeff Lebowski",
    "Email": "lebowski@example.com",
    "Phone": "555-123-4567",
    "Education": [
        "M.A. in Philosophy, Anytown University"
    ],
    "Skills": [
        "Learning Strategy & Curriculum Design",
        "Organizational Development",
        "Change Management"
    ]
}
