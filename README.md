# Hospital Admission Records Analysis

## Team Members
* **[Afrah Alsnaid]** — Lead Developer
* **Emman ali** — Data Scientist
* **Adeel Ahmad** — Quality Assurance

## Project Overview
This project focuses on analyzing hospital admission data to identify trends in patient stays and department efficiency. We are building a pipeline for hospital administrators that turns raw CSV logs into actionable insights and visualizations regarding patient volume and recovery times.

## Data Sources
The project utilizes historical hospital admission records including patient demographics, admission dates, and diagnosis codes.

> **Note:** Data is not tracked in this repository. See the setup instructions below for how to obtain and place the data files before running any analysis.

The analysis scripts expect raw data to be placed at: `data/raw/admissions.csv`

## Setup Instructions
To get this project running on your local machine, follow these steps exactly:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LevelUp-Applied-AI/m1-l1-git-workflows-afrah24ali.git
   cd m1-l1-git-workflows-afrah24ali


   m1-l1-git-workflows-afrah24ali/
├── README.md             — Project overview and setup instructions
├── CHANGELOG.md          — Record of notable changes
├── AGENTS.md             — AI contribution policy
├── requirements.txt      — Python dependencies
├── setup.sh              — Automated environment setup script
├── test_environment.py   — Environment validation
├── .gitignore            — Files excluded from version control
├── src/                  — Production source code
├── notebooks/            — Exploratory analysis notebooks
├── data/                 — Data directory (contents not committed to Git)
│   └── raw/              — Original unmodified data files
└── tests/                — Automated tests

## Contributing

### Branch integration/collab-setup

Branches should follow these naming conventions:

feature/<Emman>
fix/<Adel>
setup/<Afrah>

Example:

feature/data-cleaning
fix/readme-typo
setup/environment-script

### Pull Request Process

1. Create a new branch from `main`
2. Make your changes
3. Test the project locally
4. Commit your changes
5. Open a Pull Request to the `main` branch

### Commit Message Format

Commit messages should follow this format:

type: short description

Examples:

feat: add hospital data loader
fix: correct README typo
setup: add environment setup script