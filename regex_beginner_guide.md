# 📚 **Introduction to Regex (Regular Expressions)**

**Authors:** [Habib, Billel, Anthony]  

---

## 🧐 **What is Regex?**

Regex, short for **Regular Expressions**, is a powerful tool used to search, match, and manipulate text. It may look intimidating at first, but it's super helpful once you get the hang of it!

---

## 👥 **Who Uses Regex?**

Regex is used by:

- **Developers** to search and replace text in code.
- **System Administrators** to find patterns in log files.
- **Data Analysts** to clean up datasets.
- **Anyone working with text** who needs to find specific patterns!

---

## 📝 **Why Use Regex?**

Regex helps you:

1. **Search efficiently** for specific patterns in large amounts of text.
2. **Extract useful information** (e.g., emails, dates, or errors).
3. **Automate text processing** tasks.

It saves time and reduces the need for manual searching!

---

## ⚙️ **How to Use Regex?**

A regex pattern is made of characters and symbols that represent specific search criteria.

### Basic Syntax

- **`.` (Dot)** - Matches any single character.  
- **`^` (Caret)** - Matches the start of a line.  
- **`$` (Dollar)** - Matches the end of a line.  
- **`\d`** - Matches a digit (0-9).  
- **`\w`** - Matches a word character (a-z, A-Z, 0-9, _).  
- **`+`** - Matches one or more of the previous character.  
- **`*`** - Matches zero or more of the previous character.  

---

## 📌 **Examples**

### Example 1: Finding Error Messages

To find words like `error`, `Errors`, or `ERR:` in a paragraph, use the following regex:

```
[Ee]rror|ERR:
```

**Explanation:**  
- `[Ee]` matches `E` or `e`.  
- `rror` matches the rest of the word `error`.  
- `|` acts like "OR".  
- `ERR:` matches exactly `ERR:`.

### Example 2: Finding a Date (YYYY-MM-DD)

To find dates in the format **YYYY-MM-DD**, use this regex:

```
\d{4}-\d{2}-\d{2}
```

**Explanation:**  
- `\d{4}` matches exactly 4 digits for the year.  
- `-` matches the hyphen.  
- `\d{2}` matches 2 digits for the month and day.

### Example 3: Finding an Email Address

To find email addresses, use this regex:

```
\w+@\w+\.\w+
```

**Explanation:**  
- `\w+` matches one or more word characters.  
- `@` matches the `@` symbol.  
- `\w+` matches the domain name.  
- `\.` matches a dot.  
- `\w+` matches the domain extension (e.g., `com`, `org`).

---

## 🛠️ **Practice!**

To get better with regex, try out these interactive tutorials:  
- [RegexOne](https://regexone.com/)  
- [Video Tutorial](https://youtu.be/xMhKstbdr3k?si=GyCuOMJV_vQI0iLE)