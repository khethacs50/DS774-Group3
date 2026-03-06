## Data Science 774/874 – Post-block Assignment 1

### Group Number

**3**

### Enterprise

**CreditScoreCheck Ltd.**

### Deadline

**15 March 2026, 23:55**

---

## Project Overview

Our group is acting as a data consultancy for **CreditScoreCheck Ltd.**, a B2B firm specializing in data monetization.
We focus on a **“No-Model” trajectory**, selling raw data insights and lead-generation packages to banking clients.

---

## Ethical Challenge: Credit Discrimination (Redlining)

We empirically demonstrate the impact of **proxy discrimination** and **poor sampling techniques**.

### The Problem

Using biased sampling that mirrors historical redlining — **Race used as a proxy for Income**.

### The Demonstration

We compare:

* A **Fair synthetic dataset**

  * Race and Income are **independent**

* A **Biased synthetic dataset**

  * Race is a **deterministic factor** for *Call / Do Not Call* lists

---

## Repository Structure

```
/data
/notebooks
/poster
/admin
```

* **/data** – Contains the Kaggle datasets:

  * `application_record.csv`
  * `credit_record.csv`

* **/notebooks** – Python notebooks (`.ipynb`) used for:

  * Synthetic data generation
  * Visualization

* **/poster** – The A4 PDF poster and metaphor summary.

* **/admin** – Mandatory declaration files.

---

## Tech Stack

* **Backend:** Firebase (Data Server)
* **Programming:** Python

  * Pandas
  * NumPy
  * Matplotlib
* **Collaboration:** GitHub & Google Colab

---

*Note: This repository is for internal group collaboration for Stellenbosch University DS 774/874.*
