# BBall Ontology and Applications

## Repository Structure

* **CompetencyQuestions/**
  This folder contains the SPARQL queries corresponding to all the defined competency questions.

* **Results/**
  This folder includes all the results produced by executing the SPARQL queries, as well as the figures generated from these results.

---

## The BBall Ontology for Basketball Games

**Link:** [https://users.ics.forth.gr/~mountant/bball.html](https://users.ics.forth.gr/~mountant/bball.html)

**Description:**
The BBall ontology can be used for describing in RDF the key metadata for basketball games and statistics, including all its participants, such as players, teams, referees, coaches, and venues.

**Figure:**

<img width="700" height="400" alt="bball" src="https://github.com/user-attachments/assets/c6f7ab8d-00c2-4e50-91fc-2b6ad383b35c" />

---

## Applications
### EuroLens

**Description:**
Here, we demonstrate the *EuroLens* application, which is a prototype that enables users to get precise answers to complex information needs. EuroLens exploits a set of predefined filters that are converted into accurate SPARQL queries through SPARQL templates. Its functionality and overall workflow are explained through the application interface and supporting material.

**Application Link:**
[https://demos.isl.ics.forth.gr/HoopProphets/apps/eurolens](https://demos.isl.ics.forth.gr/HoopProphets/apps/eurolens)

[![EuroLens Tutorial Video](https://img.youtube.com/vi/uxwbzBhJcFU/0.jpg)](https://youtu.be/uxwbzBhJcFU)

---

### HoopProphets: A Text-to-SPARQL Application using LLMs

**Description:**
HoopProphets is a text-to-SPARQL application that accepts a natural language question as input and, by exploiting Large Language Model (LLM) prompts, generates the corresponding SPARQL query along with the answer retrieved from a SPARQL endpoint.


**Demo Video:**
[![HoopProphets Demo Video](https://img.youtube.com/vi/X6HCxxFDgXM/0.jpg)](https://www.youtube.com/watch?v=X6HCxxFDgXM)

---

## Evaluation of Text-to-SPARQL
The evaluation framework and results for the Text-to-SPARQL approach can be found in https://github.com/mountanton/BasketballQA 

