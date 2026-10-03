<div align="center">

# 🔗 CSV Joiner

### Merge two CSV files on a shared key — like a SQL JOIN, in your browser

[![View Live Demo](https://img.shields.io/badge/▶_Try_It_Live-7a3fb0?style=for-the-badge&logoColor=white)](https://jithinjolly2000-maker.github.io/csv-joiner/)

![Built with](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0a7a52?style=flat-square)
![Privacy](https://img.shields.io/badge/Privacy-100%25_in--browser-17854a?style=flat-square)
![Hosting](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat-square&logo=github)

</div>

---

Load two CSVs, pick the key column in each, choose a join type, and get a merged table you can export.

## ✨ Join types

| Type | Keeps |
|------|-------|
| **Inner** | Only keys present in **both** files |
| **Left** | All rows from file A; B columns filled where matched |
| **Full outer** | Every key from either file |

Column-name collisions from the right file are auto-prefixed `B_` so nothing is lost. Export the joined result back to CSV with one click.

## 🔒 Private by design

Everything runs **100% in your browser** — no file is uploaded. Use real data, or click **Load sample data**.

## 🧰 Tech

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no dependencies, one `index.html`
- Robust CSV parsing; hash-join on the key for speed
- Hosted free on **GitHub Pages**

## ▶️ Run locally

```bash
start index.html      # Windows — no build step
```

<div align="center">

---

**Built by Jithin J** · [GitHub](https://github.com/jithinjolly2000-maker) · [LinkedIn](https://www.linkedin.com/in/jithin2k)

</div>
