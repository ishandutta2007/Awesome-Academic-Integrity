# Awesome-Academic-Integrity

## Similar Projects to Academic Integrity Platforms

**Academic Integrity Platforms** (plagiarism detection / originality checking tools) help educators, publishers, and institutions detect copied or unoriginal content in student papers, research articles, and code submissions. Leading commercial tools include Turnitin, Ouriginal, Copyleaks, SafeAssign, Compilatio, Unicheck, PlagScan, StrikePlagiarism, Urkund, and Originality.ai.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully featured commercial systems with massive proprietary academic databases are difficult to replicate in pure open source. The strongest open-source coverage exists for **source-code plagiarism detection**, while text-based tools rely on local corpora, web search, or open academic indexes.

## 🏢 SaaS / Hosted Platforms

- **[Turnitin](https://www.turnitin.com/)** — The dominant academic integrity platform used by universities worldwide for plagiarism detection, AI writing detection, and grading tools.
- **[Ouriginal](https://www.ouriginal.com/)** (formerly Urkund) — European-focused plagiarism detection solution popular in higher education.
- **[Copyleaks](https://copyleaks.com/)** — AI-powered plagiarism and AI-content detection platform with API access.
- **[SafeAssign](https://www.blackboard.com/)** (Blackboard) — Integrated plagiarism checking tool within Blackboard Learn.
- **[Compilatio](https://www.compilatio.net/)** — Plagiarism detection service widely used in French-speaking and European institutions.
- **[Unicheck](https://unicheck.com/)** — Cloud-based similarity checking platform (note: some services have evolved or been discontinued/merged).
- **[PlagScan](https://www.plagscan.com/)** — Plagiarism detection tool previously popular in education (status may vary by region).
- **[StrikePlagiarism](https://strikeplagiarism.com/)** — Plagiarism detection system used in several countries.
- **[Urkund](https://www.urkund.com/)** — Classic plagiarism detection service (now part of Ouriginal / larger portfolios).
- **[Originality.ai](https://originality.ai/)** — AI content and plagiarism detection focused on content publishers and SEO.

## 🔓 Open-Source Software

### Source Code Plagiarism Detection (Strongest Open-Source Area)
- **[JPlag](https://github.com/jplag/JPlag)** — State-of-the-art open-source tool for detecting source code plagiarism and collusion. Supports many languages (Java, C/C++, Python, JavaScript, TypeScript, Go, Kotlin, etc.). Fully local processing — no code is uploaded.
- **[Dolos](https://github.com/dodona-edu/dolos)** — Modern open-source source code plagiarism detector from Ghent University. Offers an intuitive web interface, interactive visualizations, and support for many programming languages (MIT).
- **[copydetect](https://github.com/blingenf/copydetect)** — Lightweight Python tool based on the Winnowing algorithm (same family as Stanford MOSS). Generates HTML similarity reports.
- **[jieplag](https://github.com/thu-cs-lab/jieplag)** — High-performance plagiarism detection tool written in Rust, inspired by Stanford MOSS. Supports multiple languages.
- **[AC2](https://github.com/manuel-freire/ac2)** — Source code plagiarism detection tool with multiple similarity algorithms and strong visualization features.
- Stanford **MOSS** (Measure of Software Similarity) — Long-standing free academic service (not fully open-source) that many open-source tools are inspired by or re-implement.

### Text / Document Plagiarism Detection
- **[Noplag](https://noplag.com/)** — Open-core plagiarism checker with an auditable open-source detection engine (Apache 2.0). Supports self-hosting of the engine and multilingual checking.
- Various open-source text similarity tools based on TF-IDF, cosine similarity, or fingerprinting (e.g., text-matcher, simple plagiarism checkers on GitHub).
- Research projects such as **PlagiarismGuard** that aggregate open academic databases (OpenAlex, Semantic Scholar, CrossRef) for similarity analysis without proprietary corpora.

### Supporting Approaches & Libraries
- Fingerprinting and winnowing libraries that power many of the above tools.
- Local corpus comparison scripts using NLP techniques (spaCy, scikit-learn, etc.).
- Integration of open academic search APIs for web-scale checking in self-hosted setups.

### Typical Open-Source Approach
- **For programming courses** → JPlag, Dolos, or copydetect (excellent accuracy and fully local).
- **For general text** → Combine open-source similarity engines with institutional document repositories or open academic indexes.
- **For AI-generated content** → Emerging open models and detectors (still maturing compared with commercial AI detectors).

Open-source tools give full transparency and data control, which is especially valuable for institutions concerned about student privacy or vendor lock-in.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects for plagiarism detection, code similarity, or academic integrity tooling.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open academic integrity tooling helps keep education fair and transparent! 📝
