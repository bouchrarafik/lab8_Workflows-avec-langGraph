LAB 8 — Workflows avec LangGraph

Cours : SMA et IAD — Master SDIA
Professeur : RETAL SARA
Réalisé par : Bouchra RAFIK

 Description

Ce projet implémente plusieurs workflows avec LangGraph afin d’étudier :

la création de graphes simples
la manipulation de l’état (State)
les reducers
les messages
les conditions dynamiques
les boucles dans un graphe

 Prérequis
Python 3.12+
uv
 Installation
uv venv
.venv\Scripts\activate
uv add langgraph langchain-core langchain-ollama typing-extensions ipython

## 📂 Structure du projet


lab8_Workflows_with_langGraph/
├── hello_graph.py
├── workflows/
├── images/
└── README.md

▶ Exécution
PARTIE 1 — Hello Graph
uv run --active python hello_graph.py
PARTIE 2 — Two Step Workflow
uv run --active python workflows/two_step_workflow.py
PARTIE 3 — Reducers Demo
uv run --active python workflows/reducers_demo.py
PARTIE 4 — Message State
uv run --active python workflows/message_state.py
PARTIE 5 — Conditional Workflow
uv run --active python workflows/conditional_workflow.py
PARTIE 6 — Workflow Loop
uv run --active python workflows/workflow_loop.py
 Concepts étudiés

Partie	Concept
1	StateGraph, node simple
2	Workflow séquentiel
3	Reducer avec Annotated
4	Messages + état dynamique
5	Conditions dynamiques
6	Boucle + arrêt automatique


 Captures d’exécution

### PARTIE 1 — Hello Graph
![Hello Graph](images/1.png)

### PARTIE 2 — Two Step Workflow
![Two Step Workflow](images/2.png)

### PARTIE 3 — Reducers Demo
![Reducers Demo](images/3.png)

### PARTIE 4 — Message State
![Message State](images/4.png)

### PARTIE 5 — Conditional Workflow
![Conditional Workflow](images/5.png)

### PARTIE 6 — Workflow Loop
![Workflow Loop](images/6.png)


Conclusion

Ce TP permet de comprendre la construction de workflows avec LangGraph :

structuration en graphe
gestion d’état
logique conditionnelle
boucles contrôlées
accumulation de données