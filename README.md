# NorPEN CDM subcommittee 

![NorPEN Logo](https://usercontent.one/wp/norpen.org/wp-content/uploads/2024/02/NorPEN_logo.png?media=1731672452)

## 📖 Overview  

**NorPEN CDM subcommittee** is an initiative on **Common Data Models (CDM)** implementation for the **Nordic Pharmaco-Epidemiological Network (NorPEN)**.  

This repository provides:  
- Standardized **data model definitions**  
- **ETL scripts** for data transformation  
- **Documentation & guides** for researchers  

The goal is to **harmonize pharmacological and epidemiological data** across Nordic registers, supporting **collaborative research, reproducibility, and transparency**.

---

## ❓ What is a Common Data Model (CDM)?  

A **Common Data Model (CDM)** is a standardized framework that allows integration and analysis of heterogeneous data sources.  

NorPEN CDM is designed to:  
- 🔗 Harmonize data from multiple registers  
- 📊 Enable efficient multi-database studies  
- ✅ Ensure transparency and consistency across research projects  

---

## 📂 Repository Structure  

```
.
├── data_model/        # Data model definitions (schemas, tables, fields)
├── scripts/           # ETL scripts for data transformation and loading
├── documentation/     # Documentation, data dictionary, and guides
├── examples/          # Example datasets and usage guides
├── tests/             # Validation and QA scripts
└── README.md          # This file
```

---

## 🚀 Getting Started  

### ✅ Prerequisites  
- Python >= 3.8 (for ETL scripts)  
- R (optional, for statistical analysis)  
- Access to Nordic register data (subject to governance and approvals)  

### ⚙️ Installation  

1. **Clone the repository**
    ```bash
    git clone https://github.com/mauriziosessaku/NorPEN_CDM.git
    cd NorPEN_CDM
    ```

2. **Set up your Python environment**
    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

3. **Explore the documentation**  
   See [documentation/](./documentation/) for details on the **data model** and **ETL process**.

---

## 🧑‍💻 Using the CDM  

- **Data Model:** [`data_model/`](./data_model/) – schemas and table definitions  
- **ETL Scripts:** [`scripts/`](./scripts/) – convert raw register data into the CDM format  
- **Guides:** [`documentation/`](./documentation/) – data dictionary & step-by-step usage  

---

## 🤝 Contributing  

We welcome contributions from the **NorPEN community** and collaborators!  

- Open an [issue](https://github.com/mauriziosessaku/NorPEN_CDM/issues) for suggestions or problems  
- Submit a pull request linked to an issue  
- Follow our [contribution guidelines](./CONTRIBUTING.md) (if available)  

---

## 📜 License  

This repository is licensed under the [MIT License](./LICENSE).  

---

## 📬 Contact  

For questions or collaborations, please:  
- Open an [issue](https://github.com/mauriziosessaku/NorPEN_CDM/issues)  
- Or reach out to the repository maintainers  

---

**NorPEN CDM** — empowering reproducible and collaborative pharmacoepidemiology in the Nordics.
