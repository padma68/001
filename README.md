Link Shortener development using java programming.
# 🔗 Java Link Shortener

This is a simple **Link Shortener** built using **Java** as part of a programming internship project. It allows users to shorten long URLs into short, unique links and retrieve the original links later using a basic command-line interface (CLI).

---

## 📌 Features

- ✅ Shorten long URLs into unique short URLs.
- ✅ Expand short URLs back to their original long form.
- ✅ Handles duplicate entries.
- ✅ Basic error handling (invalid/unknown short URLs).
- 🧪 Command-line interface for easy interaction.

---

## 💻 Technologies Used

- Java 8+
- Java Collections (HashMap)
- CLI (Scanner class)
- Base62-style encoding with custom logic

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/java-link-shortener.git
cd java-link-shortener

javac LinkShortener.java
java LinkShortener


output:
--- Link Shortener ---
1. Shorten URL
2. Expand URL
3. Exit
Choose: 1
Enter long URL: https://example.com/tutorial/java
Short URL: http://short.ly/aaaaan

Choose: 2
Enter short URL: http://short.ly/aaaaan
Original URL: https://example.com/tutorial/java




