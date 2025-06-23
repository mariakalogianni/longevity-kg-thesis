# Master Thesis: Longevity Knowledge Graph

## 1. Introduction
Σύντομη περιγραφή του στόχου: Κατασκευή και ανάλυση Knowledge Graph για την επιμήκυνση της υγείας.

## 2. Objectives
- Ανάπτυξη pipeline εισαγωγής δεδομένων από PrimeKG.
- Εφαρμογή graph embeddings και community detection.
- Early-warning συστήματα για πρόβλεψη νοσημάτων.

## 3. Data
- **PrimeKG** (Human disease–gene interactions)
- (Μελλοντικά) OMIM, HPO, GEO datasets

## 4. Methods
- Graph Neural Networks (PyG)
- Community Detection (Louvain, Leiden)
- Predictive models για early detection

## 5. Setup
1. Clone this repo  
2. Copy `config_example.yml` → `config.yml` και συμπλήρωσε τα credentials  
3. `pip install -r requirements.txt`  
4. Εκτέλεσε `python src/load_data.py` για import στο Neo4j  

## 6. Timeline
- **Week 1**: Setup περιβάλλοντος & data ingestion  
- **Week 2-3**: Exploratory data analysis  
- **Week 4-6**: Graph modeling & embeddings  
- **Week 7-9**: Community detection & interpretability  
- **Week 10-12**: Validation, write-up, deliverables  

## 7. References
- [PrimeKG GitHub](https://github.com/mims-harvard/PrimeKG)  
- Relevant papers…
