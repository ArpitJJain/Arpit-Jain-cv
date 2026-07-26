# Arpit Jain — Curriculum Vitae & Cover Letter

Automated LaTeX compilation pipeline for compiling and deploying **Arpit Jain's CV and Cover Letter** to **GitHub Pages** and **GitHub Releases**.

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── compile-pdf.yml    # CI/CD workflow for compilation & deployment
├── data/                      # Modular LaTeX components
│   ├── education.tex          # Academic background & achievements
│   ├── experience.tex         # Professional history & key accomplishments
│   ├── header.tex             # Contact info & header block
│   ├── skills.tex             # Technical skills matrix
│   └── summary.tex            # Executive summary & core competencies
├── cover_letter.tex           # Main TeX file for Cover Letter
├── resume.tex                 # Main TeX file for Curriculum Vitae
├── index.html                 # Web viewer interface for GitHub Pages
└── README.md                  # Project documentation