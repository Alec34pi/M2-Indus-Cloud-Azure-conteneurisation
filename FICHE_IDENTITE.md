# Fiche d'identité de l'artefact conteneurisé

| Rubrique | Valeur |
| :--- | :--- |
| **1. Nom de l'artefact et tag** | `acrdermascanap24.azurecr.io/dermascan-health:0.1.0` |
| **2. Digest sha256** | `sha256:13b287ad67b71546f2b339875c2ba1b7a8f43b8aaaba3c2b3a05231007d6974f` |
| **3. Image de base et tag exact** | `python:3.11-slim` |
| **4. Version de Python embarquée** | `Python 3.11.17` |
| **5. Dépendances directes et versions** | `Flask==3.1.0` (déclaré dans `requirements.txt`) |
| **6. Dépendances transitives** | `blinker`, `click`, `itsdangerous`, `Jinja2`, `MarkupSafe`, `Werkzeug==3.1.9` |
| **7. Licences et obligations** | **Flask** (BSD-3-Clause) et **CPython** (PSFL) : permissives avec obligation de conserver la notice de copyright. **Paquets système Linux/Debian** (GPLv3 / LGPL) : copyleft imposant la mise à disposition du code source en cas de redistribution. |
| **8. Architecture et OS cibles** | `linux/amd64` |
| **9. Utilisateur d'exécution (uid)** | `appuser` (uid 10001) |
| **10. Port exposé et endpoint de santé** | Port `8000/TCP`, endpoint HTTP `/health` |
| **11. Producteur** | Alec Pibre (promotion AP24), 7 octobre 2026 |
| **12. Registre de publication** | LoginServer : `acrdermascanap24.azurecr.io`<br>Dépôt : `dermascan-health` |
| **13. Destination connue** | Socle pour la base de l'API d'inférence (séance 2) |