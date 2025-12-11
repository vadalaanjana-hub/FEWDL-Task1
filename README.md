# FEWDL-Task1
# SymptomSense – Interactive Symptom Self-Assessment Web Application

## Overview

SymptomSense is an interactive, browser-based web application that allows users to perform a *preliminary* self-assessment of their health symptoms. By entering symptoms, users receive potential condition suggestions and general recommendations. The tool is designed to promote awareness, support early decision-making, and encourage timely medical consultation.

This application is intended for **educational and informational purposes only** and does **not** provide professional medical diagnosis.

---

## Features / Functional Requirements

### 1. Symptom Input and Categorization

* Users can enter symptoms (e.g., cough, fever, headache) through a simple, user-friendly interface.
* Symptoms can be tagged with severity levels (mild, moderate, severe).
* Optional notes allow users to provide more context.

### 2. Condition Suggestion Engine

* A basic symptom-condition mapping provides possible conditions based on combinations of symptoms.
* Each condition includes an urgency level and general recommendations.
* Results are displayed in a structured, readable format.

### 3. Follow-Up Recommendations

* The system provides suggestions such as rest, hydration, or seeking medical care.
* Critical symptoms trigger urgent or emergency recommendations.

### 4. Responsive Interface

* Fully responsive layout optimized for both desktop and mobile devices.
* Clean, modern UI using light purple and peach color themes.

### 5. Symptom History Management

* Every assessment is saved automatically using the browser’s localStorage.
* Users can:

  * Review past assessments
  * Export history as a JSON file
  * Clear stored history

---

## Optional Enhancements Implemented

### Severity Levels

Each symptom entry can include severity information, improving assessment accuracy.

### Symptom Trend Visualization

A simple bar-chart visual shows the most frequently reported symptoms over time.

### Health Resource Links

Links to trusted sources such as WHO, CDC, and NHS are included.

### Personalized Dashboard Elements

The history panel acts as a quick dashboard for past assessments and symptom patterns.

---

## File Structure

This project is designed as a **single-file website**:

```
index.html
```

All HTML, CSS, and JavaScript are embedded within one file for easy deployment.

To run the application, simply open **index.html** in any modern web browser.

---

## How It Works

1. **User inputs symptoms** → these are collected with severity and optional notes.
2. **Assessment logic runs** → simple rule matching checks symptoms against known patterns.
3. **Possible conditions displayed** → along with urgency levels and recommendations.
4. **Entry saved to history** → users can revisit past results.
5. **Trend chart updates** → showing frequency of symptoms over time.

---

## Technologies Used

* **HTML5** for structure
* **CSS3** for layout, color themes, and responsive design
* **JavaScript (Vanilla)** for:

  * symptom processing
  * condition matching logic
  * history management (localStorage)
  * trend visualization using Canvas API

---

## Limitations

* Uses a **simplified symptom-condition mapping** and is not medically validated.
* Does not replace professional medical evaluation.
* History is stored locally and will not sync across devices.

---

## Future Enhancements (Suggested)

* AI-based symptom analysis
* Multi-language support
* Cloud-based user accounts and sync
* More detailed condition database
* Integration with wearable health data

---

## Disclaimer

This tool is **not a diagnostic application**. It should be used for preliminary guidance only. For accurate diagnosis and treatment, users should consult qualified healthcare professionals.

---

## Author & Credits

Developed as an educational demonstration of a simple health-assessment tool using web technologies.

If you need further customization, improvements, or additional pages, feel free to ask!
