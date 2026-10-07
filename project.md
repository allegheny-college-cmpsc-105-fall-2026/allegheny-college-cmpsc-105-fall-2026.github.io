---
layout: page
title: Projects
description: Details about course projects.
mathjax: true
---

# Data Exploration Project

During the latter half of the semester, you will work in teams to tackle an in-depth data exploration challenge. 

This project is designed to take you through the complete lifecycle of data analysis, from initial exploration and cleaning to final insights and communication.

The first two deliverables are graded based on **effort and completion**. The final two deliverables, which represent the polished outcome of your work, are graded on **correctness**, **depth of analysis**, and **effectiveness of communication**.

Your team will collaborate throughout the project cycle, contributing to each deliverable and participating in discussions to refine your approach. Each team member should lead at least one deliverable for the project. On each of your submissions, note the contributions of each team member. 

You should maintain your project files and documentation in a GitHub repository. Make sure to commit regularly and provide clear commit messages to track your progress effectively. On the due date for each deliverable, I will review your repository to assess your progress and provide feedback.

---

## Deliverable 1: Data Exploration
**Focus:** Exploration and Data Quality  
**Grading:** Effort & Completion

Before testing complex hypotheses, your team must understand the shape, quirks, and limitations of your assigned dataset. 

**Tasks:**
1. **Data Ingestion & Cleaning:** Load your dataset into a Pandas DataFrame. Identify and handle missing values, correct data types, and document your choices.
2. **Summary Statistics:** Generate descriptive statistics (means, medians, standard deviations, categorical counts) to establish a baseline understanding of the variables.
3. **Initial Visualizations:** Create foundational plots (e.g., histograms, scatter plots, box plots using `Seaborn`) to identify distributions, outliers, and potential correlations.
4. **Dataset Quirks:** Document initial observations, inherent biases in the data collection, and any assumptions you will need to make moving forward.

**Submission:** A functional Jupyter Notebook containing your code and preliminary observations, alongside a brief summary in a file called `eda.md`.

---

## Deliverable 2: Analysis and Pitch
**Focus:** Execution and Scoping
**Grading:** Effort & Completion

In this phase, you will prove core analytical competency using provided questions, then define the scope for your own original investigation.

**Tasks:**
1. **Guided Hypotheses:** Write code and generate visualizations to answer the 2-3 specific instructor-provided questions for your dataset.
2. **Novel Problem Formulation:** Propose 2-3 original questions or hypotheses your team intends to investigate for the remainder of the project.
3. **Analytical Strategy:** For each original question, articulate *why* it matters and precisely *how* you will use your dataset to answer it (identifying target variables and grouping strategies).
4. **Reproducibility Check:** Ensure your notebook can be run from top to bottom by another user without throwing errors or missing dependencies.

**Submission:** An updated codebase and a concise 1-page report detailing your guided results and project pitch in a file called `proposal.md`.

---

## Deliverable 3: Final Report and Reflection 
**Focus:** Synthesis and Interpretation  
**Grading:** Correctness & Effectiveness

This is the capstone report for your project, synthesizing your technical analysis into a coherent, domain-specific narrative.

**Tasks:**
1. **Novel Execution:** Finalize the code testing your team's original hypotheses. 
2. **Visual Synthesis:** Create polished, presentation-ready visualizations that clearly communicate your findings. Ensure axes are labeled, legends are clear, and the charts directly support your conclusions.
3. **Interpretation:** Translate your statistical and visual results back into real-world meaning. What do the results actually imply about the subject matter? 
4. **Reflection:** Write a reflection on your team's data wrangling and analytical process. Be specific: detail assumptions that proved incorrect, unexpected data cleanliness issues, structural pivots you had to make, or debugging breakthroughs.

**Submission:** A finalized writeup including the contextualized findings, polished visualizations, and reflection in a file called `findings.md`, along with your final codebase.

---

## Deliverable 4: Presentation of Results 
**Focus:** Technical Communication  
**Grading:** Correctness & Effectiveness

Your team will give a presentation detailing your dataset, your core questions, and your final results.

**Tasks:**
1. **Narrative Design:** Structure your presentation to guide the audience through the context of your data, the hypotheses you tested, and the most impactful insights you discovered. 
2. **Conciseness:** Limit the presentation to 7 to 10 minutes. Avoid walking through raw code; focus instead on visualizations, interpretation, and domain impact.
3. **Q&A Defense:** Prepare to field technical questions regarding your analytical choices, missing data handling, and conclusions from your peers and the teaching staff.

**Submission:** Giving the presentation.