# Solving QUBOs on Quantum Computers

This repository contains well-documented Jupyter Notebooks and Python scripts that accompany the paper **"Five Starter Problems: Solving Quadratic Unconstrained Binary Optimization (QUBO) Models on Quantum Computers"** by **Arul Rhik Mazumder** and **Sridhar Tayur**.

## Google Colab & Jupyter Notebook Compatibility
The programs were originally developed and executed on **Google Colab**, but they can also be run locally using **Jupyter Notebook**. Each notebook contains:
- A **list of required packages** at the top.
- **Commented descriptions** explaining the implementation of each algorithm applied to different problems.

These programs were last tested on **December 18, 2023**. If you encounter issues due to package updates or changes in database endpoints, please reach out at **arulm@andrew.cmu.edu**.

## Important Notes for Users
- Most notebooks can be **directly opened in Google Colab** by downloading the files and opening them in Google Drive.
- **Notebook 2** can **only be run locally** because it depends on packages that require **Python 3.8, 3.9, or 3.10**, while Google Colab currently supports **Python 3.11+**. All the other codes can be succesfully deploy on Google Colab and work for **Python 3.11**.
- **Notebook 1, Notebook 5, and Notebook 6** require **API keys** from **IBM Quantum (IBMid)** and **D-Wave Leap** to function properly.

---

## API Access Requirements

### Obtaining an IBMid API Token
Some notebooks require access to IBM's quantum computing services. To obtain an IBMid API token:
1. Visit the [IBMid platform](https://quantum-computing.ibm.com/).
2. Follow the instructions to generate an API token.
3. Keep the token secure, as it is required for executing notebooks that interact with IBM's quantum systems.

### Obtaining a D-Wave Leap API Token
Due to recent changes, obtaining a D-Wave API token requires one of the following:
- **Free Trial Application**: You may apply for a free trial, though approval often requires a well-defined research project. After the trial, your account will automatically upgrade to a **Developer Plan** for continued usage.
- **Purchasing Access Time**: D-Wave offers paid access to their cloud services.
- **Course Enrollment**: Some D-Wave courses include API access as part of the curriculum.

Without a **valid D-Wave API token**, the notebooks requiring D-Wave’s cloud service **will not run**. For more details, refer to the [D-Wave Leap plans](https://www.dwavesys.com/leap).
