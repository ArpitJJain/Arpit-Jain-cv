# Arpit Jain — Curriculum Vitae & Cover Letter

Automated LaTeX compilation pipeline for compiling and deploying **Arpit Jain's CV and Cover Letter** to **GitHub Pages** and **GitHub Releases**.


### Profile URL : [Arpit Jain CV](https://arpitjjain.github.io/Arpit-Jain-cv/)

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── compile-pdf.yml    # CI/CD workflow for compilation & deployment
├── data/
│   ├── packages.tex       <-- ALL LaTeX packages & formatting definitions
│   ├── header.tex         <-- Header (Name, contact details)
│   ├── summary.tex        <-- Executive summary & Core Competencies
│   ├── experience.tex     <-- UBS, Citi, Cognizant
│   ├── education.tex      <-- Walchand Institute
│   ├── skills.tex         <-- Tech skills matrix
│   ├── cover_text.tex     <-- Cover letter main body text
│   └── signature.tex      <-- Closing sign-off & signature block
├── resume.tex             <-- Lean CV driver
├── cover_letter.tex       <-- Lean Cover Letter driver
├── index.html             <-- Web viewer
└── README.md                  # Project documentation