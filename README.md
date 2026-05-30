#NovaAI

Description

NovaAI est un assistant d'intelligence artificielle open source conçu pour fonctionner localement ou sur serveur privé.

Le projet vise à fournir :

- Conversation intelligente
- Mémoire persistante
- Recherche documentaire
- Gestion des connaissances
- API REST
- Interface Web moderne
- Fonctionnement hors ligne
- Extensibilité par modules

---

Fonctionnalités

Assistant conversationnel

L'utilisateur peut dialoguer avec NovaAI à travers une interface Web ou une API.

Mémoire

NovaAI conserve l'historique des conversations afin d'améliorer la continuité des échanges.

Recherche documentaire

Le système peut indexer des documents et rechercher des informations pertinentes.

Base de connaissances

L'utilisateur peut construire sa propre base documentaire.

API

Toutes les fonctions sont accessibles via une API REST.

Sécurité

Les données restent sous le contrôle de l'utilisateur lorsqu'elles sont hébergées localement.

---

Architecture

Frontend :

- HTML
- CSS
- JavaScript

Backend :

- Python
- FastAPI

Base de données :

- SQLite

Modules IA :

- Ollama
- Llama 3
- Mistral

---

Structure du projet

NovaAI/

backend/

- main.py
- chatbot.py
- memory.py
- rag.py
- tools.py
- config.py

frontend/

- index.html
- style.css
- app.js

database/

- conversations.db

models/

docs/

README.md

requirements.txt

LICENSE

---

Installation

Prérequis

- Python 3.11+
- Git
- Ollama

Clonage

git clone https://github.com/votre-utilisateur/NovaAI.git

Dépendances

pip install -r requirements.txt

Téléchargement du modèle

ollama pull llama3

Lancement

uvicorn backend.main:app --reload

---

Vision

NovaAI a pour objectif de fournir une plateforme IA libre, extensible et accessible permettant à chacun de construire son propre assistant intelligent sans dépendre d'un service externe.