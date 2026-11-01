# PyFile-Analyzer

Herramienta de análisis forense y reputación de archivos escrita en Python.
File forensics and reputation analysis tool written in Python.

---

## 🇪🇸 Español

### Descripción
Analiza archivos para identificar su tipo real, comprobar su integridad y consultar su reputación, incluso cuando no tienen extensión o esta es incorrecta.

### Funcionalidades
- **Detección inteligente:** identifica el tipo de archivo real (Magic Numbers) y detecta scripts (Python, Bash, HTML) analizando su contenido.
- **Integridad:** genera el hash SHA-256 del archivo para su identificación única.
- **Reputación:** consulta la API de VirusTotal para verificar si el archivo ha sido reportado como malicioso.
- **Multiplataforma:** funciona en Windows, Linux y macOS.

### Instalación
1. Clona el repo.
2. Instala dependencias: `pip install -r requirements.txt`.
3. Crea un archivo `.env` con tu `VT_API_KEY=tu_clave_aqui`.

### Uso
```bash
python3 anapyzer.py
```

---

## 🇺🇸 English

### Overview
Analyzes files to identify their real type, check their integrity, and query their reputation, even when they have no extension or an incorrect one.

### Features
- **Smart Detection:** identifies the real file type (Magic Numbers) and detects scripts (Python, Bash, HTML) by analyzing content.
- **Integrity:** generates the file's SHA-256 hash for unique identification.
- **Reputation:** queries the VirusTotal API to check whether the file has been reported as malicious.
- **Cross-platform:** works on Windows, Linux, and macOS.

### Installation
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Create a `.env` file with your `VT_API_KEY=your_key_here`.

### Usage
```bash
python3 anapyzer.py
```

---

## Licencia / License

**GNU General Public License v3.0 (GPL-3.0).**

Este proyecto se distribuye bajo los términos de la licencia GNU GPL-3.0. Consulta el archivo [LICENSE](LICENSE) para leer el texto completo.

This project is distributed under the terms of the GNU GPL-3.0. See the [LICENSE](LICENSE) file for the complete license text.
