# RAG App Starter

Foundation workspace for an internal RAG assistant.

## Structure
- `data/` source documents (git-ignored)
- `src/` application code
- `prompts/` prompt templates
- `outputs/` logs and results

## Setup
1. `python -m venv .venv`
2. `source .venv/bin/activate` (Windows: `.venv\Scripts\activate`)
3. `pip install -r requirements.txt`
4. `cp .env.example .env` and fill in your keys
5. `python src/main.py`

## Clean-run verification
Cloned into a fresh folder, created a new venv, installed from
requirements.txt, copied .env.example to .env, and ran
`python src/main.py`. Output: "Setup OK: all environment variables are loaded."