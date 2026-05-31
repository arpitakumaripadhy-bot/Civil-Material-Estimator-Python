# CivicEstimator v2.0 🏗️📊

An automation tool built in Python to streamline material estimation and cost budgeting for civil engineering projects. 

**👉 [Click here to view the Python code flawlessly if GitHub shows a loading error](https://nbviewer.org/github/arpitakumaripadhy-bot/Civil-Material-Estimator-Python/blob/main/CivicEstimator.ipynb)**

## 📋 Project Overview
As a Billing and Planning Engineer balancing site operations with a transition into Data Science, I developed this tool to eliminate manual spreadsheet calculations. This command-line application applies core structural engineering thumb rules to instantly generate a Bill of Quantities (BOQ) and cost breakdowns for concrete elements and brick walls based on dynamic user dimensions.

## 🛠️ Python Foundations Applied
This project demonstrates production-ready code organization using core concepts covered during my first month at Naresh IT:
- **User Input & Type Conversion:** Capturing data dynamically and parsing strings safely into `float` structures.
- **Data Structures (Dictionaries & Lists):** Managing material rate databases for clean key-value tracking.
- **User-Defined Functions:** Separating business logic into modular, reusable functions (`estimate_concrete` and `estimate_brickwork`).
- **Flow Control (`if-elif-else`):** Constructing an interactive menu system to route program execution paths safely.
- **Loops & String Layouts:** Iterating over dataset rows dynamically via `.items()` while using text padding (`:<20`) to format an aligned corporate invoice layout.

## 📈 Engineering Logic & Assumptions
- **Concrete (M20 Mix):** Uses a standard dry volume conversion factor of `1.54` to account for mix shrinkage and aggregate voids.
- **Brickwork:** Modeled on standard nominal brick dimensions (19 cm x 9 cm x 9 cm) accounting for a 30% mortar volume gap using a 1:3 cement-sand mortar ratio.

---
*Note: Developed using Jupyter Notebook. Architecture and debugging mentored by Gemini AI.*
