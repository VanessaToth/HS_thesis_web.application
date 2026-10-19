Sociologia Somnului – Educational Web Application

An e-learning web platform built as a high school graduation thesis (Atestat Informatică) at Liceul Teoretic Carei. The project introduces fundamental concepts of brain health, sleep mechanics, and sleep disorders through an interactive interface and quiz module.

--- 

##  Key Features

- **Multi-page Educational Layout:** 5 structured modules covering definitions, sleep duration, sleep medicine (Somnology), historical sleep phenomena, and health effects.
- **Dynamic JavaScript Quiz Engine:** 
  - DOM manipulation to dynamically render questions and answer choices from an array of objects.
  - Evaluation algorithm calculating scores, updating user feedback, and providing visual color-coded results (green for correct, red for incorrect).
- **Custom UI/UX & Media:** 
  - CSS fixed background imagery (`creier.gif`) with customized typography and container positioning.
  - Responsive horizontal navigation menu with active hover states and Ionicons vector iconography.
---

##  Tech Stack

-- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **Icons & Styling:** Ionicons Framework, FontAwesome
---

##  Project Structure

─ index.html            # Main landing page (formerly startpage.html)
- startpage.css         # Global stylesheet
─ pag1.html             # Module 1: Definition & Importance
- pag2.html             # Module 2: Sleep Duration & Purpose
- pag3.html             # Module 3: Historical Phenomena & Case Studies
- pag4.html             # Module 4: Somnology & Medical Specialties
- pag5.html             # Module 5: Health Benefits & Sleep Disorders
- quiz.html             # Interactive evaluation test module (JavaScript)
- creier.gif            # Fixed background GIF animation


##  How to Run Locally

1. Clone or download this repository.
2. Open `index.html` (or `startpage.html`) in any modern web browser.
3. Navigate to `quiz.html` to test the interactive evaluation logic.
