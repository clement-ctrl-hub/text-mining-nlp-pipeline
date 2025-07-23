#   NLP Pipeline : From Text Preprocessing to RAG

Ce projet explore une chaîne complète de traitement du langage naturel (NLP), allant du nettoyage de texte jusqu'à l'utilisation de modèles avancés comme RoBERTa et RAG. Il s’appuie sur des cas concrets : analyse de satisfaction client, classification de sentiments, question answering et génération augmentée.

---

##   Structure du projet

### 1. `1_text_pre_processing.ipynb`
   **Objectif** : Nettoyer un corpus textuel brut pour le rendre exploitable (suppression des caractères spéciaux, stopwords, lemmatisation).  
   **Outils** : `nltk`, `spacy`, `re`, `pandas`, `matplotlib`

---

### 2. `2_Github_K_means.ipynb`
   **Objectif** : Évaluer la satisfaction client à partir de leurs commentaires, via une approche non supervisée (vectorisation TF-IDF + clustering K-means).  
   **Outils** : `scikit-learn`, `pandas`, `matplotlib`, `seaborn`

---

### 3. `3_Transformer(RoBERTa).ipynb`
   **Objectif** : Expérimenter plusieurs tâches NLP avec des Transformers :
- Analyse de sentiments avec le modèle fine-tuné de Siebert  
- Tâches Zero-shot classification & fill-mask  
- Génération de texte  
- Reconnaissance d'entités nommées (NER)  
- Traduction automatique  
- Fine-tuning de RoBERTa sur un jeu de données annoté pour l’analyse de sentiment  
🛠️ **Outils** : `transformers`, `datasets`, `torch`, `sklearn`, `pandas`

---

### 4. `4_Question_Answering.ipynb`
🤖💬 **Objectif** : Créer un **chatbot de type question-answering**, capable de répondre à des questions à partir d’un contexte donné, avec interface interactive.  
🛠️ **Outils** : `transformers`, `pipeline`, `Gradio`, `torch`

---

### 5. `5_RAG.ipynb`
   **Objectif** : Implémenter un système RAG (Retrieval-Augmented Generation), combinant recherche documentaire et génération de réponse contextualisée.  
   **Outils** : `FAISS`, `transformers`, `sentence-transformers`, `pandas`,

---

