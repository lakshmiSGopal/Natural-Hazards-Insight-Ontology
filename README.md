# Natural-Hazards-Insight-Ontology
The Natural Hazards Insight Ontology is part of a broader research initiative aimed at enhancing the automatic extraction and structured representation of disaster impact information from unstructured text sources such as news reports. This work addresses the critical need for timely and accurate data during disaster events by combining ontology engineering, natural language processing (NLP), and information extraction (IE) methods. The ontology is designed to capture key disaster-related entities, including hazard types, impact factors (e.g., death toll, injuries, displacement), affected populations, locations, and recovery actions, using formal semantics. By integrating this ontology with a rule-based IE pipeline, the system supports automated triple extraction and structured data generation from raw news text. The extracted outputs can be visualized using tools like Power BI and stored for downstream applications such as disaster analytics, situational awareness, and decision support systems. 

## Contents of this Repository
This repository currently provides the core Natural Hazards Insight Ontology as an .owl file, which can be reused, customized, or extended for research and practical applications in disaster information extraction. The ontology file can be viewed, explored, and tested using Protégé, a free and open-source ontology editor developed by Stanford University. If you don’t have Protégé installed, you can download it here:https://protege.stanford.edu/products.php#desktop-protege.
Once opened in Protégé, users can:
- Explore classes and subclasses representing disaster types, impact factors, actors, locations, etc.
- Examine object properties modeling relationships (e.g., causes, impacts, occursIn).
- View individuals as example instances of disaster events.
- Use the built-in SPARQL tab to run custom queries over the ontology and test reasoning-based use cases.

As a companion to the associated research paper, this repository also includes a supplementary material PDF that provides in-depth documentation of the ontology.
The final module of this work is an interactive dashboard, where the results of the Information Extraction (IE) system are presented for exploration and analysis. The dashboard is developed with Looker Studio, which can be accessed here: https://lookerstudio.google.com/reporting/3015dd47-e21d-4286-9893-1157c4f30d1a

## Citation and Acknowledgment
This ontology and its associated resources are developed as part of the research work titled:

"A Generic Ontology-Driven Information Extraction and Impact Analysis of Hazards: A Case Study on the 2024 Wayanad Landslides"

Authors: Lakshmi S. Gopal<sup>1</sup>, Hemalatha Thirugnanam<sup>1</sup>, Tejal Shah<sup>2</sup>, Maneesha Vinodini Ramesh<sup>1</sup>

<sup>1</sup>Center for Wireless Networks & Applications (AWNA), Amrita Vishwa Vidyapeetham, Amritapuri, India

<sup>2</sup>School of Computing, Newcastle University, Newcastle Upon Tyne, UK

DOI: https://doi.org/10.5281/zenodo.15752551




