# AI Contribution Policy (AGENTS.md)

## 1. Testing Requirements
All changes generated or assisted by AI must pass `python test_environment.py` before they are committed. 
Additionally, any new data processing logic (such as calculating hospital occupancy or patient stay duration) must be manually verified by running the script locally to ensure numerical accuracy.

## 2. Secrets Policy
Do not include raw hospital patient records, Protected Health Information (PHI), or private API keys in any AI prompt. 
Never commit `.env`, `*.key`, or any files containing credentials. Data within `data/raw/` must remain local and never be uploaded to an AI service for training or processing.

## 3. Scope Boundaries
- **Agents may edit:** Analysis scripts in `src/`, exploratory notebooks in `notebooks/`, and project documentation.
- **Human review required:** Changes to `requirements.txt`, `setup.sh`, and core data schema definitions.
- **Strict Guardrail:** Do not modify `.gitignore` using an AI agent without a manual check to ensure hospital data remains excluded from version control.

## 4. Reproducibility Standard
All AI-assisted changes require "local-first" execution. This means the change must run successfully on your local machine and produce the expected hospital analysis results before it is pushed to GitHub. "The AI generated it" is not a valid excuse for broken code.