# I3--IMT541
## Overview

This lightweight application focuses on transforming structured web content from the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) into a more interactive, educational format. The application uses structured health information about diabetes, its causes, and effects on the human body, and visualizes key takeaways in a simplified and accessible form.

The application was created as part of an information structures assignment to demonstrate how publicly available health content can be processed, visualized, and presented to support better understanding for diverse audiences, especially those new to a topic like diabetes.

## Objectives

- Work with real-world structured health data to analyze and visualize essential concepts.
- Demonstrate how digital health education can be made portable and more accessible.
- Use a clear, topic-grouped structure to support flexible browsing and updating.
- Reflect on the transformation of a formal government health site into an easy-to-understand learning tool.

## Data Source

- Website: [What is Diabetes? – NIDDK](https://www.niddk.nih.gov/health-information/diabetes/overview/what-is-diabetes )
- Primary Purpose: To educate people about diabetes, including what it is, how it happens, and its impact on health.
- Information Structure: The source content is grouped by topic, with expandable/collapsible sections and embedded links for further learning.

## Application Design

- Format Used: HTML + CSS + JavaScript (original site) ➝ JSON structure for parsing.
- Output: Interactive webpage or notebook visual that summarizes diabetes types, symptoms, and treatment in simplified visuals or lists.
- Data Type: Static, educational, reliable (from a government source).
- Visualization Goal: Turn text-based content into charts, infographics, and visual narratives.

## Technology Stack

- Python: Used for extracting and parsing the content structure.
- Jupyter Notebook / Google Colab: For building an interactive prototype and displaying the results.
- pandas: For optional tabular structuring of content.
- plotly or matplotlib: To visualize concepts such as insulin response or types of diabetes.
- GitHub: For project version control and sharing.

## Installation and Running Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-info-visualizer.git
   cd diabetes-info-visualizer
