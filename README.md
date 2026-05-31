# 🤝 Contributing Guidelines

Thank you for your interest in contributing to this repository. This is a community-maintained academic resource, and every quality contribution helps students, researchers, and developers worldwide.

---

## 📋 Table of Contents

- [How to Contribute](#how-to-contribute)
- [Resource Template](#resource-template)
- [Quality Standards](#quality-standards)
- [Formatting Rules](#formatting-rules)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Reporting Broken Links](#reporting-broken-links)
- [Copyright Policy](#copyright-policy)
- [Code of Conduct](#code-of-conduct)

---

## How to Contribute

There are several ways to contribute:

1. **Add a new resource** — book, paper, course, video, tool, or blog
2. **Fix or update an existing entry** — correct information, add a link, update a broken URL
3. **Improve documentation** — fix typos, improve explanations, enhance formatting
4. **Report an issue** — flag a broken link, incorrect information, or low-quality resource
5. **Suggest a new section** — propose a new topic category that is missing

---

## Resource Template

Every new resource must follow this standard template. Copy and fill it in completely.

```markdown
### Resource Title

- **Type:** Book / Paper / Video / Course / Blog / Tool / Framework / Dataset
- **Author / Creator:** Full name or organization
- **Link:** Full URL (must be accessible)
- **Level:** 🟢 Beginner / 🟡 Intermediate / 🔴 Advanced / 🔬 Research
- **Topics Covered:** Comma-separated list (e.g., Quantum gates, VQE, Grover's algorithm)
- **Why It Is Useful:** 2–3 sentences explaining what makes this resource valuable
- **Prerequisites:** What the reader should know before using this resource
- **Free/Paid:** 🆓 Free / 💲 Paid / 🆓 Audit Free with 💲 Certificate
- **Code Available:** 💻 Yes / No
- **Recommended For:** Who benefits most (beginners, researchers, developers, etc.)
```

---

## Quality Standards

All contributions are reviewed against the following standards.

### ✅ Resources We Accept
- University lecture notes from accredited institutions
- Peer-reviewed papers (journal or conference publications)
- arXiv preprints from established researchers in the field
- Official documentation from major quantum computing organizations (IBM, Google, Xanadu, Microsoft)
- Books from recognized academic publishers (Cambridge, Springer, MIT Press, etc.)
- High-quality open courses from established universities or platforms
- Widely used and actively maintained open-source software
- Blogs from identifiable researchers or organizations with technical credibility

### ❌ Resources We Do Not Accept
- Low-quality blog posts with no technical depth or citations
- Resources promoting commercial products without clear educational value
- Content containing significant factual errors
- Duplicate resources without meaningful differentiation
- Resources that are inaccessible without registration or payment and not widely known
- Promotional or marketing content
- Resources on topics outside the scope of this repository

### Standards for Papers
- Papers from arXiv are welcome but should be from identifiable researchers and on relevant topics
- Papers should have been published in a recognized venue or be widely cited preprints
- Include the year of publication in the entry

---

## Formatting Rules

To maintain consistency across the repository:

1. **Headings** — Use `###` for individual resource entries
2. **Links** — Always use full URLs (not shortened links)
3. **Levels** — Use the emoji badges: 🟢 Beginner, 🟡 Intermediate, 🔴 Advanced, 🔬 Research
4. **Access badges** — Use 🆓 for free and 💲 for paid
5. **Code badge** — Use 💻 Yes when code is included
6. **Star notation** — Add ⭐ after the title only for truly essential resources
7. **Section placement** — Add resources to the most relevant section within the appropriate file
8. **Alphabetical order** — Within sections, order resources by author's last name or chronological order for papers
9. **Empty fields** — Do not leave template fields blank; write "N/A" if truly not applicable

---

## Submitting a Pull Request

1. **Fork** this repository to your GitHub account
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/your-username/quantum-computing-qml-resources.git
   ```
3. **Create a new branch** with a descriptive name:
   ```bash
   git checkout -b add-schuld-qml-paper
   ```
4. **Make your changes** — add your resource using the template above
5. **Commit** with a clear message:
   ```bash
   git commit -m "Add: Schuld (2021) quantum kernels paper to PAPERS.md"
   ```
6. **Push** to your fork:
   ```bash
   git push origin add-schuld-qml-paper
   ```
7. **Open a Pull Request** on GitHub. In the PR description:
   - Briefly describe what you are adding or changing
   - Confirm that you have checked the resource is accessible
   - Confirm that the resource meets the quality standards above

---

## Reporting Broken Links

If you find a broken or inaccessible link:

1. Open a **GitHub Issue** with the title: `Broken link: [Resource Name]`
2. Include the file name and section where the broken link appears
3. If you know the updated URL, include it in the issue
4. Label the issue as `broken-link`

---

## Copyright Policy

This repository does **not** host any copyrighted content. We only link to resources hosted elsewhere. Please follow these rules:

- **Do not upload** copyrighted PDFs, papers, or book chapters directly to this repository
- **Do not link** to pirated or unauthorized copies of books or papers
- For papers, prefer the **official publisher link** or the **official arXiv version** where authors have deposited their work
- If a book has a legally free version (e.g., author's personal website), link to that; otherwise link to the official publisher
- Respect the access model of each resource

---

## Code of Conduct

This repository follows a simple code of conduct:

- Be respectful and constructive in all interactions
- Disagreements about resource quality should be based on content, not personal opinions
- Reviews of pull requests should be helpful and specific
- All contributions are evaluated on their merits, regardless of the contributor's background

---

*Thank you for helping make this repository better for everyone.*

*Return to [README.md](README.md)*
