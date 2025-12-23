# HTML & CSS Foundations: Personal Profile & Text Analysis

This project was developed for an **Introduction to Software Systems** course. The website serves as a **personal page containing details about me**, while also demonstrating proficiency in web development fundamentals and client-side logic.

---

## 🚀 Key Features

* **Personal Portfolio** – A dedicated page sharing professional and personal details.
* **External CV Integration** – A link that opens my professional CV in a new browser tab for easy viewing.
* **Responsive Multi-page Design** – Built using semantic HTML5 and custom CSS3.
* **Input Validation Logic** – A text-processing system designed to handle specific data constraints.

---

## 🛠️ Implementation Details

### **Text Submission Constraints**
The application includes a validation layer for text input to simulate real-world requirements:
* **Minimum Length:** The text box is programmed to accept only submissions exceeding **10,000 words**.
* **Error Handling:** If the word count threshold is not met, the system returns a specific error message.

### **Linguistic Filtering**
The logic considers and tracks the following specific parts of speech:
* **Pronouns:** i, me, you, she, he, it, we, us, they, them
* **Prepositions:** in, on, at, to, for, with, by, from, of, about

---

## 📂 Project Structure

* **index.html** — The primary landing page featuring personal details and the text interface.
* **cv.html** — The CV viewer page (configured with `target="_blank"`).
* **style.css** — The stylesheet containing all layout, typography, and color definitions.

---
*Created as part of the Introduction to Software Systems curriculum.*
