# HTML & CSS Foundations: Text Analysis Interface

This project was developed for an **Introduction to Software Systems** course to demonstrate proficiency in web development fundamentals. The site serves as a functional demonstration of document structuring, styling, and client-side logic implementation.

## 🚀 Key Features

* **Responsive Multi-page Design:** Built using semantic HTML5 and custom CSS3 layouts.
* **External CV Integration:** A dedicated link that opens a professional CV in a new browser tab for seamless viewing.
* **Input Validation Logic:** A robust text-processing system designed to handle specific data constraints.

## 🛠️ Implementation Details

### Text Submission Constraints
The application includes a validation layer for text input to simulate real-world data requirements:
* **Minimum Length:** The text box is programmed to accept only submissions exceeding **10,000 words**. 
* **Error Handling:** If the word count threshold is not met, the system returns an error message to the user.

### Linguistic Filtering
The logic identifies and tracks specific parts of speech based on the following predefined sets:

* **Pronouns:** `i`, `me`, `you`, `she`, `he`, `it`, `we`, `us`, `they`, `them`
* **Prepositions:** `in`, `on`, `at`, `to`, `for`, `with`, `by`, `from`, `of`, `about`

## 📂 Project Structure

* `index.html` — The primary landing page and text entry interface.
* `cv.html` — The CV viewer page (configured with `target="_blank"`).
* `style.css` — The stylesheet containing all layout, typography, and color definitions.
* `/assets` — Directory for images and the CV PDF.

## 🎓 Learning Objectives
* Mastering the **CSS Box Model** and layout positioning.
* Managing **user states** through validation and error feedback.
* Practicing **semantic HTML** for better accessibility and SEO.

---
*Created as part of the Introduction to Software Systems curriculum.*
